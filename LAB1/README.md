<br>

# Lab 1 - Definición de casos de uso y requisitos de información

<br>

## Supuesto 1: Horarios

En una universidad, el personal del PDI, el personal del PAS y los estudiantes pueden consultar horarios. Por su parte, el personal del PAS puede modificar horarios y dar de alta estudiantes. El personal de PDI puede proponer cambios en los horarios y dar de alta estudiantes. La funcionalidad de dar de alta estudiantes del PAS realiza una verificación de los datos del estudiante. Sin embargo, la funcionalidad de dar de alta estudiantes del PDI, además de verificar los datos también permite de forma excepcional realizar la búsqueda en las listas de clase de sus asignaturas.

<br>

### Modelo Entidad-Relación

<br>

<div align="center"><img src="./out/horarios/ER_horarios.svg"></div>

<br>

### Diagrama de clases

<br>

<div align="center"><img src="./out/horarios/CD_horarios.svg"></div>

<br>

### Casos de uso

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
    1.- El actor, el cual se encuentra en pleno proceso de dado de alta de un estudiante [UC-04], pulsa sobre el botón para buscar al mismo en las listas de clase de sus asignaturas<br>
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
    UC-04, IR-01, IR-07</td>
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
    Plantea la posibilidad de consultar los horarios personalizados propios</td>
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
    1.- El actor pulsa sobre el botón para consultar sus horarios<br>
    2.- El sistema muestra una ventana donde se reflejan los horarios, además de un botón para cerrar la misma<br>
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
    IR-02, IR-04, IR-06, IR-07</td>
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
    PAS</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El personal del PAS debe estar autenticado en el sistema, así como no lo debe estar el nuevo estudiante</td>
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
    El estudiante ha sido dado de alta en el sistema de tal manera que sus datos, los cuales han pasado por un proceso de verificación satisfactorio, han sido almacenados en el mismo</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-04, UC-07, IR-02, IR-06, IR-07</td>
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
    El personal del PDI debe estar autenticado en el sistema, así como no lo debe estar el nuevo estudiante</td>
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
    3.A.- El actor pulsa el botón encargado de la búsqueda del estudiante en las listas de clase de sus asignaturas e introduce el identificador de este y el de una asignatura en cuestión en una nueva ventana emergente la cual está compuesta por dos cajas de texto [UC-01]. Si el estudiante ya aparece como resultado de la búsqueda, se detiene el proceso de dada de alta en el sistema. En caso contrario, el sistema notifica lo sucedido y vuelve a mostrar la ventana compuesta por diferentes cajas de texto en las que poder introducir los datos para poder seguir así con el proceso inicial de dada de alta de un estudiante<br>
    4.A.- El sistema considera los datos introducidos como incorrectos, marcando con color rojo las cajas de texto donde se han producido errores de algún tipo para facilitar así su corrección</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El estudiante ha sido dado de alta en el sistema de tal manera que sus datos, los cuales han pasado por un proceso de verificación satisfactorio, han sido almacenados en el mismo</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-01, UC-03, UC-07, IR-01, IR-02, IR-07 </td>
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
    IR-04, IR-06</td>
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
    El personal del PDI debe haber sido dado de alta y estar autenticado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para proponer una modificación en los horarios<br>
    2.- El sistema muestra dos cajas de texto para introducir el motivo por el cual se desea realizar un cambio en los horarios y comentar en qué consiste dicha modificación<br>
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
    La propuesta ha sido almacenada en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-07, IR-08</td>
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
    1.- El actor, el cual se encuentra en pleno proceso de dado de alta de un estudiante [UC-03 / UC-04], pulsa sobre el botón para verificar los datos del mismo<br>
    2.- El sistema muestra un mensaje de confirmación de la validez de los datos junto con un botón para el cierre de la ventana de dicho mensaje<br>
    3.- El actor pulsa sobre el botón para concluir la operación de verificación de datos</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    2.A.- El sistema comprueba la validez de los datos y determina que al menos uno de ellos no es correcto, procediendo a notificar al actor de este hecho para facilitarle así su corrección</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    En la base de datos del sistema ha sido actualizado el controlador de la correcta verificación de los datos del estudiante</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-03, UC-04, IR-02, IR-06, IR-07</td>
</tr>
</table>

<br>

### Requisitos de información

<br>

- ### IR-01 _AlumnoClase_

<br>

<table align = "center">
<tr>
    <td><b>IR-01:</b></td>
    <td>AlumnoClase</td>
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
    <td>UC-01, UC-04, IR-02, IR-03</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los alumnos que hay en cada clase de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de estudiante<br>
    - Identificador de evento / clase</td>
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

- ### IR-02 _Estudiante_

<br>

<table align = "center">
<tr>
    <td><b>IR-02:</b></td>
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
    <td>UC-02, UC-03, UC-04, UC-07, IR-01, IR-04</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los estudiantes de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de estudiante<br>
    - Identificador de horario <br>
    - Número del documento nacional de identidad<br>
    - Nombre y apellidos<br>
    - Fecha de nacimiento<br>
    - Sexo<br>
    - Fecha de alta como estudiante<br>
    - Dirección<br>
    - Teléfono<br>
    - Correo electrónico<br>
    - Controlador de la correcta verificación de los datos</td>
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

- ### IR-03 _EventoClase_

<br>

<table align = "center">
<tr>
    <td><b>IR-03:</b></td>
    <td>EventoClase</td>
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
    <td>IR-01, IR-05</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los eventos y las clases organizados por la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de evento / clase<br>
    - Nombre de actividad / asignatura<br>
    - Nombre del lugar asignado</td>
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
    <td>UC-02, UC-05, IR-02, IR-05, IR-08</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los horarios de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de horario<br>
    - Curso<br>
    - Grado</td>
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

- ### IR-05 _HorarioEventoClase_

<br>

<table align = "center">
<tr>
    <td><b>IR-05:</b></td>
    <td>HorarioEventoClase</td>
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
    <td>IR-03, IR-04</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los todos los horarios de cada una de las clases de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de horario<br>
    - Identificador de evento / clase<br>
    - Hora de inicio de evento / clase<br>
    - Hora de fin de evento / clase</td>
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

- ### IR-06 _PAS_

<br>

<table align = "center">
<tr>
    <td><b>IR-06:</b></td>
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
    <td>UC-02, UC-03, UC-05, UC-07</td>
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
    - Teléfono<br>
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

- ### IR-07 _PDI_

<br>

<table align = "center">
<tr>
    <td><b>IR-07:</b></td>
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
    <td>UC-01, UC-02, UC-03, UC-04, UC-06, UC-07, IR-08</td>
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
    - Teléfono<br>
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

- ### IR-08 _PropuestaCambioHorario_

<br>

<table align = "center">
<tr>
    <td><b>IR-08:</b></td>
    <td>PropuestaCambioHorario</td>
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
    <td>UC-06, IR-04, IR-07</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a las peticiones de cambio, llevadas a cabo por parte del personal del PDI, en los horarios de la universidad. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de propuesta de cambio en el horario<br>
    - Identificador de personal del PDI<br>
    - Identificador de horario<br>
    - Motivo de la proposición de cambio<br>
    - Cambio propuesto</td>
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

### Modelo Entidad-Relación

<br>

<div align="center"><img src="./out/sistema_de_compras/ER_sistema_de_compras.svg"></div>

<br>

### Diagrama de clases

<br>

<div align="center"><img src="./out/sistema_de_compras/IRs_sistema_de_compras.svg"></div>

<br>

### Casos de uso

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
     Otorga la posibilidad de poder acordar un precio para así poder realizar la venta de un producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
     Comprador + Vendedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Tanto el comprador como el vendedor deben estar autenticados en el sistema y ambos deben estar tomando parte en el proceso de realización de una venta</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El comprador y el vendedor, los cuales se encuentran en pleno proceso de realización de una venta [UC-24], pulsan sobre el botón para acordar el precio del producto en cuestión<br>
    2.- El sistema muestra a ambos actores una nueva ventana emergente la cual contiene un chat común a comprador y vendedor junto con una caja de texto sobre la cual cualquiera de ellos puede escribir su próximo mensaje. Además de lo mencionado, también hace aparición en dicha ventana un cuadro de texto donde cualquiera de ellos ha de introducir el precio acordado (el que no lo introduzca será capaz de verlo de igual manera al tratarse de un campo de texto editable por ambos, al igual que el chat) y un botón más para confirmar que se ha acordado un precio<br>
    3.- Comprador y vendedor confirman que han llegado a un acuerdo clicando sobre el botón correspondiente</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br><br></td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El precio acordado ha sido almacenado en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-24, IR-13, IR-19, IR-20</td>
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
    El comprador debe haber sido dado de alta y estar autenticado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para agregar un producto<br>
    2.- El sistema procede a mostrar un mensaje el cual confirma la correcta agregación del producto en cuestión al carrito de compra junto con un botón sobre el que pulsar para cerrar dicho mensaje. Además, el producto se marca como bloqueado [UC-23]<br>
    3.- El  actor pulsa sobre el botón para concluir la operación de agregación del producto</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br><br></td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El estado del carrito ha sido actualizado y guardado en el sistema, pues ahora se le ha sumado un nuevo producto, el cual además ha sido marcado como bloqueado</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-23, IR-13, IR-17</td>
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
    Ofrece el medio necesario para avisar a determinados usuarios</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El proveedor debe haber sido dado de alta y estar autenticado el sistema, así como debe haberse producido una determinada acción la cual será notificada</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El proveedor pulsa sobre el botón para avisar de un suceso determinado<br>
    2.- El sistema muestra dos cajas de texto para introducir el motivo por el cual se desea avisar y el propio aviso en sí<br>
    3.- El actor introduce el texto exigido en cada una de las cajas de texto a rellenar<br>
    4.- El sistema, tras haber comprobado la validez de los datos introducidos, muestra un mensaje de confirmación del éxito de la operación junto con un botón para cerrar dicho mensaje<br>
    5.- El actor pulsa sobre el botón para poner así fin a la operación de aviso. Desembocando esta acción en el envío de una notificación [UC-20] a ciertos usuarios del sistema</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema comprueba la validez de los datos introducidos y ha determinado que no cumple las condiciones exigidas, procediendo a avisar al actor de ello para facilitarle así su corrección
    </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El aviso y la notificación generada correspondiente a dicho aviso han sido guardados en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-11, UC-12, UC-20, IR-10, IR-14, IR-18</td>
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
    Ofrece el medio necesario para avisar a determinados usuarios de la llegada de un nuevo producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El proveedor debe haber sido dado de alta y estar autenticado el sistema, así como debe haberse producido la llegada de un nuevo producto, acción la cual será notificada</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El proveedor pulsa sobre el botón para avisar de la llegada de un nuevo producto<br>
    2.- El sistema muestra dos cajas de texto para introducir el motivo por el cual se desea avisar y el propio aviso en sí. Además de lo mencionado, existe también un botón para la incorporación de una oferta sobre el producto en cuestión<br>
    3.- El actor introduce el texto exigido en cada una de las cajas de texto a rellenar<br>
    4.- El sistema, tras haber comprobado la validez de los datos introducidos, muestra un mensaje de confirmación del éxito de la operación junto con un botón para cerrar dicha notificación<br>
    5.- El actor pulsa sobre el botón para poner así fin a la operación de aviso. Desembocando esta acción en el envío de una notificación [UC-20] a ciertos usuarios del sistema</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    3.A.- El actor pulsa el botón encargado de la incorporación de una oferta sobre el producto tratado e introduce el precio rebajado de este en una nueva ventana emergente la cual está compuesta por una única caja de texto [UC-22]. A continuación aparecerá un mensaje de confirmación de la operación que, al ser aceptado por el actor, provocará el establecimiento definitivo de la oferta y la vuelta al proceso inicial de aviso de la llegada de un nuevo producto<br>
    4.A.- El sistema comprueba la validez de los datos introducidos y ha determinado que no cumple las condiciones exigidas, procediendo a avisar al actor de ello para facilitarle así su corrección
    </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El aviso y la notificación generada correspondiente a dicho aviso han sido guardados en el sistema y, en caso de haberse incorporado una oferta sobre el producto, la misma también ha sido almacenada</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-10, UC-20, UC-22, IR-10, IR-14, IR-15, IR-18</td>
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
    Ofrece el medio necesario para avisar a determinados usuarios del fin de una oferta</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El proveedor debe haber sido dado de alta y estar autenticado el sistema, así como debe haberse producido el fin de una oferta (ya no está vigente), acción la cual será notificada</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El proveedor pulsa sobre el botón para avisar del fin de una oferta, acción que origina a su vez la eliminación de la oferta en cuestión [UC-18]<br>
    2.- El sistema muestra dos cajas de texto para introducir el motivo por el cual se desea avisar y el propio aviso en sí<br>
    3.- El actor introduce el texto exigido en cada una de las cajas de texto a rellenar<br>
    4.- El sistema, tras haber comprobado la validez de los datos introducidos, muestra un mensaje de confirmación del éxito de la operación junto con un botón para cerrar dicha notificación<br>
    5.- El actor pulsa sobre el botón para poner así fin a la operación de aviso. Desembocando esta acción en el envío de una notificación [UC-20] a ciertos usuarios del sistema</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema comprueba la validez de los datos introducidos y ha determinado que no cumple las condiciones exigidas, procediendo a avisar al actor de ello para facilitarle así su corrección
    </td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El aviso y la notificación generada correspondiente a dicho aviso han sido guardados en el sistema y la oferta ha sido eliminada del mismo</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-10, UC-18, UC-20, IR-10, IR-14, IR-15, IR-18</td>
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
    Dispone la posibilidad de buscar un producto entre los registrados en la base de datos del sistema</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Administrador / Comprador / Proveedor / Vendedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El actor debe estar autenticado en el sistema y se debe encontrar realizando una consulta sobre el precio de un producto</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor, el cual se encuentra en pleno proceso de consulta del precio de un producto [UC-16], ha pulsado sobre el botón destinado a la realización de la búsqueda de dicho producto en las base de datos del sistema<br>
    2.- El sistema muestra una nueva ventana la cual cuenta con una única caja de texto para introducir el identificador o el nombre del producto buscado<br>
    3.- El actor introduce el identificador o el nombre del producto<br>
    4.- El sistema muestra los datos del producto además de un botón para cerrar la ventana de resultados de búsqueda<br>
    5.- El actor pulsa sobre el botón para concluir la operación de búsqueda</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema muestra un mensaje el cual notifica la no presencia, en la base de datos, de algún producto cuyo identificador o nombre se corresponda con el introducido en la caja de texto. Además de un nuevo botón para el cierre de dicha notificación sobre el cual el actor debe pulsar para poder regresar así al estado inicial previo a esta situación</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-16, UC-17, IR-09, IR-13, IR-16, IR-18, IR-19</td>
</tr>
</table>

<br>

- ### UC-14 _Consultar histórico de ventas_

<br>

<table align = "center">
<tr>
    <td><b>Identificador:</b><br>
    UC-14</td>
</tr>
<tr>
    <td><b>Nombre:</b><br>
    Consultar histórico de ventas</td>
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
    Plantea la posibilidad de consultar el histórico de ventas de un producto el cual se encuentra en proceso de venta en ese momento</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Comprador + Vendedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Tanto el comprador como el vendedor deben estar autenticados en el sistema y ambos deben estar tomando parte en el proceso de realizar una venta</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El comprador y el vendedor, los cuales se encuentran en pleno proceso de realización de una venta [UC-24], pulsan sobre el botón para consultar el histórico de ventas del producto sobre el cual se está realizando la misma, con el propósito de que esta acción les ayude con el proceso<br>
    2.- El sistema muestra el histórico de ventas del producto además de un botón para cerrar la ventana de resultados de búsqueda<br>
    3.- El actor pulsa sobre el botón para concluir la operación de búsqueda</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    2.A.- El sistema muestra un mensaje el cual notifica la no presencia, en la base de datos, de alguna venta anterior del producto en cuestión. Además de un nuevo botón para el cierre de dicha notificación sobre el cual el actor debe pulsar para poder regresar así al estado inicial previo a esta situación</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-24, IR-13, IR-19, IR-20</td>
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
    Posibilita la acción de consultar la existencia de una oferta para algún producto determinado</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Administrador / Comprador / Proveedor / Vendedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El actor debe estar autenticado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para consultar la existencia de una oferta en un producto determinado<br>
    2.- El sistema muestra una nueva ventana la cual cuenta con una única caja de texto para introducir el identificador o el nombre del producto en cuestión<br>
    3.- El actor introduce el identificador o el nombre del producto<br>
    4.- El sistema muestra las ofertas disponibles junto con un botón para cerrar la ventana de resultados de la consulta<br>
    5.- El actor pulsa sobre el botón para concluir la operación de consulta</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema muestra un mensaje el cual notifica la no presencia, en la base de datos, de alguna oferta para el producto cuyo identificador o nombre se corresponde al introducido en la caja de texto. Además, hace aparición en esta ventana un botón para el cierre de la misma</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-09, IR-13, IR-15, IR-18, IR-19</td>
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
    Permite realizar la acción de consulta del precio de un determinado producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Administrador / Comprador / Proveedor / Vendedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El actor ha de estar dado de alta y autenticado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para consultar el precio de un producto determinado<br>
    2.- El sistema muestra una nueva ventana la cual cuenta con una única caja de texto para introducir el identificador o el nombre del producto en cuestión<br>
    3.- El actor introduce el identificador o el nombre del producto, es decir, realiza una operación de búsqueda sobre el mismo [UC-13]<br>
    4.- El sistema muestra el precio junto con un botón para cerrar la ventana de resultados de la consulta<br>
    5.- El actor pulsa sobre el botón para concluir la operación de consulta</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema muestra un mensaje el cual notifica la no presencia, en la base de datos, de algún producto cuyo identificador o nombre se corresponda con el introducido en la caja de texto. Además, hace aparición en esta ventana un botón para el cierre de la misma</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-13, IR-09, IR-13, IR-16, IR-18, IR-19</td>
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
    Plantea la posibilidad de consultar la información de un producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Comprador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El comprador ha de estar dado de alta y autenticado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para consultar un producto en la base de datos del sistema<br>
    2.- El sistema muestra una nueva ventana la cual cuenta con una única caja de texto para introducir el identificador del producto<br>
    3.- El actor introduce el identificador del producto<br>
    4.- El sistema verifica la disponibilidad del producto [UC-25] para luego, en caso de verificación exitosa, mostrar los datos del producto además de un botón para cerrar la ventana de resultados de búsqueda<br>
    5.- El actor pulsa sobre el botón para concluir la operación de búsqueda</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema determina la no disponibilidad del producto, por lo que procede a mostrar un mensaje el cual notifica este suceso. Además, hace aparición un nuevo botón para el cierre de dicha notificación sobre el cual el actor debe pulsar para poder regresar así al estado inicial previo a esta situación</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-13, UC-25, IR-13, IR-16</td>
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
    Otorga el poder de marcar una oferta determinada como no vigente en la base de datos del sistema</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El proveedor debe estar autenticado en el sistema y este debe encontrarse avisando el fin de una oferta</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor, al iniciar el proceso de aviso del fin de una oferta [UC-12], ha procedido a su vez a la eliminación de la misma<br>
    2.- El sistema muestra un un mensaje de confirmación del éxito de la operación junto con un botón para cerrar dicha notificación<br>
    3.- El actor pulsa sobre el botón para concluir la operación de eliminación de una oferta</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br><br></td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    La oferta cuyo fin está siendo avisado ha sido marcada como no vigente</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-12, IR-15, IR-18</td>
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
    Dispone la posibilidad de marcar un producto como no disponible en la base de datos del sistema</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Administrador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El administrador debe haber sido dado de alta y estar autenticado en el sistema. Por otra parte, el producto a eliminar debe estar también registrado en el mismo</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para eliminar un producto en cuestión<br>
    2.- El sistema muestra una nueva ventana la cual cuenta con una única caja de texto para introducir el identificador del producto que se desea eliminar<br>
    3.- El actor introduce el identificador del producto<br>
    4.- El sistema muestra los datos del producto además de un botón para la confirmación de su eliminación<br>
    5.- El actor pulsa sobre el botón para la confirmación de la eliminación del producto<br>
    6.- El sistema muestra un un mensaje ratificando el éxito de la operación junto con un botón para cerrar dicha notificación<br>
    7.- El actor pulsa sobre el botón para concluir la operación de eliminación de un producto</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    4.A.- El sistema muestra un mensaje el cual notifica la no presencia, en la base de datos, de algún producto cuyo identificador se corresponda con el introducido en la caja de texto. Además de un nuevo botón para el cierre de dicha notificación sobre el cual el actor debe pulsar para poder regresar así al estado inicial previo a esta situación</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    Un determinado producto ha sido marcado como no disponible en el sistema</td>
</tr>
    <td><b>Referencias:</b><br>
    IR-09, IR-16</td>
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
    Posibilita la acción de enviar una notificación</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El proveedor debe haber sido dado de alta y estar autenticado el sistema, así como este debe encontrarse realizando un aviso</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- Una vez el actor rellena y confirma un aviso [UC-10 / UC-11 / UC-12], es enviada su correspondiente notificación<br>
    2.- El sistema muestra una nueva ventana en la que aparece cómo es la notificación enviada, la cual ha sido generada a partir del aviso del que se partía en un principio, junto con un mensaje de confirmación del éxito de la operación y un botón para cerrar dicha ventana<br>
    3.- El actor pulsa sobre el botón para poner así fin a la operación de envío de una notificación</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br><br></td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    La notificación generada ha sido almacenada en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-10, UC-11, UC-12, IR-14, IR-18</td>
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
    Permite finalizar el proceso de compra</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Comprador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El comprador debe haber sido dado de alta y estar autenticado en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa sobre el botón para finalizar la compra<br>
    2.- El sistema procede a mostrar un mensaje el cual confirma la correcta finalización de la compra junto con un botón sobre el que pulsar para cerrar dicho mensaje<br>
    3.- El actor pulsa sobre el botón para concluir la operación de finalización de la compra</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br><br></td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    La información de la compra ha quedado almacenada en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    IR-12, IR-13</td>
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
    Plantea la posibilidad de incorporar una oferta a un producto nuevo cuya llegada está siendo avisada</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Proveedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El proveedor debe haber sido dado de alta y estar autenticado en el sistema. Además, este ha de encontrarse avisando la llegada de un nuevo producto</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor, el cual se encuentra en pleno proceso de aviso de la llegada de un nuevo producto [UC-11], pulsa sobre el botón para la incorporación de una oferta sobre el mismo<br>
    2.- El sistema muestra una nueva ventana la cual cuenta con una única caja de texto en la que introducir el precio rebajado del producto en cuestión<br>
    3.- El sistema comprueba la validez de los datos y los almacena una vez determina que son correctos, mostrando un mensaje de confirmación del éxito de la operación junto con un botón para cerrar dicha notificación<br>
    4.- El actor pulsa sobre el botón para concluir la operación de incorporación de una oferta</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    3.A.- El sistema comprueba la validez de los datos y determina que no son correctos, procediendo a avisar al actor de ello para facilitarle así su corrección</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    La oferta ha sido almacenada en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-11, IR-15, IR-18</td>
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
    Dispone la posibilidad de marcar como bloqueado un producto el cual está siendo agregado al carrito de compra</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Comprador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El comprador ha de estar autenticado en el sistema, así como debe encontrarse en pleno proceso de agregación de un producto a su carrito</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- Una vez el actor agrega un producto al carrito y confirma dicha operación de manera exitosa [UC-09], dicho producto es marcado como bloqueado<br>
    2.- El sistema muestra una nueva ventana la cual cuenta con un mensaje de confirmación del éxito de la operación y un botón para cerrar dicha ventana<br>
    3.- El actor pulsa sobre el botón para poner así fin a la operación de marcado del bloqueo de un producto</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br><br></td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    El producto agregado al carrito ha sido marcado como bloqueado en el sistema</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-09, IR-13, IR-16</td>
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
    Posibilita la acción de realizar la venta de un producto</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
    Comprador + Vendedor</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    Tanto el comprador como el vendedor deben haber sido dados de alta y estar autenticados en el sistema</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El comprador y el vendedor pulsan sobre el botón para realizar la venta de un producto<br>
    2.- El sistema muestra un mensaje el cual confirma la posibilidad de realizar la venta junto con un botón que deberá ser pulsado por los actores para proseguir así en la acción mediante el acuerdo de un precio [UC-08]. Además de lo mencionado, existe también un botón para la consulta del histórico de ventas del producto<br>
    3.- Una vez acordado el precio, el sistema valida la acción y procede a mostrar un mensaje corroborador de la correcta realización de la venta del producto en cuestión junto con un botón sobre el que pulsar para cerrar dicho mensaje<br>
    4.- Los actores pulsan sobre el botón para concluir la operación de realización de la venta de un producto</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    3.A.- Algún actor (o ambos) pulsa el botón encargado de la consulta del histórico de ventas del producto en base al cual desean realizar la venta [UC-14]. Si dicho producto ha sido vendido anteriormente se mostrará en una nueva ventana el histórico de sus ventas. En caso contrario, el sistema notifica lo sucedido. Sea cual sea el resultado de la búsqueda, además de este se mostrará un botón para su cierre con el objetivo de poder continuar así el proceso inicial de realización de una venta</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br>
    Los datos de la venta han sido almacenados en el sistema, incluyéndose en estos el precio final acordado entre comprador y vendedor</td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-08, UC-14, IR-13, IR-19, IR-20</td>
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
    Ofrece el medio necesario para verificar la disponibilidad de un producto el cual estamos consultando</td>
</tr>
<tr>
    <td><b>Actores:</b><br>
   Comprador</td>
</tr>
<tr>
    <td><b>Precondiciones:</b><br>
    El comprador ha de estar autenticado en el sistema y debe encontrarse realizando el proceso de consulta de un producto</td>
</tr>
<tr>
    <td><b>Flujo Normal:</b><br>
    1.- El actor pulsa, el cual se encuentra en pleno proceso de consulta de un producto [UC-17], sobre el botón para verificar la disponibilidad del mismo<br>
    2.- El sistema muestra un mensaje de confirmación de la disponibilidad del producto en cuestión junto con un botón para el cierre de la ventana de dicho mensaje<br>
    3.- El actor pulsa sobre el botón para concluir la operación de verificación de la disponibilidad de un producto</td>
</tr>
<tr>
    <td><b>Flujo Alternativo:</b><br>
    2.A.- El sistema muestra un mensaje el cual manifiesta la no disponibilidad del producto junto con un botón que deberá ser pulsado por el actor para el cierre de dicha notificación</td>
</tr>
<tr>
    <td><b>Poscondiciones:</b><br><br></td>
</tr>
<tr>
    <td><b>Referencias:</b><br>
    UC-17, IR-13, IR-16</td>
</tr>
</table>

<br>

- ### IR-09 _Administrador_

<br>

<table align = "center">
<tr>
    <td><b>IR-09:</b></td>
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
    <td>UC-13, UC-15, UC-16, UC-19</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los administradores del sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de administrador<br>
    - Número del documento nacional de identidad<br>
    - Nombre y apellidos<br>
    - Fecha de nacimiento<br>
    - Sexo<br>
    - Fecha de alta como estudiante<br>
    - Dirección<br>
    - Teléfono<br>
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

- ### IR-10 _Aviso_

<br>

<table align = "center">
<tr>
    <td><b>IR-10:</b></td>
    <td>Aviso</td>
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
    <td>UC-10, UC-11, UC-12, IR-14, IR-15, IR-16, IR-18</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los avisos llevados a cabo por los proveedores del sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de aviso<br>
    - Identificador de producto<br>
    - Identificador de oferta<br>
    - Identificador de proveedor<br>
    - Tipo de aviso (llegada de nuevo producto o fin de oferta)<br>
    - Motivo del aviso<br>
    - Cuerpo del aviso</td>
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

- ### IR-11 _Carrito_

<br>

<table align = "center">
<tr>
    <td><b>IR-11:</b></td>
    <td>Carrito</td>
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
    <td>IR-12, IR-13, IR-17</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información del carrito asignado a cada uno de los compradores del sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de carrito<br>
    - Identificador de comprador</td>
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

- ### IR-12 _Compra_

<br>

<table align = "center">
<tr>
    <td><b>IR-12:</b></td>
    <td>Compra</td>
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
    <td>UC-21, IR-11, IR-13</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información de las compras realizadas por cada uno de los compradores del sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de compra<br>
    - Identificador de comprador<br>
    - Identificador de carrito<br>
    - Fecha de realización de la compra</td>
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

- ### IR-13 _Comprador_

<br>

<table align = "center">
<tr>
    <td><b>IR-13:</b></td>
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
    <td>UC-08, UC-09, UC-13, UC-14, UC-15, UC-16, UC-17, UC-21, UC-23, UC-24, UC-25, IR-11, IR-12, IR-20</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los compradores del sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de comprador<br>
    - Número del documento nacional de identidad<br>
    - Nombre y apellidos<br>
    - Fecha de nacimiento<br>
    - Sexo<br>
    - Fecha de alta como estudiante<br>
    - Dirección<br>
    - Teléfono<br>
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

- ### IR-14 _Notificación_

<br>

<table align = "center">
<tr>
    <td><b>IR-14:</b></td>
    <td>Notificación</td>
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
    <td>UC-10, UC-11, UC-12, UC-20, IR-10</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a las notificaciones generadas a partir de los avisos confeccionados por los proveedores. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de aviso<br>
    - Mensaje generado a partir del cuerpo del aviso</td>
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

- ### IR-15 _Oferta_

<br>

<table align = "center">
<tr>
    <td><b>IR-15:</b></td>
    <td>Oferta</td>
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
    <td>UC-11, UC-12, UC-15, UC-18, UC-22, IR-10, IR-16</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a las ofertas establecidas en algunos de los productos registrados en el sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de oferta<br>
    - Identificador de producto<br>
    - Precio original del producto ofertado<br>
    - Precio nuevo del producto ofertado<br>
    - Fecha de inicio de la oferta<br>
    - Fecha de fin de la oferta<br>
    - Controlador de la vigencia de la oferta</td>
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

- ### IR-16 _Producto_

<br>

<table align = "center">
<tr>
    <td><b>IR-16:</b></td>
    <td>Producto</td>
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
    <td>UC-13, UC-16, UC-17, UC-19, UC-23, UC-25, IR-10, IR-15, IR-17 </td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los productos registrados en el sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de producto<br>
    - Precio del producto<br>
    - Controlador del bloqueo temporal de un producto<br>
    - Controlador de la disponibilidad de un producto</td>
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

- ### IR-17 _ProductoEnCarrito_

<br>

<table align = "center">
<tr>
    <td><b>IR-17:</b></td>
    <td>ProductoEnCarrito</td>
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
    <td>UC-09, IR-11, IR-16</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los productos agregados a los carritos de cada uno de los compradores del sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de producto<br>
    - Identificador de carrito</td>
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

- ### IR-18 _Proveedor_

<br>

<table align = "center">
<tr>
    <td><b>IR-18:</b></td>
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
    <td>UC-10, UC-11, UC-12, UC-13, UC-15, UC-16, UC-18, UC-20, UC-22, IR-10</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los proveedores del sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de proveedor<br>
    - Número del documento nacional de identidad<br>
    - Nombre y apellidos<br>
    - Fecha de nacimiento<br>
    - Sexo<br>
    - Fecha de alta como estudiante<br>
    - Dirección<br>
    - Teléfono<br>
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

- ### IR-19 _Vendedor_

<br>

<table align = "center">
<tr>
    <td><b>IR-19:</b></td>
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
    <td>UC-08, UC-13, UC-14, UC-15, UC-16, UC-24, IR-20</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
    <td>El sistema deberá almacenar la información correspondiente a los vendedores del sistema de compras. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de vendedor<br>
    - Número del documento nacional de identidad<br>
    - Nombre y apellidos<br>
    - Fecha de nacimiento<br>
    - Sexo<br>
    - Fecha de alta como estudiante<br>
    - Dirección<br>
    - Teléfono<br>
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

- ### IR-20 _Venta_

<br>

<table align = "center">
<tr>
    <td><b>IR-20:</b></td>
    <td>Venta</td>
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
    <td>UC-08, UC-14, UC-24, IR-13, IR-19</td>
</tr>
<tr>
    <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información de las ventas realizadas por los vendedores del sistema de compras a los compradores del mismo. En concreto:</td>
</tr>
<tr>
    <td><b>Datos específicos:</b></td>
    <td>- Identificador de venta<br>
    - Identificador de comprador<br>
    - Identificador de vendedor<br>
    - Identificador de producto<br>
    - Precio acordado para el producto en cuestión</td>
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