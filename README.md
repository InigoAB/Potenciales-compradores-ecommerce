# Predicción de potenciales compradores de un ecommerce


## Modelo de clasificación de datos desbalanceados para la predicción de potenciales compradores de un ecommerce

Partiendo de varios datasets de datos de registro de usuarios, de actividad y de consumos de productos promocionales se trata de detectar los potenciales compradores del ecommerce. La principal particularidad es que los datos se encuentran muy desbalanceados.

![image](https://user-images.githubusercontent.com/73440358/177189122-193316a9-9fc9-40a9-8643-9a16da3e7889.png)

### Medodología

- Exploración y  Preparación de los datos

- Estudio y reducción de características

- Selección de métricas de referencia:
  * Exhaustividad (Recall) = Compradores identificados / Compradores reales
  * Exactitud (Accuracy) = Predicciones correctas / todas las predicciones
  
  ![image](https://user-images.githubusercontent.com/73440358/177188934-45798c77-5fd2-4953-96c6-8c7817453980.png)

- Ajuste de los pesos

- Resampling:
  * Oversampling 
  
  ![image](https://user-images.githubusercontent.com/73440358/177185912-ac14ac60-4789-4df7-8bce-d70ae5b50304.png)
  
  * Undersampling 
  
  ![image](https://user-images.githubusercontent.com/73440358/177185871-f8e9e783-cce5-4a1a-b0e6-465303e5c82f.png)
  
- Selección y ajuste del algoritmo final de clasificación

  ![image](https://user-images.githubusercontent.com/73440358/177187991-7dd4bfa0-46b2-4448-8761-7d1f55289c73.png)

  ![image](https://user-images.githubusercontent.com/73440358/177188165-f4d07afd-5c65-410c-82db-4496a518fc90.png)

