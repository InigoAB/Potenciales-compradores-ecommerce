# Predicción de potenciales compradores de un ecommerce


## Modelo de clasificación de datos desbalanceados para la predicción de potenciales compradores de un ecommerce

Partiendo de varios datasets de datos de registro de usuarios, de actividad y de consumos de productos promocionales se trata de detectar los potenciales compradores del ecommerce. La principal particularidad es que los datos se encuentran muy desbalanceados.

![image](https://user-images.githubusercontent.com/73440358/177193000-b8fb400d-b3cc-4d2e-9ca0-607c07074fe9.png)

### Objetivos principales:
- Detectar compradores
- Detectar potenciales compradores (usuarios que no compran a los que dirigir los esfuerzos comerciales)

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
  
  ![image](https://user-images.githubusercontent.com/73440358/177192798-08b21a9f-3721-4ba8-876a-e9b05a90e921.png)
  
  * Undersampling 
    
  ![image](https://user-images.githubusercontent.com/73440358/177192513-a573ee2d-63db-409f-8eac-419e0f9888cb.png)

  
- Selección y ajuste del algoritmo final de clasificación
 
  Se detectan 379 compradores (no se logra detectar 14) y se identifican 7276 usuarios como potenciales compradores:
  
  ![image](https://user-images.githubusercontent.com/73440358/177187991-7dd4bfa0-46b2-4448-8761-7d1f55289c73.png)
  
  Observando los árboles de decisión del modelo Random Forest utilizado se pueden extraer alguna características relevantes de los compradores.

  ![image](https://user-images.githubusercontent.com/73440358/177188165-f4d07afd-5c65-410c-82db-4496a518fc90.png)

