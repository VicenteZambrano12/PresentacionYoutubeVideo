Aquí tienes el prompt maestro actualizado, incorporando la instrucción sobre dónde y cómo guardar el archivo resultante. He añadido una sección específica para que la IA genere un script (en Python, PowerShell o Bash, dependiendo de lo que uses normalmente, aunque he puesto un script de Python por ser el más estándar para manejo de archivos locales) que cree esa estructura de carpetas si no existe y guarde el HTML, o bien, instrucciones claras de cómo debes guardarlo tú manualmente.

Dado que eres ingeniero en IA y sueles trabajar con Linux (Ubuntu) y Python, he adaptado la sugerencia de guardado para que te genere un pequeño script automatizado, además del HTML.
📋 Copia y pega el siguiente Prompt:

Rol: Actúa como un Desarrollador Web y experto en Frontend, con conocimientos en automatización de sistemas.

Contexto y Objetivo:
Tengo 11 archivos HTML independientes que representan las diapositivas de una presentación (PPT). Los archivos están numerados secuencialmente en su nombre. Tu objetivo principal es unificar todos estos fragmentos en un único archivo HTML funcional, convirtiéndolo en una presentación interactiva, sin alterar en lo más mínimo el diseño, estructura o estilos originales de cada diapositiva.
El objetivo secundario es que el resultado final debe guardarse automáticamente en la ruta root/resultados/ con el nombre resultado.html.

Instrucciones estrictas para el HTML:

    Unificación Secuencial: Crea un documento base e inserta el código de los 11 HTMLs en el orden numérico exacto de sus nombres de archivo.

    Fidelidad Absoluta (Zero Alteration): Bajo ninguna circunstancia modifiques el código interno (HTML/CSS) de las diapositivas proporcionadas. Mantén sus clases, IDs y estilos en línea intactos.

    Estructura Contenedora: Envuelve cada diapositiva original dentro de un contenedor (por ejemplo, <div class="slide" id="slide-1">...</div>) para poder manipular su visibilidad sin tocar su contenido original.

    Lógica de Presentación (CSS): Añade el CSS mínimo y estrictamente necesario al documento principal para asegurar que solo se muestre una diapositiva en pantalla a la vez, y que ocupe el espacio correcto de la pantalla (comportamiento clásico de un PPT a pantalla completa).

    Navegación Interactiva (JavaScript):

        Escribe un script en JS puro (Vanilla JS) que permita navegar entre las diapositivas.

        Añade un addEventListener al documento para que la presentación avance a la siguiente diapositiva al pulsar la Flecha Derecha (ArrowRight) y retroceda a la anterior al pulsar la Flecha Izquierda (ArrowLeft).

        Asegúrate de que la navegación tiene límites lógicos controlados (no puede retroceder antes de la diapositiva 1 ni intentar avanzar después de la 11).

Instrucciones para el almacenamiento (Python):
Para cumplir con el requisito de almacenamiento en root/resultados/resultado.html, asume que ejecutaré esto en un entorno de desarrollo (Ubuntu Linux).

    Proporciona un script de Python conciso que:

        Tome el HTML unificado que has generado (puedes guardarlo en una variable de texto múltiple o leerlo de un archivo si lo prefieres para el script).

        Verifique si el directorio root/resultados existe en el directorio de trabajo actual. Si no existe, debe crearlo recursivamente.

        Escriba el HTML generado en el archivo root/resultados/resultado.html.

Formato de Salida Esperado:

    Bloque 1: El código del archivo HTML unificado completo y funcional.

    Bloque 2: El script de Python para automatizar la creación de la carpeta y el guardado del archivo.

A continuación, te proporciono el código de los 11 archivos HTML en orden: