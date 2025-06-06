# Propuesta TP DSW

## Grupo
### Integrantes
* -	51939 - Ponzano Deluca, Benjamin 
  -	51655 - Linch, Baltasar Antonio 
  -	50715 - Felicevich, Mirko 


### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app]([https://github.com/BenjaPonzano/tp-backend-dsw.git](https://github.com/BenjaPonzano/TP-backend-dsw-2025))


## Tema
### Descripción
El proyecto consiste en desarrollar una tienda online especializada en la venta de camisetas de fútbol, tanto retro como actuales, de distintos clubes y selecciones. El sistema permitirá visualizar el catálogo, filtrar camisetas por club, país, época, o tipo (retro/actual), agregar productos al carrito, realizar compras y gestionar usuarios administradores para la carga y edición de productos.

### Modelo
[![Modelo-Dominio-Tp-DSW.png](https://i.postimg.cc/7L0Lq6mt/Modelo-Dominio-Tp-DSW.png)](https://postimg.cc/Ty2x9R8n)



## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Distribuidor<br>2. CRUD TipoCamiseta<br>3. CRUD Usuario|
|CRUD dependiente|1. CRUD Camiseta {depende de} CRUD TipoCamiseta<br>2. CRUD Compra {depende de}  Usuario/Camiseta|
|Listado<br>+<br>detalle| 1.Lista de camisetas filtradas por club, país o época<br> 2.Historial de compra de Usuario
|CUU/Epic|1. Cargar camisetas<br>2. Realizar compra<br>|


Adicionales para Aprobación:
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Camiseta<br>2. CRUD TipoProducto<br>3. CRUD Usuario<br>4. CRUD Distribuidor<br>5. CRUD Precio<br>6. CRUD Reseña<br>7. CRUD Compra|
|CUU/Epic|1. Cargar camisetas<br>2.Realizar compra<br>3.Cancelar compra|

### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Lista de camisetas filtradas por club, país o época <br>2. Historial de compra de Usuario <br>3. Lista de distribuidores <br>4. Lista de Usuarios filtrado por Nombre y Apellido|
|CUU/Epic|1. Cargar camisetas <br>2. Realizar compra <br>3. Eliminar Usuario|
|Otros|1. Eliminar Camiseta <br>2. Agregar reseña de camiseta|



