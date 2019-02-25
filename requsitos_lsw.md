# Especificacion de requisitos

## Requisitos de administradores

| Id | Requisito |
|:----------|:-------------|
|RF1_admin|Los administradores podŕan dar de alta a nuevos PDI.|
|RF2_admin|Los administradores podrá confirmar/validar una reserva de manera concurrente.|
|RF3_admin|Los administradores podrán realizar reservas dado un horario en formato csv.|
|RF4_admin|Los administradores podrán modificar los datos de un espacios.|
|RF5_admin|Los administradores podrán gestionar (crear,modificar y eliminar) cualquier reserva.
|RF6_admin|Los administradores podrán crear cuentas de administradores|
|RF7_admin|Los administradores podrán obtener toda la informacion de una reserva|
|RF8_admin|Los administradores podrán marcar un espacio como no reservable durante un intervalo de tiempo|

---

## Requisitos de PDI

| Id | Requisito |
|:----------|:-------------|
|RF1_PDI|El PDI podrá aplicar repetición en una reserva|
|RF2_PDI|El PDI podrá realizar una reserva de un espacio con un mes de antelación|
|RF3_PDI|El PDI podrá cambiar sus datos personales|

---

## Requisitos de estudiantes

| Id | Requisito |
|:----------|:-------------|
|RF1_user|Los estudiantes podrán realizar la reserva de un espacion con una semana de antelación como máximo|
|RF2_user|Los estudiantes podrán cambiar sus datos personales|

---

## Requisitos generales del sistema

| Id | Requisito |
|:----------|:-------------|
|RF1_gen|El sistema permitirá a todos los usuarios realizar búsquedas de los espacios dados unos criterios|
|RF2_gen|El sistema permitirá a todos los usuarios obtner toda la informacion pública de un espacio.|
|RF3_gen|El sistema permitirá a los usuarios hacer login|
|RF4_gen|El sistema permitirá a los usuarios registrarse como estudiantes con su NIA|


# Diccionario de datos

1. Criterios de búsqueda:
    - Tamaño del espacio
    - Disponibilidad de fecha
    - Tipo de espacio:
        - Laboratorio
        - Aula
        - Seminario
        - ...
    - Material disponible
2. Información pública de un espacio:
    - Nombre
    - Tamaño
    - Estado actual (reservado/no reservado)
    - Material disponible
    - ....
3. Información pública de una reserva:
    - Fecha
    - Hora inicio
    - Hora fin
3. Información privada de una reserva:
    - Reservante
    - Descripcion
    - Repetición de la reserva
4. PDI: Personal Docente e Investigador
5. NIA: Numero de Identificación de Alumno
6. Datos personales:
    - Contraseña de acceso
