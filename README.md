 ![imagen the blinkit](https://wareiq-prelogin.s3.ap-south-1.amazonaws.com/wp-content/uploads/2024/07/22131902/Blinkit-Case-Study.png)
## Lets blink it!  😉 
 # 📊 Análisis productos BlinkIT

## Descripción del Proyecto

- Este proyecto realiza un análisis explotarotrio y modelado de datos de los productos vendidos por BlinkIT de varias tiendas según el contenido graso de los productos. El objetivo es identificar qué productos o categorías de productos son los más vendidos, de qué tiendas y cuál de ellos es el más rentable según la relación existente entre las ventas y el peso del producto.

- Para llevar a cabo el análisis he realizado un analisis exploratorio de las variables categóricas y númericas y he tenido en cuenta la correlación existente entre estas para detectar patrones de comportamiento. 

## 🗂️ Estructura del Proyecto

1. **data/**     ➡️                   *Datos crudos y procesados*

2. **src/**           ➡️                  *Scripts de procesamiento y modelado*

3. **results/**     ➡️               *Gráficos y archivos de resultados - Dashboard*

4. **README.md**    ➡️         *Descripción del proyecto*

    


## 🛠️ Instalación y Requisitos

- Excel: Microsoft® Excel® LTSC Profesional Plus 2021 MSO 64 bits 


## 📊 Resultados y Conclusiones

   - Se analizan un total de **10 tiendas** y **1559 productos diferentes**.
 
   -  El **cómputo total de productos que aparecen en todas las tiendas es de 8523** que suponen **1.201.683,89€ de ventas** con un **promedio de ventas por producto y tienda de 140,99€**. Asimismo, el **ratio de valoración es de 3,97 sobre 5**.

   - Teniendo en cuenta el **contenido graso de los productos**, identificamos que los productos bajos en grasa son los que más ventas generan (65%)

   - **Según el tamaño de las tiendas**, las de tamaño medio son las que más ventas generan, con un 42,3% de las mismas, seguidas por las tiendas de tamaño pequeño que generan un 37,0% de las ventas. Por último, las tiendas grandes generan un 20,7% de las ventas. 

   - Dentro de la **categoría de tiendas**, en conjunto, los supermercados tipo 1 son los que más ventas generan. No obstante, esto se debe a que es el que más tiendas tiene (6). Si analizamos las ventas individuales por tiendas, todas las tiendas de tipo supermercado generan un 11% de las ventas aproximadamente, independientemente del tamaño de las mismas. Son las tiendas de comestibles (Grocery) las que generan menores ventas, un 6% aproximado cada una.
 
   - Asimismo, si hacemos foco en la **ubicación de las tiendas**, las ubicadas en la zona Tier 3 son las que más ventas han generado. 

   - Por otro lado, parece que la estrategia de mostrar más parte del  producto para vender más no funciona ya que, haciendo foco en la **visibilidad de los productos**, los más vendidos son los que menos visibilidad tienen (entre 0 y 10% de visibilidad suponen un 78% de las ventas).  No obstante, haciendo foco en la distribución de las ventas dentro de cada categoria de visibilidad se observa que las ventas de los productos con mayor visibilidad se concentran en las tiendas pequeñas.
   
   ![alt text](./src/Imagenes%20readme/image-5.png)
   - Asimismo, suponiendo que cada kg de producto ocupa el mismo espacio en tienda, para analizar **qué producto es más rentable en espacio**, obtuve la **relación entre las ventas y el peso individual de los productos**. 
   Tras el análisis, a pesar de que las ventas acumuladas de los productos son similares, independientemente del peso del mismo, se detecta como a mayor peso del producto menores son las ventas que se generan por kg. 

   ![alt text](./src/Imagenes%20readme/image-6.png)

   Según los datos, más del 50% de las ventas está concentrado en los productos que nos generan entre 6 y 16 € por kg de producto. 

   ![alt text](./src/Imagenes%20readme/image-7.png)
- Por último, en relación a la **categoría de productos**, las frutas y verduras son los productos más vendidos en contraposición a los pescados que son los menos vendidos. No obstante, si tenemos en cuenta la relación anterior indicada, de ventas/kg y teniendo en cuenta todos los productos, los pescados son los segundos. De hecho, para los productos regulares en grasa son los que más €/kg generan con diferencia (22€/kg), estando en el límite inferior los productos de desayuno.

   - Distribución teniendo en cuenta todos los productos:
![alt text](./src/Imagenes%20readme/image-8.png)

   - Distribución de los productos Regular:
![alt text](./src/Imagenes%20readme/image-9.png)

   - Sin embargo, si filtramos solo por los productos bajos en grasa, los pescados son los que menos €/kg nos generan y los productos de desayuno pasan a ser los primeros.
![alt text](./src/Imagenes%20readme/image-11.png)

Por tanto, para optimizar mejor el espacio en tienda, convendría exponer estos productos.  

## 🔄 Próximos Pasos

   - Para futuros análisis, sería interesante incluir no solo las ventas de los productos, sino los costes y descuentos aplicados a los mismos. De este modo podríamos obtener el margen de beneficio por productos y tiendas. Asimismo, sería interesante incluir la cantidad de productos vendidos ya que actualmente solo se incluye un registro por producto y tienda. 

   - Asimismo, sería interesante tener un histórico de los datos para así poder hacer un análisis temporal de la evolución de los beneficios, para conocer si la empresa está creciendo y también poder predecir las ventas a futuro pudiendo estimar el stock necesario de cada producto.

   - En caso de realizar campañas de marketing, también sería necesario disponer de dicha información para analizar el impacto en las ventas y valorar si realmente fué rentable realizarla (comparándolo con el coste de la misma)

   - Por otro lado, si pudieramos tener un censo de todos los productos ofrecidos en las tiendas y del espacio que se destina a la exposición de cada uno de ellos, podríamos sacar la rentabilidad del espacio destinado a cada producto y conocer los productos que no se están vendiendo o no se venden durante un periodo de tiempo  (actualmente solo disponemos de los productos vendidos)

   -  También sería interesante identificar el ticket de la venta y la hora en la que se realizó, esto nos permitiría conocer el ticket medio de venta o saber en qué franja horaria se producen más compras para optimizar la plantilla.

   - Igualmente, si pudieramos asociar cada venta realizada con el cliente que ha realizado la compra y censáramos datos básicos del cliente (edad, sexo, etc) podríamos analizar qué productos son más comprados por cada tipología de clientes y así poder hacer campañas de marketing más eficientes o distribuir los productos según el tipo de clientes y compras que realizan. Por ejemplo, si los jóvenes están más interesados en comida saludable y la tienda está ubicada en un sitio en el que la edad media de los habitantes es baja, podríamos destinar más espacio en tienda a este tipo de productos ya que atraerá más clientela.
   

## 🤝 Contribuciones

   -  Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, por favor abre un pull request o una issue, envía un correo a vanesafloresrivera87@gmail.com o contáctame través de [linkedin](https://www.linkedin.com/in/vanesa-flores-rivera/).


## ✒️ Autores

   - **Vanesa Flores Rivera**: [linkedin](https://www.linkedin.com/in/vanesa-flores-rivera/), [github](https://github.com/VanesaFloresRivera)


