# BD-TE
**Base de datos relacional sobre las publicaciones del Trimestre Económico**

Se descargaron los datos asociados a las publicaciones de la revista científica el Trimestre Económico publicada por el Fondo de Cultura Económica. Los datos obtenidos corresponden a las publicaciones disponibles en la página electrónica de la revista:<sup>a</sup>



Los datos se almacenaron en una base de datos relacional que consta de las siguientes siete tablas:

1) ARTICULOS: Datos bibliográficos básicos de cada publicación. La tabla contiene los siguientes campos:\
i) LLAVE: Identificador único para cada publicación\
ii) ANIO: Año de la publicación\
iii) TITULO: Título de la publicación\
iv) TIPO: Clasificación asignada por la revista (Artículo, Perspectiva Económica, etcétera)\
v) VOLUMEN: Volumen de la publicación\
vi) NUMERO: Número de la publicación\
vii) PRIMERA_P: Primera página de la contribución\
viii) ULTIMA_P: Última página de la contribución\
ix) EXTENCION: Extención de la contribución

2) AUTORES: Nombres de los autores que contribuyen en cada publicación. Los campos son los siguientes:\
i) LLAVE: Identificador único para cada publicación\
ii) ID_AUTOR: Identificador para cada autor dentro de cada publicación\
iii) AUTOR: Nombre reportado en cada publicación\
iv) EST_AUTOR: Nombre estandarizado del autor (Estandarización propia)

3) INSTITUCIONES: Nombres de las instituciones a las que reportan adscripción los autores. Los campos son los que siguen:\
i) LLAVE: Identificador único para cada publicación\
ii) ID_AUTOR: Identificador para cada autor dentro de cada publicación\
iii) INSTITUCION: Institución a la que los autores reportan a adscripción\
iv) EST_INSTITUCION: Nombre estandarizado y agrupado de la institución (Estandarización propia)

4) JEL: Clasificación JEL (*Journal of Economic Literature*) reportada. Se incluyen los campos siguientes:\
i) LLAVE: Identificador único para cada publicación\
ii) ID_JEL: Identificador para cada clasificación JEL usada para cada publicación\
iii) JEL: Clasificación JEL reportada

5) PALABRAS CLAVE: Palabras clave anotadas por los autores en cada artículo. Contiene los campos siguientes:\
i) LLAVE: Identificador único para cada publicación\
ii) ID_PC: Identificador para cada palabra clave usada en cada publicación\
iii) PALABRAS_CLAVE: Palabras clave reportadas\
iv) EST_PALABRAS_CLAVE: Estandarización de las palabras clave reportadas (Estandarización propia)

6) RESUMEN: Es el resumen para cada publicación considerada. Se incluyen los campos siguientes:\
i) LLAVE: Identificador único para cada publicación\
ii) TEXTO: Resumen para cada publicación

7) BIBLIOGRAFIA: Tabla formada por las fuentes bibliográficas de cada publicación: Los campos son los siguientes:\
i) LLAVE: Identificador único para cada publicación\
ii) ID_BIB: Identificador para el dato bibliográfico en cada publicación\
iii) BIB: Bibliografía reportada




<sup>a</sup> La página electrónica es la siguiente: http://www.eltrimestreeconomico.com.mx/index.php/te . Se destaca que sólo no se obtuvo la información de un artículo cuyo contenido sólo aparece en formato PDF en la página electrónica de la revista
