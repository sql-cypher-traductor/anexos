<table>
    <tr>
        <td><b>ID: </b>QTE-05</td>
        <td><b>Rol: </b>Desarrollador</td>
    </tr>
    <tr>
        <td colspan=2><b>Título: </b>Ejecución de consultas en Neo4j</td>
    </tr>
    <tr>
        <td><b>Prioridad en negocio: </b>Alta</td>
        <td><b>Riesgo en desarrollo: </b>Medio</td>
    </tr>
    <tr>
        <td><b>Estimación: </b>8</td>
        <td><b>Iteración asignada: </b>Sprint 4</td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Historia de usuario: </b><br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Como</b> desarrollador,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Quiero</b> ejecutar las consultas traducidas en Neo4j,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Para</b> obtener los resultados rápidamente.
        </td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Criterios de aceptación: </b><br>
            <ul>
                <li>Si la ejecución de la consulta fue exitosa, se debe mostrar un mensaje de confirmación junto al tiempo de ejecución.</li>
                <li>Para sentencias SELECT se debe indicar el número de registros que encontrados.</li>
                <li>Para sentencias INSERT, UPDATE y DELETE se debe indicará la cantidad de registros alterados (agregados, modificados o eliminados).</li>
                <li>Se debe mostrar mensajes claros de error si se detectan problemas de ejecución.</li>
            </ul>
        </td>
    </tr>
</table>