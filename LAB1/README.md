<br>

# Lab 1 - Definición de casos de uso y requisitos de información

<br>

## Supuesto 1: Horarios
En una universidad, el personal del PDI, el personal del PAS y los estudiantes pueden consultar horarios. Por su parte, el personal del PAS puede modificar horarios y dar de alta estudiantes. El personal de PDI puede proponer cambios en los horarios y dar de alta estudiantes. La funcionalidad de dar de alta estudiantes del PAS realiza una verificación de los datos del estudiante. Sin embargo, la funcionalidad de dar de alta estudiantes del PDI, además de verificar los datos también permite de forma excepcional realizar la búsqueda en las listas de clase de sus asignaturas.

<br>

- ### UC-01 *Buscar en lista de clase*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-01</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Buscar en lista de clase</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Daniel López García</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Posibilita la acción de buscar a un estudiante el cual acaba de ser dado de alta en el sistema en la lista de clase</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PDI</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PDI debe estar autenticado en el sistema como tal y debe haber dado de alta a un estudiante en el mismo</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para buscar en la lista de clase<br>
    2.- El sistema muestra una caja de texto para introducir el identificador del estudiante al cual se le quiere dar de alta<br>
    3.- El actor introduce el identificador del estudiante<br>
    4.- El sistema muestra los datos del estudiante además de un botón para cerrar la ventana de resultados de búsqueda<br>
    6.- El actor pulsa sobre el botón para concluir la operación de búsqueda</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema no muestra nada en caso de que el estudiante aún no haya sido dado de alta correctamente, mostrando cuáles han sido los errores para facilitar su corrección</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-04, IR-01, IR-03</td>
</tr>
</table>

<br>

- ### UC-02 *Consultar horario*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-02</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Consultar horario</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Daniel López García</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Plantea la posibilidad de consultar un horario personalizado propio</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Estudiante / PAS / PDI</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El usuario (estudiante / personal del PAS / personal del PDI) debe haber sido de alta y estar autenticado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para consultar su horario<br>
    2.- El sistema muestra una ventana donde se refleja el horario además de un botón para cerrar la ventana<br>
    3.- El actor pulsa sobre el botón para concluir la operación de consulta</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br><br></td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-01, IR-02, IR-03, IR-04</td>
</tr>
</table>

<br>

- ### UC-03 *Dar de alta estudiante*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-03</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Dar de alta estudiante</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Daniel López García</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Otorga el poder de dar de alta a un estudiante en el sistema</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PAS / PDI</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PAS / PDI debe estar autenticado en el sistema así como no lo debe estar el nuevo estudiante</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El personal del PAS / PDI pulsa sobre el botón para dar de alta a un nuevo estudiante<br>
    2.- El sistema muestra diversas cajas de texto para introducir los diferentes datos del estudiante al cual se le quiere dar de alta<br>
    3.- El personal del PAS / PDI introduce los datos del estudiante<br>
    4.- El sistema comprueba la validez de los datos y los almacena una vez determina que son correctos, mostrando un mensaje de confirmación del éxito de la operación junto a un botón para cerrar dicha notificación<br>
    6.- El personal del PAS / PDI pulsa sobre el botón para concluir la operación de búsqueda</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema considera los datos introducidos como incorrectos, marcando con color rojo las cajas de texto donde se han producido errores de algún tipo para facilitar así su corrección</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El estudiante ha sido dado de alta en el sistema y sus datos han sido almacenados en el mismo</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-04, UC-07, IR-01, IR-02, IR-03 </td>
</tr>
</table>

<br>

- ### UC-04 *Dar de alta estudiante [vista PDI]*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-04</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Dar de alta estudiante [vista PDI]</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Daniel López García</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Otorga el poder de dar de alta a un estudiante en el sistema</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PDI</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PDI debe estar autenticado en el sistema así como no lo debe estar el nuevo estudiante</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El personal del PDI pulsa sobre el botón para dar de alta a un nuevo estudiante<br>
    2.- El sistema muestra diversas cajas de texto para introducir los diferentes datos del estudiante al cual se le quiere dar de alta<br>
    3.- El personal del PDI introduce los datos del estudiante<br>
    4.- El sistema comprueba la validez de los datos y los almacena una vez determina que son correctos, mostrando un mensaje de confirmación del éxito de la operación junto a un botón para cerrar dicha notificación<br>
    6.- El personal del PDI pulsa sobre el botón para concluir la operación de búsqueda</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema considera los datos introducidos como incorrectos, marcando con color rojo las cajas de texto donde se han producido errores de algún tipo para facilitar así su corrección</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El estudiante ha sido dado de alta en el sistema y sus datos han sido almacenados en el mismo</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-01, UC-03, UC-07, IR-01, IR-03, IR-05 </td>
</tr>
</table>

<br>

- ### UC-05 *Modificar horario*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-05</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Modificar horario</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Daniel López García</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Permite realizar modificaciones en el horario por voluntad propia o atendiendo a peticiones</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PAS</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PAS debe haber sido de alta y estar autenticado en el sistema.<br>
    También se plantea la necesidad de la existencia de una propuesta de cambio en el horario en el caso de que la modificación responda a dicha petición</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para modificar el horario<br>
    2.- El sistema muestra un calendario con el horario actual sobre el cual se pueden realizar cambios<br>
    3.- El actor realiza los cambios que cree pertinentes<br>
    4.- El sistema, tras haber comprobado la validez de las modificaciones, muestra un nuevo botón cuya utilidad es la de confirmar los cambios establecidos<br>
    6.- El actor pulsa sobre el botón para concluir la operación de modificación del horario</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema comprueba la validez de las modificaciones y considera que hay uno o más errores por lo que se avisa al actor de ello, permitiéndole así que los corrija</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El cambio realizado en el horario ha sido guardado en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-02, IR-04</td>
</tr>
</table>

<br>

- ### UC-06 *Proponer cambio de horario*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-06</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Proponer cambio de horario</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Daniel López García</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Ofrece el medio necesario para realizar la propuesta de realizar un cambio en el horario</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PDI</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PDI debe haber sido de alta y estar autenticado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para proponer la acción de modificar el horario<br>
    2.- El sistema muestra una caja de texto para introducir el motivo por el cual se desea realizar un cambio en el horario<br>
    3.- El actor introduce el argumento de su petición<br>
    4.- El sistema comprueba la validez de los datos y los almacena</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema comprueba la validez de los datos y determina que no son correctos, procediendo a avisar al actor de ello permitiéndole que los corrija</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    La propuesta ha sido almacenada en el sistema y enviada al personal del PAS</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-03, IR-04</td>
</tr>
</table>

<br>

- ### UC-07 *Verificar datos*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-07</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Verificar datos</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Daniel López García</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Permite el hecho de confirmar la validez de los datos de un nuevo estudiante el cual acaba de ser dado de alta</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PAS / PDI</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PAS / PDI debe estar autenticado en el sistema, así como el estudiante cuyos datos van a ser verificados debe estar siendo dado de alta aún en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para verificar los datos<br>
    2.- El sistema muestra un mensaje de confirmación de la validez de los datos junto con un botón para el cierre de la ventana de dicho mensaje<br>
    3.- El actor pulsa sobre el botón para concluir la operación de verificación de datos</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    2.A.- El sistema comprueba la validez de los datos y determina que al menos uno de ellos no es correcto, procediendo a notificar al actor de este hecho para que este los corrija</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-03, UC-04, IR-01, IR-02, IR-03</td>
</tr>
</table>

<br>

- ### IR-01 *Estudiante*

<br>

<table align = "center">
<tr>
    <td><b>IR-01:</b></td>
    <td>Estudiante</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Daniel López García</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>UC-01, UC-02, UC-03, UC-04, UC-07, IR-02, IR-03, IR-04, IR-05</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los estudiantes de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de estudiante<br>
    - Número del documento nacional de identidad<br>
    - Nombre y apellidos<br>
    - Fecha de nacimiento<br>
    - Sexo<br>
    - Fecha de alta como estudiante<br>
    - Dirección<br>
    - Teléfonos<br>
    - Correo electrónico</td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br>

- ### IR-02 *PAS*

<br>

<table align = "center">
<tr>
    <td><b>IR-02:</b></td>
    <td>PAS</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Daniel López García</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>UC-02, UC-03, UC-05, UC-07, IR-01, IR-04</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente al personal del PAS de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de personal del PAS<br>
    - Número del documento nacional de identidad<br>
    - Nombre y apellidos<br>
    - Fecha de nacimiento<br>
    - Sexo<br>
    - Fecha de alta como personal del PAS<br>
    - Dirección<br>
    - Teléfonos<br>
    - Correo electrónico</td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br>

- ### IR-03 *PDI*

<br>

<table align = "center">
<tr>
    <td><b>IR-03:</b></td>
    <td>PDI</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Daniel López García</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>UC-01, UC-02, UC-03, UC-04, UC-06, UC-07, IR-01, IR-04, IR-05</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente al personal del PDI de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de personal del PDI<br>
    - Número del documento nacional de identidad<br>
    - Nombre y apellidos<br>
    - Fecha de nacimiento<br>
    - Sexo<br>
    - Fecha de alta como personal del PDI<br>
    - Dirección<br>
    - Teléfonos<br>
    - Correo electrónico</td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br>

- ### IR-04 *Horario*

<br>

<table align = "center">
<tr>
    <td><b>IR-04:</b></td>
    <td>Horario</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Daniel López García</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>UC-02, UC-05, UC-06, IR-01, IR-02, IR-03, IR-05</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente al horario de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de usuario al que corresponde el horario<br>
    - Listado de tramos horarios en los que se divide cada día<br>
    - Identificadores de las clases que tienen lugar en cada tramo horario<br>
    - Nota creada por el usuario para un día en específico</td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br>

- ### IR-05 *Clase*

<br>

<table align = "center">
<tr>
    <td><b>IR-05:</b></td>
    <td>Clase</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Daniel López García</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>UC-01, UC-03, UC-04, IR-01</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a las clases de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de clase<br>
    - Nombre del aulario asignado<br>
    - Nombre del aula asignada<br>
    - Número de estudiantes<br>
    - Listado de identificadores de estudiantes inscritos<br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br><br>

## Supuesto 2: Sistema de Compras
En un sistema de compra, existen cuatro tipos de usuarios: comprador, vendedor, proveedor y administrador. Los compradores pueden agregar productos, consultar precios, finalizar la compra y consultar ofertas. Agregar productos implica marcar esos productos como bloqueados. Los vendedores también pueden consultar ofertas y consultar precios. Los proveedores pueden consultar precios, avisar de nuevos productos y consultar ofertas. Avisar de nuevos productos, de forma excepcional, realiza la incorporación de una oferta. Los proveedores también tienen una funcionalidad para avisar del fin de una oferta. Cuando se avisa del fin de una oferta, se ejecuta la funcionalidad de eliminar la oferta. Ambas funcionalidades de avisar del proveedor tienen en común que se encarga de enviar una notificación. Los administradores pueden consultar precios, consultar ofertas y eliminar productos. La funcionalidad de consultar precios incluye una funcionalidad de buscar productos que es similar a la funcionalidad de consultar productos de los compradores. Sin embargo, la funcionalidad de consultar productos añade una funcionalidad para verificar la disponibilidad. Para realizar una venta, un comprador y un vendedor participan de forma conjunta. En dicha operación, se lleva a cabo el acuerdo de un precio; excepcionalmente, durante la realización de la venta, se consultará el histórico de ventas.

<br>

- ### UC-08 *Acordar precio*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-08</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Acordar precio</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-09 *Agregar producto*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-09</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Agregar producto</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-10 *Avisar*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-10</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Avisar</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-11 *Avisar de nuevo producto*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-11</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Avisar de nuevo producto</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-12 *Avisar fin de oferta*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-12</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Avisar fin de oferta</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-13 *Buscar producto*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-13</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Buscar producto</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-14 *Consultar histórico de precios*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-14</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Consultar histórico de precios</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-15 *Consultar oferta*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-15</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Consultar oferta</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-16 *Consultar precio*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-16</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Consultar precio</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-17 *Consultar producto*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-17</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Consultar producto</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-18 *Eliminar oferta*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-18</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Eliminar oferta</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-19 *Eliminar producto*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-19</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Eliminar producto</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-20 *Enviar notificación*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-20</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Enviar notificación</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    "breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "actores participantes en el caso de uso"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    "condiciones que deben cumplirse para poder ejecutar el caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    "flujo normal (feliz) de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    "flujos alternativos de ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    "condiciones que deben cumplirse al finalizar la ejecución del caso de uso"</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
</table>

<br>

- ### UC-21 *Finalizar compra*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-21</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Finalizar compra</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Finalizar la compra por parte del comprador</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    "Comprador"</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El comprador debe tener un proceso de compra abierto</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón de finalización de compra <br>
    2.- Aparece un cuadro de confirmación en el que actor debe confirmar <br>
    3.- El actor confirma
    4.- El sistema procesa la compra existente asociada al actor </td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    3.A.- El actor no confirma</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    La compra queda registrada en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-05</td>
</tr>
</table>

<br>

- ### UC-22 *Incorporar oferta*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-22</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Incorporar oferta</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Se incorpora una oferta relativa a un nuevo producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Se debe haber avisado de un nuevo producto</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa  a un botón para incorporar la oferta <br>
    2.- El actor introduce los detalles de la oferta <br>
    3.- El actor confirma la oferta <br>
    4.- El sistema carga la oferta<br></td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    3.A- El actor no confirma </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El sistema registra la nueva oferta</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-06, UC-11, UC10</td>
</tr>
</table>

<br>

- ### UC-23 *Marcar producto como bloqueado*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-23</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Marcar producto como bloqueado</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
El actor marca un producto producto como bloqueado despues de agregarlo</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
Comprador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El actor debe haber agregado el producto previamente</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
   1.- El actor señala un producto agregado <br>
   2.- Aparece una opción para bloquear el producto <br> 
   3.- El actor pulsa en la opción anterior <br>
   4.- Aparece un cuadro para confirmar o bloquear la acción
   5.- El actor confirma</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    5.A.- El actor cancela la acción</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El producto queda registrado como bloqueado en el sistema</td>
</tr>
<tr>
    <td><b>IR-05, UC9</b><br>
</td>
</tr>
</table>

<br>

- ### UC-24 *Realizar venta*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-24</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Realizar venta</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    El actor tiene la posibilidad de realizar una venta a un cliente </td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Vendedor, Comprador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Debe existe un proceso de compra abierto</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- 1.Se pulsa en un botón para realizar una venta <br>
    2.- Se abre un cuadro para introducir los datos de la venta, productos, etc <br>
    3.- El actor tiene la posibilidad de confirmar o rechazar la venta <br>
    4.- El actor acordará un precio</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    2.A.- El actor realiza una consulta un histórico de precios para obtener dicha información.</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    La venta se realiza</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
IR-05, IR-08, UC18, UC14</td>
</tr>
</table>

<br>

- ### UC-25 *Verificar disponibilidad de producto*

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-25</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Verificar disponibilidad de producto</td>
</tr>
<tr>
    <td><b>Autor:</b><br>
    Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fecha:</b><br>
    01/10/2022</td>
</tr>
<tr>
    <td><b>Descripción:</b><br>
    Permite verificar la disponibilidad de un producto, las existencias reales del producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
   Comprador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Se debe haber consultado un producto</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- Hay un producto consultado, existe la opción de verificar su disponibilidad <br>
    2.- El actor pulsa en un botón para verificar su disponiblidad <br>
    3.- El sistema le ofrece toda la información relacionada con la disponibilidad de dicho producto</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    - </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    - </td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-05, UC13 </td>
</tr>
</table>

<br>

- ### IR-04 *Administrador*

<br>

<table align = "center">
<tr>
    <td><b>IR-04:</b></td>
    <td>Administrador</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>"referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del requisito de información"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Dato 1<br>
    - Dato 2<br>
    - Dato 3<br>
    - Dato 4<br>
    - Dato 5</td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br>

- ### IR-05 *Comprador*

<br>

<table align = "center">
<tr>
    <td><b>IR-05:</b></td>
    <td>Comprador</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>"referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del requisito de información"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Dato 1<br>
    - Dato 2<br>
    - Dato 3<br>
    - Dato 4<br>
    - Dato 5</td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br>

- ### IR-06 *Proveedor*

<br>

<table align = "center">
<tr>
    <td><b>IR-06:</b></td>
    <td>Proveedor</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>"referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del requisito de información"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Dato 1<br>
    - Dato 2<br>
    - Dato 3<br>
    - Dato 4<br>
    - Dato 5</td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br>

- ### IR-07 *Usuario*

<br>

<table align = "center">
<tr>
    <td><b>IR-07:</b></td>
    <td>Usuario</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>"referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del requisito de información"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Dato 1<br>
    - Dato 2<br>
    - Dato 3<br>
    - Dato 4<br>
    - Dato 5</td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br>

- ### IR-08 *Vendedor*

<br>

<table align = "center">
<tr>
    <td><b>IR-08:</b></td>
    <td>Vendedor</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autor:</b></td>
    <td>Miguel Ángel Moncada Álvarez</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>"referencias a otros requisitos (UC o IR) cuando sea necesario"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del requisito de información"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Dato 1<br>
    - Dato 2<br>
    - Dato 3<br>
    - Dato 4<br>
    - Dato 5</td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>Muy elevada</td>
</tr>
<tr>
    <td><b>Estado:</b></td>
    <td>Aceptado</td>
</tr>
<tr>
    <td><b>Comentarios:</b></td>
    <td></td>
</tr>
</table>

<br>