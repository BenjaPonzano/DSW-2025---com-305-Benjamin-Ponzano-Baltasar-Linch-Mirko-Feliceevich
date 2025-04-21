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
![image](https://github.com/BenjaPonzano/tp/assets/164565109/08c5b23e-e60d-4bac-b0a7-421d774baff3)



## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Torneo<br>2. CRUD Equipo<br>3. CRUD Jugador|
|CRUD dependiente|1. CRUD Equipo {depende de} CRUD Jugador<br>2. CRUD Torneo {depende de} CRUD CreadordeTorneo|
|Listado<br>+<br>detalle| 1.Listado de torneos filtrado por un nivel necesario, muestra hora y fecha de inicio, hora fin de ingreso y cupo disponible=> detalle CRUD Torneo<br> 2.Listado de equipos filtrado por numero de participantes, muestra nombre de equipo y nivel promedio=> detalle CRUD Equipo
|CUU/Epic|1. Crear equipo<br>2. Buscar Torneo del nivel del equipo e inscribirse|


Adicionales para Aprobación:
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Torneo<br>2. CRUD Equipo<br>3. CRUD Jugadoor<br>4. CRUD Creador de torneo<br>5. CRUD Sistema<br>6. CRUD ...<br>7. CRUD ...|
|CUU/Epic|1. Crear equipo<br>2.Buscar Torneo del nivel del equipo e inscribirse<br>3. Enviar solicitud de ingreso a un equipo|


