# Propuesta "ESTACIONAMIENTO"

## Grupo
### Integrantes
* 50249 - Papaolo, Francisco    papaolofrann@gmail.com
* 49621 - Renzi, Alvaro         alvarorenzivillani@gmail.com

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)

## Tema
### Descripción
Se desarrollará un sistema de gestión para un estacionamiento de vehículos, en el que los usuarios puedan registrarse, reservar plazas de estacionamiento, saber el precio a pagar según su tipo de vehículo y la duración de la reserva entre otras cosas. También buscamos facilitar la administración del estacionamiento para el encargado de dicha tarea.


### Modelo 
imagen del DER: https://drive.google.com/file/d/1AzC9rFicjhewpsGT7enKgLsjp75MPD0c/view?usp=drive_link

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Plaza<br>|
|CRUD dependiente|1. CRUD Plaza {depende de} CRUD Tipo Plaza<br>|
|Listado<br>+<br>detalle| 1. Listado de Plazas filtrado por tipo de plaza, muestra nro y tipo de plaza => detalle CRUD Plaza<br>|
|CUU/Epic|1. Se adaptan 5 plazas para personas discapacitadas|


(Sera planteado en la proxima entrega los temas que se encuentran por debajo de este parentesis)

Adicionales para Aprobación 
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

