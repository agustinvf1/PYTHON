# MODELO DE REGRESIÓN LINEAL MÚLTIPLE.

# **Integrantes:**


Espindola Luciano

Val Agustín

Larroza Milagros

---
# Conclusiones

### 1. Desempeño del modelo

Para realizar este trabajo optamos por el Modelo de Regresión Lineal Múltiple y entrenamos con los datos del archivo "precio_casas". Al poner a prueba el modelo con datos nuevos, obtuvimos un coeficiente de determinacion de 0.7209 del test y de 0.7085 durante el entrenamiento, con un margen de error promedio (RMSE) de $36,587.57 por propiedad. Esto significa que nuestro modelo logra entender y explicar el 72.1% de los motivos por los que cambia el precio de una casa, logrando un buen resultado que funciona bien con propiedades que no conocía.

### 2. Variable más influyente

Al analizar los coeficientes obtenidos tras el entrenamiento, la variable con mayor influencia en la predicción fue num_cocinas, con un resultado de -55,648.73. Esto significa que, manteniendo constantes las demás variables, un incremento en la cantidad de cocinas genera una disminución significativa en el precio de la propiedad. Por otro lado, variables como num_habitaciones con un resultado de -17,819.12 también muestran un impacto negativo, mientras que aspectos como pies_cuadrados_casa con 88.94 o pies_cuadrados_garaje con 53.10 suman valor al precio total de la vivienda, el cual parte de una base intercepto de $72,196.83.

### 3. Calidad de las features

La calidad de las features seleccionadas y posibles mejoras: Las variables seleccionadas pies_cuadrados_casa, num_baños, num_habitaciones, num_cocinas, num_coches_garaje, pies_cuadrados_garaje demostraron ser buenas predictoras debido a que permitieron que el modelo explique la variabilidad de los precios, logrando un buen desempeño del 72% y una adecuada capacidad de generalización en los datos de prueba. Para mejorar la capacidad predictiva en futuras iteraciones, se sugiere incorporar nuevas variables del dataset, como la ubicación geográfica, la antigüedad de la propiedad o el tamaño total del lote, ya que en el mercado inmobiliario la relación entre el tamaño y el valor de las casas suele tener comportamientos no lineales.

### 4. Comparación

Finalmente, al comparar el rendimiento entre los datos de entrenamiento R² de 0.7085 y RMSE de  37,788.29,y los datos de prueba R² de 0.7209 y RMSE de 36,587.57, podemos observar que ambos resultados son muy cercanos. Esto demuestra que el modelo logró aprender los patrones generales sin memorizar los datos, garantizando una adecuada capacidad de generalización ante propiedades nuevas y descartando problemas de sobreajuste o subajuste**

