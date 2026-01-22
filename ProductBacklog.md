<table>
    <thead>
        <tr>
            <th>Épica</th>
            <th>ID HU</th>
            <th>Título</th>
            <th>Historia de Usuario</th>
            <th>SP</th>
            <th>Sprint</th>
            <th>ID Tarea</th>
            <th>Tarea</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=22>AUM</td>
            <td rowspan=8>AUM-01</td>
            <td rowspan=8>Registro e Inicio de Sesión</td>
            <td rowspan=8><b>Como</b> usuario,<br><b>Quiero</b> registrarme e iniciar sesión en el sistema,<br><b>Para</b> poder acceder a las funcionalidades del sistema.</td>
            <td rowspan=8>8</td>
            <td rowspan=8>Sprint 1</td>
            <td>T01</td>
            <td>Implementar funcionalidad de registro de usuario.</td>
        </tr>
        <tr>
            <td>T02</td>
            <td>Implementar funcionalidad para inicio de sesión.</td>
        </tr>
        <tr>
            <td>T03</td>
            <td>Implementar validación de campos y credenciales para autenticación.</td>
        </tr>
        <tr>
            <td>T04</td>
            <td>Implementar endpoints para registro e inicio de sesión.</td>
        </tr>
        <tr>
            <td>T05</td>
            <td>Diseñar pantalla de registro de usuario.</td>
        </tr>
        <tr>
            <td>T06</td>
            <td>Desarrollar la pantalla de registro de usuario.</td>
        </tr>
        <tr>
            <td>T07</td>
            <td>Diseñar pantalla de inicio de sesión.</td>
        </tr>
        <tr>
            <td>T08</td>
            <td>Desarrollar la pantalla de inicio de sesión.</td>
        </tr>
        <tr>
            <td rowspan=5>AUM-02</td>
            <td rowspan=5>Actualización del perfil</td>
            <td rowspan=5><b>Como</b> usuario autenticado,<br><b>Quiero</b> modificar mi información personal,<br><b>Para</b> tener actualizados los datos de mi perfil.</td>
            <td rowspan=5>5</td>
            <td rowspan=5>Sprint 4</td>
            <td>T09</td>
            <td>Implementar funcionalidad para actualización de perfil.</td>
        </tr>
        <tr>
            <td>T10</td>
            <td>Implementar validación de campos modificados.</td>
        </tr>
        <tr>
            <td>T11</td>
            <td>Implementar un endpoint para actualizar información.</td>
        </tr>
        <tr>
            <td>T12</td>
            <td>Diseñar pantalla de actualización de perfil.</td>
        </tr>
        <tr>
            <td>T13</td>
            <td>Desarrollar pantalla de actualización de datos.</td>
        </tr>
        <tr>
            <td rowspan=5>AUM-03</td>
            <td rowspan=5>Restablecimiento de contraseña</td>
            <td rowspan=5><b>Como</b> usuario registrado,<br><b>Quiero</b> restablecer mi contraseña,<br><b>Para</b> recuperar el acceso a mi cuenta y a las funciones del sistema.</td>
            <td rowspan=5>5</td>
            <td rowspan=5>Sprint 4</td>
            <td>T14</td>
            <td>Implementar funcionalidad de restablecimiento de contraseña.</td>
        </tr>
        <tr>
            <td>T15</td>
            <td>Implementar validación de email asociado a una cuenta.</td>
        </tr>
        <tr>
            <td>T16</td>
            <td>Implementar validación de formato para nueva contraseña.</td>
        </tr>
        <tr>
            <td>T17</td>
            <td>Diseñar formularios para solicitar correo y restablecer la contraseña.</td>
        </tr>
        <tr>
            <td>T18</td>
            <td>Desarrollar formularios para solicitud de correo y restablecimiento de contraseña.</td>
        </tr>
        <tr>
            <td rowspan=4>AUM-04</td>
            <td rowspan=4>Gestión de usuarios</td>
            <td rowspan=4><b>Como</b> administrador del sistema,<br><b>Quiero</b> administrar la información de los usuarios,<br><b>Para</b> controlar el acceso y uso correcto a la aplicación.</td>
            <td rowspan=4>8</td>
            <td rowspan=4>Sprint 4</td>
            <td>T19</td>
            <td>Implementar la funcionalidad para gestión de usuarios.</td>
        </tr>
        <tr>
            <td>T20</td>
            <td>Implementar los endpoints correspondientes para administración de usuarios.</td>
        </tr>
        <tr>
            <td>T21</td>
            <td>Diseñar pantalla de gestión de usuarios.</td>
        </tr>
        <tr>
            <td>T22</td>
            <td>Desarrollar la pantalla de gestión de usuarios.</td>
        </tr>
        <tr>
            <td rowspan=9>CON</td>
            <td rowspan=5>CON-01</td>
            <td rowspan=5>Configuración de conexiones</td>
            <td rowspan=5><b>Como</b> desarrollador,<br><b>Quiero</b> configurar las conexiones a SQL Server y Neo4j,<br><b>Para</b> poder acceder a las bases de datos SQL existentes, traducir sentencias SQL a Cypher y ejecutarlas en una base de datos en Neo4j.</td>
            <td rowspan=5>8</td>
            <td rowspan=5>Sprint 1</td>
            <td>T23</td>
            <td>Implementar funcionalidad para configurar las conexiones a las bases de datos.</td>
        </tr>
        <tr>
            <td>T24</td>
            <td>Implementar pruebas de conectividad y funciones de conexión y desconexión.</td>
        </tr>
        <tr>
            <td>T25</td>
            <td>Implementar un endpoint para el almacenamiento de una conexión.</td>
        </tr>
        <tr>
            <td>T26</td>
            <td>Diseñar modal para configurar una conexión.</td>
        </tr>
        <tr>
            <td>T27</td>
            <td>Desarrollar modal para configurar una conexión.</td>
        </tr>
        <tr>
            <td rowspan=4>CON-02</td>
            <td rowspan=4>Gestión de conexiones</td>
            <td rowspan=4><b>Como</b> desarrollador,<br><b>Quiero</b> visualizar la lista de conexiones,<br><b>Para</b> poder agregar una nueva conexión o gestionar una conexión guardada.</td>
            <td rowspan=4>5</td>
            <td rowspan=4>Sprint 5</td>
            <td>T28</td>
            <td>Implementar funcionalidad para administración de conexiones.</td>
        </tr>
        <tr>
            <td>T29</td>
            <td>Implementar endpoints para la gestión de conexiones.</td>
        </tr>
        <tr>
            <td>T30</td>
            <td>Diseñar pantalla de gestión de conexiones.</td>
        </tr>
        <tr>
            <td>T31</td>
            <td>Desarrollar pantalla para administrar conexiones.</td>
        </tr>
        <tr>
            <td rowspan=21>QTE</td>
            <td rowspan=5>QTE-01</td>
            <td rowspan=5>Traducción de sentencias SELECT estándar</td>
            <td rowspan=5><b>Como</b> desarrollador,<br><b>Quiero</b> traducir sentencias SELECT a lenguaje Cypher,<br><b>Para</b> aprender a obtener datos específicos de una base de datos orientada a grafos.</td>
            <td rowspan=5>8</td>
            <td rowspan=5>Sprint 2</td>
            <td>T32</td>
            <td>Definir reglas léxicas y sintácticas de la sentencia SELECT, las cláusulas WHERE, ORDER BY, palabras reservadas como FROM, DISTINCT, LIMIT, operadores lógicos y de comparación.</td>
        </tr>
        <tr>
            <td>T33</td>
            <td>Implementar funcionalidad para traducción de consultas SELECT.</td>
        </tr>
        <tr>
            <td>T34</td>
            <td>Implementar un endpoint para la traducción de consultas.</td>
        </tr>
        <tr>
            <td>T35</td>
            <td>Diseñar pantalla de traducción.</td>
        </tr>
        <tr>
            <td>T36</td>
            <td>Desarrollar pantalla de traducción de consultas.</td>
        </tr>
        <tr>
            <td rowspan=2>QTE-02</td>
            <td rowspan=2>Traducción de agrupaciones y agregaciones</td>
            <td rowspan=2><b>Como</b> desarrollador,<br><b>Quiero</b> traducir consultas SQL SELECT que incluya agrupación de datos y funciones de agregación,<br><b>Para</b> conocer la estructura de consultas complejas en lenguaje Cypher.</td>
            <td rowspan=2>8</td>
            <td rowspan=2>Sprint 3</td>
            <td>T37</td>
            <td>Implementar funcionalidad para traducción con agrupaciones y funciones de agregación.</td>
        </tr>
        <tr>
            <td>T38</td>
            <td>Extender gramática para funciones de agregación como COUNT, SUM, MIN, MAX o AVG, cláusulas ORDER BY, HAVING y palabras reservadas como AS.</td>
        </tr>
        <tr>
            <td rowspan=2>QTE-03</td>
            <td rowspan=2>Traducción de relaciones</td>
            <td rowspan=2><b>Como</b> desarrollador,<br><b>Quiero</b> traducir consultas SQL SELECT que involucren relaciones entre tablas,<br><b>Para</b> conocer cómo se construyen relaciones entre nodos en lenguaje Cypher.</td>
            <td rowspan=2>8</td>
            <td rowspan=2>Sprint 3</td>
            <td>T39</td>
            <td>Extender gramática para cláusulas INNER JOIN, LEFT JOIN y RIGHT JOIN y la palabra reservada ON</td>
        </tr>
        <tr>
            <td>T40</td>
            <td>Implementar funcionalidad para traducción de consultas SELECT que incluyan relaciones.</td>
        </tr>
        <tr>
            <td rowspan=2>QTE-04</td>
            <td rowspan=2>Traducción de sentencias CUD</td>
            <td rowspan=2><b>Como</b> desarrollador,<br><b>Quiero</b> traducir sentencias SQL para creación, modificación y eliminación de datos a lenguaje Cypher,<br><b>Para</b> poder administrar la información contenida en una base de datos orientada a grafos.</td>
            <td rowspan=2>5</td>
            <td rowspan=2>Sprint 3</td>
            <td>T41</td>
            <td>Extender gramática para sentencias INSERT INTO, UPDATE y DELETE.</td>
        </tr>
        <tr>
            <td>T42</td>
            <td>Implementar funcionalidad para la traducción de INSERT INTO, UPDATE y DELETE.</td>
        </tr>
        <tr>
            <td rowspan=6>QTE-05</td>
            <td rowspan=6>Ejecución de consultas en Neo4j</td>
            <td rowspan=6><b>Como</b> desarrollador,<br><b>Quiero</b> ejecutar las consultas traducidas en Neo4j,<br><b>Para</b> obtener los resultados rápidamente y visualizarlos en diferentes formatos.</td>
            <td rowspan=6>8</td>
            <td rowspan=6>Sprint 2</td>
            <td>T43</td>
            <td>Implementar funcionalidad para la ejecución de consultas.</td>
        </tr>
        <tr>
            <td>T44</td>
            <td>Implementar funcionalidad para visualización y formato de resultados.</td>
        </tr>
        <tr>
            <td>T45</td>
            <td>Implementar funcionalidad para exportación de resultados en varios formatos.</td>
        </tr>
        <tr>
            <td>T46</td>
            <td>Implementar endpoints para la ejecución de consultas y exportación de resultados.</td>
        </tr>
        <tr>
            <td>T47</td>
            <td>Diseñar panel para resultados de la ejecución.</td>
        </tr>
        <tr>
            <td>T48</td>
            <td>Desarrollar panel para visualización de resultados.</td>
        </tr>
        <tr>
            <td rowspan=4>QTE-06</td>
            <td rowspan=4>Administración del historial de consultas</td>
            <td rowspan=4><b>Como</b> desarrollador,<br><b>Quiero</b> ver un historial de consultas realizadas,<br><b>Para</b> poder utilizarlas nuevamente sin tener que reescribirlas.</td>
            <td rowspan=4>5</td>
            <td rowspan=4>Sprint 5</td>
            <td>T49</td>
            <td>Implementar funcionalidad para gestión de consultas almacenadas.</td>
        </tr>
        <tr>
            <td>T50</td>
            <td>Implementar endpoints para la administración de consultas.</td>
        </tr>
        <tr>
            <td>T51</td>
            <td>Diseñar pantalla de historial de consultas.</td>
        </tr>
        <tr>
            <td>T52</td>
            <td>Desarrollar pantalla de historial de consultas.</td>
        </tr>
        <tr>
            <td rowspan=8>OBS</td>
            <td rowspan=4>OBS-01</td>
            <td rowspan=4>Seguimiento de Logs</td>
            <td rowspan=4><b>Como</b> administrador del sistema,<br><b>Quiero</b> acceder a los logs del sistema,<br><b>Para</b> auditar toda actividad ejecutada y diagnosticar problemas.</td>
            <td rowspan=4>8</td>
            <td rowspan=4>Sprint 5</td>
            <td>T53</td>
            <td>Implementar funcionalidad para almacenamiento de logs.</td>
        </tr>
        <tr>
            <td>T54</td>
            <td>Implementar un endpoint para la obtención de logs.</td>
        </tr>
        <tr>
            <td>T55</td>
            <td>Diseñar pantalla para visualización de logs.</td>
        </tr>
        <tr>
            <td>T56</td>
            <td>Desarrollar pantalla para visualización de logs.</td>
        </tr>
        <tr>
            <td rowspan=4>OBS-02</td>
            <td rowspan=4>Monitoreo de rendimiento</td>
            <td rowspan=4><b>Como</b> administrador del sistema,<br><b>Quiero</b> ver un dashboard de estadísticas globales,<br><b>Para</b> identificar áreas de mejora en el sistema.</td>
            <td rowspan=4>8</td>
            <td rowspan=4>Sprint 6</td>
            <td>T57</td>
            <td>Implementar funcionalidad para la obtención de estadísticas de uso del sistema.</td>
        </tr>
        <tr>
            <td>T58</td>
            <td>Implementar un endpoint para la visualización de estadísticas globales del sistema.</td>
        </tr>
        <tr>
            <td>T59</td>
            <td>Diseñar dashboard de estadísticas generales.</td>
        </tr>
        <tr>
            <td>T60</td>
            <td>Desarrollar dashboard para la visualización de estadísticas generales.</td>
        </tr>
    </tbody>
</table>