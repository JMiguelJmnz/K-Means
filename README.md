# K-Means

Analisis de agrupacion por K-Means para generar conclusiones de acuerdo a diversas categorías utilizando la base de datos Iris

Comenzamos cargando la información junto con las librerias necesarias:
<br>![image](https://github.com/user-attachments/assets/7118964e-bafc-4fe6-aa94-dd81ad8e49bb)

Primero realizamos el analisis sin realizar ningun tipo de transformacion
<br>![image](https://github.com/user-attachments/assets/697e5960-bf6f-4f2f-a586-5e06445c0427)

Graficamos el Codo de Jambu donde es un poco complicado diferenciar si el número de
clusters óptimo seria 2 o 3
<br>![image](https://github.com/user-attachments/assets/219bc47c-d39a-4a9d-806a-3e0a17a5c71c)

Utilizamos 2 clusters
<br>![image](https://github.com/user-attachments/assets/d567c7c7-24ca-459d-9105-8043b55596dc)
<br>![image](https://github.com/user-attachments/assets/6d8e7947-b600-4db5-aac5-759af0d2a74d)
<br>![image](https://github.com/user-attachments/assets/3dafa23f-f84f-47be-97c8-48baaa925d90)

Realizando el criterio de silhouette podemos observar que dos clusters es el número óptimo a utilizar y así corroboramos el codo de jambu
<br>![image](https://github.com/user-attachments/assets/9ff3f8ae-a992-4c7d-a4b3-f53adbeaa033)

Esta vez realizamos la transformación de PCA
<br>![image](https://github.com/user-attachments/assets/0d3b4e7c-3397-4e2e-95cc-a0a5f827ceaa)

El nuevo codo de Jambu resulta muy parecido al primero pero se ve mejor la distinción en donde se encuentra el número óptimo
<br>![image](https://github.com/user-attachments/assets/51394190-fed1-4a3b-98d5-a4bdf3ae918a)

La graficacion de los clusters obtiene una mejor diferenciación esta vez
<br>![image](https://github.com/user-attachments/assets/a70d1898-bd64-413f-aa90-2aac7b6da3c5)
