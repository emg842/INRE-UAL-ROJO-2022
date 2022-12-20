<br>

[Volver a la página anterior](https://github.com/emg842/INRE-UAL-ROJO-2022)

<br>

# <a name="iniciodocumento"></a> Especificación de los requisitos del software

<br>

## <a name="hojaderevision"></a> Hoja de revisión

<br>

<table align = "center">
    <tr>
        <td><b>Fecha</b></td>
        <td><b>Versión</b></td>
        <td><b>Descripción</b></td>
        <td><b>Autor</b></td>
    </tr>
    <tr>
        <td>06/12/2022</td>
        <td>1.0</td>
        <td>Realización del DCU general</td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td>10/12/2022</td>
        <td>1.0</td>
        <td>Realización tablas requisitos funcionales</td>
        <td>Eduardo Martín Gómez</td>
    </tr>
    <tr>
        <td>10/12/2022</td>
        <td>1.0</td>
        <td>Actualizar progreso en la Hoja de revisión</td>
        <td>Miguel Ángel Moncada Álvarez</td>
    </tr>
    <tr>
        <td>11/12/2022</td>
        <td>1.0</td>
        <td>Actualización del DCU general</td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td>11/12/2022</td>
        <td>1.0</td>
        <td>Adición de requisitos funcionales1</td>
        <td>Miguel Ángel Moncada Álvarez</td>
    </tr>
        <tr>
        <td>11/12/2022</td>
        <td>1.0</td>
        <td>Adición de requisitos No funcionales</td>
        <td>Miguel Ángel Moncada Álvarez</td>
    </tr>
    </tr>
        <tr>
        <td>13/12/2022</td>
        <td>1.0</td>
        <td>Introducción y objetivos de negocio</td>
        <td>Daniel López García</td>
    </tr>
    <tr>
        <td>13/12/2022</td>
        <td>1.0</td>
        <td>Diagrama E/R general</td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td>13/12/2022</td>
        <td>1.0</td>
        <td>Diagrama de casos de uso general actualizado en adición de fragmentos del mismo (DCU del usuario del portal, DCU del usuario del sistema de información y DCU del gestor)</td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td>14/12/2022</td>
        <td>1.0</td>
        <td>Diagrama de clases general</td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td>14/12/2022</td>
        <td>1.0</td>
        <td>Subida diagrama E/R fragmentado en dos (portal y sistema de información)</td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td>14/12/2022</td>
        <td>1.0</td>
        <td>Subida diagrama CU fragmentado en dos (portal y sistema de información)</td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
        <tr>
        <td>14/12/2022</td>
        <td>1.0</td>
        <td>Subida diagrama de clases fragmentado en dos (portal y sistema de información)</td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    </tr>
        <tr>
        <td>14/12/2022</td>
        <td>1.0</td>
        <td>Separación de requisitos funcionales y no funcionales en función de si pertenecen al portal o al sistema de información</td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    </tr>
    <tr>
        <td>14/12/2022</td>
        <td>1.0</td>
        <td>Subida del organigrama</td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td>14/12/2022</td>
        <td>1.0</td>
        <td>Subida de los modelos de procesos de negocio</td>
        <td>Daniel López García</td>
    <tr>
        <td>15/12/2022</td>
        <td>1.0</td>
        <td>Listado de Casos de uso</td>
        <td>Miguel Ángel Moncada Álvarez</td>
    </tr>
    <tr>
        <td>15/12/2022</td>
        <td>1.0</td>
        <td>Subida de los requisitos de información</td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td>15/12/2022</td>
        <td>1.0</td>
        <td>Corrección tablas requisitos funcionales</td>
        <td>Eduardo Martín Gómez</td>
    </tr>
    <tr>
        <td>15/12/2022</td>
        <td>1.0</td>
        <td>Subida de los casos de uso del portal detallados</td>
        <td>Daniel López García</td>
    </tr>
        <tr>
        <td>16/12/2022</td>
        <td>1.0</td>
        <td>Subida de los casos de uso del Sistema de información detallados</td>
        <td>Miguel Ángel Moncada Álvarez</td>
    </tr>
    <tr>
        <td>20/12/2022</td>
        <td>1.0</td>
        <td>Corrección tablas requisitos funcionales por cambios en el diagrama</td>
        <td>Eduardo Martín Gómez</td>
    </tr>
</table>

<br><br>

## <a name="contenidos"></a> Contenidos

<br>

[Hoja de revisión](#hojaderevision)<br>
[Contenidos](#contenidos)<br>
[1. &nbsp;&nbsp;&nbsp;&nbsp; Introducción](#introduccion)<br>
[2. &nbsp;&nbsp;&nbsp;&nbsp; Información del dominio del problema [opcional]](#informaciondeldominiodelproblema)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [2.1. &nbsp;&nbsp;&nbsp;&nbsp; Organigrama](#organigrama)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [2.2. &nbsp;&nbsp;&nbsp;&nbsp; Glosario de términos](#glosariodeterminos)<br>
[3. &nbsp;&nbsp;&nbsp;&nbsp; Necesidades del negocio](#necesidadesdelnegocio)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [3.1. &nbsp;&nbsp;&nbsp;&nbsp; Objetivos del negocio](#objetivosdelnegocio)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [3.2. &nbsp;&nbsp;&nbsp;&nbsp; Modelos de Procesos de Negocio [opcional]](#modelosdeprocesosdenegocio)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Procesos](#procesos)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Tareas](#tareas)<br>
[4. &nbsp;&nbsp;&nbsp;&nbsp; Requisitos del sistema a desarrollar](#requisitosdelsistemaadesarrollar)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [4.1. &nbsp;&nbsp;&nbsp;&nbsp; Requisitos](#requisitos)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Requisitos funcionales del Portal](#requisitosfuncionalesdelportal)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Requisitos funcionales del Sistema de información](#requisitosfuncionalesdelsistemadeinformacion)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Requisitos no funcionales del Portal](#requisitosnofuncionalesdelportal)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Requisitos no funcionales del Sistema de Información](#requisitosnofuncionalesdelsistemadeinformacion)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Requisitos de información del Portal](#requisitosdeinformaciondelportal)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Requisitos de información del Sistema de Información](#requisitosdeinformaciondelsistemadeinformacion)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [4.2. &nbsp;&nbsp;&nbsp;&nbsp; Casos de uso](#casosdeuso)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Lista de diagramas de casos de uso del modelo](#listadediagramasdecasosdeusodelmodelo)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Diagramas de casos de uso](#diagramasdecasosdeuso)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Lista de casos de uso del Portal](#listadecasosdeusodelportal)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Lista de casos de uso del Sistema de Información](#listadecasosdeusodelsistemadeinformacion)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Lista de actores del Portal](#listadeactoresdelportal)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Lista de actores del Sistema de información](#listadeactoresdelsistemadeinformacion)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Detalle de los casos de uso del Portal](#detalledeloscasosdeusodelportal)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Detalle de los casos de uso del Sistema de información](#detalledeloscasosdeusodelsistemadeinformacion)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [4.3. &nbsp;&nbsp;&nbsp;&nbsp; Diagramas E/R y de clases asociados a los requisitos de información](#diagramaserydeclasesasociadosalosrequisitosdeinformacion)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Lista de diagramas E/R del modelo](#listadediagramaserdelmodelo)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Diagramas E/R del modelo](#diagramaserdelmodelo)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Lista de diagramas de clases del modelo](#listadediagramasdeclasesdelmodelo)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Diagramas de clases del modelo](#diagramasdeclasesdelmodelo)<br>
[Apéndices](#apendices)

<br><br>

## <a name="introduccion"></a> 1. Introducción

<br>

<p>Una vez leído el pliego de las condiciones hemos decicido abarcar este proyecto para crear dos aplicaciones con objeto de favorecer y facilitar el uso de transporte público en la isla de Gran Canaria. Para ello hemos desarrollado una entrevista (ver anexo) con un usuario habitual para, de este modo, aclarar algunas dudas que nos han surgido durante el planteamiento inicial del proyecto. Una vez terminada, nos disponemos a crear el presente archivo con nuestra propuesta documentada de las aplicaciones del pliego inicial.</p>

<br>

## <a name="informaciondeldominiodelproblema"></a> 2. Información del Dominio del problema [opcional]

<br>

### <a name="organigrama"></a> 2.1. Organigrama

<br>

<div align="center"><img src="./out/organigrama/organigrama.svg"></div>

<br>

### <a name="glosariodeterminos"></a> 2.2. Glosario de términos

<br>

<table align = "center">
    <tr>
        <td><b>Término</b></td>
        <td><b>Descripción</b></td>
    </tr>
    <tr>
        <td>Cloud Tag</td>
        <td>Nube donde de forma gráfica en forma de etiquetas se pueden acceder a las funcionalidades de la página</td>
    </tr>
</table>

<br><br>

## <a name="necesidadesdelnegocio"></a> 3. Necesidades del negocio

<br>

### <a name="objetivosdelnegocio"></a> 3.1. Objetivos del negocio

<br>

<p>Como ya hemos visto la intención de este proyecto es la de crear dos aplicaciones, una aplicación que nos muestre información sobre eventos, rutas de autobuses, noticias e itinerarios de la isla, ... (entre otras muchas opciones) y otra aplicación que implementará una pasarela de pago para poder comprar billetes y reservar itinerarios, un mapa iteractivo sobre el que poder realizar diversas operaciones, etc. Nuestro propósito es el de crear ambas aplicaciones con una grata experiencia de usuario y de manera eficiente. Siempre, claro está, cuidando que sea accesible para la gran mayoría de usuarios.</p>

<br>

### <a name="modelosdeprocesosdenegocio"></a> 3.2. Modelos de Procesos de Negocio [opcional]

<br>

### <a name="procesos"></a> Procesos

<br>

<table align = "center">
    <tr>
        <td><b>Nombre</b></td>
        <td><b>Descripción</b></td>
    </tr>
    <tr>
        <td>Validación del DNI al registrarse</td>
        <td>Un usuario no registrado envía una foto la cual será recibida por el gestor de contenidos, este a su vez lo enviará por un proceso de verificación llevado a cabo por el software externo a la empresa. En caso de que el software verifique la validez del DNI este enviará un informe comentando dicho resultado al gestor de contenidos y en caso de ser rechazada la imagen se enviará un informe con los fallos al gestor de contenidos. Cuando el gestor reciba el informe de los fallos se lo mandará al usuario para que vuelva a mandar la imagen del DNI y haga de nuevo el proceso de verificación. Si la foto ha sido validada le mandará al usuario un mensaje de verificación y terminará el proceso</td>
    </tr>
    <tr>
        <td>Adquisición de un bono o de un título único de transporte</td>
        <td>El usuario tendrá la opción tanto de comprar un bono, como de adquirir el título de transporte. Una vez seleccionada la opción, se deberá enviar el formulario del servicio escogido al sistema. En caso de que cumpla los requisitos, se proporcionará el bono o título solicitado al usuario en cuestión, haciéndole llegar un mensaje con las credenciales correspondientes a dicho bono o título a su correo. En caso contrario, se le mandará un mensaje comunicándole que el formulario debe volver a ser rellenado pues ha habido algún tipo de error</td>
    </tr>
    <tr>
        <td>Reserva de itinerario</td>
        <td>1. El proceso comienza cuando un cliente busca un itinerario y solicita su reserva.<br>
        2. La solicitud es recibida por el sistema de reservas, que verifica la disponibilidad de los servicios solicitados.<br>
        3. Si hay disponibilidad, se procede a generar una factura del precio total del itinerario y se envía al cliente.<br>
        4. Si no hay disponibilidad se mandará un aviso al cliente.<br>
        5. Cuando el cliente recibe la factura podrá realizar el pago o cancelar la reserva terminando el proceso.<br>
        6. Cuando el cliente reciba el aviso de que no hay disponibilidad, podrá buscar otro itinerario iniciando de nuevo el proceso o terminar el proceso.<br>
        7. Cuando realice el pago le llegará un aviso al sistema de reservas, este se encargará de generar el recibo y de enviárselo al cliente.<br>
        8. Cuando al cliente le llega el recibo se termina el proceso.</td>
    </tr>
</table>

<br>

### <a name="tareas"></a> Tareas

<br>

- Tareas del proceso 1: Validación del DNI al registrarse

<br>

<p>Un usuario no registrado envía una foto la cual será recibida por el gestor de contenidos, este a su vez lo enviará por un proceso de verificación llevado a cabo por el software externo a la empresa. En caso de que el software verifique la validez del DNI este enviará un informe comentando dicho resultado al gestor de contenidos y en caso de ser rechazada la imagen se enviará un informe con los fallos al gestor de contenidos. Cuando el gestor reciba el informe de los fallos se lo mandará al usuario para que vuelva a mandar la imagen del DNI y haga de nuevo el proceso de verificación. Si la foto ha sido validada le mandará al usuario un mensaje de verificación y terminará el proceso</p>

<br>

<div align="center"><img src="./out/BPMN/BPMN_validacion_de_DNI.svg"></div>

<br>

- Tareas del proceso 2: Adquisición de un bono o de un título único de transporte

<br>

<p>El usuario tendrá la opción tanto de comprar un bono, como de adquirir el título de transporte. Una vez seleccionada la opción, se deberá enviar el formulario del servicio escogido al sistema. En caso de que cumpla los requisitos, se proporcionará el bono o título solicitado al usuario en cuestión, haciéndole llegar un mensaje con las credenciales correspondientes a dicho bono o título a su correo. En caso contrario, se le mandará un mensaje comunicándole que el formulario debe volver a ser rellenado pues ha habido algún tipo de error</p>

<br>

<div align="center"><img src="./out/BPMN/BPMN_adquisicion_de_bono_o_titulo.svg"></div>

<br>

- Tareas del proceso 3: Reserva de itinerario

<br>

<p>1. El proceso comienza cuando un cliente busca un itinerario y solicita su reserva.<br>
2. La solicitud es recibida por el sistema de reservas, que verifica la disponibilidad de los servicios solicitados.<br>
3. Si hay disponibilidad, se procede a generar una factura del precio total del itinerario y se envía al cliente.<br>
4. Si no hay disponibilidad se mandará un aviso al cliente.<br>
5. Cuando el cliente recibe la factura podrá realizar el pago o cancelar la reserva terminando el proceso.<br>
6. Cuando el cliente reciba el aviso de que no hay disponibilidad, podrá buscar otro itinerario iniciando de nuevo el proceso o terminar el proceso.<br>
7. Cuando realice el pago le llegará un aviso al sistema de reservas, este se encargará de generar el recibo y de enviárselo al cliente.<br>
8. Cuando al cliente le llega el recibo se termina el proceso.</td></p>

<br>

<div align="center"><img src="./out/BPMN/BPMN_reserva_de_itinerario.svg"></div>

<br><br>

## <a name="requisitosdelsistemaadesarrollar"></a> 4. Requisitos del sistema a desarrollar

<br>

### <a name="requisitos"></a> 4.1. Requisitos

<br>

### <a name="requisitosfuncionalesdelportal"></a> Requisitos funcionales del Portal

<br>

<table align = "center">
    <tr>
        <td><b>FR-01:</b></td>
        <td>Acceder al blog</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-03</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema ofrece acceso al blog con información acerca del transporte en las Islas Canarias</td>
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

<table align = "center">
    <tr>
        <td><b>FR-02:</b></td>
        <td>Acceder al foro</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-04</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema ofrece acceso al foro de la página donde se podrá comentar acerca de la situación del transporte, rutas, servicios ofrecidos... etc </td>
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

<table align = "center">
    <tr>
        <td><b>FR-03:</b></td>
        <td>Acceder a cloud tag</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-05</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrece de forma gráfica acceso a las funcionalidades de la página a través de etiquetas visuales en la nube</td>
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

<table align = "center">
    <tr>
        <td><b>FR-04:</b></td>
        <td>Buscador</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-06</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Permitirá la localización de cualquier contenido de manera inmediata mediante la introducción de términos clave</td>
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
        <td>- En las búsquedas no se diferenciarán las palabras con o sin acento, mayúsculas o minúsculas.<br>
        - Dispondrá de opciones que permitan la parametrización de las búsquedas considerando características como el idioma, secciones del sitio, etc </td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>FR-05:</b></td>
        <td>Ver noticias</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-08</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrece la posibilidad de ver las noticias acerca de eventos en las Islas Canarias y la disponibilidad del transporte </td>
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

<table align = "center">
    <tr>
        <td><b>FR-06:</b></td>
        <td>Contactar con el equipo de la aplicación</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-09</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Da la posibilidad de contactar con el equipo de la aplicación ya sea a través del correo electrónico o de un número de teléfono</td>
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

<table align = "center">
    <tr>
        <td><b>FR-07:</b></td>
        <td>Ver horarios de las líneas y servicios</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-02</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Muestra los horarios de las distintas líneas. Además, se podrán ver los diferentes servicios disponibles.</td>
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

<table align = "center">
    <tr>
        <td><b>FR-08:</b></td>
        <td>Ver itinerarios destacados</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-12</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrece una lista con los itinerarios más destacados entre los usuarios</td>
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

<table align = "center">
    <tr>
        <td><b>FR-09:</b></td>
        <td>Ver tarifas y títulos de transporte</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-13</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrece una vista de las distintas tarifas y titulos disponibles para adquirir</td>
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

<table align = "center">
    <tr>
        <td><b>FR-10:</b></td>
        <td>Ver publicidad</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-14</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Aparecen anuncios acerca del transporte en la isla o anuncios de otras empresas externas</td>
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

<table align = "center">
    <tr>
        <td><b>FR-11:</b></td>
        <td>Ver información corporativa</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-01</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrece información corporativa del ayuntamiento de las Islas Canarias</td>
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

<table align = "center">
    <tr>
        <td><b>FR-12:</b></td>
        <td>Cambio de idioma</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-07</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrece la posibilidad de cambiar el idioma en el que aparece el contenido de la página</td>
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

<table align = "center">
    <tr>
        <td><b>FR-13:</b></td>
        <td>Ver información acerca de lugares</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-10</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrece información acerca de los distintos lugares de las Islas Canarias</td>
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

<table align = "center">
    <tr>
        <td><b>FR-14:</b></td>
        <td>Recibir avisos</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-11</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se ofrece información acerca de posibles cambios o alteraciones en en el turismo de las Islas Canarias</td>
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

<table align = "center">
    <tr>
        <td><b>FR-15:</b></td>
        <td>Crear nuevas páginas</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-15</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán crear nuevas páginas en la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-16:</b></td>
        <td>Previsualizar páginas nuevas</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-16</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán visualizar las nuevas páginas que se han creado antes de añadirlas a la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-17:</b></td>
        <td>Modificar datos de una página</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-17</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán modificar datos ya existentes en la página web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-18:</b></td>
        <td>Gestionar publicidad</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-21</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá gestionar la publicidad que se muestra en la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-19:</b></td>
        <td>Ver estadísticas de acceso</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-20</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán visualizar las estadísticas de acceso a la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-20:</b></td>
        <td>Eliminar páginas</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán eliminar páginas de la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-21:</b></td>
        <td>Gestionar idiomas</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-18</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán gestionar los distintos idiomas que va a soportar la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-22:</b></td>
        <td>Modificar diseño común</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-19</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá modificar el diseño común de la página web</td>
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

### <a name="requisitosfuncionalesdelsistemadeinformacion"></a> Requisitos funcionales del Sistema de información

<br>

<table align = "center">
    <tr>
        <td><b>FR-01:</b></td>
        <td>Búsqueda de itinerarios</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-33</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se realiza una búsqueda de itinerarios</td>
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

<table align = "center">
    <tr>
        <td><b>FR-02:</b></td>
        <td>Seleccionar fecha y hora de un itinerario</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-39</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá seleccionar la fecha y la hora de salida o llegada que se desee para llegar hasta algún punto. Como resultado, se mostrarán los itinerarios que se adapten a estos requisitos</td>
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

<table align = "center">
    <tr>
        <td><b>FR-03:</b></td>
        <td>Seleccionar origen-destino</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-34</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Selección del origen y el destino del itinerario</td>
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

<table align = "center">
    <tr>
        <td><b>FR-04:</b></td>
        <td>Pedir imprimible del esquema del recorrido</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-40</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se solicita el imprimible del esquema del recorrido correspondiente al itinerario en cuestión</td>
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

<table align = "center">
    <tr>
        <td><b>FR-05:</b></td>
        <td>Seleccionar criterio de búsqueda de itinerarios</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-35</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se realiza la búsqueda de itinerarios según el criterio escogido</td>
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

<table align = "center">
    <tr>
        <td><b>FR-06:</b></td>
        <td>Ordenar la búsqueda por coste</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-36</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se ordenan los distintos itinerarios que se muestran en base al menor coste de estos</td>
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

<table align = "center">
    <tr>
        <td><b>FR-07:</b></td>
        <td>Ordenar la búsqueda por tiempo</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-37</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se ordenan los distintos itinerarios que se muestran en base a la duración del trayecto total</td>
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

<table align = "center">
    <tr>
        <td><b>FR-08:</b></td>
        <td>Ordenar la búsqueda por transbordos</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-38</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se ordenan los distintos itinerarios que se muestran en base a los que requieran menos transbordos</td>
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

<table align = "center">
    <tr>
        <td><b>FR-09:</b></td>
        <td>Ver recorrido de una línea</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-26</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá ver el recorrido de la línea en el mapa</td>
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

<table align = "center">
    <tr>
        <td><b>FR-10:</b></td>
        <td>Iniciar sesión</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-20</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Inicia sesión introduciendo tanto el nombre de usuario como su contraseña</td>
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

<table align = "center">
    <tr>
        <td><b>FR-11:</b></td>
        <td>Registrarse</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-21</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El usuario se podrá registrar en la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-12:</b></td>
        <td>Renovar título</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-16</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Renueva el título de transporte actual</td>
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

<table align = "center">
    <tr>
        <td><b>FR-13:</b></td>
        <td>Adquirir título de transporte</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-19</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrece la posibilidad de comprar un título de transporte</td>
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

<table align = "center">
    <tr>
        <td><b>FR-14:</b></td>
        <td>Recargar saldo del título de transporte</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-18</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Recarga el saldo del título de transporte adjuntada a la cuenta iniciada</td>
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

<table align = "center">
    <tr>
        <td><b>FR-15:</b></td>
        <td>Adquirir bono transporte</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-15</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá adquirir un bono de transporte que otorgará al usuario una serie de ventajas</td>
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

<table align = "center">
    <tr>
        <td><b>FR-16:</b></td>
        <td>Ver histórico de itinerarios</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-17</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá ver el historial de itinerarios realizados con anterioridad</td>
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

<table align = "center">
    <tr>
        <td><b>FR-17:</b></td>
        <td>Gestionar sistema de ventas y título de transporte</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-06</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Gestiona las acciones de venta de servicios de transporte y el título de transporte único para cada usuario siempre que esté registrado</td>
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

<table align = "center">
    <tr>
        <td><b>FR-18:</b></td>
        <td>Crear aviso por correo electrónico</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-14</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se mandarán avisos de incidencias/alteraciones/novedades al correo electrónico de los usuarios</td>
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

<table align = "center">
    <tr>
        <td><b>FR-19:</b></td>
        <td>Crear aviso por sms</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-13</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se mandarán avisos de incidencias/alteraciones/novedades al teléfono móvil de los usuarios vía sms</td>
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

<table align = "center">
    <tr>
        <td><b>FR-20:</b></td>
        <td>Crear aviso visual</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-12</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se crearán avisos visuales de incidencias/alteraciones/novedades</td>
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

<table align = "center">
    <tr>
        <td><b>FR-21:</b></td>
        <td>Crear aviso acústico</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-11</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se crearán avisos acústicos de incidencias/alteraciones/novedades</td>
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

<table align = "center">
    <tr>
        <td><b>FR-22:</b></td>
        <td>Gestionar usuarios</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-08</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán gestionar los usuarios registrados en la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-23:</b></td>
        <td>Definir condiciones</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-10</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán crear condiciones en el flujo de la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-24:</b></td>
        <td>Definir variables</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-09</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán definir variables en el flujo de la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-25:</b></td>
        <td>Definir eventos/incidencias</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-07</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán definir eventos e incidencias en la web</td>
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

<table align = "center">
    <tr>
        <td><b>FR-26:</b></td>
        <td>Ver actividad de los operadores</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-01</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá ver la actividad de los operadores en base a los datos de las jornadas laborales de estos<td>
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
        <td>Se estudian tanto grupal como individualmente</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>FR-27:</b></td>
        <td>Visualizar foto de estado de la actividad de los operadores</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-02</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá ver la foto del estado actual de la actividad realizada por los operadores durante sus jornadas laborales</td>
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
        <td>Se estudian tanto grupal como individualmente</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>FR-28:</b></td>
        <td>Visualizar película de evolución temporal de los operadores</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-03</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá visualizar una película de evolución temporal de la actividad realizada por los operadores</td>
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
        <td>Se estudian tanto grupal como individualmente</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>FR-29:</b></td>
        <td>Gestionar elementos del mapa</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-04</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán gestionar los distintos elementos del mapa interactivo</td>
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
        <td>Se estudian tanto grupal como individualmente</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>FR-30:</b></td>
        <td>Gestionar líneas (visualmente)</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-05</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán gestionar las distintas líneas de transporte del mapa interactivo/td>
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
        <td>Se estudian tanto grupal como individualmente</td>
    </tr>
</table>
<br>

<table align = "center">
    <tr>
        <td><b>FR-31:</b></td>
        <td>Ver información acerca de lugares/paradas/sitios de interés turístico</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá ver información detallada acerca de lugares y sitios de interés turístico, así como de las distintas paradas y zonas de las Islas Canarias</td>
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

<table align = "center">
    <tr>
        <td><b>FR-32:</b></td>
        <td>Reservar itinerario</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-23</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá reservar un itinerario</td>
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

<table align = "center">
    <tr>
        <td><b>FR-33:</b></td>
        <td>Pagar reserva de itinerario</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-24</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá pagar la reserva del itinerario en cuestión</td>
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

<table align = "center">
    <tr>
        <td><b>FR-34:</b></td>
        <td>Pedir justificante de pago</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-25</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá pedir el justificante del pago de la reserva de un itinerario</td>
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

<table align = "center">
    <tr>
        <td><b>FR-35:</b></td>
        <td>Buscar una parada</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-27</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá buscar una parada en concreto</td>
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

<table align = "center">
    <tr>
        <td><b>FR-36:</b></td>
        <td>Introducción de identificador de parada</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-32</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá introducir un identificador de parada para facilitar la búsqueda de la misma</td>
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

<table align = "center">
    <tr>
        <td><b>FR-37:</b></td>
        <td>Buscar parada en base a un criterio</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-28</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrá personalizar la búsqueda de paradas estableciendo un determinado criterio</td>
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

<table align = "center">
    <tr>
        <td><b>FR-38:</b></td>
        <td>Búsqueda de paradas pertenecientes a un lugar</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-29</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán buscar paradas que pertenezcan a un lugar en concreto</td>
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

<table align = "center">
    <tr>
        <td><b>FR-39:</b></td>
        <td>Búsqueda de paradas pertenecientes a una línea</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-30</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán buscar paradas que pertenezcan a una línea en concreto</td>
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

<table align = "center">
    <tr>
        <td><b>FR-40:</b></td>
        <td>Búsqueda de paradas cercanas a un origen/destino determinado</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>UC-31</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Se podrán buscar las paradas más cercanas a un punto de origen o destino</td>
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

### <a name="requisitosnofuncionalesdelportal"></a> Requisitos no funcionales del Portal

<br>

<table align = "center">
    <tr>
        <td><b>NFR-01:</b></td>
        <td>Dar un servicio multidispositivo soportado</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>Identificadores de casos de uso, de requisitos funcionales, no funcionales y de requisitos información del sistema</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Permite el funcionamiento de la página en cualquier dispositivo</td>
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

<table align = "center">
    <tr>
        <td><b>NFR-02:</b></td>
        <td>Ofrecer un buscador insensible a acentos o mayúsculas</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>Identificadores de casos de uso, de requisitos funcionales, no funcionales y de requisitos información del sistema</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrecer los mismos resultados independientemente de escribir en mayúscula o con acentos</td>
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

<table align = "center">
    <tr>
        <td><b>NFR-03:</b></td>
        <td>Editor WYSIMYG</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>Identificadores de casos de uso, de requisitos funcionales, no funcionales y de requisitos información del sistema</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Proporcionar un editor WYSIWYG de manera que el gestor no tenga necesidad de tener conocimientos de codificación para editar la página</td>
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

<table align = "center">
    <tr>
        <td><b>NFR-04:</b></td>
        <td>Establecer sistema de seguridad</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>Identificadores de casos de uso, de requisitos funcionales, no funcionales y de requisitos información del sistema</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Proteger los datos y proporcionar una navegación segura al hacer uso de la página</td>
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

<table align = "center">
    <tr>
        <td><b>NFR-05:</b></td>
        <td>Emplear lenguaje PL/SQL</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>Identificadores de casos de uso, de requisitos funcionales, no funcionales y de requisitos información del sistema</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Realizar las tareas de codificación empleando lenguaje PL/SQL</td>
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

### <a name="requisitosnofuncionalesdelsistemadeinformacion"></a> Requisitos no funcionales del Sistema de información

<br>

<table align = "center">
    <tr>
        <td><b>NFR-01:</b></td>
        <td>Dar un servicio multidispositivo soportado</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>Identificadores de casos de uso, de requisitos funcionales, no funcionales y de requisitos información del sistema</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Permite el funcionamiento de la página en cualquier dispositivo</td>
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

<table align = "center">
    <tr>
        <td><b>NFR-02:</b></td>
        <td>Ofrecer un buscador insensible a acentos o mayúsculas</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>Identificadores de casos de uso, de requisitos funcionales, no funcionales y de requisitos información del sistema</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrecer los mismos resultados independientemente de escribir en mayúscula o con acentos</td>
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

<table align = "center">
    <tr>
        <td><b>NFR-03:</b></td>
        <td>Establecer sistema de seguridad</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>Identificadores de casos de uso, de requisitos funcionales, no funcionales y de requisitos información del sistema</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Proteger los datos y proporcionar una navegación segura al hacer uso de la página</td>
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

<table align = "center">
    <tr>
        <td><b>NFR-04:</b></td>
        <td>Tiempo de búsqueda de itinerarios menor a 100ms</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>Identificadores de casos de uso, de requisitos funcionales, no funcionales y de requisitos información del sistema</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>Ofrecer los resultados de búsqueda de un itinerario en un tiempo menor a 100ms</td>
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

### <a name="requisitosdeinformaciondelportal"></a> Requisitos de información del Portal

<br>

<table align = "center">
    <tr>
        <td><b>IR-01:</b></td>
        <td>Usuario</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td></td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los usuarios del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de usuario<br>
        - Número del documento nacional de identidad<br>
        - Nombre y apellidos<br>
        - Fecha de nacimiento<br>
        - Sexo<br>
        - Fecha de alta como usuario<br>
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

<table align = "center">
    <tr>
        <td><b>IR-02:</b></td>
        <td>Gestor</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td></td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los gestores del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de gestor<br>
        - Número del documento nacional de identidad<br>
        - Nombre y apellidos<br>
        - Fecha de nacimiento<br>
        - Sexo<br>
        - Fecha de alta como gestor<br>
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

<table align = "center">
    <tr>
        <td><b>IR-03:</b></td>
        <td>Imagen</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-04, IR-06, IR-08, IR-10, IR-12, IR-14, IR-16, IR-18, IR-20, CU-01, CU-02, CU-05, CU-08, CU-09, CU-10, CU-11, CU-12, CU-13, CU-14, CU-21</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Título identificativo de imagen<br>
        - Url de imagen</td>
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

<table align = "center">
    <tr>
        <td><b>IR-04:</b></td>
        <td>ImagenAvisoInformativo</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-05, CU-11</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes relacionadas con los avisos informativos del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Identificador de aviso<br>
        - Idioma del aviso (español, inglés, alemán, francés o italiano)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-05:</b></td>
        <td>AvisoInformativo</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-04, CU-07, CU-11, CU-18</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los avisos informativos del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de aviso<br>
        - Idioma del aviso (español, inglés, alemán, francés o italiano)<br>
        - Cabecera del aviso<br>
        - Cuerpo del aviso<br>
        - Texto adicional nº 1<br>
        - Texto adicional nº 2</td>
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

<table align = "center">
    <tr>
        <td><b>IR-06:</b></td>
        <td>ImagenInfoContacto</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-07, CU-09, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes relacionadas con la página de contacto del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Idioma de la página de contacto (español, inglés, alemán, francés o italiano)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-07:</b></td>
        <td>InfoContacto</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-06, CU-07, CU-09, CU-17, CU-18, CU-19, CU-20, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la página de contacto del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Idioma de la página de contacto (español, inglés, alemán, francés o italiano)<br>
        - Cuerpo de la página<br>
        - Texto adicional nº 1<br>
        - Texto adicional nº 2<br>
        - Número de accesos a la página</td>
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

<table align = "center">
    <tr>
        <td><b>IR-08:</b></td>
        <td>ImagenInfoCorporativa</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-09, CU-01, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes relacionadas con la página de información corporativa del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Idioma de la página de información corporativa (español, inglés, alemán, francés o italiano)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-09:</b></td>
        <td>InfoCorporativa</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-08, CU-01, CU-07, CU-17, CU-18, CU-19, CU-20, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la página de información corporativa del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Idioma de la página de información corporativa (español, inglés, alemán, francés o italiano)<br>
        - Cuerpo de la página<br>
        - Texto adicional nº 1<br>
        - Texto adicional nº 2<br>
        - Número de accesos a la página</td>
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

<table align = "center">
    <tr>
        <td><b>IR-10:</b></td>
        <td>ImagenInfoHorariosServicios</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
        <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-11, CU-02, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes relacionadas con la página de horarios y servicios del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Idioma de la página de horarios y servicios (español, inglés, alemán, francés o italiano)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-11:</b></td>
        <td>InfoHorariosServicios</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-10, CU-02, CU-07, CU-17, CU-18, CU-19, CU-20, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la página de horarios y servicios del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Idioma de la página de horarios y servicios (español, inglés, alemán, francés o italiano)<br>
        - Cuerpo de la página<br>
        - Texto adicional nº 1<br>
        - Texto adicional nº 2<br>
        - Número de accesos a la página</td>
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

<table align = "center">
    <tr>
        <td><b>IR-12:</b></td>
        <td>ImagenInfoItinerariosDestacados</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-13, CU-12, CU-22</td>
    </tr>
      <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes relacionadas con la página de itinerarios destacados del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Idioma de la página de itinerarios destacados (español, inglés, alemán, francés o italiano)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-13:</b></td>
        <td>InfoItinerariosDestacados</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-12, CU-07, CU-12, CU-17, CU-18, CU-19, CU-20, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la página de itinerarios destacados del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Idioma de la página de itinerarios destacados (español, inglés, alemán, francés o italiano)<br>
        - Cuerpo de la página<br>
        - Texto adicional nº 1<br>
        - Texto adicional nº 2<br>
        - Número de accesos a la página</td>
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

<table align = "center">
    <tr>
        <td><b>IR-14:</b></td>
        <td>ImagenInfoLugares</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-15, CU-10, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes relacionadas con la página de lugares del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Idioma de la página de lugares (español, inglés, alemán, francés o italiano)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-15:</b></td>
        <td>InfoLugares</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-14, CU-07, CU-10, CU-17, CU-18, CU-19, CU-20, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la página de lugares del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Idioma de la página de lugares (español, inglés, alemán, francés o italiano)<br>
        - Cuerpo de la página<br>
        - Texto adicional nº 1<br>
        - Texto adicional nº 2<br>
        - Número de accesos a la página</td>
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

<table align = "center">
    <tr>
        <td><b>IR-16:</b></td>
        <td>ImagenInfoNoticias</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-17, CU-08, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes relacionadas con la página de noticias del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Idioma de la página de noticias (español, inglés, alemán, francés o italiano)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-17:</b></td>
        <td>InfoNoticias</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-16, CU-07, CU-08, CU-17, CU-18, CU-19, CU-20, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la página de noticias del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Idioma de la página de noticias (español, inglés, alemán, francés o italiano)<br>
        - Cuerpo de la página<br>
        - Texto adicional nº 1<br>
        - Texto adicional nº 2<br>
        - Número de accesos a la página</td>
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

<table align = "center">
    <tr>
        <td><b>IR-18:</b></td>
        <td>ImagenInfoTitulosTarifas</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-19, CU-13, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes relacionadas con la página de títulos y tarifas del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Idioma de la página de títulos y tarifas (español, inglés, alemán, francés o italiano)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-19:</b></td>
        <td>InfoTitulosTarifas</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-18, CU-07, CU-13, CU-17, CU-18, CU-19, CU-20, CU-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la página de títulos y tarifas del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Idioma de la página de títulos y tarifas (español, inglés, alemán, francés o italiano)<br>
        - Cuerpo de la página<br>
        - Texto adicional nº 1<br>
        - Texto adicional nº 2<br>
        - Número de accesos a la página</td>
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

<table align = "center">
    <tr>
        <td><b>IR-20:</b></td>
        <td>ImagenPublicidad</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-21, CU-14, CU-21</td>
    </tr>
     <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes relacionadas con la publicidad del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Identificador de publicidad<br>
        - Idioma de la publicidad (español, inglés, alemán, francés o italiano)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-21:</b></td>
        <td>Publicidad</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
        <tr>
        <td><b>Referencias:</b></td>
        <td>IR-20, CU-07, CU-14, CU-18, CU-21</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la publicidad del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de publicidad<br>
        - Idioma de la publicidad (español, inglés, alemán, francés o italiano)<br>
        - Cuerpo del aviso<br>
        - Texto adicional nº 1<br>
        - Texto adicional nº 2<br>
        - Fecha de expiración de la publicidad</td>
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

### <a name="requisitosdeinformaciondelsistemadeinformacion"></a> Requisitos de información del Sistema de información

<br>

<table align = "center">
    <tr>
        <td><b>IR-01:</b></td>
        <td>Aviso</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-02, IR-05</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los avisos del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de aviso<br>
        - Identificador de gestor<br>
        - Motivo del aviso<br>
        - Cuerpo del aviso<br>
        - Tipo de aviso (Acústico, visual, SMS o correo)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-02:</b></td>
        <td>AvisoCondicion</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-01, IR-03</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los avisos generados por una condición creada por un gestor del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de aviso<br>
        - Identificador de condición</td>
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

<table align = "center">
    <tr>
        <td><b>IR-03:</b></td>
        <td>Condicion</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-02, IR-04, IR-05</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las condiciones creadas por gestores del mismo para la generación de avisos. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de condición<br>
        - Identificador de gestor<br>
        - Descripción de la condición<br>
        - Controlador de la activación de la condición (si se quiere tener en cuenta o ser ignorada)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-04:</b></td>
        <td>CondicionVariable</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-03, IR-06</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las variables asociadas a la activación de condiciones creadas por gestores del mismo para la generación de avisos. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de condición<br>
        - Identificador de variable</td>
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

<table align = "center">
    <tr>
        <td><b>IR-05:</b></td>
        <td>Gestor</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-01, IR-03, IR-06, IR-11</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los gestores del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de gestor<br>
        - Número del documento nacional de identidad<br>
        - Nombre y apellidos<br>
        - Fecha de nacimiento<br>
        - Sexo<br>
        - Fecha de alta como gestor<br>
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

<table align = "center">
    <tr>
        <td><b>IR-06:</b></td>
        <td>Variable</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-04, IR-05</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las variables creadas por gestores del mismo para la activación de condiciones generadoras de avisos. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de variable<br>
        - Identificador de gestor<br>
        - Descripción de la variable<br>
        - Controlador de la activación de la variable (si se quiere tener en cuenta o ser ignorada)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-07:</b></td>
        <td>Calle</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-08, IR-10, IR-12, IR-19</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las calles de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de calle<br>
        - Identificador de lugar<br>
        - Nombre de la calle<br>
        - Tipo de calle (calle, carretera, avenida, plaza, camino o paseo)<br>
        - Número de visitas<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-08:</b></td>
        <td>CoordenadasGeograficas</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-07, IR-10, IR-11, IR-12</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las coordenadas geográficas de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Latitud<br>
        - Longitud<br>
        - Altura<br>
        - Identificador de calle<br>
        - Identificador de lugar</td>
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

<table align = "center">
    <tr>
        <td><b>IR-09:</b></td>
        <td>EventoCultural</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-12, IR-15</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los eventos culturales de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de evento cultural<br>
        - Identificador de lugar<br>
        - Nombre del evento cultural<br>
        - Descripción del evento cultural<br>
        - Fecha y hora de celebración del evento cultural<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-10:</b></td>
        <td>Portal</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-07, IR-08</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los portales de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Número de portal<br>
        - Identificador de calle<br>
        - Latitud<br>
        - Longitud<br>
        - Altura<br>
        - Nombre identificativo de portal<br>
        - Número de visitas</td>
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

<table align = "center">
    <tr>
        <td><b>IR-11:</b></td>
        <td>EventoIncidencia</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-05, IR-08, IR-15</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los eventos/incidencias definidos por gestores del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de evento/incidencia<br>
        - Latitud<br>
        - Longitud<br>
        - Altura<br>
        - Identificador de gestor<br>
        - Cabecera del evento/incidencia<br>
        - Descripción del evento/incidencia<br>
        - Fecha y hora de suceso del evento/incidencia<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-12:</b></td>
        <td>Lugar</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-07, IR-08, IR-09, IR-12, IR-20</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los lugares de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de lugar<br>
        - Identificador de lugar contenedor<br>
        - Nombre del lugar<br>
        - Tipo de lugar (zona, barrio o municipio)<br>
        - Número de visitas<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-13:</b></td>
        <td>Linea</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-14</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las líneas de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de línea<br>
        - Nombre identificativo de línea<br>
        - Descripción de la línea<br>
        - Número de visitas<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-14:</b></td>
        <td>ParadaEstacionLinea</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-13, IR-19</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las paradas/estaciones de las líneas de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de línea<br>
        - Identificador de parada/estación<br>
        - Función de la parada/estación (origen, destino o paso por parada)<br>
        - Número de parada<br>
        - Hora de paso por parada/estación</td>
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

<table align = "center">
    <tr>
        <td><b>IR-15:</b></td>
        <td>Imagen</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-09, IR-11, IR-19, IR-20, IR-21</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las imágenes del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de imagen<br>
        - Identificador de parada/estación<br>
        - Identificador de sitio de interés turístico<br>
        - Identificador de evento cultural<br>
        - Identificador de situación<br>
        - Identificador de evento/incidencia<br>
        - Título identificativo de imagen<br>
        - Url de imagen</td>
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

<table align = "center">
    <tr>
        <td><b>IR-16:</b></td>
        <td>Servicio</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-21, IR-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los servicios ofrecidos por los operadores del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de servicio<br>
        - Cabecera identificativa de servicio<br>
        - Descripción del servicio<br>
        - Fecha y hora inicial del servicio<br>
        - Fecha y hora inicial real del servicio<br>
        - Fecha y hora final del servicio<br>
        - Fecha y hora final real del servicio<br>
        - Controlador de la cancelación del servicio<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-17:</b></td>
        <td>Operador</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-22</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los operadores del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Matrícula del operador<br>
        - Medio de transporte (guagua urbana, guagua interurbana, coche/taxi, embarcación pesada o avión)<br>
        - Capacidad del operador<br>
        - Ocupación del operador<br>
        - Controlador de la disponibilidad del operador<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-18:</b></td>
        <td>Etapa</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-23, IR-24</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las etapas de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de etapa<br>
        - Lugar de origen de la etapa<br>
        - Lugar de destino de la etapa<br>
        - Distancia (en km) de la etapa<br>
        - Coste de la etapa<br>
        - Fecha y hora de salida del lugar de origen de la etapa<br>
        - Fecha y hora de llegada al lugar de destino de la etapa<br>
        - Medio de transporte en que se realiza la etapa (guagua urbana, guagua interurbana, coche/taxi, embarcación pesada o avión)<br>
        - Número de visitas<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-19:</b></td>
        <td>ParadaEstacion</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-07, IR-14, IR-15, IR-24</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las paradas/estaciones de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de parada/estación<br>
        - Identificador de calle<br>
        - Nombre de la parada/estación<br>
        - Tipo (parada o estación)<br>
        - Controlador de la disponibilidad de la parada/estación<br>
        - Número de visitas<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-20:</b></td>
        <td>SitioInteresTuristico</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-12, IR-15</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los sitios de interés turístico de utilidad para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de sitio de interés turístico<br>
        - Identificador de lugar<br>
        - Nombre del sitio de interés turístico<br>
        - Tipo de sitio de interés turístico (plaza, parque nacional, duna, parque, playa o monumento)<br>
        - Descripción del sitio de interés turístico<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-21:</b></td>
        <td>Situacion</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-15, IR-16</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las diferentes situaciones obstáculo dadas durante los servicios ofrecidos por los operadores del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de situación<br>
        - Identificador de servicio<br>
        - Cabecera identificativa de situación<br>
        - Descripción de la situación<br>
        - Resolución esporádica llevada a cabo<br>
        - Fecha y hora en que se ha producido la situación<br>
        - Fecha y hora en que se ha actualizado por última vez el estado de la situación<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-22:</b></td>
        <td>ServicioOperador</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-16, IR-17</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la asociación entre los servicios ofrecidos por los operadores y los propios operadores del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de servicio<br>
        - Matrícula del operador</td>
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

<table align = "center">
    <tr>
        <td><b>IR-23:</b></td>
        <td>EtapaItinerario</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-18, IR-25</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la asociación entre los itinerarios de interés para el mismo y las etapas que lo componen. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de etapa<br>
        - Identificador de itinerario</td>
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

<table align = "center">
    <tr>
        <td><b>IR-24:</b></td>
        <td>ParadaEstacionEtapa</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-18, IR-19</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a la asociación entre las etapas de interés para el mismo y las paradas/estaciones de origen y destino de dicha etapa. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de parada/estación<br>
        - Identificador de etapa<br>
        - Función de la parada/estación (origen o destino)</td>
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

<table align = "center">
    <tr>
        <td><b>IR-25:</b></td>
        <td>Itinerario</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-23, IR-26</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los itinerarios de interés para el mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de itinerario<br>
        - Lugar de origen del itinerario<br>
        - Lugar de destino del itinerario<br>
        - Distancia (en km) del itinerario<br>
        - Coste del itinerario<br>
        - Fecha y hora de salida del lugar de origen del itinerario<br>
        - Fecha y hora de llegada al lugar de destino del itinerario<br>
        - Número de transbordos<br>
        - Número de reservas<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-26:</b></td>
        <td>Reserva</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-25, IR-29</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a las reservas de itinerarios efectuadas por los usuarios del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de reserva<br>
        - Identificador de usuario<br>
        - Identificador de itinerario<br>
        - Descripción de la reserva</td>
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

<table align = "center">
    <tr>
        <td><b>IR-27:</b></td>
        <td>Bono</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-29</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los bonos adquiridos por los usuarios del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de bono<br>
        - Identificador de usuario<br>
        - Nombre identificativo de bono<br>
        - Descripción del bono<br>
        - Coste del bono<br>
        - Información adicional</td>
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

<table align = "center">
    <tr>
        <td><b>IR-28:</b></td>
        <td>TituloTransporte</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-29</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los títulos de transporte adquiridos por los usuarios del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Código del título de transporte<br>
        - Identificador de usuario<br>
        - Categoría del título de transporte (básica, avanzada o premium)<br>
        - Fecha de expedición del título de transporte<br>
        - Fecha de caducidad del título de transporte<br>
        - Saldo disponible en el título de transporte<br>
        - Coste de recarga del título de transporte</td>
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

<table align = "center">
    <tr>
        <td><b>IR-29:</b></td>
        <td>Usuario</td>
    </tr>
    <tr>
        <td><b>Versión:</b></td>
        <td>1.0 (Diciembre-2022)</td>
    </tr>
    <tr>
        <td><b>Autor:</b></td>
        <td>Joaquín Murcia Escánez</td>
    </tr>
    <tr>
        <td><b>Fuentes:</b></td>
        <td>Pliego de condiciones y entrevista</td>
    </tr>
    <tr>
        <td><b>Referencias:</b></td>
        <td>IR-26, IR-27, IR-28</td>
    </tr>
    <tr>
        <td><b>Descripción:</b></td>
        <td>El sistema deberá almacenar la información correspondiente a los usuarios del mismo. En concreto:</td>
    </tr>
    <tr>
        <td><b>Datos específicos:</b></td>
        <td>- Identificador de usuario<br>
        - Número del documento nacional de identidad<br>
        - Nombre y apellidos<br>
        - Fecha de nacimiento<br>
        - Sexo<br>
        - Fecha de alta como usuario<br>
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

### <a name="casosdeuso"></a> 4.2. Casos de uso

<br>

### <a name="listadediagramasdecasosdeusodelmodelo"></a> Lista de diagramas de casos de uso del modelo

<br>

[- Diagrama de casos de uso general](#diagramacugeneral)<br>
[- Diagrama de casos de uso del Portal](#diagramacudelportal)<br>
[- Diagrama de casos de uso del Sistema de información](#diagramacudelsistemadeinformacion)

<br>

### <a name="diagramasdecasosdeuso"></a> Diagramas de casos de uso

<br>

<a name="diagramacugeneral"></a> Diagrama de casos de uso general

<br>

<div align="center"><img src="./out/DCU/DCU_general.svg"></div>

<br>

<a name="diagramacudelportal"></a> Diagrama de casos de uso del Portal

<br>

<div align="center"><img src="./out/DCU/DCU_P.svg"></div>

<br>

<a name="diagramacudelsistemadeinformacion"></a> Diagrama de casos de uso del Sistema de información

<br>

<div align="center"><img src="./out/DCU/DCU_SI.svg"></div>

<br>

### <a name="listadecasosdeusodelportal"></a> Lista de casos de uso del Portal

<br>

<table align = "center">
    <tr>
        <td><b>Identificador</b></td>
        <td><b>Nombre</b></td>
    </tr>
    <tr>
        <td>UC-01</td>
        <td>Ver página de información corporativa</td>
    </tr>
    <tr>
        <td>UC-02</td>
        <td>Ver página de horarios y servicios</td>
    </tr>
    <tr>
        <td>UC-03</td>
        <td>Acceder al blog</td>
    </tr>
    <tr>
        <td>UC-04</td>
        <td>Acceder al foro</td>
    </tr>
    <tr>
        <td>UC-05</td>
        <td>Ver cloud tag</td>
    </tr>
    <tr>
        <td>UC-06</td>
        <td>Buscar</td>
    </tr>
    <tr>
        <td>UC-07</td>
        <td>Cambiar idioma</td>
    </tr>
    <tr>
        <td>UC-08</td>
        <td>Ver noticias</td>
    </tr>
    <tr>
        <td>UC-09</td>
        <td>Ver página de contacto</td>
    </tr>
    <tr>
        <td>UC-10</td>
        <td>Ver página de lugares</td>
    </tr>
    <tr>
        <td>UC-11</td>
        <td>Recibir aviso</td>
    </tr>
    <tr>
        <td>UC-12</td>
        <td>Ver página de itinerarios destacados</td>
    </tr>
    <tr>
        <td>UC-13</td>
        <td>Ver página de títulos y tarifas del transporte</td>
    </tr>
    <tr>
        <td>UC-14</td>
        <td>Ver publicidad</td>
    </tr>
    <tr>
        <td>UC-15</td>
        <td>Crear página</td>
    </tr>
    <tr>
        <td>UC-16</td>
        <td>Previsualizar página</td>
    </tr>
    <tr>
        <td>UC-17</td>
        <td>Modificar datos de una página</td>
    </tr>
    <tr>
        <td>UC-18</td>
        <td>Gestionar idiomas</td>
    </tr>
    <tr>
        <td>UC-19</td>
        <td>Modificar diseño común</td>
    </tr>
    <tr>
        <td>UC-20</td>
        <td>Ver estadísticas de acceso a una página</td>
    </tr>
    <tr>
        <td>UC-21</td>
        <td>Gestionar publicidad</td>
    </tr>
    <tr>
        <td>UC-22</td>
        <td>Eliminar página</td>
    </tr>
</table>

<br>

### <a name="listadecasosdeusodelsistemadeinformacion"></a> Lista de casos de uso del Sistema de Información

<br>

<table align = "center">
     <tr>
        <td><b>Identificador</b></td>
        <td><b>Nombre</b></td>
    </tr>
    <tr>
        <td>UC-01</td>
        <td>Ver actividad de los operadores</td>
    </tr>
    <tr>
        <td>UC-02</td>
        <td>Ver foto de estado</td>
    </tr>
    <tr>
        <td>UC-03</td>
        <td>Ver película de evolución temporal</td>
    </tr>
    <tr>
        <td>UC-04</td>
        <td>Gestionar elementos mostrados en el mapa</td>
    </tr>
    <tr>
        <td>UC-05</td>
        <td>Gestionar líneas (visualmente)</td>
    </tr>
    <tr>
        <td>UC-06</td>
        <td>Gestionar sistema de ventas y título único del transporte</td>
    </tr>
    <tr>
        <td>UC-07</td>
        <td>Definir eventos/incidencias</td>
    </tr>
    <tr>
        <td>UC-08</td>
        <td>Gestionar usuarios</td>
    </tr>
    <tr>
        <td>UC-09</td>
        <td>Definir variables</td>
    </tr>
    <tr>
        <td>UC-10</td>
        <td>Definir condiciones</td>
    </tr>
    <tr>
        <td>UC-11</td>
        <td>Crear aviso acústico</td>
    </tr>
    <tr>
        <td>UC-12</td>
        <td>Crear aviso visual</td>
    </tr>
    <tr>
        <td>UC-13</td>
        <td>Crear aviso móvil</td>
    </tr>
    <tr>
        <td>UC-14</td>
        <td>Crear aviso por correo</td>
    </tr>
    <tr>
        <td>UC-15</td>
        <td>Adquirir bono</td>
    </tr>
    <tr>
        <td>UC-16</td>
        <td>Renovar título</td>
    </tr>
    <tr>
        <td>UC-17</td>
        <td>Ver histórico de itinerarios</td>
    </tr>
    <tr>
        <td>UC-18</td>
        <td>Recargar saldo del título</td>
    </tr>
    <tr>
        <td>UC-19</td>
        <td>Adquirir título</td>
    </tr>
    <tr>
        <td>UC-20</td>
        <td>Iniciar sesión</td>
    </tr>
    <tr>
        <td>UC-21</td>
        <td>Registrarse</td>
    </tr>
    <tr>
        <td>UC-22</td>
        <td>Ver información de lugares/paradas/sitios de interés turístico/ ...</td>
    </tr>
    <tr>
        <td>UC-23</td>
        <td>Reservar itinerario</td>
    </tr>
    <tr>
        <td>UC-24</td>
        <td>Pagar reserva</td>
    </tr>
    <tr>
        <td>UC-25</td>
        <td>Pedir justificante de pago</td>
    </tr>
    <tr>
        <td>UC-26</td>
        <td>Ver recorrido de línea</td>
    </tr>
    <tr>
        <td>UC-27</td>
        <td>Buscar paradas</td>
    </tr>
    <tr>
        <td>UC-28</td>
        <td>Buscar paradas en base a un criterio</td>
    </tr>
    <tr>
        <td>UC-29</td>
        <td>Buscar paradas en función de si pertenecen a un lugar</td>
    </tr>
    <tr>
        <td>UC-30</td>
        <td>Buscar paradas en función de si pertenecen a una línea</td>
    </tr>
    <tr>
        <td>UC-31</td>
        <td>Buscar paradas en función de si se encuentran cerca del origen/destino</td>
    </tr>
    <tr>
        <td>UC-32</td>
        <td>Introducir identificador de parada</td>
    </tr>
    <tr>
        <td>UC-33</td>
        <td>Buscar itinerarios</td>
    </tr>
    <tr>
        <td>UC-34</td>
        <td>Seleccionar origen/destino</td>
    </tr>
    <tr>
        <td>UC-35</td>
        <td>Buscar itinerarios en base a un criterio</td>
    </tr>
    <tr>
        <td>UC-36</td>
        <td>Buscar itinerarios en función del coste</td>
    </tr>
    <tr>
        <td>UC-37</td>
        <td>Buscar itinerarios en función del tiempo</td>
    </tr>
    <tr>
        <td>UC-38</td>
        <td>Buscar itinerarios en función del número de transbordos</td>
    </tr>
    <tr>
        <td>UC-39</td>
        <td>Seleccionar fechas y horas de salida y llegada</td>
    </tr>
    <tr>
        <td>UC-40</td>
        <td>Pedir imprimible del esquema del recorrido</td>
    </tr>
</table>

<br>

### <a name="listadeactoresdelportal"></a> Lista de actores del Portal

<br>

<table align = "center">
    <tr>
        <td><b>Identificador</b></td>
        <td><b>Nombre</b></td>
    </tr>
    <tr>
        <td>ACT-01</td>
        <td>Usuario (Portal)</td>
    </tr>
    <tr>
        <td>ACT-02</td>
        <td>Gestor (Portal)</td>
    </tr>
</table>

<br>

### <a name="listadeactoresdelsistemadeinformacion"></a> Lista de actores del Sistema de información

<br>

<table align = "center">
    <tr>
        <td><b>Identificador</b></td>
        <td><b>Nombre</b></td>
    </tr>
    <tr>
        <td>ACT-01</td>
        <td>Usuario Registrado (Sist. Información)</td>
    </tr>
    <tr>
        <td>ACT-02</td>
        <td>Usuario No Registrado (Sist. Información)</td>
    </tr>
    <tr>
        <td>ACT-03</td>
        <td><i>Usuario (parte Mapa)</i></td>
    </tr>
        <tr>
        <td>ACT-04</td>
        <td>Gestor (Sist. Información)</td>
    </tr>
        <tr>
        <td>ACT-05</td>
        <td><i>Gestor (parte Mapa)</i></td>
</table>

<br>

### <a name="detalledeloscasosdeusodelportal"></a> Detalle de los casos de uso del Portal

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-01</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver página de información corporativa</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de ver la página del portal dedicada a mostrar información corporativa</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para ver la página de información corporativa<br>
        2.- El sistema muestra la página de información corporativa</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-08, IR-09</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-02</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver página de horarios y servicios</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de ver la página del portal dedicada a mostrar información acerca de horarios y servicios</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para ver la página de horarios y servicios<br>
        2.- El sistema muestra la página de horarios y servicios</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-10, IR-11</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-03</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Acceder al blog</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de acceder a un blog de cuya explotación y mantenimiento se encarga un sistema externo</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para acceder al blog<br>
        2.- El sistema redirige al blog</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br><br></td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-04</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Acceder al foro</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de acceder a un foro de cuya explotación y mantenimiento se encarga un sistema externo</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para acceder al foro<br>
        2.- El sistema redirige al foro</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br><br></td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-05</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver cloud tag</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de ver el cloud tag del portal dedicado a la redirección a otras páginas del mismo</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para ver el cloud tag<br>
        2.- El sistema muestra el cloud tag</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-06</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Plantea la posibilidad de poder buscar información relacionada con las palabras clave introducidas como parámetro de búsqueda en cualquiera de las páginas del portal</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre la barra de búsqueda, introduce una cadena de texto en ella y confirma la realización de una búsqueda en base a las palabras clave introducidas como parámetro clicando sobre un botón situado a la derecha de la barra de búsqueda o presionando la tecla <i>Enter</i>><br>
        2.- El sistema muestra una serie de resultados obtenidos en base a la cadena de texto introducida por el actor los cuales contienen enlaces de redireccionamiento a las secciones de la página donde se encuentra la información buscada según considere el algoritmo de búsqueda</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br><br></td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-07</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Cambiar idioma</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Otorga el poder cambiar el idioma de todo el contenido del portal</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el desplegable contenedor de los diferentes idiomas disponibles para la visualización del portal<br>
        2.- El sistema muestra los idiomas disponibles en forma de opciones seleccionables desde el desplegable<br>
        3.- El usuario clica sobre el idioma deseado para la visualización del portal<br>
        4.- El sistema muestra todo el contenido el portal en el idioma escogido por el actor</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-05, IR-07, IR-09, IR-11, IR-13, IR-15, IR-17, IR-19, IR-21</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-08</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver noticias</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
        <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de ver la página del portal dedicada a mostrar noticias</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para ver las noticias<br>
        2.- El sistema muestra las noticias</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-16, IR-17</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-09</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver página de contacto</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de ver la página del portal dedicada a mostrar información de contacto</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para ver la página de contacto<br>
        2.- El sistema muestra la página de contacto</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-06, IR-07</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-10</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver página de lugares</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de ver la página del portal dedicada a mostrar información acerca de lugares de interés turístico (lugares que albergan eventos, monumentos, ..)</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para ver la página de lugares<br>
        2.- El sistema muestra la página de lugares</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-14, IR-15</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-11</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Recibir aviso</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Permite la recepción de avisos</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El sistema muestra un aviso informativo en una zona determinada de fácil avistamiento para el actor. Dicho aviso estará compuesto por un texto y un botón para el cierre del mismo<br>
        2.- El actor clica sobre el botón destinado al cierre de la notificación poniendo así fin al proceso de recepción de un aviso</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-04, IR-05</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-12</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver página de itinerarios destacados</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de ver la página del portal dedicada a mostrar información acerca de itinearios destacados</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para ver la página de itinerarios destacados<br>
        2.- El sistema muestra la página de itinerarios destacados</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-12, IR-13</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-13</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver página de títulos y tarifas del transporte</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Posibilita la acción de ver la página del portal dedicada a mostrar información acerca de títulos y tarifas del transporte</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para ver la página de títulos y tarifas del transporte<br>
        2.- El sistema muestra la página de títulos y tarifas del transporte</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-18, IR-19</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-14</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver publicidad</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Permite la visualización de publicidad</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El sistema muestra un anuncio publicitario en una zona determinada de fácil avistamiento para el actor (sin obstaculizar su cómoda visualización del contenido de la página en cuestión)</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-20, IR-21</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-15</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Crear página</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Ofrece el medio necesario para la creación de una nueva página (sección dentro del portal) a través de una interfaz a cargo de un software ajeno</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El actor debe haber sido dado de alta y estar autenticado en el sistema</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para crear una nueva sección dentro del portal<br>
        2.- El sistema muestra una interfaz de creación de páginas ajena en la cual hace aparición un botón para la confirmación de la adición de la página modelada al portal<br>
        3.- El actor clica sobre el botón destinado a la confirmación de la adición de una nueva sección en forma de página al portal procediendo a mostrarse, con objeto de permitir al actor previsualizar como resultaría dicho añadido [CU-16], una nueva ventana la cual además cuenta con un botón de confirmación definitiva<br>
        4.- El actor pulsa sobre el botón de confirmación poniendo así fin al proceso de creación de una página</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        El contenido de la página ha sido almacenado en el sistema</td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        CU-16</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-16</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Previsualizar página</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Dispone la posibilidad de previsualizar como resultaría la adición de una nueva página al portal</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El actor debe haber sido dado de alta y estar autenticado en el sistema, así como debe encontrarse en proceso de creación de una nueva sección en forma de página para su adición en el portal</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor, el cual se encuentra en pleno proceso de creación de una página [CU-15], pulsa sobre el botón destinado a la confirmación de la adición de la misma al portal.<br>
        2.- El sistema muestra, con objeto de permitir al actor previsualizar como resultaría dicho añadido, una nueva ventana la cual además cuenta con un botón de confirmación definitiva<br>
        3.- El actor pulsa sobre el botón de confirmación poniendo así fin al proceso de creación de una página</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        El contenido de la página ha sido almacenado en el sistema</td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        CU-15</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-17</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Modificar datos de una página</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Ofrece el medio necesario para la modificación de una página (sección dentro del portal) a través de una interfaz a cargo de un software ajeno</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El actor debe haber sido dado de alta y estar autenticado en el sistema</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para modificar una sección del portal<br>
        2.- El sistema muestra una interfaz de creación de páginas ajena en la cual hace aparición un botón para la confirmación de la adición de la página modificada al portal sustituyendo así a su versión anterior<br>
        3.- El actor clica sobre el botón destinado a la confirmación de la modificación de una sección en forma de página del portal poniendo así fin al proceso de modificación de una página</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        El contenido (ya modificado) de la página ha sido almacenado en el sistema</td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-07, IR-09, IR-11, IR-13, IR-15, IR-17, IR-19</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-18</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Gestionar idiomas</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Permite gestionar los idiomas disponibles para la visualización de los contenidos del portal</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El actor debe haber sido dado de alta y estar autenticado en el sistema</td>
    </tr>
     <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para la adición de un nuevo idioma o la eliminación de uno ya disponible<br>
        2.- El sistema muestra un mensaje para la confirmación de la adición o eliminación de un idioma determinado<br>
        3.- El actor clica sobre el botón en cuestión. Si se trata del proceso de adición, este hecho provocará el envío de una petición a un sistema externo para la inserción de un nuevo idioma como disponible para la visualización del portal. En cualquier caso, desemboca en la finalización del proceso de gestión de idiomas</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-05, IR-07, IR-09, IR-11, IR-13, IR-15, IR-17, IR-19, IR-21</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-19</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Modificar diseño común</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Ofrece el medio necesario para la modificación del diseño común a todas las páginas (secciones dentro del portal) a través de una interfaz a cargo de un software ajeno</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El actor debe haber sido dado de alta y estar autenticado en el sistema</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para modificar el diseño común a todas las páginas del portal<br>
        2.- El sistema muestra una interfaz de creación de páginas ajena en la cual hace aparición un botón para la confirmación de la adición de las páginas con diseño actualizado al portal sustituyendo así a sus versiones anteriores<br>
        3.- El actor clica sobre el botón destinado a la confirmación de la modificación del diseño común a todas las páginas del portal poniendo así fin al proceso</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-07, IR-09, IR-11, IR-13, IR-15, IR-17, IR-19</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-20</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver estadísticas de acceso a una página</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Otorga la posibilidad de poder ver las estadísticas de acceso a una página determinada del portal</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El actor debe haber sido dado de alta y estar autenticado en el sistema</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para ver las estadísticas de acceso a una página<br>
        2.- El sistema muestra una ventana donde se reflejan las diferentes páginas (secciones) presentes en el portal en forma de botones clicables<br>
        3.- El actor clica sobre el botón relativo a aquella página cuyas estadísticas de acceso desea ver<br>
        4.- El sistema muestra una nueva ventana emergente donde dichas estadísticas son presentadas con todo lujo de detalles</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-07, IR-09, IR-11, IR-13, IR-15, IR-17, IR-19</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-21</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Gestionar publicidad</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Permite añadir anuncios publicitarios al portal o eliminarlos del mismo</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El actor debe haber sido dado de alta y estar autenticado en el sistema</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El gestor pulsará sobre el botón para añadir/eliminar publicidad<br>
        2.- Si se trata de añadir, el sistema mostrará una nueva ventana donde se pueden adjuntar atributos relativos a un anuncio publicitario como son un texto, una imagen, los idiomas y la fecha de expiración relacionados con el mismo. Por otro lado, si se trata de un proceso de eliminación, se mostrará también una nueva ventana pero esta será tan solo un mensaje para la cofirmación de la eliminación del anuncio. Tanto si se quiere eliminar como añadir publicidad se incluye la ventana en cuestión un botón de confirmación<br>
        3.- El actor clica sobre el botón de confirmación poniendo así fin al proceso de gestión de publicidad</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        El nuevo anuncio ha sido almacenado en el sistema o uno ya existente ha sido eliminado del mismo</td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-03, IR-20, IR-21</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-22</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Eliminar página</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Ofrece el medio necesario para la eliminación de una página (sección dentro del portal) a través de una interfaz a cargo de un software ajeno</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El actor debe haber sido dado de alta y estar autenticado en el sistema</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El actor pulsa sobre el botón para eliminar una sección del portal<br>
        2.- El sistema muestra una interfaz de creación de páginas ajena en la cual hace aparición un botón para la confirmación de la eliminación de una página del portal en cuestión<br>
        3.- El actor clica sobre el botón destinado a la confirmación de la eliminación de la página deseada poniendo así fin al proceso</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br><br></td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        El contenido de la página ha sido eliminado del sistema</td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        IR-06, IR-07, IR-08, IR-09, IR-10, IR-11, IR-12, IR-13, IR-14, IR-15, IR-16, IR-17, IR-18, IR-19</td>
    </tr>
</table>

<br>

### <a name="detalledeloscasosdeusodelsistemadeinformacion"></a> Detalle de los casos de uso del Sistema de información

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-01</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver actividad de los operadores</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-02</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver foto de estado</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-03</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver película de evolución temporal</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-04</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Gestionar elementos mostrados en el mapa</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-05</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Gestionar línea (visualmente)</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-06</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Gestionar sistemas de ventas y título único del transporte</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-07</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Definir eventos/incidencias</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-08</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Gestionar usuarios</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-09</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Definir variables</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-10</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Definir condiciones</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-11</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Crear aviso acústico</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-12</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Crear aviso visual</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-13</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Crear aviso móvil</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-14</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Crear aviso por correo</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-15</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Adquirir bono</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-16</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Renovar título</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-17</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver histórico de itinerarios</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-18</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Recargar saldo del título</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-19</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Adquirir título</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-20</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Iniciar sesión</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-21</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Registrarse</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario no registrado tendrá una opción para registrarse en el sistema</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-02</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario no debe estar registrado</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsa el botón registrarse.<br>
        2-. El usuario rellenará los campos que se pidan.<br>
        3.- El usuario pulsará continuar.<br>
        4.- El sistema verificará el registro.<br>
        5.- El sistema confirmará el registro.</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        El sistema guardará al nuevo usuario en la base de datos.</td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-22</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver información de lugares/paradas/sitios de interés turístico/ ...</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá ver la información de los lugares, paradas, o sitios de interés turistico</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario eligirá la información que quiera ver.<br>
        2.- El sistema mostrará la información.</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-23</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Reservar itinerario</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá reservar itinerarios</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.-El usuario buscará un itinerario<br>
        2.- El sistema mostrará los itinerarios<br>
        3.- El usuario eligirá uno para reservar</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-24</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Pagar reserva</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        Una vez hecha una reserva el sistema pedirá que se realice el pago</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        Hola</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario deberá haber hecho una reserva de itinerario</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.-El usuario buscará un itinerario<br>
        2.- El sistema mostrará los itinerarios<br>
        3.- El usuario eligirá uno para reservar<br>
        4.1.- El usuario hará el pago para la reserva<br>
        4.1.1.- El sistema confirmará la reserva<br>
        4.2.- El sistema pedirá al usuario iniciar sesión o registrarse<br>
        4.2.1.- El usuario se registrará o iniciará sesión<br>
        4.2.2.- El usuario hará el pago para la reserva<br>
        4.2.3.- El sistema confirmará la reserva</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        El sistema añadirá la reserva en la base de datos</td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-25</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Pedir justificante de pago</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El sistema dará la opción para que el usuario pida un justificante del pago</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario tendrá que haber hecho el pago de una reserva</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.-El usuario buscará un itinerario<br>
        2.- El sistema mostrará los itinerarios<br>
        3.- El usuario eligirá uno para reservar<br>
        4.1.- El usuario hará el pago para la reserva<br>
        4.1.1.- El sistema confirmará la reserva<br>
        4.2.- El sistema pedirá al usuario iniciar sesión o registrarse<br>
        4.2.1.- El usuario se registrará o iniciará sesión<br>
        4.2.2.- El usuario hará el pago para la reserva<br>
        4.2.3.- El sistema confirmará la reserva<br></td></td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        4.1.1.A.- El usuario pedirá el justificante.<br>
        4.1.1.A.1.- El sistema mostrará el pdf con el recibo<br>
        4.2.3.A.- El usuario pedirá el justificante.<br>
        4.2.3.A.1.- El sistema mostrará el pdf con el recibo</td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-26</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Ver recorrido de línea</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá visualizar el recorrido de las líneas de autobúses</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará en el mapa.<br>
        2.- El sistema mostrará en pantalla completa el mapa con los recorridos de las líneas.</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-27</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar paradas</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá hacer una búsqueda de las paradas de las líneas de los autobúses</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará en mostrar paradas.<br>
        2.- El sistema mostrará las paradas.<br>
        3.- El usuario buscará la parada manualmente deslizando o mediante un buscador.<br>
        4.- El usuario pulsará elegir un criterio de búsqueda.</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-28</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar paradas en base a un criterio</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá elegir un criterio para hacer la búsqueda</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario tiene que estar en la pestaña de buscar paradas</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará en mostrar paradas.<br>
        2.- El sistema mostrará las paradas.<br>
        3.- El usuario buscará la parada manualmente deslizando o mediante un buscador.<br>
        4.- El usuario pulsará elegir un criterio de búsqueda.<br>
        5.- El usuario elegirá la opción de elegir un lugar.<br>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-29</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar paradas en función de si pertenecen a un lugar</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El sistema tendrá la opción de buscar paradas por lugares</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario debe pulsar elegir criterio en la pestaña de búsqueda</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará en mostrar paradas.<br>
        2.- El sistema mostrará las paradas.<br>
        3.- El usuario buscará la parada manualmente deslizando o mediante un buscador.<br>
        4.- El usuario pulsará elegir un criterio de búsqueda.<br>
        5.- El usuario elegirá la opción de elegir un lugar.<br>
        6.- El usuario eligirá un lugar.<br>
        7.- El sistema mostrará las paradas que pertenezcan a ese lugar.</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-30</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar paradas en función de si pertenecen a una línea</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usaurio podrá elegir el criterio para ver solo las paradas que pertenezcan a una línea concreta</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario debe pulsar la opción elegir criterio en la pestaña de búsqueda</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará en mostrar paradas.<br>
        2.- El sistema mostrará de las paradas.<br>
        3.- El usuario buscará la parada manualmente deslizando o mediante un buscador.<br>
        4.- El usuario pulsará elegir un criterio de búsqueda.<br>
        5.- El usuario elegirá la opción de elegir una línea.<br>
        6.- El sistema mostrará las líneas<br>
        7.- El usuario eligirá una línea.<br>
        8.- El sistema mostrará las paradas que pertenezcan a esa línea.</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-31</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar paradas en función de si se encuentran cerca del origen/destino</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá elegir el criterio de búscar paradas cerca del lugar de destino o de origen</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario debe pulsar elegir criterio en la pestaña de búsqueda</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará en mostrar paradas.<br>
        2.- El sistema mostrará las paradas.<br>
        3.- El usuario buscará la parada manualmente deslizando o mediante un buscador.<br>
        4.- El usuario pulsará elegir un criterio de búsqueda.<br>
        5.- El usuario elegirá la opción de elegir un lugar.<br>
        6.- El usuario eligirá el lugar de destino/origen.<br>
        7.- El sistema mostrará las paradas que pertenezcan a ese lugar.</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-32</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
    	Introducir identificador de parada</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá introducir el identificador de la parada para buscarla</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario debe estar en la pestaña de buscar parada</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        <tr>
        <td><b>Precondiciones:</b><br>
        El usuario debe pulsar elegir criterio en la pestaña de búsqueda</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usaurio pulsará en mostrar paradas.<br>
        2.- El sistema mostrará las paradas.<br>
        3.- El usuario buscará la parada manualmente deslizando o mediante un buscador.<br>
        4.- El usuario introducirá en el buscador el nombre o el número de la parada.<br>
        5.- El sistema mostrará la parada búscada</td>
    </tr></td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-33</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar itinerarios</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá hacer una búsqueda de itinerarios</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario en cuestión debe encontrarse situado en la ventana del mapa interactivo</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará el botón de buscar itinerarios<br>
        2.- El sistema mostrará los itinerarios</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-34</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Seleccionar origen/destino</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá hacer una búsqueda de los itinerarios seleccionando el origen o destino</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario deberá estar en la pestaña de buscar itinerarios</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará el botón de buscar itinerarios<br>
        2.- El sistema mostrará los itinerarios<br>
        3.- El usuario pulsará en elegir origen o destino<br>
        4.- El usuario introducirá origen o destino o ambos<br>
        5.- El sistema mostrará los itinerarios con esos criterios</td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-35</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar itinerarios en base a un criterio</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá elegir los criterios en base a otros criterios</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario deberá estar en la pestaña de buscar itinerarios</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará el botón de buscar itinerarios<br>
        2.- El sistema mostrará los itinerarios<br>
        </td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        3.A- El usuario pulsará en elegir criterio</td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-36</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar itinerarios en función del coste</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá elegir buscar itinerarios por precio</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario deberá estar en la pestaña de buscar itinerarios</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará el botón de buscar itinerarios<br>
        2.- El sistema mostrará los itinerarios<br>
        </td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        3.A.- El usuario pulsará en elegir criterio<br>
        3.A.1.- El usuario elegirá el criterio de por coste<br>
        3.A.2.- El usuario elegirá el precio<br>
        3.A.3.- El sistema mostrá los itinerarios que se ajusten a ese precio
        </td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-37</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar itinerarios en función del tiempo</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá elegir los itinerarios en función del tiempo que tarden</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario deberá estar en la pestaña de buscar itinerarios</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará el botón de buscar itinerarios<br>
        2.- El sistema mostrará los itinerarios<br>
        </td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        3.A.- El usuario pulsará en elegir criterio<br>
        3.A.1.- El usaurio elegirá el criterio duración<br>
        3.A.2.- El usuario introducirá la duración que desee<br>
        3.A.3.- El sistema mostrará los itinerarios que cumplan ese criterio</td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-38</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Buscar itinerarios en función del número de transbordos</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá elegir un itinerario en función del número de transbordos que tengan</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario deberá estar en la pestaña de buscar itinerarios</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará el botón de buscar itinerarios<br>
        2.- El sistema mostrará los itinerarios<br>
        </td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        3.A.- El usuario pulsará en elegir criterio<br>
        3.A.1.- El usaurio elegirá el criterio número de transbordos<br>
        3.A.2.- El usuario introducirá la cantidad de transbordos que desee<br>
        3.A.3.- El sistema mostrará los itinerarios que cumplan ese criterio</td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-39</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Seleccionar fechas y horas de salida y llegada</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá elegir la fecha/hora de salida y de llegada del itinerario </td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario deberá estar en la pestaña de buscar itinerarios</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará el botón de buscar itinerarios<br>
        2.- El sistema mostrará los itinerarios<br>
        </td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        3.A.- El usuario pulsará en añadir fecha/hora de salida o llegada<br>
        3.A.1.- El usaurio añadirá fecha/hora de salida o fecha/hora de llegada o ambas<br>
        3.A.4.- El sistema mostrará los itinerarios que cumplan ese criterio</td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

<table align = "center">
    <tr>
        <td><b>Identificador:</b><br>
        UC-40</td>
    </tr>
    <tr>
        <td><b>Nombre:</b><br>
        Imprimir esquema del recorrido</td>
    </tr>
    <tr>
        <td><b>Autor:</b><br>
        Manuel Vallecillos Escobosa</td>
    </tr>
    <tr>
        <td><b>Fecha:</b><br>
        20/12/2022</td>
    </tr>
    <tr>
        <td><b>Descripción:</b><br>
        El usuario podrá imprimir el esquema del itinerario que desee</td>
    </tr>
    <tr>
        <td><b>Actores:</b><br>
        ACT-01, ACT-02, ACT-03</td>
    </tr>
    <tr>
        <td><b>Precondiciones:</b><br>
        El usuario deberá estar en la pestaña de buscar itinerarios</td>
    </tr>
    <tr>
        <td><b>Flujo Normal:</b><br>
        1.- El usuario pulsará el botón de buscar itinerarios<br>
        2.- El sistema mostrará los itinerarios<br>
        </td>
    </tr>
    <tr>
        <td><b>Flujo Alternativo:</b><br>
        3.A.- El usuario pulsará en imprimir ruta<br>
        3.A.3.- El sistema mostrará un pdf (que se podrá descargar) con la ruta de ese itinerario</td>
    </tr>
    <tr>
        <td><b>Poscondiciones:</b><br>
        </td>
    </tr>
    <tr>
        <td><b>Referencias:</b><br>
        Hola</td>
    </tr>
</table>

<br>

### <a name="diagramaserydeclasesasociadosalosrequisitosdeinformacion"></a> 4.3. Diagramas E/R y de clases asociados a los requisitos de información

<br>

### <a name="listadediagramaserdelmodelo"></a> Lista de diagramas E/R del modelo

<br>

[- Diagrama E/R general](#diagramaergeneral)<br>
[- Diagrama E/R del Portal](#diagramaerdelportal)<br>
[- Diagrama E/R del Sistema de información](#diagramaerdelsistemadeinformacion)

<br>

### <a name="diagramaserdelmodelo"></a> Diagramas E/R del modelo

<br>

<a name="diagramaergeneral"></a> Diagrama E/R general

<br>

<div align="center"><img src="./out/ER/ER_general.svg"></div>

<br>

<a name="diagramaerdelportal"></a> Diagrama E/R del Portal

<br>

<div align="center"><img src="./out/ER/ER_P.svg"></div>

<br>

<a name="diagramaerdelsistemadeinformacion"></a> Diagrama E/R del Sistema de información

<br>

<div align="center"><img src="./out/ER/ER_SI.svg"></div>

<br>

### <a name="listadediagramasdeclasesdelmodelo"></a> Lista de diagramas de clases del modelo

<br>

[- Diagrama de clases general](#diagramadeclasesgeneral)<br>
[- Diagrama E/R del Portal](#diagramadeclasesdelportal)<br>
[- Diagrama E/R del Sistema de información](#diagramadeclasesdelsistemadeinformacion)

<br>

### <a name="diagramasdeclasesdelmodelo"></a> Diagramas de clases del modelo

<br>

<a name="diagramadeclasesgeneral"></a> Diagrama de clases general

<br>

<div align="center"><img src="./out/DC/DC_general.svg"></div>

<br>

<a name="diagramadeclasesdelportal"></a> Diagrama de clases del Portal

<br>

<div align="center"><img src="./out/DC/DC_P.svg"></div>

<br>

<a name="diagramadeclasesdelsistemadeinformacion"></a> Diagrama de clases del Sistema de información

<br>

<div align="center"><img src="./out/DC/DC_SI.svg"></div>

<br><br>

## <a name="apendices"></a> Apéndices

<br>

[Preguntas entrevista](https://github.com/emg842/INRE-UAL-ROJO-2022/tree/main/proyecto/anexo)

<br>

[Ir al inicio del documento](#iniciodocumento)

<br>
