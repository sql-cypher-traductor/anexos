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
            <td rowspan=4>AUTH</td>
            <td>AUTH-01</td>
            <td>Registro de Usuario</td>
            <td><b>Como</b> nuevo usuario,<br><b>Quiero</b> registrarme en el sistema,<br><b>Para</b> poder acceder a las funciones de traducción y ejecución de consultas.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>AUTH-02</td>
            <td>Inicio de Sesión</td>
            <td><b>Como</b> usuario registrado,<br><b>Quiero</b> iniciar sesión,<br><b>Para</b> poder gestionar mi cuenta y utilizar las funcionalidades del sistema.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>AUTH-03</td>
            <td>Cambio de contraseña</td>
            <td><b>Como</b> usuario autenticado,<br><b>Quiero</b> cambiar mi contraseña,<br><b>Para</b> mantener seguros los datos de mi cuenta.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>AUTH-04</td>
            <td>Restablecimiento de contraseña</td>
            <td><b>Como</b> usuario que olvidó su contraseña,<br><b>Quiero</b> restablecer mi contraseña,<br><b>Para</b> recuperar el acceso a mi cuenta y a las funciones del sistema.</td>
            <td>8</td>
        </tr>
        <tr>
            <td rowspan=3>CONN</td>
            <td>CONN-01</td>
            <td>Configuración de conexión SQL Server</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> configurar la conexión a SQL Server,<br><b>Para</b> acceder a las bases de datos existentes.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>CONN-02</td>
            <td>Configuración de conexión Neo4j</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> configurar la conexión a Neo4j,<br><b>Para</b> poder ejecutar las consultas Cypher traducidas en la base de datos respectiva.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>CONN-03</td>
            <td>Gestión y visualización de conexiones</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> visualizar la lista de conexiones,<br><b>Para</b> agregar una nueva conexión o administrar una conexión guardada.</td>
            <td>5</td>
        </tr>
        <tr>
            <td rowspan=6>QTEX</td>
            <td>QTEX-01</td>
            <td>Traducción de operaciones DML básicas</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> traducir sentencias SQL simples a lenguaje Cypher,<br><b>Para</b> interactuar con bases de datos orientadas a grafos sin tener que aprender un nuevo lenguaje de consulta.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>QTEX-02</td>
            <td>Traducción de cláusulas, operadores y funciones</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> traducir consultas que incluyan cláusulas, operadores y funciones,<br><b>Para</b> comprender la estructura de consultas complejas en Cypher.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>QTEX-03</td>
            <td>Traducción de relaciones</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> traducir sentencias SQL que incluyan JOINs,<br><b>Para</b> aprender el manejo de relaciones en Cypher.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>QTEX-04</td>
            <td>Administración del historial de consultas</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> ver un historial de consultas realizadas,<br><b>Para</b> poder utilizarlas nuevamente sin tener que reescribirlas.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>QTEX-05</td>
            <td>Ejecución de consultas en Neo4j</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> ejecutar las consultas traducidas en Neo4j,<br><b>Para</b> obtener los resultados rápidamente.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>QTEX-06</td>
            <td>Visualización de resultados</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> visualizar los resultados en diferentes formatos,<br><b>Para</b> compararlos y utilizarlos como documentación externa.</td>
            <td>8</td>
        </tr>
        <tr>
            <td rowspan=4>OBSF</td>
            <td>OBSF-01</td>
            <td>Manejo de errores y retroalimentación</td>
            <td><b>Como</b> usuario,<br><b>Quiero</b> recibir feedback de errores detectados,<br><b>Para</b> corregirlos o reportarlos de forma rápida.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>OBSF-02</td>
            <td>Gestión de usuarios</td>
            <td><b>Como</b> administrador del sistema,<br><b>Quiero</b> gestionar (actualizar y/o eliminar) la información de los usuarios,<br><b>Para</b> controlar el acceso y uso correcto a la aplicación.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>OBSF-03</td>
            <td>Seguimiento de Logs</td>
            <td><b>Como</b> administrador del sistema,<br><b>Quiero</b> acceder a los logs del sistema,<br><b>Para</b> auditar toda actividad ejecutada y diagnosticar problemas.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>OBSF-04</td>
            <td>Monitoreo de rendimiento de consultas</td>
            <td><b>Como</b> desarrollador,<br><b>Quiero</b> ver métricas de rendimiento de las consultas,<br><b>Para</b> sugerir mejoras en la traducción y ejecución de consultas.</td>
            <td>8</td>
        </tr>
    </tbody>
</table>