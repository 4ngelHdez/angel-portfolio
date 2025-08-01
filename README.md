![me](/assets/img/angelgit.png)

## Acerca de mí

Soy Licenciado en Administración con una Maestría en Finanzas, un nivel de inglés intermedio (B2) y más de 10 años de experiencia trabajando en el sector minero como analista de costos, donde me especialice en el análisis de costos, monitoreo de KPI's, visualizaciones, elaboración de reportes de costos y control de presupuestos económicos, actividades con las que he impulsado mejoras medibles en el rendimiento, contribuyendo al crecimiento del negocio y a la eficiencia operativa.

#### Habilidades Técnicas: Python, SQL, Tableau, Power Bi, ETL, Excel, Dashboards.
---

## Educación
- Maestría en Finanzas | Centro de Estudios Superiores en Negocios y Humanidades (__2019__)
- Licenciatura en Administración | Instituto Tecnológico de Durango (__2016__)

## Cursos y Certificaciones
- Bootcamp para Data Analyst en Tripleten (__Mayo 2025__)
- Curso Data Analitycs de Google en Coursera (__Marzo 2024__)

## Experiencia Profesional
**Analista de costos @ Grupo Minero Bacis (__Abril 2017 - Enero 2025__)**
- Analizar datos de costos mensuales y elaborar visualizaciones que faciliten la toma de decisiones, para que faciliten la eficiencia operativa y mejor uso de los recursos.
- Monitorieo de indicadores claves de desempeño (_KPI's_) que permitan a los jefes de departamento tomar acciones en caso de que estos estuvieran por arriba de lo presupuestado.

## Proyectos

### Análisis de Prueba A/B para Optimización de Interfaz en Comercio Electrónico

**Descripción del Proyecto**  
Este proyecto consistió en el análisis de una prueba A/B realizada por una tienda en línea internacional, con el objetivo de evaluar la efectividad de una nueva interfaz que incluía un sistema de recomendaciones. Aunque la prueba fue abandonada parcialmente, se nos proporcionaron los datos para realizar una evaluación completa de su impacto. El análisis cubrió el periodo del 7 de diciembre de 2020 al 1 de enero de 2021.

**Objetivos**  
  * Verificar la calidad e integridad de los datos: duplicados, nulos y tipos de datos.<br>
  * Evaluar la equidad entre los grupos de prueba y control.<br>
  * Analizar el comportamiento de los usuarios en las diferentes etapas del embudo de conversión.<br>
  * Comparar la conversión entre la interfaz original y la interfaz con recomendaciones.<br>
  * Aplicar una prueba estadística (prueba Z) para determinar si las diferencias observadas son significativas.<br>


**Metodología**  
Utilicé Python y librerías como pandas, numpy, seaborn, plotly, scipy y statsmodels para realizar un análisis exploratorio y evaluar la validez de la prueba A/B. El trabajo incluyó:<br>

   - Limpieza de datos: conversión de fechas, detección de valores nulos y duplicados, y depuración de usuarios presentes en ambos grupos.<br>
   - Creación de embudos de conversión para visualizar el comportamiento en cada etapa: login, vista de producto, carrito y compra.<br>
   - Cálculo de métricas clave (tasa de conversión, coeficientes de variación).<br>
   - Comparación gráfica de los grupos A y B.<br>
   - Aplicación de una prueba Z para contrastar las conversiones entre interfaces.<br>

**Conclusiones**  
   * Distribución desigual de usuarios y eventos: El grupo A tenía una participación significativamente mayor en la prueba de recomendaciones (14215 eventos frente a 3979 en grupo B).<br>

   * Conversión más alta con la interfaz tradicional:<br>
      * En el grupo de control, la interfaz tradicional superó a la interfaz con recomendaciones en la conversión en todas las etapas clave (hasta 7.23% más en “purchase”).<br>
      * En el grupo de prueba, la interfaz tradicional también mostró mejores resultados (hasta 12.39% más en “product_page”).<br>

   * No se encontró una diferencia estadísticamente significativa entre los grupos, según la prueba Z (valor p = 0.099), por lo que no se rechaza la hipótesis nula.<br>

   * Recomendación: No continuar con la implementación del sistema de recomendaciones, ya que no demostró mejoras en la conversión y puede resultar contraproducente.<br>


**Lenguajes y herramientas principales**  
<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=yellow" />
  <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" />
</div>

**Visualizaciones**

A continuación, presento algunas de las visualizaciones generadas durante el análisis del mercado de videojuegos:

   <img width="674" height="450" alt="Image" src="https://github.com/user-attachments/assets/d821d613-c028-4c31-8e19-af71a59186ef" />

  Según el embudo un poco mas de 182 K usuarios hicieron login en la página.<br>
  Más de 120.8 K entraron a la página del producto.<br>
  De aquí esta un poco invertido el embudo, lo ideal sería que los usuarios primero agregaran al carrito y luego realizaran la compra pero no, más de 60.3 K usuarios realizaron la compra y alrededor de 60.1 K entraron a la página del carrito.
  
   <img width="674" height="450" alt="Image" src="https://github.com/user-attachments/assets/8918781d-9278-4fea-a686-618f6cb66e21" />

   En el grupo de control la interface normal genero mejor conversión que la nueva interface con recomendaciones para los usuarios, ya que la conversión fue mayor en las etapas del embudo:<br>
    - En la etapa de product_page por 1.94 %. <br>
    - En purchase por 7.23 %.<br>
    <br>
    Solo en la etapa de product_cart el grupo de recomendación fue mejor por 10.18%.
 
   <img width="674" height="450" alt="Image" src="https://github.com/user-attachments/assets/949f6b48-ac00-4020-85d7-099c8cfd5d66" />

   En el grupo de prueba la interface normal genero mejor conversión que la nueva interface con recomendaciones para los usuarios, ya que la conversión fue mayor en todas las etapas del embudo:<br>
    - En la etapa de product_page por 12.39 %. <br>
    - En product_cart por 0.78 %.<br>
    - En purchase por 3.00 %.

**Te invito a conocer más detalles del proyecto en el [repositorio completo](https://github.com/4ngelHdez/TestAB).**

---

### Análisis de Facturación de Empresa de Bebidas

**Descripción del Proyecto**  
En este proyecto, me enfoqué en analizar el comportamiento de la facturación y los métodos de pago de una empresa internacional de bebidas refrescantes que opera en diversos países de América Latina. El objetivo principal fue entender las tendencias de facturación y las preferencias de pago de los consumidores en las diferentes regiones donde la empresa distribuye sus productos.

**Objetivos**  
   * Estudiar y validar los datos de facturación.
   * Agrupar eventos de facturación para identificar patrones.
   * Visualizar los resultados del análisis para comprender el comportamiento de la facturación.

**Metodología**  
El proyecto se basó en el análisis de un conjunto de datos de facturación de la empresa de bebidas, cargado desde un archivo Excel. Se realizó un análisis exploratorio de los datos. Las columnas de los datos se normalizaron cambiando sus nombres a minúsculas y renombrando algunas para mayor claridad (por ejemplo, 'país' a 'pais' y 'tamaño' a 'tamano'). Se agregó una columna para extraer el año de la fecha de facturación. Se contaron las facturas por ciudad y las formas de pago utilizadas para obtener una visión general. Se agruparon los datos para obtener la suma total de ventas por tienda, por forma de pago, y por la combinación de tienda y forma de pago. Finalmente, los datos agrupados se exportaron a un archivo Excel y se crearon visualizaciones gráficas para el análisis.

**Conclusiones**
  - Guadalajara fue la ciudad con mayor número de facturas emitidas, con 13,483 operaciones, seguida por Santiago de Chile (13,075) y Buenos Aires (12,344). Ciudad de México, Bogotá y Medellín se ubicaron en cuarto, quinto y sexto lugar, respectivamente.<br>
  - Se identificaron cuatro métodos de pago principales: Crédito, Débito, Efectivo y Nequi.<br>
  - En todas las visualizaciones realizadas, se observó una tendencia consistente en la preferencia de los usuarios por el pago con tarjeta. La tarjeta de crédito fue el método preferido, seguida de cerca por la tarjeta de débito. El efectivo ocupó el tercer lugar, y Nequi, una tecnología de pago más reciente, fue la menos utilizada.

**Lenguajes y herramientas principales**  
<div style="display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px;">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=yellow" />
</div>

**Visualizaciones**

A continuación, presento algunas de las visualizaciones generadas durante el análisis de la facturación:

   <img width="674" height="450" alt="Image" src="https://github.com/user-attachments/assets/ab8d9e07-dce3-4625-9412-3647ec617023" />

  En esta gráfica se puede ver como en las diferentes tiendas se distribuye la preferencia de los usuarios por realizar sus compras con tarjeta de crédito y debito, seguido por la compra en efectivo y dejan por último el método de pago de Nequi.
  
   <img width="674" height="450" alt="Image" src="https://github.com/user-attachments/assets/5a9fe4c9-f8cf-4b93-bf95-a448bd0d6e38" />

   En esta visualización de puede observar la facturación de las ventas en las diferentes ciudades en las que se distribuye el producto, así como la preferencia de los usuarios en los métodos de pago.
 
   <img width="674" height="450" alt="Image" src="https://github.com/user-attachments/assets/06b41934-44f6-48a6-8c77-297ed4b7c362" />

   Y por último, aquí se puede observar la facturación de las ventas en los diferentes paises en los que se distribuye el producto, y de igual manera, la preferencia de los usuarios en los métodos de pago.

**Te invito a conocer más detalles del proyecto en el [repositorio completo](https://github.com/4ngelHdez/Facturacion).**

---

### Tableau Dashboards

A continuación, puedes ver uno de los dashboards que he desarrollado:
    
<div style="text-align: center; margin-top: 20px;">
  <a href="https://public.tableau.com/app/profile/angel.hernandez.sosa/viz/Proyectofinal14_17490762916930/Dashboard1?publish=yes" target="_blank">
    <img width="384" height="83" alt="Image" src="https://github.com/user-attachments/assets/3885db47-5a55-4ef9-8f2c-fd6c39f4ed36" />
  </a>
</div>

---

## Te dejo mis datos de contacto.
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:j.angel.hdez1@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/angel-hernandez-sosa/)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/4ngelHdez)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtu.be/pF1dqC3OLOI)

