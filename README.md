El documento contiene información de los resultados de las reviews de alojamientos en Airbnb. El objetivo es predecir si el rating del alojamiento podrá alcanzar las 4 estrellas o no. Las hipótesis serán: 
 -La ubicación del alojamiento tiene impacto sobre el rating
 -La política de mínimo de noches a contratar influye a la hora de que el cliente establezca una reseña. 
 -La fecha de la última review se vincula con el nivel de compromiso o desconformidad del cliente.
 
Las variables que se les dará mayor importancia con este fin son:
  -review_rate_number: representa el rating promedio que se le ha dado al alojamiento. Es la variable que se busca predecir.
  -minimum_nights: indica el mínimo de noches que por política de
  -neighbourhood: representa la ciudad del alojamiento.
  -last_review: fecha de la última review.

Otras variables:
  -id: número único de identificación del alojamiento.
  -name: nombre del alojamiento.
  -host_id: id de identificación del host.
  -host_identity_verified: verifica si existe o no identidad del host.
  -host_name: indica primer nombre del host.
  -neighbourhood_group: agrupación de neighbourhood.
  -lat: coordenada de latitud del alojamiento.
  -long: coordenada de longitud del alojamiento.
  -instant_bookable: política de booking, puede ser instantánea (true) o con aceptación del alojamiento (false).
  -cancellation_policy: política de cancelación.
  -room_type: tipo de apartamento.
  -construction_year: año de construcción del alojamiento.
  -price: precio por noche del alojamiento.
  -service_fee: tasa por servicio.
  -number_of_reviews: cantidad de reviews.
  -reviews_per_month: reviews por mes promedio.
  -availability_365: disponibilidad de habitaciones a lo largo del año (sumatoria de disponibilidad de habitaciones en cada día a lo largo de últimos 365 días).
  -house_rules: breve texto que declara reglas del alojamiento.
  
  
