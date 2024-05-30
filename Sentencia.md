# Tarea de la semana 8.
## 1. Cuantos productos no tiene registro el país de origen:
 - Sentencia:
  ```
SELECT COUNT (*) - COUNT(country_of_origin) AS products_without_country
FROM product;
  ```
-Captura.

![Captura de pantalla 2024-05-30 154945](https://github.com/CarlosQ18a/Tareas-Deberes/assets/146890782/9b38d72f-6076-4c75-9704-f57a1dbac1d2)

## 2. Numero de clientes por ciudad.
 - Sentencia:
  ```
  SELECT DISTINCT city, COUNT(city) FROM client GROUP BY (city) ....
  ```
-Captura.

![image](https://github.com/CarlosQ18a/Tareas-Deberes/assets/146890782/4c054234-eb41-4375-bfb6-5cf33688b8fe)
