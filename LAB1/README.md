<br>

# Lab 1 - Definición de casos de uso y requisitos de información

<br>

## Supuesto 1: Horarios
En una universidad, el personal del PDI, el personal del PAS y los estudiantes pueden consultar horarios. Por su parte, el personal del PAS puede modificar horarios y dar de alta estudiantes. El personal de PDI puede proponer cambios en los horarios y dar de alta estudiantes. La funcionalidad de dar de alta estudiantes del PAS realiza una verificación de los datos del estudiante. Sin embargo, la funcionalidad de dar de alta estudiantes del PDI, además de verificar los datos también permite de forma excepcional realizar la búsqueda en las listas de clase de sus asignaturas.

<br>

- ### Buscar en lista de clase

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
    1.- El actor pulsa sobre el botón para buscar en la lista de clase <br>
    2.- El sistema muestra una caja de texto para introducir el identificador del estudiante al cual se le quiere dar de alta <br>
    3.- El actor introduce el identificador del estudiante <br>
    4.- El sistema muestra los datos del estudiante <br>
    5.- El sistema muestra un botón para cerrar la ventana de resultados de búsqueda <br>
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
    UC-04, INF-001</td>
</tr>
</table>

<br>

<table align = "center">
<tr>
    <td><b>INF-001:</b></td>
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
    <td>UC-01, UC-02, UC-03, UC-04, UC-07</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los estudiantes de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de estudiante <br>
    - Número del documento nacional de identidad <br>
    - Nombre y apellidos <br>
    - Fecha de nacimiento <br>
    - Sexo <br>
    - Fecha de alta como estudiante <br>
    - Dirección <br>
    - Teléfonos <br>
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

- ### Consultar horario

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Dar de alta estudiante

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Dar de alta estudiante [vista PDI]

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Modificar horario

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Proponer cambio de horario

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Verificar datos

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Agregar producto

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Avisar

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Avisar de nuevo producto

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Avisar fin de oferta

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Buscar producto

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Consultar histórico de precios

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Consultar oferta

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Consultar precio

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Consultar producto

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Eliminar oferta

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Eliminar producto

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ###   Enviar notificación

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Finalizar compra

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Incorporar oferta

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Marcar producto como bloqueado

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Realizar venta

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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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

- ### Verificar disponibilidad del producto

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-25</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Verificar disponibilidad del producto</td>
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

<table align = "center">
<tr>
    <td><b>INF-010:</b></td>
    <td>"actor???"</td>
</tr>
<tr>
    <td><b>Versión:</b></td>
    <td>1.0 (Octubre-2022)</td>
</tr>
<tr>
    <td><b>Autores:</b></td>
    <td>Daniel López García, Eduardo Martín Gómez, Miguel Ángel Moncada Álvarez, Joaquín Murcia Escánez, Manuel Vallecillos Escobosa</td>
</tr>
<tr>
    <td><b>Fuentes:</b></td>
    <td>Entrevistas y reglamento</td>
</tr>
<tr>
    <td><b>Referencias:</b></td>
    <td>- "nombre caso de uso???"</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>"breve descripción del caso de uso"</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- "dato 1" <br>
    - "dato 2" <br>
    - "dato 3" <br>
    - "dato 4" <br>
    - "dato 5" <br></td>
</tr>
<tr>
    <td><b>Importancia:</b></td>
    <td>"Muy elevada | Elevada | Moderada"</td>
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