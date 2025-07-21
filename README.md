Linux, Google Earth Engine y aplicaciones de análisis espacial con
Python y R, nivel básico
================
José Martínez

Versión HTML (quizá más legible),
[aquí](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/README.html)

## Código QR para acceder a este portal

<img src="media/img/qr.jpg" width="300px">

<https://github.com/geofis/curso-linux-gee-aplicaciones-r-python-julio-2025.git>

------------------------------------------------------------------------

## Dirigido a …

- Estudiantes y profesionales interesados en aprender sobre GNU/Linux,
  Python, R y Google Earth Engine para análisis espacial.

## Objetivos del curso

- Conocer los fundamentos de GNU/Linux y su uso en ciencia y análisis
  espacial.

- Aprender a manejar la terminal de Linux y comandos básicos.

- Familiarizarse con Python y R para análisis espacial.

- Aprender a usar Google Earth Engine para análisis de imágenes
  satelitales.

- Integrar GEE con Python y R para análisis reproducible.

## Metodología común

Sesiones introductorias, lo más cortas posibles, y prácticas guiadas,
con el objetivo de que cada participante pueda seguirlas en su propia
PC. Se proporcionarán recursos adicionales para quienes deseen
profundizar en los temas tratados.

Abriré una sesión de Google Meet para que puedas compartir tu pantalla
en caso de que necesites apoyo guiado, o para que puedas compartir tus
avances. Considera igualmente que Gemini puede ayudarte si le compartes
tu pantalla. Si envías consultas a herramientas de IA, es altamente
probable que, tratándose de comandos Linux, Python o R, la respuesta sea
correcta. No obstante, mientras estés en modo “principiante”, te
recomiendo que verifiques las respuestas conmigo, ya que es fácil
cometer errores de sintaxis o de interpretación. Además, la instancia de
Linux que estés usando para aprender, no debería usarlas para realizar
tareas críticas o de producción, ya que es posible que tus archivos no
estén bien respaldados o que la configuración no sea la adecuada para
tus necesidades.

Cada día, dejaré prácticas para realizar en casa. Son voluntarias, pero
si las realizas, te servirán para reforzar lo aprendido en cada sesión.

## ¿Qué necesitas?

- Libreta, si eres de apuntar.

- Lápiz o bolígrafo.

- Teléfono móvil.

- PC portátil o Raspberry Pi u otra *single board computer*.

# Contenido

## Preliminares

- [Bienvenida](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/bienvenida.html)

- \[Motivación\](<https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/motivacion.html>

## Temáticos

### Esquema general del curso

| Tema | Contenido teórico                                      | Práctica aplicada                                         |
|------|--------------------------------------------------------|-----------------------------------------------------------|
| 1    | Linux o GNU/Linux: kernel, filosofía, distros          | Instala y prueba una o varias distros Linux               |
| 2    | Terminal, estructura de archivos y comandos esenciales | Aprende a navegar y operar en la terminal                 |
| 3    | Introducción a Python para análisis espacial           | Manipula datos espaciales vectoriales y ráster con Python |
| 4    | Introducción a R para análisis espacial                | Realiza análisis espacial básico en R                     |
| 5    | Introducción a Google Earth Engine (GEE)               | Usa Earth Engine para analizar imágenes satelitales       |
| 6    | Aplicaciones integradas: de lo local a lo global       | Integra GEE con R o Python para análisis reproducible     |

### Contenido teórico

- [**Tema 1. Linux o GNU/Linux: kernel, filosofía, distros, terminal,
  estructura**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-1-intro.html).

  - Diferencias entre Linux (kernel), GNU/Linux (sistema completo) y
    distros

  - Filosofía del software libre y código abierto (las 4 libertades)

  - Ventajas de Linux para ciencia y análisis espacial

  - Estructura básica del sistema: kernel, shell, interfaz gráfica

  - Distribuciones populares: Ubuntu, Debian, Mint, Fedora, Arch, etc.

  - Entornos ligeros para PCs modestas: XFCE, LXQt, etc.

  - Opciones para usar Linux desde Windows: WSL2, VM, USB, Colab, Docker

  - Terminal, estructura jerárquica del sistema de archivos.

  - Casos reales en ciencia, educación y proyectos ambientales

- [**Tema 2. Comandos esenciales, tuberías,
  permisos**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-2-intro.html)

  - Comandos básicos (`ls`, `cd`, `cp`, `mv`, `rm`, `mkdir`, `nano`,
    `touch`, `grep`, `find`, etc.)

  - Tuberías (*pipelines*)

  - Permisos, usuarios, instalación de software (`apt`, `conda`)

  - Navegación en la terminal y uso del historial

  - Edición de texto en terminal

  - Automatización de tareas mediante scripts

- [**Tema 3. Introducción a Python para análisis
  espacial**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-3-intro.html)

  - Uso de Jupyter Notebooks

  - Paquetes básicos para análisis espacial: `numpy`, `pandas`,
    `matplotlib`, `geopandas`, `shapely`, `rasterio`

  - Lectura y visualización de shapefiles y rásters simples

  - Extracción de información por atributos y geometría

- [**Tema 4. Introducción a R para análisis
  espacial**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-4-intro.html)

  - Interfaz básica de R y RStudio

  - Paquetes para análisis espacial en R: `sf`, `terra`, `ggplot2`,
    `dplyr`

  - Importación de capas vectoriales y ráster

  - Operaciones simples sobre objetos espaciales

- [**Tema 5. Introducción a Google Earth Engine
  (GEE)**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-5-intro.html)

  - Filosofía de Earth Engine

  - Explorador y código en el editor

  - Imágenes satelitales: Sentinel-2, Landsat

  - Colecciones vectoriales, filtrado temporal y espacial

- [**Tema 6. Aplicaciones integradas: de lo local a lo
  global**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-6-intro.html)

  - Ejemplos combinados: descargar imágenes de GEE, procesarlas en
    Python o R

  - Casos reales: NDVI, coberturas, mapas de calor, zonificación

  - Buenas prácticas en reproducibilidad: scripts, notebooks, metadatos

### Prácticas

- [**Tema 1. Instala y prueba una o varias distros Linux, terminal,
  estructura**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-1-practica.html)

  - Elige e instala una distribución Linux en tu equipo mediante alguna
    de estas opciones: máquina virtual, WSL2, USB booteable o
    instalación completa.

  - Inicia sesión en tu nuevo entorno Linux y explora el entorno gráfico
    y el menú de aplicaciones.

  - Abre una terminal y ejecuta comandos básicos como `pwd`, `ls`, `cd`,
    `whoami`, `uptime`.

  - Navega por la estructura de directorios (`/home`, `/etc`, `/bin`,
    `/usr`, `/var`) y toma nota de sus funciones principales.

  - Configura tu entorno inicial: cambia idioma o zona horaria si es
    necesario, personaliza la terminal, instala un editor de texto (como
    `nano` o `vim`) y verifica que puedas usar `sudo`.

  - Si tu instalación lo permite, explora el gestor de paquetes (`apt`,
    `dnf`, `pacman`, según distro).

  - (Opcional) Prueba una segunda distro ligera (como Xubuntu, Lubuntu,
    MX Linux) para comparar rendimiento y apariencia.

- [**Tema 2. Aprende a navegar y operar de forma avanzada en la
  terminal**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-2-practica.html)

  - Navega por directorios, crea y elimina archivos/carpetas

  - Usa comandos para ver procesos, espacio, permisos y editar texto

  - Instala software con `apt` y `conda`

  - Automatiza tareas con pequeños scripts

- [**Tema 3. Manipula datos espaciales vectoriales y ráster con
  Python**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-3-practica.html)

  - Abre y visualiza un shapefile

  - Calcula áreas y estadísticas básicas

  - Extrae valores desde rásters a puntos

  - Visualiza resultados con `matplotlib` y `geopandas`

- [**Tema 4. Realiza análisis espacial básico en
  R**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-4-practica.html)

  - Carga y explora datos vectoriales y ráster

  - Usa `dplyr` y `ggplot2` para resumir y visualizar

  - Aplica operaciones espaciales: intersección, unión, recorte

  - Genera un mapa con leyenda y escala

- [**Tema 5. Usa Earth Engine para analizar imágenes
  satelitales**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-5-practica.html)

  - Crea una cuenta y autoriza tu acceso

  - Filtra y visualiza imágenes por fecha, nube y localización

  - Exporta un ráster a Drive o Asset

  - Aplica NDVI o similares a una zona de interés

- [**Tema 6. Integra GEE con R o Python para análisis
  reproducible**](https://geofis.github.io/curso-linux-gee-aplicaciones-r-python-julio-2025/media/tema-6-practica.html)

  - Usa `ee` en Python o R para cargar imágenes desde scripts

  - Descarga y analiza los resultados localmente

  - Crea una rutina de trabajo reproducible: código + resultados +
    visualizaciones

## Referencias
