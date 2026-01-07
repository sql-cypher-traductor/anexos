<table>
    <tr>
        <td><b>ID: </b>QTE-01</td>
        <td><b>Rol: </b>Desarrollador</td>
    </tr>
    <tr>
        <td colspan=2><b>Título: </b>Traducción de sentencias SELECT estándar</td>
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
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Quiero</b> traducir sentencias SELECT a lenguaje Cypher,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Para</b> obtener datos específicos de una base de datos orientada a grafos.
        </td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Criterios de aceptación: </b><br>
            <ul>
                <li>El sistema deberá traducir  la sentencia SELECT para todas las columnas o solo columnas específicas de una tabla.</li>
                <li>El sistema deberá soportar la cláusula WHERE, operadores de comparación (=, <, <= >, >=, <>) y operadores lógicos (AND, OR, NOT).</li>
                <li>El sistema deberá traducir la cláusula ORDER BY junto a la forma de ordenamiento (ASC o DESC).</li>
                <li>El sistema deberá traducir correctamente las palabras reservadas DISTINCT, y LIMIT/TOP.</li>
                <li>El usuario deberá ingresar una sentencia SQL que cumpla con las restricciones indicadas.</li>
                <li>El usuario deberá seleccionar la opción “Traducir” para visualizar la sentencia en lenguaje Cypher equivalente a la que ingresó.</li>
                <li>Si la sentencia tiene errores de sintaxis o no es soportada, el sistema indicará un mensaje de error y no podrá ser traducida.</li>
                <li>Las consultas traducidas, serán agregadas automáticamente al historial con la etiqueta TRADUCIDA.</li>
            </ul>
        </td>
    </tr>
</table>
