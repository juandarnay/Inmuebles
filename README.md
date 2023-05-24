# Inmuebles
Conjunto de datos de inmuebles de la República Argentina y Uruguay

Estructura de los datos
Los conjuntos de datos siguen el siguiente esquema:

id - Identificador del aviso. No es único: si el aviso es actualizado por la inmobiliaria (nueva versión del aviso) se crea un nuevo registro con la misma id pero distintas fechas: de alta y de baja.
start_date - Fecha de alta del aviso.
end_date - Fecha de baja del aviso.
created_on - Fecha de alta de la primera versión del aviso.
lat - Latitud.
lon - Longitud.
l1 - Nivel administrativo 1: país.
l2 - Nivel administrativo 2: usualmente provincia.
l3 - Nivel administrativo 3: usualmente ciudad.
l4 - Nivel administrativo 4: usualmente barrio.
l5 - Nivel administrativo 5
l6 - Nivel administrativo 6
rooms - Cantidad de ambientes (útil en Argentina).
bedrooms - Cantidad de dormitorios (útil en el resto de los países).
bathrooms - Cantidad de baños.
surface_total - Superficie total en m².
surface_covered - Superficie cubierta en m².
price - Precio publicado en el anuncio.
currency - Moneda del precio publicado.
price_period - Periodo del precio (Diario, Semanal, Mensual)
title - Título del anuncio.
description - Descripción del anuncio.
property_type - Tipo de propiedad (Casa, Departamento, PH).
operation_type - Tipo de operación (Venta, Alquiler).
