# AluraStore

Este proyecto analiza el desempeño financiero y de satisfacción del cliente de **cuatro tiendas** usando Python y visualización de datos. El objetivo es determinar cuál tienda debería ser cerrada o vendida, con base en métricas como ingresos, costos de envío, rentabilidad y calificaciones de los clientes.

## 📊 Datos utilizados

Se utilizan archivos CSV públicos alojados en GitHub, correspondientes a las ventas de las cuatro tiendas:

- `tienda_1.csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Cada archivo incluye información como:
- Producto vendido
- Categoría
- Precio
- Calificación del cliente
- Costo de envío

## ⚙️ Tecnologías

- Python 3
- pandas
- matplotlib

## 📈 Métricas calculadas

- **Facturación total (mdp)** por tienda
- **Calificación promedio** de cada tienda
- **Costo de envío promedio y total**
- **Rentabilidad** (Ingresos - Costo total de envío)
- Productos más y menos vendidos por tienda
- Distribución de ventas por categoría

## 📊 Visualizaciones

- Gráfico combinado: facturación vs. costo promedio de envío
- Gráfico de barras horizontales: calificación promedio
- Gráfico de pastel: distribución de rentabilidad por tienda

## 📌 Conclusiones y recomendaciones

- La **Tienda 4** es la menos rentable, a pesar de tener el **costo de envío promedio más bajo**, por lo que se recomienda **cerrar o vender** esta tienda.
- La **Tienda 1**, aunque tiene la **calificación más baja** y el **costo de envío más alto**, es la más rentable. Se recomienda **mejorar la atención al cliente** para elevar su calificación, lo cual podría aumentar aún más sus ventas.
  
## 🚀 Cómo ejecutar

1. Abre el notebook en Google Colab o Jupyter.
2. Asegúrate de tener instaladas las dependencias: pandas y matplotlib

## Autor
Proyecto realizado por Lauro Rodríguez, como parte del Challenge de Data Science de Alura LATAM.
