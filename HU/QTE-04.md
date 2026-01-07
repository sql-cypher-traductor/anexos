<table>
    <tr>
        <td><b>ID: </b>QTE-04</td>
        <td><b>Rol: </b>Desarrollador</td>
    </tr>
    <tr>
        <td colspan=2><b>Título: </b>Traducción de relaciones</td>
    </tr>
    <tr>
        <td><b>Prioridad en negocio: </b>Alta</td>
        <td><b>Riesgo en desarrollo: </b>Alto</td>
    </tr>
    <tr>
        <td><b>Estimación: </b>5</td>
        <td><b>Iteración asignada: </b>Sprint 3</td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Historia de usuario: </b><br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Como</b> desarrollador,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Quiero</b> traducir sentencias SQL para creación, modificación y eliminación de datos a lenguaje Cypher,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Para</b> poder administrar la información contenida en una base de datos orientada a grafos.
        </td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Criterios de aceptación: </b><br>
            <ul>
                <li>El sistema deberá traducir las sentencias INSERT INTO, UPDATE y DELETE.</li>
                <li>El usuario deberá seleccionar la opción “Traducir” para visualizar la sentencia en lenguaje Cypher equivalente a la que ingresó.</li>
                <li>Si la sentencia tiene errores de sintaxis o no es soportada, el sistema indicará un mensaje de error y no podrá ser traducida.</li>
                <li>Las consultas traducidas, serán agregadas automáticamente al historial con la etiqueta TRADUCIDA.</li>
            </ul>
        </td>
    </tr>
</table>