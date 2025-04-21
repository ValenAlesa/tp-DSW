# Propuesta TP DSW

## Grupo
### Integrantes
* 51415 - Alesandroni, Valentino
* 50470 - Silpituca, Lorenzo
* ..... - Rodriguez, Martiniano

### Repositorios
* [Fullstack App](https://github.com/Lsilpituca/DSW-Project)

## Tema
### Descripción
Plataforma que conecta personas que ofrecen servicios con quienes los necesitan, de forma simple y directa. Cada usuario tiene su perfil, puede publicar lo que hace o buscar lo que necesita, y todo se gestiona desde reservas y valoraciones. Los servicios están organizados por tipo y ubicación. Por ahora, no incluye mensajería ni pagos internos, enfocándose en ser un punto de encuentro claro y funcional.

### Modelo
![imagen del modelo de dominio](https://drive.google.com/file/d/19VxkmKn1wPJuhsqC5kBZvtcKO5uo2C6n/view?usp=sharing)
![imagen del DER](https://drive.google.com/file/d/1rXAAGGF4su6ZZzDrimdi9e0aV_5lAfNK/view?usp=sharing)

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Habitación {depende de} CRUD Tipo Habitacion<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva|


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

