# Mini-Core

Este mini-core fue realizado en express.js para el backend y react para el frontend
![image](https://github.com/ChrisNT23/MiniCore-/assets/105956304/b4852ae3-df7c-4c86-b7de-4d34df799c78)


## Descripción del proyecto
Se tienen dos tablas, una de vendedores y otra de ventas, un vendedor puede tener varias ventas.
Las ventas tienen una fecha y un monto, que son los elementos principales que se utilizan para la lógica del proyecto.

El objetivo es encontrar en un rango de fechas las ventas pertenecientes a cada ventas y mostrar cual fue el producto más vendido en dichas fechas

## Diagrama de la  Aplicación del diseño de ingeniería
![image](frontend/uploads/DiagramaMVC.png)

Primero comenzamos con el cliente realizando una acción en el aplicativo (Controladores), estos se manejan de manera conjunta tanto del lado backend, que es donde se crean estos métodos y se setean las rutas para ser consumidas desde el frontend (en este caso tenemos todos los controladores de la consulta), estos controladores manipulan los modelos definidos en la base de datos (models) estos son creados en la base de datos MongoDB con ayuda de Express y con ayuda de la biblioteca de modelado de objetos para Node.js y mongoDB mongoose. Por último con ayuda del framework REACT mostraremos toda la información al cliente cumpliéndose la estructura MVC con ayuda de las herramientas combinadas MERN (MongoDB, Express, React, Node).

