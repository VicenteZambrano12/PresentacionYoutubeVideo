# Materiales del vídeo: presentaciones con inteligencia artificial

**Un regalo para todos los escépticos.**

Este espacio reúne los materiales que acompañan a un vídeo de mi canal de YouTube sobre la creación de presentaciones con inteligencia artificial (IA). Aquí puedes consultar los recursos y descargarlos para seguir el vídeo, practicar o adaptar el proceso a tu propia presentación.

**No es una aplicación ni un proyecto de programación.** No necesitas instalar herramientas de desarrollo ni saber programar: este espacio funciona como una carpeta de materiales para descargar.

## Descargar todos los materiales en ZIP

La opción más sencilla es descargar todo en un único archivo:

### Opción 1: descarga directa

**[Descargar los materiales en ZIP](https://github.com/VicenteZambrano12/PresentacionYoutubeVideo/archive/refs/heads/main.zip)**

### Opción 2: desde la página de GitHub

1. Abre la [página principal de los materiales](https://github.com/VicenteZambrano12/PresentacionYoutubeVideo).
2. Pulsa el botón **Code** que aparece encima de la lista de archivos.
3. Selecciona **Download ZIP**.
4. Guarda el archivo en tu ordenador.

No necesitas una cuenta de GitHub para descargar estos materiales.

### Abrir el ZIP

El ZIP es un archivo que agrupa todas las carpetas y documentos. Antes de trabajar con ellos, descomprímelo:

- **Windows:** haz clic derecho sobre el ZIP y selecciona **Extraer todo**.
- **macOS:** haz doble clic sobre el ZIP.
- **Linux:** haz clic derecho sobre el ZIP y selecciona **Extraer aquí** o la opción equivalente.

Después, abre la carpeta extraída. Los materiales estarán organizados igual que en esta página.

## Qué encontrarás y para qué sirve cada carpeta

La estructura de carpetas y los materiales son un **ejemplo de la presentación que se trabaja en el vídeo**. Sirven para seguir el proceso y entender cómo organizar la información; no son una estructura obligatoria para todas las presentaciones.

En este ejemplo, la organización separa el contenido de la presentación de los recursos que puedes reutilizar en otras presentaciones. Puedes adaptar tanto los materiales como las carpetas a tu tema y a tus necesidades.

| Carpeta | Qué contiene o para qué está destinada |
| --- | --- |
| [prompts](./prompts/) | Instrucciones para pedir a la IA que genere elementos de la presentación. Un *prompt* es el texto que copias y envías a una herramienta de IA para explicarle qué necesitas. |
| [presentacion/material](./presentacion/material/) | Material propio de la presentación de ejemplo: fotografías, mapas, tablas, gráficos y datos. |
| [presentacion/recursos](./presentacion/recursos/) | Recursos generales de marca o empresa, como logotipos y pautas de estilo, que se pueden reutilizar en distintas presentaciones. |
| `presentacion/recursos/plantillas` | Espacio previsto para las plantillas HTML de las diapositivas: diseños base sobre los que colocar el contenido. |
| `presentacion/resultados` | Espacio previsto para las diapositivas generadas y la presentación final en archivos HTML, que se visualizan en un navegador web. |

**Estado actual:** ya hay un prompt para generar el estilo visual, imágenes de marca, un archivo de estilos y materiales de ejemplo sobre Roma. Las carpetas de plantillas y resultados están vacías por ahora; por eso pueden no aparecer en GitHub ni en el ZIP. No se incluye todavía una presentación HTML final.

## Cómo utilizar los materiales

### 1. Descarga y localiza los archivos

Descarga el ZIP y descomprímelo siguiendo los pasos anteriores. Mantén las carpetas organizadas para localizar fácilmente cada recurso durante el vídeo.

### 2. Revisa el contenido de la presentación

En [material](./presentacion/material/) encontrarás:

- [Fotos](./presentacion/material/fotos/) de personajes históricos.
- [Mapas](./presentacion/material/mapas/) de distintas etapas de Roma.
- [Tablas, gráficos y datos](./presentacion/material/tablas_graficas/) para apoyar el contenido de las diapositivas.

Estos archivos son el contenido de la presentación de ejemplo del vídeo. La división en fotos, mapas y tablas o gráficos responde a ese contenido sobre Roma. Para crear una presentación sobre otro tema, utiliza tus propias imágenes, datos y textos, y adapta esta estructura al tipo de información que quieras presentar.

### 3. Define el aspecto visual con la IA

Abre el [prompt de generación de estilos](./prompts/generacion_estilos.md), copia su contenido y pégalo en la herramienta de IA que estés utilizando.

Antes de enviarlo, adapta el apartado **Contexto** a tu marca o al estilo que buscas. Por ejemplo: «Una presentación educativa sobre historia, con colores sobrios y texto fácil de leer».

Este prompt pide a la IA una propuesta de **colores y tipografías**, no una presentación completa. La respuesta se entrega en formato **JSON**, un archivo de texto que organiza la información con etiquetas. No necesitas programarlo: puedes consultar los colores y fuentes propuestos y aplicarlos en tu herramienta de presentaciones.

También puedes consultar el [archivo de estilos del ejemplo](./presentacion/recursos/estilos.json) y las [imágenes de marca](./presentacion/recursos/imagenes/).

### 4. Sigue el proceso del vídeo

Utiliza el vídeo como guía para combinar el contenido, los recursos visuales y las instrucciones para la IA. La idea de esta organización es trabajar en este orden:

**Contenido → estilo de marca → plantilla HTML de diapositivas → presentación HTML final.**

Cuando se incorporen plantillas y resultados, podrás utilizarlos como referencia y comparar el material de partida con el resultado final.

### 5. Adapta y revisa tu presentación

Cambia los recursos del ejemplo por los de tu tema o empresa y revisa el resultado antes de compartirlo: comprueba los datos, la ortografía, las fuentes y que el texto se lea bien.

Usa únicamente imágenes y materiales para los que tengas permiso. Que un recurso pueda descargarse no implica que esté libre de restricciones de uso.

## Dudas habituales

**¿Necesito saber programar?**  
No. Puedes consultar los documentos, copiar las instrucciones para la IA y utilizar las imágenes sin herramientas de programación.

**¿Cómo abro los archivos?**  
Las imágenes se abren con el visor habitual de tu dispositivo. Los archivos `.md` son documentos de texto que también puedes leer directamente en GitHub; los `.json` se pueden consultar con un editor de texto.

Cuando haya archivos `.html`, podrás ver las diapositivas o la presentación en un navegador como Chrome, Edge, Firefox o Safari, sin necesitar PowerPoint. Después de descomprimir el ZIP, haz doble clic en el archivo HTML o haz clic derecho y selecciona **Abrir con** y tu navegador. Mantén la estructura de carpetas para que las imágenes y los demás recursos vinculados se carguen correctamente. En GitHub verás el contenido del archivo HTML como texto; para visualizar la presentación, descárgala y ábrela en el navegador.

**¿Cómo descargo una versión actualizada?**  
Vuelve a descargar el ZIP desde esta página. Cada descarga incluye los archivos disponibles en ese momento; una copia ya descargada no se actualiza automáticamente.
