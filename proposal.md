# Propuesta TP DSW

## Grupo
### Integrantes
* -	51939 - Ponzano Deluca, Benjamin 
  -	51655 - Linch, Baltasar Antonio 
  -	50715 - Felicevich, Mirko 


### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](https://github.com/BenjaPonzano/tp-backend-dsw.git)


## Tema
### Descripción
El proyecto consiste en desarrollar una tienda online especializada en la venta de camisetas de fútbol, tanto retro como actuales, de distintos clubes y selecciones. El sistema permitirá visualizar el catálogo, filtrar camisetas por club, país, época, o tipo (retro/actual), agregar productos al carrito, realizar compras y gestionar usuarios administradores para la carga y edición de productos.

### Modelo
[![image.png](https://i.postimg.cc/J7N9GPkP/image.png)](https://postimg.cc/JthTF3Kk)



## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Camiseta<br>2. CRUD Categoria<br>3. CRUD Usuario|
|CRUD dependiente|1. CRUD Camiseta {depende de} CRUD TipoProducto<br>CRUD Camiseta {depende de}  Club|
|Listado<br>+<br>detalle| 1.Lista de camisetas filtradas por club, país o época<br> 2.Detalle de una camiseta (foto, descripción, precio, etc.)
|CUU/Epic|1. Cliente agrega camisetas al carrito<br>2. Cliente realiza una compra<br>|


Adicionales para Aprobación:
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Camiseta<br>2. CRUD TipoProducto<br>3. CRUD Usuario<br>4. CRUD Direccion de envio<br>5. CRUD Precio<br>6. CRUD ...<br>7. CRUD ...|
|CUU/Epic|1. Cliente agrega camisetas al carrito<br>2.Cliente realiza una compra<br>3.Admin carga o edita productos|


