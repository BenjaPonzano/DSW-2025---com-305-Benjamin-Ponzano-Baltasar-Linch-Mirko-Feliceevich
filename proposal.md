# Propuesta TP DSW

## Grupo
### Integrantes
* -	51939 - Ponzano Deluca, Benjamin
  -	51655 - Linch, Baltasar Antonio
  -	50715 - Felicevich, Mirko


### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
Sistema encargado de crear torneos de Counter Strike, cualquier jugador podrá crear su equipo con otros usuarios, en caso de no tenerlo se podrá buscar equipos en los cuales falten integrantes. Los equipos podrán anotarse a los torneos que deseen siempre y cuando cumpla con los requisitos de estos. Cada jugador contara con un nivel con respecto a su habilidad de juego, rescatado de las partidas jugadas en torneos creados por el sistema.

### Modelo
![image](https://github.com/BenjaPonzano/tp/assets/164565109/08c5b23e-e60d-4bac-b0a7-421d774baff3)



## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Torneo<br>2. CRUD Equipo<br>3. CRUD Jugador|
|CRUD dependiente|1. CRUD Equipo {depende de} CRUD Jugador<br>2. CRUD Torneo {depende de} CRUD CreadordeTorneo|
|Listado<br>+<br>detalle| 1.Listado de torneos filtrado por un nivel necesario, muestra hora y fecha de inicio, hora fin de ingreso y cupo disponible=> detalle CRUD Torneo<br> 2.Listado de equipos filtrado por numero de participantes, muestra nombre de equipo y nivel promedio=> detalle CRUD Equipo
|CUU/Epic|1. Crear equipo<br>2. Anotarse a torneo|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Torneo<br>2. CRUD Equipo<br>3. CRUD Jugadoor<br>4. CRUD Creador de torneo<br>5. CRUD Sistema<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

