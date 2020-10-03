# Kellogg  challenge
## datajam 2019 
---

### Contexto 

<img align="left" width="150" height="150" src="images/cerealdo.png">   

>De acuerdo a El Economista en su artículo “Cercanía da atractivo al canal tradicional”, el consumidor mexicano decide su lugar de compra basado en tres principales factores: cercanía (91%) –esto puede ser aún más sensible en las grandes ciudades donde los tiempos promedio de desplazamiento pueden llegar a ser de más de una hora-, pago rápido o con pocas filas (41%), y que los productos ofrecidos le hagan su vida más fácil (30%).Para mejorar la visibilidad del canal _conveniencia/tradicional_ así como las características relacionada de los consumidores,
>Esto incluye las tiendas de conveniencia, tiendas del canal tradicional  conocidas también como “la tiendita de la esquina”, o bien los formatos pequeños  de autoservicios que han desarrollado algunos grandes retailers como Superama, Fresko, City Market, etc.
>_Fuente_: [Storecheck](https://blog.storecheck.com.mx/importancia-del-canal-tradicional-en-retail)


<img align="right" width="200" height="100" src="images/Logo-INEGI.png">  

Para mejorar el entendimiento del consumidor y las Tiendas que visita del canal tradicional se puede combinar la información disponible en el portal del Instituto nacional de Estadística y Geografía [INEGI](https://www.inegi.org.mx/)

Por una parte, existe el  Directorio Estadístico Nacional de Unidades Económicas (DENUE) que mapea todas las unidades económicas y comerciales del pais; de estas nos interesan aquellas donde se pueda tener presencia de las categorías que maneja Kellogg.

Estos negocios podrían caer en los siguientes tipos:

+ Comercio al por menor en tiendas de abarrotes, ultramarinos y misceláneas
+ Comercio al por menor en minisupers
+ Comercio al por menor de otros alimentos
+ Comercio al por menor en supermercados
+ Comercio al por menor de cerveza
+ Comercio al por menor de frutas y verduras frescas
+ Comercio al por menor de semillas y granos alimenticios, especias y chiles secos
+ Comercio al por menor de leche, otros productos lácteos y embutidos
+ Farmacias con minisúper
+ Farmacias sin minisúper



Por otra parte, al incluir la información demográfica a nivel AGEB (Area Geográfica y Estadística Básica),es posible establecer una clasificación de los negocios que comparten características similares atribuibles al perfil del consumidor.




---
## Equipos Participantes


--- 

### Situación a resolver

Teniendo los datos para la zona metropolitana de la Ciudad de México; suponga que se tiene una base de datos de algunos clientes actuales y su desempeño en los productos _Top_ para 3 categorías.
Haciendo uso de la base de datos muestra y de los datos abiertos del INEGI. ¿Cuáles negocios en la periferia de los actuales se buscaría añadir a las redes de distribución actual para maximizar la posibilidad de aumento en ventas?

---

### Descripción de los datos del negocio

En este planteamiento hipotético se adjunta un archivo con los datos de las ventas para clientes de la zona metropolitána de CDMX. 


| Nombre de la Variable		| Tipo de Variable	| Descripción						|
| ------------------------- |:-----------------:| ---------------------------------:|
| Branch_Name				| str				| Nombre del centro de distribución |
| Customer_Code				| int				| Código del cliente				|
| Customer_Name				| str				| Nombre del cliente				|
| Customer_Type				| str				| Tipo de cliente					|
| Category_Name				| str			    | Categoría de producto				|
| Lat						| float				| Latitud (Coodenada)				|
| Long						| float				| Longitud (Coordenada)				|
| Product_Description		| str				| Descripción del producto			|
| Qty						| float				| Cantidad vendida al cliente       |


----
### Sugerencias

+ Filtrar los datos del INEGI + Denue solo para el área metropolitana
+ Elegir los campos de información del INEGI que permitan clasificar las características poblacionales
+ Es posible que los nombres del cliente que aparecen en la base de datos de ventas y los de DENUE no coincidan
+ Elegir bien los comercios del DENUE que hagan sentido para este tipo de productos.


---
### Fuentes de datos

>Descargas del [DENUE](https://www.inegi.org.mx/app/descarga/) para comercio al por menor.

>[Mapa](https://www.inegi.org.mx/app/mapa/denue/) interactivo DENUE

>Datos estadísticos [AGEB](https://www.inegi.org.mx/app/tmp/scitel/default?ev=7)

>Datos de muestra de ventas [Kellogg](data/sales_sample.csv)



---

## Soluciones

+ Cada equipo deberá hacer un _branch_ para subir su propuesta de solución.
+ Crear una carpeta con el nombre de equipo.
+ En esta carpeta colocar el código y todo material de soporte para justificar el desarrollo propuesto
+ Crear una liga a su carpeta en la sección de [Equipos](#Equipos-Participantes) a la carpeta anterior.



