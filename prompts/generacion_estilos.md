**Rol:** Actúa como un experto en diseño de identidad corporativa, UX/UI y diseño de presentaciones ejecutivas.

**Tarea:** Genera un archivo JSON válido y bien estructurado que contenga las directrices visuales (colores y tipografía) de una marca, optimizado para su uso automatizado en plantillas de presentaciones corporativas.

**Contexto:** *(Opcional: Define aquí el estilo de tu marca. Ej. "Es para una empresa de tecnología moderna", "Es para una consultora financiera con tonos azules formales", etc. Si lo dejas en blanco, inventa una paleta corporativa moderna, elegante y de alto contraste).*

**Requisitos de la estructura del JSON:**
El JSON debe contener las siguientes jerarquías y datos:

1. **Paleta para Diapositivas de Transición (Divisores de sección y títulos):**
   - `background`: Color de fondo (generalmente un tono oscuro o vibrante de la marca).
   - `text_primary`: Color del texto principal (debe tener alto contraste con el fondo).
   - `accent`: Color para líneas divisorias o elementos decorativos.

2. **Paleta para Diapositivas Normales (Contenido):**
   - `background`: Color de fondo (generalmente blanco o muy claro para legibilidad).
   - `text_prima ry`: Color de texto principal (oscuro, para el cuerpo).
   - `text_secondary`: Color para subtítulos o texto menos importante.
   - `accent`: Color para viñetas, iconos, enlaces o gráficos.

3. **Tipografía:**
   - `font_families`: Define una fuente para `headings` (encabezados) y otra para `body` (cuerpo general). Usa fuentes estándar o de Google Fonts (ej. Montserrat, Roboto, Inter).
   - `font_sizes` (en pt o px): 
      - `h1` (Títulos de divisores/portada)
      - `h2` (Títulos de diapositivas normales)
      - `body` (Texto general)
      - `small` (Notas al pie o referencias)

**Restricciones de salida:**
- Los colores deben entregarse estrictamente en formato Hexadecimal (ej. "#003366").
- La salida debe ser ÚNICAMENTE el bloque de código JSON válido, sin texto introductorio, sin explicaciones finales y sin formato Markdown fuera del bloque de código. Las claves del JSON deben estar en inglés y en `snake_case`.