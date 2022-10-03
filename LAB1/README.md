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
    Posibilita la acción de buscar a un estudiante en la lista de clase</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    PDI</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PDI debe estar autenticado en el sistema como tal y se debe encontrar dando de alta a un estudiante en el mismo</td>
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
    4.A.- El sistema no muestra nada en caso de que el estudiante aún no haya sido dado de alta</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-04, INF-01, INF-03</td>
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
    INF-01, INF-02, INF-03</td>
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
    UC-04, UC-07, INF-01, INF-02, INF-03 </td>
</tr>
</table>

<br>

- ### **UC-04** *Dar de alta estudiante [vista PDI]*

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
    UC-01, UC-03, UC-07, INF-01, INF-03 </td>
</tr>
</table>

<br>

- ### **UC-05** *Modificar horario*

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

- ### **UC-06** *Proponer cambio horario*

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

- ### **UC-07** *Verificar datos*

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

- ### **INF-01** *Estudiante*

<br>

<table align = "center">
<tr>
    <td><b>INF-01:</b></td>
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
    <td>UC-01, UC-02, UC-03, UC-04, UC-07, INF-01, INF-02</td>
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

- ### **INF-02** *PAS*

<br>

<table align = "center">
<tr>
    <td><b>INF-02:</b></td>
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
    <td>UC-02, UC-03, UC-05, UC-07, INF-01</td>
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

- ### **INF-03** *PDI*

<br>

<table align = "center">
<tr>
    <td><b>INF-03:</b></td>
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
    <td>UC-02, UC-03, UC-04, UC-06, UC-07, INF-01</td>
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

<br><br>

## Supuesto 2: Sistema de Compras
En un sistema de compra, existen cuatro tipos de usuarios: comprador, vendedor, proveedor y administrador. Los compradores pueden agregar productos, consultar precios, finalizar la compra y consultar ofertas. Agregar productos implica marcar esos productos como bloqueados. Los vendedores también pueden consultar ofertas y consultar precios. Los proveedores pueden consultar precios, avisar de nuevos productos y consultar ofertas. Avisar de nuevos productos, de forma excepcional, realiza la incorporación de una oferta. Los proveedores también tienen una funcionalidad para avisar del fin de una oferta. Cuando se avisa del fin de una oferta, se ejecuta la funcionalidad de eliminar la oferta. Ambas funcionalidades de avisar del proveedor tienen en común que se encarga de enviar una notificación. Los administradores pueden consultar precios, consultar ofertas y eliminar productos. La funcionalidad de consultar precios incluye una funcionalidad de buscar productos que es similar a la funcionalidad de consultar productos de los compradores. Sin embargo, la funcionalidad de consultar productos añade una funcionalidad para verificar la disponibilidad. Para realizar una venta, un comprador y un vendedor participan de forma conjunta. En dicha operación, se lleva a cabo el acuerdo de un precio; excepcionalmente, durante la realización de la venta, se consultará el histórico de ventas.

<br>

- ### Acordar precio

<br>