# Propuesta TP DSW

## Grupo

### Integrantes

- 51415 - Alesandroni, Valentino
- 51357 - Rodriguez, Martiniano

### Repositorios

- [Fullstack App](https://github.com/Lsilpituca/DSW-Project)

## Tema

### Descripción

Plataforma que conecta personas que ofrecen servicios con quienes los necesitan, de forma simple y directa. Cada usuario tiene su perfil, puede publicar lo que hace o buscar lo que necesita, y todo se gestiona desde reservas y valoraciones. Los servicios están organizados por tipo y ubicación. Por ahora, no incluye mensajería ni pagos internos, enfocándose en ser un punto de encuentro claro y funcional.

### Modelo

![imagen del DER](https://github.com/ValenAlesa/tp-DSW/blob/main/DER%20-%20DSW.drawio.png)

## Alcance Funcional

### Alcance Mínimo

_Nota_: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Servicio<br>2. CRUD Provincia<br>|
|CRUD dependiente|1. CRUD Ciudad {depende de} CRUD Ciudad<br>|
|Listado<br>+<br>detalle| 1. Listado de publicaciones filtrado por fecha|
|CUU/Epic|1. Reservar un servicio<br>2. Realizar la publicación del servicio| (charlarlo)

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD ||
|CUU/Epic||

### Alcance Adicional Voluntario

_Nota_: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

| Req      | Detalle                                                                                                                                                                                                             |
| :------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Listados | 1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes |
| CUU/Epic | 1. Consumir servicios<br>2. Cancelación de reserva                                                                                                                                                                  |
| Otros    | 1. Envío de recordatorio de reserva por email                                                                                                                                                                       |
