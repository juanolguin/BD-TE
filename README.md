# DB-ETE
Base de datos relacional sobre las publicaciones del Trimestre Económico

Se descargaron los datos asociados a las publicaciones de la revista científica el Trimestre Económico publicada por el Fondo de Cultura Económica. Los datos obtenidos corresponden a las publicaciones disponibles en la página electrónica de la revista: http://www.eltrimestreeconomico.com.mx/index.php/te

Los datos se almacenaron en una base de datos relacional que consta de las tablas siguientes:

1) ARTICULOS: Datos bibliográficos básicos de cada publicación. La tabla contiene los siguientes campos:

i) LLAVE: Identificador único para cada publicación\
ii) ANIO: Año de la publicación\
iii) TITULO: Título de la publicación\
iv) TIPO: Clasificación asignada por la revista (Artículo, Perspectiva Económica, etcétera)\
v) VOLUMEN: Volumen de la publicación\
vi) NUMERO: Número de la publicación\
vii) PRIMERA_P: Primera página de la contribución\
viii) ULTIMA_P: Última página de la contribución\
ix) EXTENCION: Extención de la contribución\

2) AUTORES: Nombres de los autores que contribuyen en cada publicación. Los campos son los siguientes:

i) LLAVE: Identificador único para cada publicación\
ii) ID_AUTOR: Identificador para cada autor dentro de cada publicación\
iii) AUTOR: Nombre reportado en cada publicación\
iv) EST_AUTOR: Nombre estandarizado del autor (Estandarización propia)\

3) INSTITUCIONES: 

4) JEL:

5) PALABRAS CLAVE:

6) RESUMEN:

7) BIBLIOGRAFIA:
