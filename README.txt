::::::::::::::::'###:::::'######::'########:'########:::'#######::::::::::::::::
:::::::::::::::'## ##:::'##... ##:... ##..:: ##.... ##:'##.... ##:::::::::::::::
::::::::::::::'##:. ##:: ##:::..::::: ##:::: ##:::: ##: ##:::: ##:::::::::::::::
:::::::::::::'##:::. ##:. ######::::: ##:::: ########:: ##:::: ##:::::::::::::::
::::::::::::: #########::..... ##:::: ##:::: ##.. ##::: ##:::: ##:::::::::::::::
::::::::::::: ##.... ##:'##::: ##:::: ##:::: ##::. ##:: ##:::: ##:::::::::::::::
::::::::::::: ##:::: ##:. ######::::: ##:::: ##:::. ##:. #######::::::::::::::::
:::::::::::::..:::::..:::......::::::..:::::..:::::..:::.......:::::::::::::::::
:'########:::::'###::::'########::::'###:::::::'##::::::::::'###::::'########:::
: ##.... ##:::'## ##:::... ##..::::'## ##:::::: ##:::::::::'## ##::: ##.... ##::
: ##:::: ##::'##:. ##::::: ##:::::'##:. ##::::: ##::::::::'##:. ##:: ##:::: ##::
: ##:::: ##:'##:::. ##:::: ##::::'##:::. ##:::: ##:::::::'##:::. ##: ########:::
: ##:::: ##: #########:::: ##:::: #########:::: ##::::::: #########: ##.... ##::
: ##:::: ##: ##.... ##:::: ##:::: ##.... ##:::: ##::::::: ##.... ##: ##:::: ##::
: ########:: ##:::: ##:::: ##:::: ##:::: ##:::: ########: ##:::: ##: ########:::
:........:::..:::::..:::::..:::::..:::::..:::::........::..:::::..::........::::


           Bienvenido al repositorio de *notebooks Jupyter* de Astro Data Lab
                                EN ESPAÑOL


                       web: https://datalab.noirlab.edu
                    github: https://github.com/astro-datalab


                        Versión de este archivo: 20251205


::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Este archivo contiene información sobre:

- El conjunto de *notebooks Jupyter* predeterminados incluidos en las cuentas 
  de usuario  
- Cómo verificar si existen versiones actualizadas de los *notebooks*
  o si hay *notebooks* nuevos  
- Cómo contribuir *notebooks* de interés a Data Lab para uso público  

Puedes seguir el orden indicado a continuación si recién estás comenzando.

Todos los *notebooks* fueron desarrollados para Python 3. Además, se incluye 
una versión HTML de los *notebooks* para mostrarlos completamente renderizados.

NOTEBOOKS PREDETERMINADOS DE DATALAB
====================================

01- COMENZANDO

Los *notebooks* en `01_ComenzandoConDataLab/` proveen una introducción 101 
a Python, Jupyter y SQL, y muestran, para Data Lab, algunos pasos básicos como 
cargar módulos, autenticarse, generar una lista de conjuntos de datos 
disponibles, un ejemplo de consulta y un ejemplo de recorte de imagen. También 
muestran cómo obtener estadísticas de tablas de catálogos para determinar 
recuentos aproximados de filas y columnas.

02- SOBRE ACCESO A DATOS

El *notebook* en `02_SobreAccesoADatos/` provee a los usuarios ejemplos de 
funciones y comandos típicos para explorar y usar algunos de los principales 
conjuntos de datos alojados por Astro Data Lab. Es una referencia para 
aplicaciones científicas, aunque no tan detallada como los ejemplos científicos 
específicos mostrados más abajo (ítem 03).

03- EJEMPLOS DE CIENCIA

La carpeta `03_ScienceExamples/` contiene *notebooks* que muestran
aplicaciones científicas utilizando los conjuntos de datos alojados en
Data Lab. Cada aplicación científica contiene al menos un *notebook*,
y cada *survey* / conjunto de datos aparece en al menos un *notebook*.  
En algunos casos, el mismo caso científico aparece usando dos o más *surveys*.

- **AnalysisDeSeriesRRLyrae**: analizar series temporales para
  medir el período de estrellas RR Lyrae usando fotometría de SMASH.

- **DESI**: introducción al conjunto de datos DESI EDR en Data Lab y una
  comparación entre espectros de SDSS y DESI.

- **DESILegacyIS**: un notebook reproduciendo algunas gráficas del artículo de
  introducción a los Legacy Imaging Surveys de DESI, utilizando los
  conjuntos de datos Legacy Survey y el AllWISE de Data Lab.

- **DistribucionesDeEnergiaEspectral**:  
  (1) usar filtros de banda angosta para construir SEDs de objetos del conjunto de datos S-PLUS,  
  y (2) comparar la fotometría en el infrarrojo medio de unWISE y AllWISE (3.4 y 4.6 micrones).

- **EnanasBlancas**: buscar y analizar enanas blancas y otros objetos
  peculiares posiblemente eyectados del disco galáctico a velocidades
  muy altas (> 400 km/s).

- **EstructuraAGranEscala**: inspeccionar estructuras a gran escala
  utilizando información espectroscópica de SDSS combinada con
  información fotométrica de los *Legacy Surveys* (LS) del pre-imaging de DESI.

- **EstructuraGalactica**: analizar poblaciones estelares en diferentes
  partes del Plano Galáctico usando el conjunto de datos DECaPS, y en
  los campos de SMASH. Otro *notebook* explora cúmulos estelares en Gaia,
  incluyendo visualizaciones animadas.

- **ExplorandoM31**: explorar la galaxia M31 con el conjunto de datos PHAT.

- **GalaxiesConLineasDeEmision**: dos *notebooks* muestran cómo obtener y apilar
  espectros usando el servicio espectroscópico de Data Lab, y cómo
  detectar *outliers* en el diagrama diagnóstico BPT.

- **GalaxiasEnanas**: descubrir galaxias enanas como sobredensidades
  estelares en los conjuntos de datos DELVE DR1 y DR2, DES DR1,
  NSC DR1 y DR2, y SMASH.

- **GNIRS_DQS_InventarioEspectral**: muestra cómo acceder al
  **Gemini Near Infrared Spectrograph – Distant Quasar Survey
  (GNIRS-DQS)** en Data Lab y ejemplos de gráficos de espectros.

- **GOGREEN_GalaxiasEnEntornosEnriquecidos**: dos *notebooks* muestran
  acceso a datos y servicios de recortes de imágenes con la primera
  liberación de datos de GOGREEN y GCLASS, el primer programa
  Gemini Large and Long cuyos productos científicos de alto nivel están
  alojados en Data Lab.

- **NubesDeMagallanes**: examinar las subestructuras estelares que
  rodean las Nubes de Magallanes usando los conjuntos de datos VHS y Gaia.

- **Pal5ColasDeMarea**: identificar las colas de marea del cúmulo globular
  Palomar 5 en el catálogo NSC, así como en conjunto con Gaia para
  explorar el movimiento propio del cúmulo y sus colas.

- **PGIRCurvasDeLuz** 

- **SeparationesEstrellasGalQSO**: usar propiedades fotométricas (colores,
  morfología/parámetros de forma, etc.) para distinguir entre estrellas,
  galaxias y QSOs en los conjuntos de datos DES y LS.


Los notebooks de EjemplosDeCiencia se encuentran aquí:

   https://github.com/astro-datalab/notebooks-latest-es/tree/master/03_EjemplosDeCiencia/

04- COMO-HACER

La carpeta "04_ComoHacer/" contiene subcarpetas con notebooks que muestran
cómo usar los servicios de Data Lab con más detalle que los breves ejemplos
incluidos en los notebooks de Comenzando y SobreAccesoADatos. La
funcionalidad se presenta con el conjunto completo de palabras clave y
opciones para lo siguiente:

- AuthClient: autenticación en Data Lab.
- TablasCruzadas: hacer crossmatch entre una tabla provista por el usuario
                    y una tabla alojada en Data Lab, además del uso de tablas
                    precalculadas (pre-crossmatched).
- ReduccionDeDatos: mostrar cómo realizar la reducción de datos de imágenes GMOS
                 y la reducción de espectros de rendija larga GMOS usando los
                 paquetes Gemini DRAGONS y Gemini Pyraf.
- ServicioDeArchivos: uso de archivos en lugar de tablas de base de datos, incluyendo
               espectros de SDSS/BOSS.
- QueryClient: enviar consultas a las bases de datos y recuperar los resultados.
- SPARCL: descubrir, recuperar, analizar y graficar espectros (SDSS, BOSS, DESI)
          usando el servicio SPARCL.
- ServicioSia: obtener cutouts usando un servicio de Simple Image Access (SIA).
- StoreClient: almacenar datos en un almacenamiento virtual (VOSpace o MyDB).

Los notebooks de ComoHacer se encuentran aquí:

   https://github.com/astro-datalab/notebooks-latest-es/tree/master/04_ComoHacer/

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

CÓMO ACTUALIZAR LOS NOTEBOOKS
==============================

Data Lab nunca modifica los notebooks que fueron colocados en tu
directorio notebooks/ durante la creación de la cuenta. Con el tiempo,
a medida que los notebooks predeterminados evolucionan, diferirán de los
que tienes en notebooks/.

Para obtener una copia completa de los notebooks predeterminados más
recientes, haz clic en la esquina superior izquierda del panel de
JupyterLab en el ícono "+", lo cual abrirá una nueva página de
launcher. Luego, en la sección "Other", haz clic en la opción
"Terminal", donde puedes usar la función getlatest-es:

# sin argumento: copia los notebooks más recientes a un directorio con la fecha y hora actual
username@datalab>getlatest-es
Copia /dlusers/username/notebooks-latest-es/ a notebooks-es_20211118_212650/

# con un directorio de destino como argumento
username@datalab>getlatest-es mydir
Copia /dlusers/username/notebooks-latest/ a midir/

Todos los notebooks tienen una variable __version__ definida en la
primera celda. Simplemente ejecutar 'grep version foofile.ipynb'
mostrará la versión del archivo dado.

Finalmente, copias de este archivo README.txt así como los notebooks
más recientes se mantienen en la cuenta de GitHub de Data Lab:
https://github.com/astro-datalab/notebooks-latest-es/ desde donde puedes
clonarlos libremente.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

DOCUMENTACIÓN Y RECURSOS
=========================

El Manual de Usuario incluye un tutorial sobre el uso de Jupyter Notebooks con Data Lab:
https://datalab.noirlab.edu/docs/manual/UsingAstroDataLab/JupyterNotebooks/JupyterNotebooks.html

El Manual de Usuario también incluye información adicional sobre los Ejemplos de Ciencia
presentados en los notebooks:
https://datalab.noirlab.edu/docs/manual/UsingAstroDataLab/ScienceExamples/index.html

Consejos útiles sobre el uso de SQL y la escritura de consultas pueden encontrarse aquí:
https://datalab.noirlab.edu/docs/manual/UsingAstroDataLab/SQLGotchas/SQLGotchas/SQLGotchas.html

Finalmente, por favor visita el Helpdesk para ver las FAQs o hacer tus preguntas:
https://datalab.noirlab.edu/help/

