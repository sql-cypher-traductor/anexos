<table>
    <tr>
        <td><b>ID: </b>TREX-01</td>
        <td><b>Usuario: </b>Desarrollador</td>
    </tr>
    <tr>
        <td colspan=2><b>Título: </b>Traducción de operaciones DML básicas</td>
    </tr>
    <tr>
        <td><b>Prioridad en negocio: </b>Alta</td>
        <td><b>Riesgo en desarrollo: </b>Alto</td>
    </tr>
    <tr>
        <td><b>Estimación: </b>8</td>
        <td><b>Iteración asignada: </b>Sprint 3</td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Historia de usuario: </b><br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Como</b> desarrollador,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Quiero</b> traducir sentencias SQL simples a lenguaje Cypher,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Para</b> interactuar con bases de datos orientadas a grafos sin tener que aprender un nuevo lenguaje de consulta.
        </td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Criterios de aceptación: </b><br>
            <ul>
                <li>Se debe agregar una sentencia SQL válida.</li>
                <li>Debe soportar las sentencias son: <b>SELECT</b>, <b>INSERT INTO</b>, <b>UPDATE</b> y <b>DELETE</b>.</li>
                <li>El sistema debe permitir el uso de la cláusula WHERE, las palabras reservadas <b>ALL</b>, <b>DISTINCT</b> y los operadores lógicos <b>NOT</b>, <b>AND</b> y <b>OR</b>.</li>
                <li>Al seleccionar la opción Traducir, se debe mostrar la sentencia equivalente en lenguaje Cypher.</li>
                <li>Si la sentencia tiene errores de sintaxis o no es soportada, se debe mostrar un mensaje.</li>
            </ul>
        </td>
    </tr>
</table>
