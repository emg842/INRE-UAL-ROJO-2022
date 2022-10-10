<br>

# Lab 1 - Definición de casos de uso y requisitos de información

<br>

## Supuesto 1: Horarios

En una universidad, el personal del PDI, el personal del PAS y los estudiantes pueden consultar horarios. Por su parte, el personal del PAS puede modificar horarios y dar de alta estudiantes. El personal de PDI puede proponer cambios en los horarios y dar de alta estudiantes. La funcionalidad de dar de alta estudiantes del PAS realiza una verificación de los datos del estudiante. Sin embargo, la funcionalidad de dar de alta estudiantes del PDI, además de verificar los datos también permite de forma excepcional realizar la búsqueda en las listas de clase de sus asignaturas.

<br>

- ### UC-01 _Buscar en lista de clase_

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
    Posibilita la acción de buscar a un estudiante en las listas de clase de sus asignaturas como paso previo a su dada de alta en el sistema</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PDI</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PDI debe estar autenticado en el sistema y debe encontrarse en la fase inicial del proceso de dada de alta a un estudiante en el mismo</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para buscar a un estudiante en las listas de clase de sus asignaturas<br>
    2.- El sistema muestra una nueva ventana la cual cuenta con dos cajas de texto para introducir el identificador del estudiante al cual se le quiere dar de alta y el identificador de una asignatura la cual va a ser cursada por el mismo<br>
    3.- El actor introduce el identificador del estudiante y el de la asignatura<br>
    4.- El sistema muestra los datos del estudiante además de un botón para cerrar la ventana de resultados de búsqueda<br>
    5.- El actor pulsa sobre el botón para concluir la operación de búsqueda</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema muestra un mensaje el cual notifica la no presencia del alumno cuyo identificador se corresponde al introducido en la caja de texto en la lista de clase de la asignatura en cuestión, junto con un botón para cerrar la ventana de resultados de búsqueda</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-04, IR-03, IR-05</td>
</tr>
</table>

<br>

- ### UC-02 _Consultar horario_

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
    2.- El sistema muestra una ventana donde se reflejan los horarios además de un botón para cerrar la misma<br>
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

- ### UC-03 _Dar de alta estudiante_

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
    Otorga el poder dar de alta a un estudiante en el sistema</td>
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
    1.- El actor pulsa sobre el botón para dar de alta a un nuevo estudiante<br>
    2.- El sistema muestra diversas cajas de texto para introducir los diferentes datos del estudiante al cual se le quiere dar de alta<br>
    3.- El actor introduce los datos del estudiante<br>
    4.- El sistema comprueba la validez de los datos [UC-07] y los almacena una vez determina que son correctos, mostrando un mensaje de confirmación del éxito de la operación junto con un botón para cerrar dicha notificación<br>
    5.- El actor pulsa sobre el botón para concluir la operación de dada de alta del estudiante</td>
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

- ### UC-04 _Dar de alta estudiante [vista PDI]_

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
    1.- El actor pulsa sobre el botón para dar de alta a un nuevo estudiante<br>
    2.- El sistema muestra diversas cajas de texto para introducir los diferentes datos del estudiante al cual se le quiere dar de alta junto con un botón cuya función es la de realizar una búsqueda del estudiante en las listas de clase de sus asignaturas<br>
    3.- El actor introduce los datos del estudiante<br>
    4.- El sistema comprueba la validez de los datos [UC-07] y los almacena una vez determina que son correctos, mostrando un mensaje de confirmación del éxito de la operación junto con un botón para cerrar dicha notificación<br>
    5.- El actor pulsa sobre el botón para concluir la operación de dada de alta del estudiante</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    3.A.- El actor pulsa el botón encargado de la búsqueda del estudiante en las listas de clase de sus asignaturas e introduce el identificador de este y el de una asignatura en cuestión en una nueva ventana emergente la cual está compuesta por dos cajas de texto [UC-01]. Si el estudiante ya aparece como resultado de la búsqueda, se detiene el proceso de dada de alta en el sistema. En caso contrario, el sistema notifica lo sucedido y vuelve a mostrar la ventana compuesta por diferentes cajas de texto en las que poder introducir los datos para poder seguir así con el proceso inicial<br>
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

- ### UC-05 _Modificar horario_

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
    Permite realizar modificaciones en los horarios por voluntad propia o atendiendo a peticiones</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PAS</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PAS debe haber sido de alta y estar autenticado en el sistema.<br>
    También se plantea la necesidad de la existencia de una propuesta de cambio en los horarios en el caso de que la modificación responda a dicha petición</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para modificar los horarios<br>
    2.- El sistema muestra un calendario con los horarios actuales sobre los cuales se pueden realizar cambios<br>
    3.- El actor realiza los cambios que cree pertinentes<br>
    4.- El sistema, tras haber comprobado la validez de las modificaciones, muestra un nuevo botón cuya utilidad es la de confirmar los cambios establecidos<br>
    5.- El actor pulsa sobre el botón para concluir la operación de modificación de los horarios</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema, al comprobar la validez de las modificaciones, considera que hay uno o más errores, por lo que avisa al actor de ello para facilitarle así su corrección</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    Los horarios, ya modificados, han sido guardados en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-02, IR-04</td>
</tr>
</table>

<br>

- ### UC-06 _Proponer cambio de horario_

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
    Ofrece el medio necesario para realizar la propuesta de efectuar un cambio en los horarios</td>
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
    1.- El actor pulsa sobre el botón para proponer una modificación en los horarios<br>
    2.- El sistema muestra una caja de texto para introducir el motivo por el cual se desea realizar un cambio en los horarios y comentar en qué consiste dicha modificación<br>
    3.- El actor introduce una breve explicación del cambio solicitado, así como el motivo que da soporte al mismo a modo de argumento de su petición<br>
    4.- El sistema, tras haber comprobado la validez de las datos, muestra un nuevo botón cuya utilidad es la de confirmar el envío de la propuesta<br>
    5.- El actor pulsa sobre el botón para concluir la operación de solicitud de cambio en los horarios</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema comprueba la validez de los datos y determina que no son correctos, procediendo a avisar al actor de ello para facilitarle así su corrección</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    La propuesta ha sido almacenada en el sistema y enviada al personal del PAS (encargados de la gestión de las modificaciones en los horarios)</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-03, IR-06</td>
</tr>
</table>

<br>

- ### UC-07 _Verificar datos_

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
    Dispone la posibilidad de confirmar la validez de los datos de un nuevo estudiante el cual está siendo dado de alta</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PAS / PDI</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PAS / PDI debe estar autenticado en el sistema, así como el estudiante cuyos datos van a ser verificados debe estar siendo dado de alta en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para verificar los datos<br>
    2.- El sistema muestra un mensaje de confirmación de la validez de los datos junto con un botón para el cierre de la ventana de dicho mensaje<br>
    3.- El actor pulsa sobre el botón para concluir la operación de verificación de datos</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    2.A.- El sistema comprueba la validez de los datos y determina que al menos uno de ellos no es correcto, procediendo a notificar al actor de este hecho para facilitarle así su corrección</td>
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

- ### IR-01 _Estudiante_

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

- ### IR-02 _PAS_

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

- ### IR-03 _PDI_

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

- ### IR-04 _Horario_

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
    <td>El sistema deberá almacenar la información correspondiente a los horarios de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de usuario al que corresponden los horarios<br>
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

- ### IR-05 _Clase_

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

- ### UC-08 _Acordar precio_

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
     El vendedor acuerda un precio con el comprador para poder realizar la venta</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
     Comprador/Vendedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El comprador y el vendedor deben estar dados de alta</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El vendedor propone un precio para la venta de su producto.
    2.- El comprador acepta el precio o le hace una contraoferta al vendedor.
    3.- Se concluye el acuerdo del precio.
    </td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El precio es actualizado oficialmente en el sistema para que la compra pueda ser llevada a cabo.</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    "UC24"</td>
</tr>
</table>

<br>

- ### UC-09 _Agregar producto_

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
    Permite agregar un producto determinado al carrito de compra</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Comprador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El comprador debe de estar dado de alta en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El comprador pulsa sobre el botón para agregar un producto
    2.- El sistema comprueba que el producto está disponible y lo agrega al carrito de compra
    </td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    Si el producto en cuestión no está disponible, el sistema avisa al comprador.</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El producto agregado al carrito es marcado como bloqueado</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-23</td>
</tr>
</table>

<br>

- ### UC-10 _Avisar_

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
    Avisa a determinados usuarios sobre algún cambio del sistema</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El proveedor debe de estar dado de alta en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El proveedor avisa sobre algún cambio del sistema</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    Se envía una notifiación a determinados usuarios con el cambio habido en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-11,UC-12,UC-20
    </td>
</tr>
</table>

<br>

- ### UC-11 _Avisar de nuevo producto_

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

- ### UC-12 _Avisar fin de oferta_

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
    Se encarga de avisar cuando termina la oferta de un producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Administrador/Comprador/Usuario/Vendedor/Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Que el proveedor este dado de alta en la base de datos</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor elimina la oferta de la base de datos<br>
    2.- El sistema muestra una pantalla de confirmación<br>
    3.- El actor confirma la eliminación de la oferta<br>
    4.- El actor pulsa el boton avisar para notificar el fin de la oferta<br>
    5.- El sistema muestra una ventana de confirmación para enviar notificación<br>
    6.- El actor confirma y se envia la notificación del fin de oferta </td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    3.A.- El actor cancela la eliminación del producto y el sistema vuelve a la pantalla anterior<br>
    5.A.- El actor cancela la notificación del fin de oferta, el sistema no muestra la notificación al usuario</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    Se notifica del fin de la oferta</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-10</td>
</tr>
</table>

<br>

- ### UC-13 _Buscar producto_

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
    Se va a encargar de buscar los productos que hay registrados en la base de datos</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Usuario</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Que haya productos registrados en el sistema </td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El usuario busca un producto<br>
    2.- El sistema muestra los resultados que coinciden con su búsqueda</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    2-A.- El sistema no encuentra resultados y muestra un mensaje "No existe la búsqueda"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    </td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-07</td>
</tr>
</table>

<br>

- ### UC-14 _Consultar histórico de precios_

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
    Mostrará una lista con el histórico de precios</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Vendedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Tiene que haber un registro de los precios de los productos guardado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    </td>
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

- ### UC-15 _Consultar oferta_

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

- ### UC-16 _Consultar precio_

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
    Realiza la acción de consultar el precio de un determinado producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Comprador/Usuario/Vendedor/Proveedor/Administrador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El usuario ha de estar dado de alta en la base de datos</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El usuario busca un producto<br>
    2.- El usuario consulta el precio producto<br>
    3.- Surge una ventana emergente con la información del producto</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    1.- No hay camino alternativo</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El alumno sigue dado de alta en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-07</td>
</tr>
</table>

<br>

- ### UC-17 _Consultar producto_

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
    Realiza la acción de consultar la información de un producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Usuario/Comprador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El comprador ha de estar dado de alta en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El usuario visualiza el producto<br>
    2.- El usuario consulta el producto<br>
    3.- Surge una ventana emergente con la información del producto</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    1.- En caso de no encontrar el producto se muestra una ventana con el texto: "No existe"</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    </td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-13/UC-25/IR-07</td>
</tr>
</table>

<br>

- ### UC-18 _Eliminar oferta_

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
    Realiza la eliminación de una oferta determinada</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El proveedor ha de haber avisado el fin de dicha oferta</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El proveedor avisa del fin de una oferta <br>
    2.- El proveedor elimina dicha oferta del sistema</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
     La oferta en cuestión tiene que ser eliminada del sistema.</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC10/UC12/UC20/IR06</td>
</tr>
</table>

<br>

- ### UC-19 _Eliminar producto_

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
    Se realiza la eliminación de un producto </td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Administrador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El administrador ha de estar registrado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El administrador selecciona el producto a eliminar.<br>
    2.- El administrador selecciona la opción de eliminar el producto.
    </td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El producto en cuestión desaparece del sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR04/Producto(IR)</td>
</tr>
</table>

<br>

- ### UC-20 _Enviar notificación_

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
    Se realiza en envío de una notificación</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Tiene que haber surgido un nuevo producto o el fin de una oferta</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- Finaliza una oferta 
    2.- El proveedor envía la notificación</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    1.- Surge un nuevo producto
    2.- Se incorpora una nueva oferta(puede pasar)
    3.- El proveedor envía la notificacción.
    </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    </td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC10/UC11/UC12/UC22/IR(06)/IR(07)/IR(producto)</td>
</tr>
</table>

<br>

- ### UC-21 _Finalizar compra_

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

- ### UC-22 _Incorporar oferta_

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

- ### UC-23 _Marcar producto como bloqueado_

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

- ### UC-24 _Realizar venta_

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

- ### UC-25 _Verificar disponibilidad de producto_

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

- ### IR-04 _Administrador_

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

- ### IR-05 _Comprador_

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

- ### IR-06 _Proveedor_

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

- ### IR-07 _Usuario_

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

- ### IR-08 _Vendedor_

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
