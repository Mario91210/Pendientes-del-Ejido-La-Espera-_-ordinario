# Pendientes-del-Ejido-La-Espera-_-ordinario
Mario González Dimas      
                                                                  mgonzalez26@ucol.mx     
(Facultad de Ingeniería Civil, carretera Coquimatlán-Colima km 9 código postal 28400
Resumen
En este proyecto se prevé hacer un mapa temático del ejido la esperanza el cual con-tenga las características junto con las pen-dientes, de poder leerlo y saber que se pue-de sembrar en el área a estudiar ya que es fundamental saber este tipo de cultivos te-niendo el estudio adecuado.
Palabras clave: Sembrar, Cultivo, Mapa Temático, Pendiente, Ejido.                                                                                                                                   
Abstract
In this project it is planned to make a themat-ic map of the ejido, the hope which contains the characteristics along with the slopes, to be able to read it and know that it can be sown in the area to be studied since it is es-sential to know this type of crops having the appropriate study.
Keywords: 
	Sowing, Cultivation, Thematic Map, Earrings, Ejido.
  
  
INTRODUCCION 
En el proyecto se utilizará un conjunto de datos vectoriales descargados desde la pá-gina del INEGI los cuales nos permitirán crear una representación gráfica (Mapa) en ArcMap de las distintas clases de pendientes aptas para el cultivo de maíz, caña y gana-dería, teniendo en cuenta que las pendientes demasiado inclinadas no son favorables de-bido a que existe una gran pérdida de te-rreno a causa de la erosión del mismo, ade-más se aprovecha más un terreno plano o con menor pendiente. En algunos casos la pendiente es importante para poder colocar un sistema de riego; es muy favorable tener pendientes en el terreno para que con ayuda de la gravedad el agua pueda llegar a su destino de riego.
Con la ayuda de la programación asignare-mos una clasificación correspondiente a la pendiente conveniente para el cultivo y la ganadería, que automáticamente dándole la clase de pendiente asignará para qué es apta esa área. 

DESARROLLO

Para desarrollar este programa se tiene que utilizar un paquete de Python que proporciona los diferentes pendientes que tiene el ejido a estudiar con la he-rramienta de los sistemas de informa-ción Geográfica como lo es QGIS.

1.-   Se tiene que importar e instalar la librería usada la cual es openpyxl ya que con ella se basara nuestro proyec-to.

 ![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/1.png)

2.- Para poder leer el programa se debe tener el ejido a estudiar como shp para 
![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/2.1.png)

3.-Se toman y verifican las características del terreno a estudiar para poder tener los cálculos necesarios.
![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/3.png)

4.-Se imprimen los datos correspondientes para poder correr el programa.
![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/4.png)

5.-Se especifica lo que se tiene que im-primir mediante la tabla de atributos del ejido.
![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/5.png)

6.-Al poner la condición en el programa en Python se denominará dependiendo de los grados el cultivo para lo cual es buena esa área, ya sea agrícola o de agricultura.
![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/6.0.png)

7.- El resultado es que el mapa a realizar junto con el programa señale con dife-rentes colores las diferentes pendientes las cuales puedan ser de buena utilidad.
![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/mapa.png)

MANEJO DE DATOS 
El tipo de datos que se manejan en el programa son:

Datos geoespaciales: son requeridos para la localización de las curvas de nivel del ejido y el sistema de referen-ciación.

Lenguaje de programación: para lo-grar crear el programa y este ejecute correctamente lo que se pide.

Sistemas de Información Geográfica: los SIG importantes para el desarrollo de la localización de cada zona apta para el cultivo.

Excel
Es un programa informático desarrolla-do y distribuido por Microsoft Corp

Sistema Operativo
El programa está diseñado para trabajar en el Sistema Operativo Windows. 

Equipo utilizado 
El equipo en el cual fue probado el pro-grama es una computadora portátil de la marca Hp pavilion con las siguientes características
![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/7.png)

RESULTADOS

Lo que se logró obtener con el código fue un programa en el cual se le inser-tan los diferentes ángulos de las pen-dientes que tiene nuestro ejido para ob-tener el uso de suelos y que se pueda usar en   ámbito de la agricultura.

En el siguiente código se producen des-de el Angulo mínimo    hasta el ángulo máximo 
![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/tabla1.png)
![PalabrasdelTextoalternativo](https://github.com/Mario91210/Pendientes-del-Ejido-La-Espera-_-ordinario/blob/master/Imagenes/PORTADA.png)

Con la tabla mostrada anteriormente, generamos una gráfica de pastel en la que se pueden observar las diferentes pendientes que existen en el Ejido la Esperanza.
-Maíz	0º-5º
-Caña	5º-45º
-Café 	<45º

CODIGO 
import openpyxl
import PIL

#ELE es abreviación de Ejido La Esperanza
doc = openpyxl.lod_workbook("ELE")

selecciom = hoja['B2':'D5']
for fials in seleccion:
    for columnas in filas:
        print (columnas.coordinate, colum-nas.valie)
    print ("---Final de Fila---")

#Si desea ver la imagen del area de estudio indique "y"
run = raw_input("Decea ver el Ejido de estudio y/n\n")

from PIL import Image
#Para que la imagen pudea ser mostradra de-bera de indicarse con el nombre de la imagen
def show(path_name):
    image = ()
image.open(path_name)=
    image.show()
show()    

CONCLUSIÒN
En conclusión, puedo asumir que el cálculo de pendientes en este proyecto es importante para los ejidatarios de esa comunidad, poder conocer las con-diciones aptas para el cultivo que les convenga, ya que en este ejido es con-veniente y por facilidad de la zona la producción agrícola del maíz, y es in-dispensable tener espacialmente el con-trol mediante un estudio de suelos.
Sabiendo que la ubicación de este ejido es rica en recursos agrícolas, por lo que se debe agilizar con las pendientes co-rrectas los cultivos que convengan y sobre todo se produzca con los cuida-dos correspondientes.










