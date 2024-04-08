# Propuesta TP DSW

## Grupo
### Integrantes
* -	51939 - Ponzano Deluca, Benjamin - com 304
  -	51655 - Linch, Baltasar Antonio - com 305
  -	50715 - Felicevich, Mirko - com 303


### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)


## Tema
### Descripción
Sistema encargado de crear torneos de Counter Strike, cualquier jugador podrá crear su equipo con otros usuarios, en caso de no tenerlo se podrá buscar equipos en los cuales falten integrantes. Los equipos podrán anotarse a los torneos que deseen siempre y cuando cumpla con los requisitos de estos. Cada jugador contara con un nivel con respecto a su habilidad de juego, rescatado de las partidas jugadas en torneos creados por el sistema.

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


