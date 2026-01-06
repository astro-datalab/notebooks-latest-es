# Cuadernos de Ejemplo de DESI

El Astro Data Lab incluye una colección de cuadernos que muestran cómo trabajar con los datos de DESI. Estos están distribuidos en varias ubicaciones, como se detalla a continuación.

## Esta carpeta: `03_EjemplosDeCiencia//DESI/`

- `01_Intro_a_DESI_DR1.ipynb` muestra cómo acceder al catálogo de corrimientos al rojo desde la base de datos del Astro Data Lab, cómo separar objetos según la información de selección de blancos de DESI, cómo acceder a todos los espectros disponibles para un objeto dado usando [SPARCL (SPectra Analysis and Retrievable Catalog Lab)](https://astrosparcl.datalab.noirlab.edu), y finalmente cómo graficar el espectro “mejor”.

- `01_Intro_a_DESI_EDR.ipynb` es la versión anterior del Lanzamiento de Datos Temprano (EDR), con funcionalidad similar: cómo acceder al catálogo de corrimientos al rojo desde la base de datos del Astro Data Lab, cómo separar objetos según la información de selección de blancos de DESI, cómo acceder a todos los espectros disponibles para un objeto usando SPARCL, y finalmente cómo graficar el espectro “mejor”. Recomendamos utilizar la versión más reciente (DR1), ya que reemplaza los datos del EDR.

- `01a_Intro_a_DESI_DR1-Py3.ipynb` está adaptado de `01_Intro_to_DESI_DR1.ipynb` para funcionar sin el software de DESI. Requiere un entorno Python 3 con los clientes `datalab` y `sparcl` instalados (ambos pueden instalarse con `pip` localmente si no se trabaja en el servidor Jupyter del Astro Data Lab).

- `02_Comparacion_DESI_SDSS.ipynb` muestra cómo usar la búsqueda de datos de SPARCL para encontrar espectros disponibles de SDSS DR16 y DESI DR1 de fuentes en una región específica del cielo con restricciones en redshift y tipo espectral, cómo recuperar y comparar espectros de la misma galaxia observada con SDSS y DESI.

## Carpeta “Cómo Hacer”: `04_ComoHacer/`

- `QueryClient/Como_consultar_datos_de_DESI_DR1.ipynb` demuestra una variedad de consultas a la base de datos `desi_dr1` del Astro Data Lab.

- `QueryClient/Como_consultar_datos_de_DESI_EDR.ipynb` demuestra una variedad de consultas a la base de datos `desi_edr` del Astro Data Lab (nota: reemplazada por la versión DR1).

- `SPARCL/Como_usar_SPARCL.ipynb` proporciona una introducción básica al uso del cliente SPARCL (`sparclclient`) para encontrar y recuperar datos espectroscópicos dentro de un entorno tipo notebook en Python. [(SPARCL = SPectra Analysis and Retrievable Catalog Lab)](https://astrosparcl.datalab.noirlab.edu)

- `SPARCL/Graficar_Espectros_con_Jdaviz.ipynb` muestra cómo recuperar espectros desde SPARCL y visualizarlos usando la herramienta de análisis y visualización [Jdaviz](https://jdaviz.readthedocs.io/en/latest/index.html).

- `SPARCL/raficar_Espectros_con_Prospect.ipynb` muestra cómo recuperar espectros desde SPARCL y visualizarlos usando la herramienta interactiva de visualización espectral [prospect](https://desi-prospect.readthedocs.io/en/latest/).

## Otras referencias útiles

### Sitios de documentación de datos de DESI

La [página principal de DESI](https://datalab.noirlab.edu/desi/index.php) en el Astro Data Lab incluye una breve introducción a DESI y su primer lanzamiento de datos. La [página de acceso a datos](https://datalab.noirlab.edu/desi/access.php) describe múltiples formas de acceder a los datos a través del Astro Data Lab o SPARCL.

El sitio web de [Documentación de Datos de DESI](https://data.desi.lbl.gov/doc/) describe el acceso, formato y lanzamientos de datos, e incluye enlaces a artículos técnicos, información sobre licencias de datos y reconocimientos. Es la referencia principal y oficial sobre DESI.

### Ayuda con Astro Data Lab y DESI

Si tienes una pregunta sobre el Astro Data Lab, por favor visita el [Foro de Usuarios de Data Lab](https://datalab.noirlab.edu/help/).

Si tienes una pregunta sobre DESI, por favor visita el [Foro de Usuarios de DESI](https://help.desi.lbl.gov).
