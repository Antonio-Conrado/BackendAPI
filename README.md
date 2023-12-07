
# Proyecto Tienda de Zapateria
# API REST de Zapatería

Esta API REST se creo con ASP.NET Core Web API y proporciona una interfaz para realizar operaciones CRUD en varias entidades, como productos, categorías, roles, ventas y vista.
## Requisitos previos

* .Net 7.0
* Visual Studio 2022 Version 17.7.6 en adelante
* SQL Server

## Instalación

1. Clona el repositorio de GitHub
2.  Ejecuta BD.sql en SQL Server Management Studio

##### Enpoints de la API Rest

Los siguientes endpoints están disponibles para las siguientes entidades:

**Categoria:**  Operaciones CRUD para categorías.

**Marca:** Permiten a los usuarios consultar las marcas disponibles.

**Talla:** Permiten a los usuarios consultar las tallas disponibles.

**Rol:** Operaciones CRUD para Rol.

**Venta:** Permiten a los usuarios consultar registrar nuevas ventas.

**Inventario:** Operaciones CRUD para Inventario.

**Usuario:**  Operaciones CRUD para Usuario, además se utilizó bcrypt para el hash de la contraseña en la base de datos y se añadio el endpoint para autenticarse.

**Vista:**  Operaciones CRUD para vistas.

#### Captura de un endpoint para obtener la lista de Roles a traves de swagger
![](https://iili.io/JIqyaAQ.png)

#### Captura de la clave Acceso de un usuario utilizando Bcrypt en la base de datos
![](https://iili.io/JIBRXgs.jpg)

### Para autenticarse utilizar los datos del archivo Usuarios.txt
