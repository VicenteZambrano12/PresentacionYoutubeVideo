Actúa como un experto desarrollador front-end y diseñador de presentaciones corporativas. Tu objetivo es generar el código HTML para **exactamente 3 diapositivas** que servirán como plantillas para una presentación corporativa.

A continuación, te proporciono la estructura de carpetas del proyecto y los estilos corporativos que debes respetar.

### Entradas
*   **Estructura de ficheros:** 
    ```text
    [Inserta aquí tu estructura de ficheros]
    ```
*   **Estilos (JSON):** 
    ```json
    [Inserta aquí tu JSON de estilos]
    ```

### Tareas a realizar
Genera el código HTML independiente para las siguientes 3 diapositivas:
1.  **Diapositiva de Título:** Para la portada de la presentación. Debe incluir el logo de la empresa.
2.  **Diapositiva Divisora de Sección:** Para separar diferentes temáticas o bloques dentro de la presentación.
3.  **Diapositiva de Contenido:** Una plantilla con una estructura limpia para añadir información textual o elementos.

### Restricciones y requisitos técnicos
*   **Rutas de archivos:** Los archivos HTML que vas a generar se alojarán en la carpeta `plantillas/`, pero ten en cuenta que la presentación final se ensamblará o ejecutará en la carpeta `resultados/`. Asegúrate de construir las rutas relativas (especialmente la del logo corporativo) en base a la estructura de ficheros adjunta para que funcionen correctamente.
*   **Uso de imágenes:** NO inventes URLs, no uses enlaces externos (como *via.placeholder.com*) ni imágenes en base64. Limítate a usar la etiqueta `<img src="...">` apuntando a la ruta local correcta del logo según la estructura proporcionada.
*   **Diseño y Estilos:** Adapta todo el CSS (ya sea en línea o dentro de una etiqueta `<style>`) basándote *exclusivamente* en las variables de color, tipografía y diseño proporcionadas en el JSON.
*   **Límite de salida:** Genera **exactamente 3** bloques de código HTML distintos. Ni más, ni menos.