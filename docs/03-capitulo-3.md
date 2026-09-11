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
    <td>Como visitante, deseo explorar la landing page de Hatarium para conocer las funcionalidades, beneficios y servicios que ofrece la plataforma para la gestión ganadera.</td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US001</strong></td>
    <td>Explorar Landing Page</td>
    <td>Como visitante, quiero explorar la landing page para conocer las funcionalidades, características y beneficios que ofrece Hatarium.</td>
    <td>
      <strong>E01: Visualización de contenido principal</strong><br>
      Dado que el visitante accede a la landing page.<br>
      Cuando navega por las diferentes secciones.<br>
      Entonces el sistema muestra información clara y organizada sobre Hatarium.
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
    <td>Como visitante, quiero visualizar las funcionalidades y servicios de Hatarium para comprender cómo la plataforma puede ayudar en la gestión ganadera.</td>
    <td>
      <strong>E01: Visualización de funcionalidades</strong><br>
      Dado que el visitante accede a la sección de funcionalidades.<br>
      Cuando revisa el contenido disponible.<br>
      Entonces el sistema muestra información detallada sobre los servicios de Hatarium.
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
    <td>Contacto con Hatarium</td>
    <td>Como visitante, quiero acceder a información de contacto para comunicarme con el equipo de Hatarium y resolver dudas sobre la plataforma.</td>
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
    <td>Como developer, necesito implementar la landing page responsiva de Hatarium para mostrar información del producto y permitir la navegación entre secciones.</td>
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
    <td>Como developer, necesito implementar el formulario de contacto para permitir que los visitantes envíen consultas al equipo de Hatarium.</td>
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
    <td>Como ganadero, deseo registrarme e iniciar sesión en la plataforma Hatarium para acceder de manera segura a las funcionalidades del sistema.</td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US004</strong></td>
    <td>Registro de Usuario</td>
    <td>Como ganadero, quiero crear una cuenta en Hatarium para acceder a las funcionalidades de gestión ganadera.</td>
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
    <td>Como developer, necesito implementar autenticación basada en JWT para gestionar sesiones seguras dentro de Hatarium.</td>
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

  <tr>
    <td><strong>TS007</strong></td>
    <td>Implementación de Gestión de Lotes</td>
    <td>Como developer, necesito implementar funcionalidades para la creación y administración de lotes de ganado.</td>
    <td>
      <strong>E01: Creación de lotes</strong><br>
      Dado que el usuario registra información válida.<br>
      Cuando solicita crear un lote.<br>
      Entonces el sistema almacena correctamente el lote.
      <p></p>
      <strong>E02: Asociación de animales</strong><br>
      Dado que existen animales registrados.<br>
      Cuando el usuario asigna animales a un lote.<br>
      Entonces el sistema actualiza correctamente las relaciones correspondientes.
    </td>
    <td>EP003 (Gestión de Ganado)</td>
  </tr>

  <!-- ======================= EP004 ======================= -->
  <tr>
    <td><strong>EP004</strong></td>
    <td>Gestión de Alimentación y Salud Animal</td>
    <td>Como ganadero, deseo gestionar la alimentación y monitorear la salud de mis animales para mantener un mejor control sanitario y productivo dentro de Hatarium.</td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US011</strong></td>
    <td>Registro de Alimentación</td>
    <td>Como ganadero, quiero registrar la alimentación de mis animales para controlar su consumo y mejorar su productividad.</td>
    <td>
      <strong>E01: Registro exitoso de alimentación</strong><br>
      Dado que el ganadero accede al módulo de alimentación.<br>
      Cuando registra correctamente la información alimentaria.<br>
      Entonces el sistema almacena el registro y confirma la operación.
      <p></p>
      <strong>E02: Datos inválidos</strong><br>
      Dado que el ganadero registra información alimentaria.<br>
      Cuando existen campos vacíos o datos incorrectos.<br>
      Entonces el sistema muestra un mensaje de validación.
    </td>
    <td>EP004 (Gestión de Alimentación y Salud Animal)</td>
  </tr>

  <tr>
    <td><strong>US012</strong></td>
    <td>Monitoreo y Consulta de Historial Sanitario</td>
    <td>Como ganadero, quiero visualizar el estado sanitario e historial de salud de mis animales para supervisar su evolución general y revisar las indicaciones o diagnósticos previos del veterinario.</td>
    <td>
      <strong>E01: Consulta de estado sanitario</strong><br>
      Dado que existen registros médicos o notas preventivas del animal.<br>
      Cuando el ganadero consulta la información sanitaria.<br>
      Entonces el sistema muestra el historial cronológico y el estado de salud actualizado.
      <p></p>
      <strong>E02: Historial no disponible</strong><br>
      Dado que el animal no tiene registros sanitarios asociados.<br>
      Cuando el usuario consulta la información.<br>
      Entonces el sistema informa que no existen datos registrados.
    </td>
    <td>EP004 (Gestión de Alimentación y Salud Animal)</td>
  </tr>

  <tr>
    <td><strong>US013</strong></td>
    <td>Visualización de Vacunas y Controles Preventivos</td>
    <td>Como ganadero, quiero visualizar el calendario y las vacunas aplicadas a mis animales por el médico veterinario para verificar el cumplimiento del plan sanitario.</td>
    <td>
      <strong>E01: Visualización de vacunas aplicadas</strong><br>
      Dado que el médico veterinario ha registrado la aplicación de una vacuna.<br>
      Cuando el ganadero accede al módulo sanitario de Hatarium.<br>
      Entonces el sistema despliega el detalle de la vacuna, fecha de aplicación y lote administrado.
      <p></p>
      <strong>E02: Consulta de próximas vacunaciones</strong><br>
      Dado que existen vacunas programadas en el calendario sanitario.<br>
      Cuando el ganadero revisa el módulo de prevención.<br>
      Entonces el sistema muestra las fechas proyectadas para las siguientes dosis.
    </td>
    <td>EP004 (Gestión de Alimentación y Salud Animal)</td>
  </tr>

  <tr>
    <td><strong>US014</strong></td>
    <td>Procesamiento de Eventos y Alertas Sanitarias</td>
    <td>Como ganadero, quiero que el sistema procese automáticamente las condiciones médicas y plazos preventivos para identificar oportunamente riesgos de salud o vacunaciones pendientes.</td>
    <td>
      <strong>E01: Evaluación automática de eventos sanitarios</strong><br>
      Dado que el backend procesa las reglas de negocio del hato.<br>
      Cuando el sistema detecta de forma interna un riesgo médico latente o evento próximo.<br>
      Entonces el sistema registra y dispara la regla de alerta sanitaria correspondiente.
      <p></p>
      <strong>E02: Procesamiento de vacunación pendiente</strong><br>
      Dado que existe una vacuna próxima a cumplir su plazo de vigencia.<br>
      Cuando el motor del sistema evalúa la fecha programada frente al calendario actual.<br>
      Entonces el sistema marca internamente el evento pendiente para ser visualizado en los paneles de notificación.
    </td>
    <td>EP004 (Gestión de Alimentación y Salud Animal)</td>
  </tr>

  <!-- ======================= EP005 ======================= -->
  <tr>
    <td><strong>EP005</strong></td>
    <td>Reportes y Seguimiento Ganadero</td>
    <td>Como ganadero, deseo visualizar reportes, estadísticas y seguimiento sanitario del ganado para mejorar la toma de decisiones y mantener un mejor control productivo y de salud animal.</td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US015</strong></td>
    <td>Visualización de Reportes Productivos</td>
    <td>Como ganadero, quiero visualizar reportes productivos para analizar el rendimiento y estado general de mi ganado.</td>
    <td>
      <strong>E01: Generación de reportes</strong><br>
      Dado que existen registros productivos almacenados.<br>
      Cuando el ganadero solicita un reporte.<br>
      Entonces el sistema genera información consolidada del ganado.
      <p></p>
      <strong>E02: Reporte sin información disponible</strong><br>
      Dado que el usuario solicita un reporte.<br>
      Cuando no existen registros suficientes.<br>
      Entonces el sistema informa que no es posible generar el reporte.
    </td>
    <td>EP005 (Reportes y Seguimiento Ganadero)</td>
  </tr>

  <tr>
    <td><strong>US016</strong></td>
    <td>Consulta de Historial Sanitario Completo</td>
    <td>Como ganadero, quiero consultar el historial sanitario detallado de mis animales para realizar seguimiento de vacunas, tratamientos anteriores y estado clínico de cada ejemplar.</td>
    <td>
      <strong>E01: Consulta exitosa del historial</strong><br>
      Dado que el animal posee registros sanitarios.<br>
      Cuando el ganadero consulta la información.<br>
      Entonces el sistema muestra el historial actualizado del animal.
      <p></p>
      <strong>E02: Historial no disponible</strong><br>
      Dado que el usuario consulta un animal sin registros.<br>
      Cuando el sistema procesa la solicitud.<br>
      Entonces el sistema informa que no existen datos sanitarios registrados.
    </td>
    <td>EP005 (Reportes y Seguimiento Ganadero)</td>
  </tr>

  <tr>
    <td><strong>US017</strong></td>
    <td>Visualización de Alertas y Estadísticas Sanitarias</td>
    <td>Como ganadero, quiero visualizar alertas y estadísticas sanitarias para identificar riesgos y eventos importantes relacionados con la salud del ganado.</td>
    <td>
      <strong>E01: Visualización de estadísticas sanitarias</strong><br>
      Dado que existen registros sanitarios almacenados.<br>
      Cuando el usuario accede al módulo estadístico.<br>
      Entonces el sistema muestra información consolidada y actualizada.
      <p></p>
      <strong>E02: Generación de alertas sanitarias</strong><br>
      Dado que existe una condición de riesgo o vacunación pendiente.<br>
      Cuando el sistema detecta un evento importante.<br>
      Entonces el sistema genera una alerta para el ganadero.
    </td>
    <td>EP005 (Reportes y Seguimiento Ganadero)</td>
  </tr>

  <!-- ======================= EP006 ======================= -->
  <tr>
    <td><strong>EP006</strong></td>
    <td>APIs y Servicios Backend</td>
    <td>Como developer, deseo implementar APIs REST, servicios backend y mecanismos de persistencia para soportar las funcionalidades principales de la plataforma Hatarium.</td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>TS008</strong></td>
    <td>Implementación de Endpoints para Alimentación y Control Sanitario</td>
    <td>Como developer, necesito implementar endpoints sanitarios y alimentarios para registrar consumos, consultar el historial clínico y permitir la lectura del calendario de vacunas.</td>
    <td>
      <strong>E01: Registro alimentario exitoso</strong><br>
      Dado que el endpoint de alimentación está disponible.<br>
      Cuando se envía información válida.<br>
      Entonces el sistema almacena correctamente el registro.
      <p></p>
      <strong>E02: Consulta de historial sanitario</strong><br>
      Dado que existen registros sanitarios.<br>
      Cuando el usuario consulta el historial del animal.<br>
      Entonces el sistema devuelve la información actualizada.
    </td>
    <td>EP006 (APIs y Servicios Backend)</td>
  </tr>

  <tr>
    <td><strong>TS009</strong></td>
    <td>Implementación de Generación de Reportes y Estadísticas</td>
    <td>Como developer, necesito implementar servicios backend para consolidar reportes productivos y estadísticas sanitarias del ganado.</td>
    <td>
      <strong>E01: Generación de reportes</strong><br>
      Dado que existen registros almacenados.<br>
      Cuando el usuario solicita un reporte.<br>
      Entonces el sistema genera información consolidada correctamente.
      <p></p>
      <strong>E02: Generación de estadísticas sanitarias</strong><br>
      Dado que existen datos sanitarios registrados.<br>
      Cuando el sistema procesa la información.<br>
      Entonces se generan estadísticas actualizadas.
    </td>
    <td>EP006 (APIs y Servicios Backend)</td>
  </tr>

  <!-- ======================= EP007 ======================= -->
  <tr>
    <td><strong>EP007</strong></td>
    <td>Atención Veterinaria Especializada e Integración IoT</td>
    <td>Como Médico Veterinario Especializado, deseo acceder a herramientas avanzadas para registrar visitas técnicas, prescribir tratamientos y monitorear constantes vitales mediante sensores IoT.</td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US018</strong></td>
    <td>Registro de Visita Técnica y Diagnósticos en Campo</td>
    <td>Como médico veterinario, quiero registrar los detalles de mi visita técnica y los diagnósticos clínicos encontrados en el portal web de Hatarium para formalizar la atención médica del animal.</td>
    <td>
      <strong>E01: Registro de visita exitoso</strong><br>
      Dado que el veterinario accede a la plataforma web.<br>
      Cuando completa la evaluación clínica y guarda el diagnóstico con su severidad.<br>
      Entonces el sistema registra la atención médica y actualiza el estado del paciente.
      <p></p>
      <strong>E02: Validación de campos obligatorios</strong><br>
      Dado que se está registrando un diagnóstico clínico.<br>
      Cuando el veterinario no especifica la severidad o la descripción del cuadro clínico.<br>
      Entonces el sistema bloquea la acción y solicita completar la información requerida.
    </td>
    <td>EP007 (Atención Veterinaria Especializada e Integración IoT)</td>
  </tr>

  <tr>
    <td><strong>US019</strong></td>
    <td>Monitoreo con Sensores IoT y Control de Tratamientos Médicos</td>
    <td>Como médico veterinario, quiero prescribir tratamientos y monitorear la telemetría de sensores IoT (temperatura corporal, pulso y nivel de actividad) para evaluar en tiempo real la recuperación del animal.</td>
    <td>
      <strong>E01: Prescripción de tratamiento médico</strong><br>
      Dado que existe un diagnóstico registrado en la plataforma web.<br>
      Cuando el veterinario especifica el medicamento, la dosificación y la duración en días.<br>
      Entonces el sistema anexa la receta al historial médico del animal.
      <p></p>
      <strong>E02: Visualización de lecturas de sensores IoT (Plan Premium)</strong><br>
      Dado que el animal cuenta con un collar de monitoreo IoT vinculado.<br>
      Cuando el veterinario consulta el panel de constantes vitales.<br>
      Entonces el sistema despliega gráficos de temperatura corporal y frecuencia cardíaca en tiempo real.
      <p></p>
      <strong>E03: Alerta por anomalía en signos vitales</strong><br>
      Dado que el sensor IoT registra una temperatura superior a los parámetros normales.<br>
      Cuando la plataforma procesa la lectura de telemetría.<br>
      Entonces genera una alerta crítica en el panel del veterinario y del ganadero.
    </td>
    <td>EP007 (Atención Veterinaria Especializada e Integración IoT)</td>
  </tr>

  <tr>
    <td><strong>TS010</strong></td>
    <td>API REST para Gestión Veterinaria y Telemetría IoT</td>
    <td>Como developer, necesito exponer los endpoints para el registro de visitas médicas, prescripciones y la ingesta de telemetría proveniente de dispositivos IoT.</td>
    <td>
      <strong>E01: Ingesta de datos de sensores IoT</strong><br>
      Dado que un dispositivo collar IoT transmite lecturas de temperatura y pulso.<br>
      Cuando el endpoint de telemetría procesa el paquete de datos.<br>
      Entonces valida los identificadores del sensor y almacena las lecturas en la base de datos.
      <p></p>
      <strong>E02: Validación de seguridad por JWT y Roles</strong><br>
      Dado que se envía una petición para prescribir un tratamiento médico.<br>
      Cuando la API evalúa el token JWT del usuario.<br>
      Entonces permite la operación únicamente si el rol corresponde a VETERINARIO.
    </td>
    <td>EP007 (Atención Veterinaria Especializada e Integración IoT)</td>
  </tr>

</table>
## 3.2. Impact Mapping

## 3.3. Product Backlog