<div style="page-break-before: always;"></div>

# Capítulo III: Requirements Specification

## 3.1. User Stories

<table border="1" cellspacing="0" cellpadding="8">
  <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de Aceptación</th>
    <th>Relacionado con (Epic ID)</th>
  </tr>

  <!-- EP001 -->
  <tr>
    <td><strong>EP001</strong></td>
    <td>Informarse sobre el Producto</td>
    <td>Como visitante, deseo explorar la landing page de Bovix para conocer las funcionalidades, beneficios y servicios que ofrece la plataforma para la gestión ganadera.</td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US001</strong></td>
    <td>Explorar Landing Page</td>
    <td>Como visitante, quiero explorar la landing page para conocer las funcionalidades, características y beneficios que ofrece Bovix.</td>
    <td>
      <strong>E01: Visualización de contenido principal</strong><br>
      Dado que el visitante accede a la landing page.<br>
      Cuando navega por las diferentes secciones.<br>
      Entonces el sistema muestra información clara y organizada sobre Bovix.
      <p></p>
      <strong>E02: Navegación responsiva</strong><br>
      Dado que el visitante utiliza distintos dispositivos.<br>
      Cuando accede a la landing page.<br>
      Entonces el contenido se adapta correctamente al tamaño de pantalla.
      <p></p>
      <strong>E03: Navegación entre secciones</strong><br>
      Dado que el visitante interactúa con el menú de navegación.<br>
      Cuando selecciona una sección específica.<br>
      Entonces el sistema desplaza correctamente hacia la sección correspondiente.
    </td>
    <td>EP001 (Informarse sobre el Producto)</td>
  </tr>
    <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de Aceptación</th>
    <th>Relacionado con (Epic ID)</th>
  </tr>

  <tr>
    <td><strong>US002</strong></td>
    <td>Visualización de Funcionalidades y Servicios</td>
    <td>Como visitante, quiero visualizar las funcionalidades y servicios de Bovix para comprender cómo la plataforma puede ayudar en la gestión ganadera.</td>
    <td>
      <strong>E01: Visualización de funcionalidades</strong><br>
      Dado que el visitante accede a la sección de funcionalidades.<br>
      Cuando revisa el contenido disponible.<br>
      Entonces el sistema muestra información detallada sobre los servicios de Bovix.
      <p></p>
      <strong>E02: Información organizada</strong><br>
      Dado que el visitante navega por la sección informativa.<br>
      Cuando consulta las funcionalidades del sistema.<br>
      Entonces el contenido se presenta de manera clara y estructurada.
    </td>
    <td>EP001 (Informarse sobre el Producto)</td>
  </tr>

  <tr>
    <td><strong>US003</strong></td>
    <td>Contacto con Bovix</td>
    <td>Como visitante, quiero acceder a información de contacto para comunicarme con el equipo de Bovix y resolver dudas sobre la plataforma.</td>
    <td>
      <strong>E01: Visualización de información de contacto</strong><br>
      Dado que el visitante accede a la sección de contacto.<br>
      Cuando revisa la información disponible.<br>
      Entonces el sistema muestra medios de comunicación válidos.
      <p></p>
      <strong>E02: Envío de formulario de contacto</strong><br>
      Dado que el visitante completa el formulario de contacto.<br>
      Cuando envía información válida.<br>
      Entonces el sistema confirma correctamente el envío del mensaje.
    </td>
    <td>EP001 (Informarse sobre el Producto)</td>
  </tr>

  <tr>
    <td><strong>TS001</strong></td>
    <td>Desarrollo de Landing Page Responsiva</td>
    <td>Como developer, necesito implementar la landing page responsiva de Bovix para mostrar información del producto y permitir la navegación entre secciones.</td>
    <td>
      <strong>E01: Implementación de estructura visual</strong><br>
      Dado que el desarrollo de la landing page ha iniciado.<br>
      Cuando se implementan las secciones principales.<br>
      Entonces el sistema muestra correctamente el contenido visual del producto.
      <p></p>
      <strong>E02: Adaptación responsive</strong><br>
      Dado que la landing page es visualizada en distintos dispositivos.<br>
      Cuando el usuario accede desde móvil, tablet o desktop.<br>
      Entonces el diseño se adapta correctamente.
      <p></p>
      <strong>E03: Navegación funcional</strong><br>
      Dado que el menú de navegación está implementado.<br>
      Cuando el usuario selecciona una opción.<br>
      Entonces el sistema dirige correctamente a la sección correspondiente.
    </td>
    <td>EP001 (Informarse sobre el Producto)</td>
  </tr>

  <tr>
    <td><strong>TS002</strong></td>
    <td>Desarrollo de Formulario de Contacto</td>
    <td>Como developer, necesito implementar el formulario de contacto para permitir que los visitantes envíen consultas al equipo de Bovix.</td>
    <td>
      <strong>E01: Validación de campos</strong><br>
      Dado que el visitante completa el formulario.<br>
      Cuando omite campos obligatorios.<br>
      Entonces el sistema muestra mensajes de validación.
      <p></p>
      <strong>E02: Envío exitoso</strong><br>
      Dado que el visitante ingresa información válida.<br>
      Cuando envía el formulario.<br>
      Entonces el sistema confirma correctamente el envío del mensaje.
    </td>
    <td>EP001 (Informarse sobre el Producto)</td>
  </tr>

  <!-- EP002 -->
  <tr>
    <td><strong>EP002</strong></td>
    <td>Gestión de Acceso y Autenticación</td>
    <td>Como ganadero, deseo registrarme e iniciar sesión en la plataforma Bovix para acceder de manera segura a las funcionalidades del sistema.</td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US004</strong></td>
    <td>Registro de Usuario</td>
    <td>Como ganadero, quiero crear una cuenta en Bovix para acceder a las funcionalidades de gestión ganadera.</td>
    <td>
      <strong>E01: Registro exitoso</strong><br>
      Dado que el ganadero completa correctamente el formulario de registro.<br>
      Cuando envía la información solicitada.<br>
      Entonces el sistema crea la cuenta correctamente.
      <p></p>
      <strong>E02: Campos obligatorios incompletos</strong><br>
      Dado que el usuario intenta registrarse.<br>
      Cuando omite información obligatoria.<br>
      Entonces el sistema muestra mensajes de validación.
      <p></p>
      <strong>E03: Correo electrónico inválido</strong><br>
      Dado que el usuario ingresa un correo incorrecto.<br>
      Cuando intenta completar el registro.<br>
      Entonces el sistema rechaza la operación y muestra un mensaje de error.
    </td>
    <td>EP002 (Gestión de Acceso y Autenticación)</td>
  </tr>

  <tr>
    <td><strong>US005</strong></td>
    <td>Inicio de Sesión</td>
    <td>Como ganadero, quiero iniciar sesión en la plataforma para acceder a mi información y funcionalidades personalizadas.</td>
    <td>
      <strong>E01: Inicio de sesión exitoso</strong><br>
      Dado que el usuario posee una cuenta registrada.<br>
      Cuando ingresa credenciales válidas.<br>
      Entonces el sistema permite el acceso correctamente.
      <p></p>
      <strong>E02: Credenciales incorrectas</strong><br>
      Dado que el usuario intenta iniciar sesión.<br>
      Cuando ingresa datos inválidos.<br>
      Entonces el sistema muestra un mensaje de error.
      <p></p>
      <strong>E03: Persistencia de sesión</strong><br>
      Dado que el usuario inicia sesión correctamente.<br>
      Cuando navega por la aplicación.<br>
      Entonces el sistema mantiene activa la sesión del usuario.
    </td>
    <td>EP002 (Gestión de Acceso y Autenticación)</td>
  </tr>

  <tr>
    <td><strong>US006</strong></td>
    <td>Cerrar Sesión</td>
    <td>Como ganadero, quiero cerrar sesión de manera segura para proteger la información de mi cuenta.</td>
    <td>
      <strong>E01: Cierre de sesión exitoso</strong><br>
      Dado que el usuario mantiene una sesión activa.<br>
      Cuando selecciona la opción de cerrar sesión.<br>
      Entonces el sistema finaliza correctamente la sesión.
      <p></p>
      <strong>E02: Redirección posterior</strong><br>
      Dado que el usuario cerró sesión correctamente.<br>
      Cuando finaliza el proceso.<br>
      Entonces el sistema redirige a la pantalla principal o login.
    </td>
    <td>EP002 (Gestión de Acceso y Autenticación)</td>
  </tr>

  <tr>
    <td><strong>TS003</strong></td>
    <td>API de Registro de Usuarios</td>
    <td>Como developer, necesito implementar el endpoint de registro para permitir la creación segura de cuentas de usuario.</td>
    <td>
      <strong>E01: Registro exitoso mediante API</strong><br>
      Dado que el endpoint de registro está disponible.<br>
      Cuando se envía información válida.<br>
      Entonces el sistema retorna una respuesta exitosa.
      <p></p>
      <strong>E02: Validación de datos</strong><br>
      Dado que el usuario envía información incompleta o inválida.<br>
      Cuando el sistema procesa la solicitud.<br>
      Entonces el endpoint rechaza la operación y muestra errores de validación.
      <p></p>
      <strong>E03: Seguridad de contraseña</strong><br>
      Dado que el usuario crea una cuenta.<br>
      Cuando la contraseña es almacenada.<br>
      Entonces el sistema aplica hash de seguridad antes de persistirla.
    </td>
    <td>EP002 (Gestión de Acceso y Autenticación)</td>
  </tr>

  <tr>
    <td><strong>TS004</strong></td>
    <td>Sistema de Autenticación JWT</td>
    <td>Como developer, necesito implementar autenticación basada en JWT para gestionar sesiones seguras dentro de Bovix.</td>
    <td>
      <strong>E01: Generación de token</strong><br>
      Dado que el usuario inicia sesión correctamente.<br>
      Cuando el sistema valida las credenciales.<br>
      Entonces se genera un token JWT válido.
      <p></p>
      <strong>E02: Validación de sesión</strong><br>
      Dado que el usuario realiza solicitudes autenticadas.<br>
      Cuando el token JWT es válido.<br>
      Entonces el sistema permite el acceso a los recursos protegidos.
      <p></p>
      <strong>E03: Rechazo de token inválido</strong><br>
      Dado que el usuario utiliza un token inválido o expirado.<br>
      Cuando intenta acceder a recursos protegidos.<br>
      Entonces el sistema rechaza la solicitud.
    </td>
    <td>EP002 (Gestión de Acceso y Autenticación)</td>
  </tr>

  <!-- EP003 -->
  <tr>
    <td><strong>EP003</strong></td>
    <td>Gestión de Ganado</td>
    <td>Como ganadero, deseo registrar y administrar la información de mis animales para mantener un control organizado y actualizado del ganado.</td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US007</strong></td>
    <td>Registro de Ganado</td>
    <td>Como ganadero, quiero registrar nuevos animales para mantener actualizado el inventario de mi ganado.</td>
    <td>
      <strong>E01: Registro exitoso de animal</strong><br>
      Dado que el ganadero accede al formulario de registro.<br>
      Cuando ingresa correctamente los datos del animal.<br>
      Entonces el sistema almacena la información exitosamente.
      <p></p>
      <strong>E02: Validación de campos obligatorios</strong><br>
      Dado que el usuario intenta registrar un animal.<br>
      Cuando omite campos requeridos.<br>
      Entonces el sistema muestra mensajes de validación.
      <p></p>
      <strong>E03: Registro inválido</strong><br>
      Dado que el usuario ingresa datos incorrectos.<br>
      Cuando envía el formulario.<br>
      Entonces el sistema rechaza el registro y muestra un mensaje de error.
    </td>
    <td>EP003 (Gestión de Ganado)</td>
  </tr>

  <tr>
    <td><strong>US008</strong></td>
    <td>Consulta de Información del Ganado</td>
    <td>Como ganadero, quiero consultar la información de mis animales para acceder rápidamente a sus datos registrados.</td>
    <td>
      <strong>E01: Consulta exitosa</strong><br>
      Dado que existen animales registrados.<br>
      Cuando el ganadero realiza una búsqueda válida.<br>
      Entonces el sistema muestra la información correspondiente.
      <p></p>
      <strong>E02: Búsqueda sin resultados</strong><br>
      Dado que el usuario realiza una búsqueda.<br>
      Cuando no existen coincidencias registradas.<br>
      Entonces el sistema informa que no se encontraron resultados.
    </td>
    <td>EP003 (Gestión de Ganado)</td>
  </tr>

  <tr>
    <td><strong>US009</strong></td>
    <td>Actualización de Información del Ganado</td>
    <td>Como ganadero, quiero actualizar la información de mis animales para mantener datos precisos y actualizados dentro del sistema.</td>
    <td>
      <strong>E01: Actualización exitosa</strong><br>
      Dado que el animal existe en el sistema.<br>
      Cuando el usuario modifica correctamente la información.<br>
      Entonces el sistema actualiza los datos exitosamente.
      <p></p>
      <strong>E02: Validación de datos</strong><br>
      Dado que el usuario edita información del animal.<br>
      Cuando ingresa datos inválidos.<br>
      Entonces el sistema rechaza la operación y muestra un mensaje de error.
    </td>
    <td>EP003 (Gestión de Ganado)</td>
  </tr>

  <tr>
    <td><strong>US010</strong></td>
    <td>Gestión de Lotes de Ganado</td>
    <td>Como ganadero, quiero organizar mis animales en lotes para administrar de manera más eficiente mi ganado.</td>
    <td>
      <strong>E01: Creación de lote</strong><br>
      Dado que el usuario accede al módulo de lotes.<br>
      Cuando registra información válida del lote.<br>
      Entonces el sistema crea correctamente el lote.
      <p></p>
      <strong>E02: Asignación de animales</strong><br>
      Dado que existen animales registrados.<br>
      Cuando el usuario asigna animales a un lote.<br>
      Entonces el sistema actualiza correctamente la información del lote.
    </td>
    <td>EP003 (Gestión de Ganado)</td>
  </tr>

  <tr>
    <td><strong>TS005</strong></td>
    <td>Implementación de Endpoint para Registro de Ganado</td>
    <td>Como developer, necesito implementar el endpoint de registro de animales para almacenar la información del ganado dentro de la plataforma.</td>
    <td>
      <strong>E01: Registro exitoso mediante API</strong><br>
      Dado que el endpoint se encuentra disponible.<br>
      Cuando se envían datos válidos del animal.<br>
      Entonces el sistema retorna una respuesta exitosa.
      <p></p>
      <strong>E02: Validación de datos</strong><br>
      Dado que se reciben datos inválidos.<br>
      Cuando el sistema procesa la solicitud.<br>
      Entonces el endpoint rechaza la operación con un mensaje de error.
      <p></p>
      <strong>E03: Persistencia de información</strong><br>
      Dado que el registro es válido.<br>
      Cuando la operación finaliza.<br>
      Entonces el sistema almacena correctamente la información en la base de datos.
    </td>
    <td>EP003 (Gestión de Ganado)</td>
  </tr>

  <tr>
    <td><strong>TS006</strong></td>
    <td>Implementación de Endpoints de Consulta y Edición</td>
    <td>Como developer, necesito implementar endpoints de consulta y actualización para gestionar la información registrada del ganado.</td>
    <td>
      <strong>E01: Consulta de información</strong><br>
      Dado que existen animales registrados.<br>
      Cuando el usuario realiza una solicitud GET válida.<br>
      Entonces el sistema devuelve la información correspondiente.
      <p></p>
      <strong>E02: Actualización de registros</strong><br>
      Dado que el animal existe en el sistema.<br>
      Cuando el usuario envía información válida para editar.<br>
      Entonces el sistema actualiza correctamente los datos.
      <p></p>
      <strong>E03: Manejo de errores</strong><br>
      Dado que se realiza una solicitud inválida.<br>
      Cuando el sistema procesa la operación.<br>
      Entonces el endpoint devuelve mensajes de error apropiados.
    </td>
    <td>EP003 (Gestión de Ganado)</td>
  </tr>

</table>
## 3.2. Impact Mapping

## 3.3. Product Backlog