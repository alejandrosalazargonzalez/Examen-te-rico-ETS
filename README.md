# Examen-te-rico-ETS

## Ejercicio 1 Tienda de Comercio Electrónico

Una tienda en línea necesita un sistema que permita a los clientes comprar productos a través de un sitio web.

Como parte de los requisitos funcionales, el sistema debe incluir los siguientes procesos:

1. El cliente puede navegar por el catálogo para visualizar los productos disponibles.
2. Una vez que el cliente selecciona un producto, tiene la opción de colocar el artículo en el carrito.
3. Para completar la compra, el cliente debe realizar las siguientes acciones:
    * Informar su dirección de envío (extensión opcional si ya tiene una dirección registrada).
    * Completar los datos de su tarjeta de crédito para el pago.
4. Durante la transacción, el sistema debe:
    * Verificar los datos de la tarjeta de crédito del cliente.
    * Facturar la compra exitosamente.
    * Enviar un e-mail de confirmación con los detalles de la compra al cliente.

El sistema también debe mostrar qué partes de este flujo son obligatorias y cuáles son opcionales. A partir de los requerimientos indicados:

Diseña un diagrama de casos de uso que represente las interacciones entre el cliente, el sistema y los casos de uso necesariosy los actores implicados para realizar una compra. Usa relaciones como << include >> y << extend >> según corresponda.

<img src="Tienda_de_Comercio_Electrónico.png" alt="diagrama_de_casos_de_uso_tienda_gigital">

## Ejercicio 2: Realiza la especificación de Casos de Uso

Realiza la especificación de casos de uso de la siguiente imagen.
<img src="alguiler-pelicula-cu.png" alt="ejercicio_casos_de_uso">

|  Actor | Cliente |
|---|---|
| Descripción  | _Usuario del sistema de VIDEOMAX_  |
| Características  | _Registra cliente, Registra alquiler y Registra reserva, dependen involucran al administrador_ |
| Relaciones | __  |
| Referencias | _Proporciona Datos Personalez, Alquila Pelicula, Reserva Pelicula, Devuelve pelicula, Selecciona Pelicula_ |   
|  Notas |  __ |
| Autor  | _Alejandro Salazar González_ |
|Fecha | _18/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

|  Actor | Proveedor |
|---|---|
| Descripción  | _Proveedor de peliculas de VIDEOMAX_  |
| Características  | __ |
| Relaciones | __  |
| Referencias | _Abastece Pelicula Segùn Existencia, Abastece Pelicula_ |   
|  Notas |  __ |
| Autor  | _Alejandro Salazar González_ |
|Fecha | _18/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

|  Actor | Administrador VIDEOMAX |
|---|---|
| Descripción  | _Administrador del sistema de VIDEOMAX_  |
| Características  | _Los casos de uso  Registra Cliente, Registra Alquiler, Registra Reserva, dependen de que un cliente haga algo_ |
| Relaciones | __  |
| Referencias | _Registra Cliente, Registra Alquiler, Registra Reserva, Registra Pelicula, Actualiza Proveedor_ |   
|  Notas |  __ |
| Autor  | _Alejandro Salazar González_ |
|Fecha | _18/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |