# Landing Page de un Artista Digital


# Objetivo
El objetivo de esta actividad es diseñar y maquetar una página de presentación (landing page) para una artista digital ficticia, preparando y optimizando todos los recursos multimedia necesarios. Con esta práctica demostrarás tu capacidad para seleccionar, manipular e integrar imágenes, audio, vídeo y animaciones en un proyecto web, respetando las licencias de uso y las buenas prácticas de rendimiento y accesibilidad.

**Escenario**


Vas a crear la página de perfil para "Nébula", una artista digital especializada en paisajes de ciencia ficción. La página debe ser visualmente atractiva y mostrar su trabajo de manera profesional. Deberás buscar, editar y generar todo el contenido multimedia necesario respetando los requisitos técnicos establecidos.



# Tareas a Realizar
**1. Imagen Principal (Hero Image)**
Búsqueda y Licencia: Encuentra una imagen de un paisaje futurista o espacial en un banco de imágenes con licencia Creative Commons o Dominio Público (Unsplash, Pixabay, Pexels, etc.).
Tratamiento Digital: Usando una herramienta de edición de imágenes (GIMP, Photoshop, Squoosh, etc.):
Redimensiónala a un ancho exacto de 1920px manteniendo el aspect ratio.
Optimízala para que su peso sea inferior a 250 KB.
Exportala en el formato más adecuado. Deberás justificar tu elección en la documentación.


**2. Logotipo del Artista**


Creación / Búsqueda: Busca o diseña un icono simple que represente a "Nébula" (una estrella, un planeta, etc.) en formato vector (.svg) o mapa de bits (.png).
Tratamiento:
Si usas .png, asegúrate de que tenga fondo transparente.
Si usas .svg, justifica en el documento por qué es la opción óptima para un logotipo web.


**3. Galería de Trabajos**


Selección: Elige 3 imágenes (mínimo) más del mismo artista o de temática similar a la imagen principal.
Tratamiento: Crea versiones en miniatura (thumbnails) de 400x250px para cada una. Optimízalas en formato .webp para que pesen lo menos posible.


**4. Animación de "Llamada a la Acción" (Call to Action)**


Creación: Imagen animada.  a partir de 3 imágenes fijas (mínimo, fotograma a fotograma), crea una animación en bucle para un botón de "Contacto" o un banner promocional (ej. un sobre que se mueve, un texto que parpadea o un efecto de neón).
Herramientas y Formato: Puedes usar GIMP, ezgif.com u otras herramientas similares. Exporta el resultado en formato GIF animado o WebP animado (opción recomendada por rendimiento).


**5. Vídeo de Presentación**


Búsqueda y Licencia: Encuentra un vídeo corto (10-15 segundos) de una animación espacial o un timelapse del cielo nocturno.
Tratamiento: Usando una herramienta como HandBrake, FFmpeg o un conversor especializado:
Convierte o exporta el vídeo al formato más adecuado con el bitrate adecuado.
Comprímelo para que su peso total sea inferior a 3 MB.
Genera una imagen fija (poster.webp) a partir de un fotograma del vídeo para usarla como miniatura de precarga.


**6. Audio Ambiental**


Búsqueda y Licencia: Encuentra un clip de audio de 30-60 segundos con sonido ambiental de "ciencia ficción".
Tratamiento: Con Audacity, AudioMass o una herramienta similar:
Recorta el audio para que dure exactamente 15 segundos.
Aplica un efecto suave de entrada y salida (Fade-in y Fade-out).
Exporta el clip en el formato correcto con una tasa de bits de apropiada (estudio/voz) o (música).


# Maquetación e Integración HTML5
Crea la estructura de carpetas adecuada en producción:
Plaintext


/
├── index.html
├── README.md
└── assets/
    ├── img/
    ├── audio/
    └── video/
 
Estructura la página usando HTML5 semántico (<header>, <main>, <footer>, etc.).
Integración y Atribución:
Usa las etiquetas semánticas <figure> y <figcaption> para incluir la atribución de licencia Creative Commons directamente bajo las imágenes principales y el vídeo.
Integra los recursos con las etiquetas correspondientes: <img>, <video controls poster="assets/img/poster.webp"> y <audio controls>.
Buenas Prácticas WPO y Accesibilidad: Añade obligatoriamente los atributos alt descriptivo, width, height y loading="lazy" en todas las imágenes estáticas de la página.


**Alternativa**
Si eres capaz de adaptar alguna de las landing de los ejercicios anteriores para cumplir con los requisitos pedidos, puedes hacerlo sin problema. Pero consúltalo conmigo antes de ponerte a ello, por asegurarnos de que lo que planteas cuadra con los requisitos.



**Requisitos de Entrega:**


Como siempre, repositorio que contenga:

El archivo index.html maquetado con la integración multimedia.
La carpeta assets/ con todas sus subcarpetas y los archivos multimedia optimizados.
Un archivo README.md que documente los siguientes apartados:
Tabla de Recursos y Licencias: Listado de cada archivo utilizado, enlace a la URL original de descarga y tipo de licencia otorgada (ej. CC BY 4.0, Dominio Público, etc.).
Justificación Técnica de Formatos: Explicación breve de por qué elegiste cada formato (.webp frente a .jpg, .mp4 frente a .avi, etc.).
Herramientas Utilizadas: Software o servicios web empleados en cada proceso de tratamiento (ej. GIMP para redimensionar, Audacity para recortar audio, HandBrake para transcodificar vídeo).
Github Pages apuntando al index para poder ver la página online.
