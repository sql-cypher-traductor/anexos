<table>
    <tr>
        <td><b>ID: </b>QTE-02</td>
        <td><b>Rol: </b>Desarrollador</td>
    </tr>
    <tr>
        <td colspan=2><b>Título: </b>Traducción de agrupaciones y agregaciones</td>
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
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Quiero</b> traducir consultas SQL SELECT que incluya agrupación de datos y funciones de agregación,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Para</b> conocer la estructura de consultas complejas en lenguaje Cypher.
        </td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Criterios de aceptación: </b><br>
            <ul>
                <li>El sistema deberá soportar el uso de las cláusulas GROUP BY y HAVING.</li>
                <li>El sistema deberá traducir funciones de agregación: COUNT(), SUM(), AVG(), MIN(), MAX().</li>
                <li>El sistema deberá permitir el uso de AS para traducir el alias dado a un valor calculado.</li>
                <li>El usuario deberá seleccionar la opción “Traducir” para visualizar la sentencia en lenguaje Cypher equivalente a la que ingresó.</li>
                <li>Si la sentencia tiene errores de sintaxis o no es soportada, el sistema indicará un mensaje de error y no podrá ser traducida.</li>
                <li>Las consultas traducidas, serán agregadas automáticamente al historial con la etiqueta TRADUCIDA.</li>
            </ul>
        </td>
    </tr>
</table>