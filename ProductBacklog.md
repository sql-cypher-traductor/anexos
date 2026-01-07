<table>
    <thead>
        <tr>
            <th>Épica</th>
            <th>ID</th>
            <th>Título</th>
            <th>Historia de Usuario</th>
            <th>SP</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>AUM</td>
            <td>AUM-01</td>
            <td>Registro e Inicio de Sesión</td>
            <td><b>Como</b> usuario,<br><b>Quiero</b> registrarme e iniciar sesión en el sistema,<br><b>Para</b> poder acceder a las funcionalidades del sistema.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>AUM-02</td>
            <td>Actualización del perfil</td>
            <td><b>Como</b> usuario autenticado,<br><b>Quiero</b> modificar mi información personal,<br><b>Para</b> tener actualizados los datos de mi perfil.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>AUM-03</td>
            <td>Restablecimiento de contraseña</td>
            <td><b>Como</b> usuario registrado,<br><b>Quiero</b> restablecer mi contraseña,<br><b>Para</b> recuperar el acceso a mi cuenta y a las funciones del sistema.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>AUM-04</td>
            <td>Gestión de usuarios</td>
            <td><b>Como</b> administrador,<br><b>Quiero</b> administrar la información de los usuarios,<br><b>Para</b> controlar el acceso y uso correcto a la aplicación.</td>
            <td>8</td>
        </tr>
        <tr>
            <td rowspan=2>CON</td>
            <td>CON-01</td>
            <td>Configuración de conexiones</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> configurar las conexiones a SQL Server y Neo4j,<br><b>Para</b> poder acceder a las bases de datos SQL existentes, traducir sentencias SQL a Cypher y ejecutarlas en una base de datos en Neo4j.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>CON-02</td>
            <td>Gestión de conexiones</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> visualizar la lista de conexiones,<br><b>Para</b> poder agregar una nueva conexión o gestionar una conexión guardada.</td>
            <td>5</td>
        </tr>
        <tr>
            <td rowspan=6>QTE</td>
            <td>QTE-01</td>
            <td>Traducción de sentencias SELECT estándar</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> traducir sentencias SELECT a lenguaje Cypher,<br><b>Para</b> aprender a obtener datos específicos de una base de datos orientada a grafos.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>QTE-02</td>
            <td>Traducción de agrupaciones y agregaciones</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> traducir consultas SQL SELECT que incluya agrupación de datos y funciones de agregación,<br><b>Para</b> conocer la estructura de consultas complejas en lenguaje Cypher.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>QTE-03</td>
            <td>Traducción de relaciones</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> traducir consultas SQL SELECT que involucren relaciones entre tablas,<br><b>Para</b> conocer cómo se construyen relaciones entre nodos en lenguaje Cypher.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>QTE-04</td>
            <td>Traducción de sentencias CUD</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> traducir sentencias SQL para creación, modificación y eliminación de datos a lenguaje Cypher,<br><b>Para</b> poder administrar la información contenida en una base de datos orientada a grafos.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>QTE-05</td>
            <td>Ejecución de consultas en Neo4j</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> ejecutar las consultas traducidas en Neo4j,<br><b>Para</b> obtener los resultados rápidamente y visualizarlos en diferentes formatos.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>QTE-06</td>
            <td>Administración del historial de consultas</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> ver un historial de consultas realizadas,<br><b>Para</b> poder utilizarlas nuevamente sin tener que reescribirlas.</td>
            <td>5</td>
        </tr>
        <tr>
            <td rowspan=2>OBS</td>
            <td>OBS-01</td>
            <td>Seguimiento de Logs</td>
            <td><b>Como</b> administrador,<br><b>Quiero</b> acceder a los logs del sistema,<br><b>Para</b> auditar toda actividad ejecutada y diagnosticar problemas.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>OBS-02</td>
            <td>Monitoreo de rendimiento</td>
            <td><b>Como</b> administrador del sistema,<br><b>Quiero</b> ver un dashboard de estadísticas globales,<br><b>Para</b> identificar áreas de mejora en el sistema.</td>
            <td>8</td>
        </tr>
    </tbody>
</table>