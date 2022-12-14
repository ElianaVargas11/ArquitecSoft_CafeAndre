# SISTEMA DE INFORMACION PARA LA GESTION DE VENTAS “CAFÉ ANDRE”
### PROBLEMA
La principal inquietud que presenta Café André, ha nacido de la problemática existente debido a los grandes
crecimientos que han experimentado los flujos de información con los cuales se hace cada vez más necesaria la 
idea de contar con un sistema de información con el cual poder controlar, procesar y almacenar las ventas realizadas,
y a la vez poder desempeñar la labor de caja de una manera automática al final de cada jornada. Debido al crecimiento de la información 
se hace más difícil y lento el acceso a la misma, por lo que el poder contar con ésta en tiempo real mediante el sistema actual se hace imposible,
es decir, no existe interpretación de los datos, situación que en algunas circunstancias afecta gravemente a una buena toma de decisiones. 
Se pretende apuntar a una automatización en el control de las ventas, con el fin de mejorar el negocio y poder contar con un sistema que gestione 
de una manera más dinámica, manteniendo el orden y mejorando el negocio. 
### PROPUESTA GENERAL DE SOLUCIÓN
El presente proyecto está dirigido a la administración de información de la Cafetería “CAFÉ ANDRE” realizando un sistema de información para agilizar
la gestión de ventas, atención al cliente, pedidos y realizar el importe total por concepto de consumo de cada cliente. Permitiendo así un mejor manejo del negocio,
que de confianza y entregue información importante y de manera eficiente, facilitando las labores administrativas.
### VALOR PARA EL NEGOCIO
Implementar un sistema de información que agilice la gestión de ventas, pedidos, realice el importe total a pagar por el cliente y
genere reportes estadísticos de cada producto y de las ventas  realizadas por intervalos de tiempo y productos más vendidos.
### TANGIBLE
- Tener control de las ventas realizadas por empleado.
- El sistema realizara estadísticas de ventas de productos de más y menos requerido por los clientes, por lo que ayudara a evitar la compra de exceso de insumos innecesarios.

### INTANGIBLE
- Información completa de las ventas realizadas.
- Reducir errores del cajero al momento de realizar cálculos por pedido.


## FACTIBILIDAD (ANÁLISIS DE RIESGOS)
### ECONÓMICA
- El sistema costara 15.000 bs.

### TÉCNICA
- Lenguajes de programación: Angular, HTML5  y  Bootstrap.
- MySql para diseño de la base de datos.
- Spring Boot 

### LISTADO DE REQUERIMIENTOS CON HISTORIAS DE USUARIOS

| Código | RF1 |
| ------------- | ------------- |
| Nombre  | Inicio de Sesion de la aplicación  |
| Prioridad  | Alta/Escencial |
| Descripción  | Inicio de sesion del software para su ingreso al sistema por medio de usuario y contraseña validando datos de ingreso. |


| Código | RF2 |
| ------------- | ------------- |
| Nombre  | Registro de Usuarios  |
| Prioridad  | Alta/Escencial |
| Descripción  | El software almacenara los datos de los usuarios que están autorizados para manipuar (Administrador,Cajero). |


| Código | RF3 |
| ------------- | ------------- |
| Nombre  | Registro de Ventas  |
| Prioridad  | Alta/Escencial |
| Descripción  | Se realizará el registro de las ventas que se realicen por el servicio de preparación de refrigerio, bebida, postres u otros. Se detallara código de recibo, fecha, nombre del cliente y el total del importe. |


| Código | RF4 |
| ------------- | ------------- |
| Nombre  | Registro de Pedido |
| Prioridad  | Alta/Escencial |
| Descripción  | Los datos de los productos  que consumirá el cliente serán registrados  como pedido.|


| Código | RF5 |
| ------------- | ------------- |
| Nombre  | Registro de Menu |
| Prioridad  | Medio/Deseado |
| Descripción  | El software almacenara el menú que se ofrece con distintos productos, el usuario administrador podrá ir añadiendo.|


| Código | RF6 |
| ------------- | ------------- |
| Nombre  | Consulta de Usuarios |
| Prioridad  | Medio/Deseado |
| Descripción  | Permitirá a los administradores registrar, buscar, editar y listar los datos de empleados. |



| Código | RF7 |
| ------------- | ------------- |
| Nombre  | Realizar venta |
| Prioridad  | Alta/Escencial |
| Descripción  | Al terminar el pedido, se realizara la venta por el producto, el sistema realizara la emisión del importe.|


| Código | RF8 |
| ------------- | ------------- |
| Nombre  | Generar Reportes desde el sistema |
| Prioridad  | Alta/Escencial |
| Descripción  | El sistema debe generar un reporte en Excel o pdf sobre ventas realizadas escogidas en un rango de tiempo por el usuario.|









