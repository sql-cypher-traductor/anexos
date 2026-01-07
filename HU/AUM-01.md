<table>
    <tr>
        <td><b>ID: </b>AUM-01</td>
        <td><b>Rol: </b>Usuario</td>
    </tr>
    <tr>
        <td colspan=2><b>Título: </b>Registro e Inicio de Sesión</td>
    </tr>
    <tr>
        <td><b>Prioridad en negocio: </b>Alta</td>
        <td><b>Riesgo en desarrollo: </b>Medio</td>
    </tr>
    <tr>
        <td><b>Estimación: </b>8</td>
        <td><b>Iteración asignada: </b>Sprint 1</td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Historia de usuario: </b><br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Como</b> usuario,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Quiero</b> registrarme e iniciar sesión en el sistema,<br>
            &nbsp;&nbsp;&nbsp;&nbsp;<b>Para</b> poder acceder a las funcionalidades del sistema.
        </td>
    </tr>
    <tr>
        <td colspan=2>
            <b>Criterios de aceptación: </b><br>
            <ul>
                <li>El formulario de registro debe incluir los campos: nombre, apellido, email, contraseña y confirmación de contraseña.</li>
                <li>El usuario debe ingresar datos que cumplan con el formato y restricciones definidos para cada campo obligatorio.</li>
                <li>El usuario no puede crear un perfil con un correo asociado a otro.</li>
                <li>Si el registro es exitoso, el usuario será redireccionado a la pantalla de login.</li>
                <li>El usuario será registrado con el rol “desarrollador” por defecto.</li>
                <li>El formulario de inicio de sesión debe solicitar el correo y la contraseña.</li>
                <li>El usuario debe ingresar las credenciales previamente registradas.</li>
                <li>Si se inicia sesión de forma correcta, el usuario será redireccionado al dashboard principal.</li>
                <li>En caso de inconsistencias con la información ingresada, el sistema mostrará mensajes de error para campos o credenciales inválidas.</li>
            </ul>
        </td>
    </tr>
</table>