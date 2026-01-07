<table>
    <tr>
        <td><b>ID: </b>CON-01</td>
        <td><b>Rol: </b>Desarrollador</td>
    </tr>
    <tr>
        <td colspan=2><b>Título: </b>Configuración de conexión SQL Server</td>
    </tr>
    <tr>
        <td><b>Prioridad en negocio: </b>Alta</td>
        <td><b>Riesgo en desarrollo: </b>Medio</td>
    </tr>
    <tr>
        <td><b>Estimación: </b>8</td>
        <td><b>Iteración asignada: </b>Sprint 2</td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Historia de usuario: </b><br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Como</b> desarrollador,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Quiero</b> configurar las conexiones a SQL Server y Neo4j,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Para</b> poder acceder a las bases de datos SQL existentes, traducir sentencias SQL a Cypher y ejecutarlas en una base de datos en Neo4j.
        </td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Criterios de aceptación: </b><br>
            <ul>
                <li>El formulario de conexión a SQL Server deberá solicitar los campos: host, puerto, base de datos, usuario y contraseña.</li>
                <li>Una vez establecida la conexión a la base de datos SQL, el sistema indicará su esquema (tablas, columnas, relaciones y propiedades de cada una).</li>
                <li>El formulario de conexión a Neo4j deberá solicitar los campos: nombre de conexión, URI, base de datos, usuario y contraseña.</li>
                <li>El sistema validará que las credenciales de conexión de SQL Server o Neo4j ingresadas sean correctas mediante la opción "Probar Conexión".</li>
                <li>El sistema permitirá almacenar las conexiones.</li>
                <li>El sistema permitirá opciones para conectarse o desconectarse de las bases de datos.</li>
            </ul>
        </td>
    </tr>
</table>