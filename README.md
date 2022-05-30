# Hotel booking analysis

#### By _**Javier Guimerans Alonso, Gerson Villalba Arana**_

### Tipología y ciclo de vida de los datos
### PRA2: Limpieza y análisis de datos

## Descripción

En la presente práctica se realizan los procesos de selección, limpieza, preparación y visualización de datos para posteriormente, realizar análisis sobre éstos.

EL dataset con el que se trata está disponible en el sigueinte repositorio de Kaggle:

https://www.kaggle.com/insatanic/hotel-booking-data-analysis.


## Estructura del proyecto

* Tanto los datos de partida, como los datos seleccionados y limpiados se encuentran en el directorio /data.

* El código fuente se encuentra en el directorio /src.

* El documento generado se encuentra en el directorio /doc.

* El video explicativo se encuentra en el directorio /video.


## Estructura de datos

El dataset tratado tiene las siguentes variables:

* **hotel**. Hotel tratado. Variable categórica.
* **is_canceled**. Especifica si la reserva ha sido (1) o no (0) finalmente cancelada.
* **lead_time**. Tiempo de antelación con la que se reservó el hotel, en días. Variable numérica.
* **arrival_date_year**. Año de comienzo de reserva. Variable numérica.
* **arrival_date_month**. Mes de comienzo de reserva. Variable numérica.
* **arrival_date_week_number**. Semana del año en el que comienza de reserva. Variable numérica.
* **arrival_date_day_of_month**. Día del mes en el que comienza de reserva. Variable numérica.
* **stays_in_weekend_nights**. Noches totales de reserva en fin de semana. Variable numérica.
* **stays_in_week_nights**. Noches totales de reserva entre semana. Variable numérica.
* **adults**. Número de adultos en la reserva. Variable numérica.
* **children**. Número de niños en la reserva. Variable numérica.
* **babies**. Número de bebés en la reserva. Variable numérica.
* **meal**. Régimen de comidas contratado. Variable categórica.
* **country**. País de procedencia de los clientes en formato ISO3. Variable categórica.
* **market_segment**. Designación de segmento de mercado. Variable categórica.
* **distribution_channel**. Canal de reserva utilizado para la reserva. Variable categórica.
* **is_repeated_guest**. Indica si el huésped ya ha reservado en el hotel previamente. Variable categórica booleana.
* **previous_cancellations**. Indica el número de veces que el cliente ha cancelado una reserva en el hotel. Variable numérica.
* **previous_bookings_not_canceled**. Indica el número de veces que el cliente ha reservado y no cancelado en el hotel. Variable numérica.
* **reserved_room_type**. Tipo de habitación reservada. Variable categórica.
* **assigned_room_type**. Tipo de habitación asignada, que puede o no coincidir con la reservada. Variable categórica.
* **booking_changes**. Cambios que se han realizado en la reserva desde que se realiza. Variable numérica.
* **deposit_type**. Indica si el cliente ha realizado un depósito o no para asegurarse la reserva. Variable categórica.
* **agent**. Identificador del agente que ha realizado la reserva. Variable categórica.
* **company**. Identificador de la compañía que ha realizado la reserva. Variable categórica.
* **days_in_waiting_list**. Número de días que la reserva estuvo pendiente de confirmación hacia el cliente. Variable numérica.
* **customer_type**. Tipo de cliente. Variable categórica.
* **adr**. Average Daily Rate. Coste promedio de la habitación por noche en la reserva. Variable numérica
* **required_car_parking_spaces**. Número de plazas de parking reservadas. Variable numérica
* **total_of_special_requests**. Cantidad de solicitudes especiales que ha realizado el huésped. Variable numérica
* **reservation_status**. Estado de la reserva. Variable categórica.
* **reservation_status_date**. Fecha de la última actualización de estado. Variable de fecha.


## Librerías necesarias

Se utilizan las siguientes librerías de R:
* tidyverse
* reshape
* psych
* MASS
* agricolae


## Licencia
Ver archivo LICENSE