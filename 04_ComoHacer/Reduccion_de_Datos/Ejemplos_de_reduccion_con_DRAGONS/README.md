## Reducción de datos con DRAGONS (Jupyter Notebooks):

Este repositorio contiene ejemplos en Jupyter Notebook para la reducción de datos de los instrumentos del Observatorio Gemini. Normalmente, necesitas tener DRAGONS instalado en tu computadora para ejecutar estos notebooks, pero Astro Data Lab tiene un *kernel* personalizado llamado **DRAGONS (Py4.0)** que te permitirá ejecutarlos.  
Los notebooks están configurados para abrir el *kernel* de DRAGONS por defecto, pero si esto no sucede, haz clic en el nombre del *kernel* actual en la esquina superior derecha y selecciona **DRAGONS (Py4.0)**.  
Estos notebooks fueron escritos utilizando la [Interfaz de Programación de Aplicaciones (API) de DRAGONS](https://dragons.readthedocs.io/projects/recipe-system-users-manual/en/release-3.2.x/appendices/full_api_example.html) para Python, basada en los ejemplos provistos en la [Documentación de DRAGONS](https://dragons.readthedocs.io/).

---

## Notebooks disponibles actualmente:

### Flamingos2_Imagen_EnanaMarron.ipynb

Imágenes con Flamingos-2 (banda Y) de la enana marrón **WISE J041358.14-475039.3**.  
Este ejemplo se extrajo del tutorial **Gemini/DRAGONS F2**, Sección 3.  
El conjunto de datos incluye *flats*, *darks* y cuadros científicos (*science frames*).  
Enlace al [Jupyter notebook](https://github.com/astro-datalab/notebooks-latest-es/tree/master/04_ComoHacer/Reduccion_de_Datos/Ejemplos_de_reduccion_con_DRAGONS/Flamingos2_Imagen_EnanaMarron/Flamingos2_Imagen_EnanaMarron.ipynb).

### GMOS_Imagen_CampoEstelar.ipynb

Imágenes con GMOS (banda *i*) de un campo estelar.  
Este ejemplo se extrajo del tutorial **Gemini/DRAGONS GMOS**, Sección 3.  
El conjunto de datos incluye *biases*, *twilight flats* y cuadros científicos.  
Enlace al [Jupyter notebook](https://github.com/astro-datalab/notebooks-latest-es/tree/master/04_ComoHacer/Reduccion_de_Datos/Ejemplos_de_reduccion_con_DRAGONS/GMOS_Imagen_CampoEstelar/GMOS_Imagen_CampoEstelar.ipynb).

### GMOS_Imagen_de_Galaxia.ipynb 

Imágenes con GMOS (banda *g*) de la galaxia elíptica **NGC5018**.  
El conjunto de datos incluye *biases*, *twilight flats* y cuadros científicos.  
Enlace al [Jupyter notebook](https://github.com/astro-datalab/notebooks-latest-es/tree/master/04_ComoHacer/Reduccion_de_Datos/Ejemplos_de_reduccion_con_DRAGONS/GMOS_Imagen_de_Galaxia/GMOS_Imagen_de_Galaxia.ipynb).

### GNIRS_Imagen_EstallidoDeRayosGamma.ipynb

Imágenes con GNIRS (banda *J* – fuente puntual a través del *keyhole*) del estallido de rayos gamma **GRB120116A**.  
Este ejemplo se extrajo del tutorial **Gemini/DRAGONS GNIRS**, Ejemplo 1-B.  
El conjunto de datos incluye *flats*, *darks* y cuadros científicos (*science frames*).  
Enlace al [Jupyter notebook](https://github.com/astro-datalab/notebooks-latest-es/tree/master/04_ComoHacer/Reduccion_de_Datos/Ejemplos_de_reduccion_con_DRAGONS/GNIRS_Imagen_EstallidoDeRayosGamma/GNIRS_Imagen_EstallidoDeRayosGamma.ipynb).

### GSAOI_Imagen_GalaxiaEliptica.ipynb

Imágenes con GSAOI (*K-short*) de un campo alrededor de **NGC5128**.  
Este ejemplo se extrajo del tutorial **Gemini/DRAGONS GSAOI**, Sección 3.  
El conjunto de datos incluye *flats*, estrella estándar y cuadros científicos.  
Enlace al [Jupyter notebook](https://github.com/astro-datalab/notebooks-latest-es/tree/master/04_ComoHacer/Reduccion_de_Datos/Ejemplos_de_reduccion_con_DRAGONS/GSAOI_Imagen_GalaxiaEliptica/GSAOI_Imagen_GalaxiaEliptica.ipynb).

### NIRI_Imagen_Supernova.ipynb

Imágenes con NIRI (*K-prime*) de la supernova **SN2014J**.  
Este ejemplo se extrajo del tutorial **Gemini/DRAGONS NIRI**, Sección 4.  
El conjunto de datos incluye *flats*, estrella estándar, *darks* y cuadros científicos.  
Enlace al [Jupyter notebook](https://github.com/astro-datalab/notebooks-latest-es/tree/master/04_ComoHacer/Reduccion_de_Datos/Ejemplos_de_reduccion_con_DRAGONS/NIRI_Imagen_Supernova/NIRI_Imagen_Supernova.ipynb).

### GMOS_EnanaBlanca_rendijalarga.ipynb

Datos de rendija larga (*longslit*) de GMOS de una enana blanca tipo DB candidata **J2145+0031**.  
Este ejemplo se basa en el tutorial **Gemini DRAGONS GMOS longslit**, Sección 3.  
El conjunto de datos incluye *arcs*, *biases* y *flats* para la estrella estándar y el objeto científico.  
Este tutorial contiene código comentado que habilita el modo interactivo. Estas celdas no son necesarias para este ejemplo, pero puedes descomentarlas si deseas probar las funciones interactivas.  
Enlace al [Jupyter notebook](https://github.com/astro-datalab/notebooks-latest-es/tree/master/04_ComoHacer/Reduccion_de_Datos/Ejemplos_de_reduccion_con_DRAGONS/GMOS_EnanaBlanca_rendijalarga/GMOS_EnanaBlanca_rendijalarga.ipynb).

---

## Recursos adicionales

- **Documentación de DRAGONS:** La reducción de datos con DRAGONS está actualmente disponible para todos los datos de imágenes de los instrumentos actuales de Gemini. Se están agregando nuevos modos e instrumentos.  
  Instrucciones detalladas sobre la versión estable actual se pueden encontrar en la [página de documentación](https://dragons.readthedocs.io/en/stable/).

---

## ¿Necesitas ayuda?

¿Tienes problemas, comentarios, sugerencias o necesitas ayuda para ejecutar DRAGONS?  
Puedes contactar a los miembros de **US NGO** a través de nuestro [Portal](http://ast.noao.edu/csdc/usngo).

Si tienes problemas con el *kernel* **DRAGONS (Py3.7)** o al ejecutar los Jupyter Notebooks, comunícate con nosotros a través del **Helpdesk de Astro Data Lab**:  
https://datalab.noirlab.edu/help/

---

