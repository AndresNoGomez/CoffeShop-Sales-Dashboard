# CoffeeShop Sales Dashboard  

## Análisis Exploratorio de Datos (EDA) y Visualización en Dashboard de Excel  

Este proyecto analiza las ventas de la cafetería ficticia **Maven Roasters** entre enero y junio de 2023. Se ha desarrollado un **dashboard interactivo en Excel** para visualizar patrones de ventas según fecha, hora, ubicación y tipo de producto. 


![Final Dashboard](Dashboard.JPG)

---

## Organización del Proyecto  

El proyecto está estructurado de la siguiente manera:  

├── README.md   

├── Coffee Shop Sales.xlsx 

├── Dashboard.JPG    

├── Informe.pdf    

El archivo de Excel incluye las hojas:  

- **Transactions:** Datos procesados con columnas adicionales para análisis.  
- **DynamicTablesDB:** Tablas dinámicas y gráficos de apoyo.  
- **DB:** Hoja principal con el dashboard interactivo.  

---

## Descripción del Dataset  

El dataset fue obtenido de **Kaggle**: [Coffee Shop Sales Dataset](https://www.kaggle.com/datasets/f02d450f34d1dda2c29da2c31e4650dd98562f4887f4dbb1b7b3cd9ec3348191?select=Coffee+Shop+Sales.xlsx).  

Cada fila representa una **transacción individual** en una de las tres sucursales de **Maven Roasters**.  

### Columnas del Dataset  

| Columna            | Descripción | Tipo de Dato |
|--------------------|------------|-------------|
| `Transaction_ID`  | Identificador único de la transacción | Texto |
| `Transaction_date` | Fecha de la transacción | Fecha |
| `Transaction_time` | Hora de la transacción | Hora |
| `Store`           | Ubicación de la tienda | Texto |
| `Product_category` | Categoría del producto | Texto |
| `Product_type`    | Tipo de producto | Texto |
| `Product_name`    | Nombre del producto | Texto |
| `Transaction_qty` | Cantidad vendida | Entero |
| `Unit_price`      | Precio unitario ($) | Decimal |
| `Transaction_Price` | Ingreso total de la transacción (`Transaction_qty * Unit_price`) | Decimal |
| `Weekday`        | Día de la semana de la transacción | Texto |

Se añadieron las columnas **Transaction_Price** y **Weekday** para permitir un análisis más detallado.

---

## Análisis de Ventas y Conclusiones  

### Indicadores Clave  

- **214,470 productos vendidos** en seis meses.  
- **$698,812 en ingresos totales**.  
- En **junio**, el último mes del análisis, se vendieron **50,942 productos** con un ingreso de **$166,486**.  

### Tendencias Identificadas  

- **Crecimiento constante** de las ventas desde enero hasta junio.  
- **Más ventas entre semana**, con los lunes como el mejor día.  
- **Mayor actividad entre las 10 y 11 a.m.**  
- **Menos ventas entre las 5 y 8 p.m.**, especialmente en la sede de **Lower Manhattan**.  
- **Las tres tiendas tienen un rendimiento similar en ventas totales**.  
- **El café y el té representan el 75% de las ventas**, pero los productos individuales más vendidos son el **té negro Earl Grey RG** y el **chocolate caliente Dark Chocolate RG**.  

---

## Próximos Pasos  

- Analizar estrategias para **aumentar las ventas en las tardes y fines de semana**.  
- Implementar **campañas promocionales en Lower Manhattan después de las 6 p.m.**.  
- Explorar **análisis de ticket promedio y margen de beneficio por producto**.  
- Investigar patrones de **fidelización y segmentación de clientes**.  

---

## Contacto  

**Autor:** Andrés Nó Gómez  
**Email:** andresnogomez@gmail.com  


