# DB-ETE
Base de datos relacional sobre las publicaciones del Trimestre Económico

Se descargaron los datos asociados a las publicaciones de la revista científica el Trimestre Económico publicada por el Fondo de Cultura Económica. Los datos obtenidos corresponden a las publicaciones disponibles en la página electrónica de la revista: http://www.eltrimestreeconomico.com.mx/index.php/te

Los datos obtenidos se almacenaron en una base de datos que consta de las tablas siguientes:

1) ARTICULOS: Datos bibliográficos básicos de cada publicación. La tabla contiene los siguientes campos:

i) LLAVE: Identificador único para cada publicación
ii) ANIO: Año de la publicación
iii) TITULO: Título de la publicación
iv) TIPO: Clasificación asignada por la revista (Artículo, Perspectiva Económica, etcétera)
v) VOLUMEN: Volumen de la publicación
vi) NUMERO: Número de la publicación
vii) PRIMERA_P: Primera página de la contribución
viii) ULTIMA_P: Última página de la contribución
ix) EXTENCION: Extención de la contribución
