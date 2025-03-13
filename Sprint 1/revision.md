# Revisión del Software - Entrega

## 1. Información General
### 1.1. URL del Repositorio de GitHub
- **Repositorio de Github:** [GitHub - Caronte](https://github.com/ISPP-2425-G9)
- **Despliegue de la Aplicación:** [Despliegue - Caronte](https://sprint1.caronte.site/home)
- **Landing Page:** [Landing Page - Caronte](https://www.caronte.site/)

### 1.2. Credenciales de Acceso de Prueba
---
Para evaluar la aplicación, se proporcionan las siguientes credenciales:

- Usuarios Clientes:
    - **Usuario 1:** user1@caronte.site / **Contraseña:** password
    - **Usuario 2:** user2@caronte.site / **Contraseña:** password

- Usuario Administrador:
    - **Administrador:** admin@caronte.site / **Contraseña:** password

### 1.3. Requisitos para el Uso del Sistema
---
Para garantizar una correcta experiencia de uso, se recomienda:
- Permitir el acceso a **notificaciones** en el navegador para recordatorios de mensajes.

## 2. Mapeo de Casos de Uso Core a Interacciones del Software

### 2.1. Gestión de Usuarios

- **El usuario selecciona su rol al momento de registrarse en la plataforma.**
    - Mockup: Captura de pantalla del formulario de registro con selección de roles.
    ![alt text](image.png)
    - Interacción con el software: Página de registro donde el usuario elige su rol.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario se registra en el sistema, proporcionando sus credenciales.**
    - Mockup: Captura del formulario de registro con campos de usuario y contraseña.
    - Interacción con el software: Página de registro con validación de datos.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario inicia sesión en la plataforma utilizando sus credenciales previamente registradas.**
    - Mockup: Captura de la pantalla de inicio de sesión.
    - Interacción con el software: Página de login con autenticación.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario edita la información de su perfil, actualizando sus datos personales según sea necesario.**
    - Mockup: Captura de la pantalla de edición de perfil.
    - Interacción con el software: Página "Perfil" con opciones de edición.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario elimina su cuenta, eliminando su perfil del sistema de manera permanente.**
    - Mockup: Captura de la opción de eliminación de cuenta en la configuración de perfil.
    - Interacción con el software: Sección "Ajustes" con opción de eliminar cuenta.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado

### 2.2. Gestión de administrador

- **El administrador inicia sesión en el sistema con sus credenciales de acceso.**
    - Mockup: Captura de la pantalla de login del administrador.
    - Interacción con el software: Página de login exclusiva para administradores.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El administrador visualiza y lista todos los usuarios registrados en la plataforma.**
    - Mockup: Captura de la vista de listado de usuarios en el panel de administración.
    - Interacción con el software: Sección "Gestión de Usuarios" en el panel de administración.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El administrador edita la información de un usuario registrado, modificando sus datos según sea necesario.**
    - Mockup: Captura de la pantalla de edición de usuario en el panel de administración.
    - Interacción con el software: Opción "Editar Usuario" dentro del panel de administración.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El administrador elimina un perfil de usuario, eliminando su perfil del sistema de manera permanente.**
    - Mockup: Captura de la opción de eliminación de usuario en el panel de administración.
    - Interacción con el software: Botón "Eliminar Usuario" en la vista de gestión de usuarios.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado

### 2.3. Gestión de patrocinadores

- **El usuario cliente lista y visualiza los detalles de cada una de las empresas patrocinadoras.**
    - Mockup: Captura de la pantalla de lista de patrocinadores.
    - Interacción con el software: Sección "Patrocinadores" con detalle de cada empresa.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario empresa registra su información relacionada con los servicios que ofrece, datos de contacto, entre otros.**
    - Mockup: Captura del formulario de registro de empresa patrocinadora.
    - Interacción con el software: Sección "Editar Información" dentro del área de patrocinadores.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario empresa edita su información sobre los servicios ofrecidos, datos de contacto, etc.**
    - Mockup: Captura de la pantalla de edición de patrocinador.
    - Interacción con el software: Sección "Registro de Empresas" en el área de patrocinadores.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario empresa elimina su información sobre los servicios ofrecidos.**
    - Mockup: Captura de la opción de eliminación en la configuración del patrocinador.
    - Interacción con el software: Botón "Eliminar Perfil" en la gestión de patrocinadores.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario empresa visualiza el listado de empresas patrocinadoras disponibles en la plataforma.**
    - Mockup: Captura de la pantalla de lista de patrocinadores en la plataforma.
    - Interacción con el software: Página principal de "Empresas Patrocinadoras".
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado

### 2.4. Gestión de esquelas

- **El usuario cliente lista las esquelas personalizadas creadas en la plataforma.**
    - Mockup: Captura de pantalla de la sección donde se listan las esquelas.
    - Interacción con el software: Página "Mis Esquelas" donde se muestran las esquelas creadas.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario cliente crea una esquela personalizada, introduciendo los datos requeridos.**
    - Mockup: Captura del formulario de creación de esquelas.
    - Interacción con el software: Botón "Crear Esquela" en la sección "Mis Esquelas".
    - Datos requeridos: Nombre del difunto, mensaje personalizado, fecha de publicación, destinatarios.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado 
- **El usuario cliente edita una esquela personalizada, modificando su contenido según sea necesario.**
    - Mockup: Captura de la pantalla de edición de esquelas.
    - Interacción con el software: Opción "Editar" en la vista de una esquela existente.
    - Sprint: Implementado en el **Sprint 1**
    - Estado de implementación: ✅ Implementado
- **El usuario cliente envía una esquela personalizada, asegurando su entrega a los destinatarios configurados.**
    - Mockup: Captura del botón de envío en la vista de la esquela.
    - Interacción con el software: Botón "Enviar Esquela" en la vista previa de la esquela.
    - Sprint: Previsto para implementar en el **Sprint 3**
    - Estado de implementación: ⏳ Pendiente  
- **El destinatario recibe la esquela por correo electrónico o SMS.**
    - Mockup: Ejemplo de correo/SMS recibido con la esquela.
    - Interacción con el software: Mensaje generado y enviado al destinatario a través del sistema de notificaciones.
    - Sprint: Previsto para implementar en el **Sprint 3**
    - Estado de implementación: ⏳ Pendiente 

### 2.5. Gestión de mensajes

- **El usuario cliente lista los mensajes personalizados creados en la plataforma.**
    - Mockup: Captura de la sección donde se listan los mensajes.
    - Interacción con el software: Sección "Mis Mensajes" donde se muestra el historial de mensajes creados.
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente 
- **El usuario cliente crea un mensaje personalizado, introduciendo el contenido deseado.**
    - Mockup: Captura del formulario de creación de mensajes personalizados.
    - Interacción con el software: Botón "Crear Mensaje" en la sección "Mis Mensajes".
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente 
- **El usuario cliente edita un mensaje personalizado, modificando su contenido antes de su envío.**
    - Mockup: Captura de la pantalla de edición de mensajes.
    - Interacción con el software: Opción "Editar" en la vista de un mensaje guardado.
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente 
- **El usuario cliente envía un mensaje personalizado a los destinatarios configurados.**
    - Mockup: Captura del botón de envío en la vista del mensaje.
    - Interacción con el software: Botón "Enviar Mensaje" dentro de la vista previa del mensaje.
    - Sprint: Previsto para implementar en el **Sprint 3**
    - Estado de implementación: ⏳ Pendiente 
- **El destinatario recibe el mensaje por correo electrónico o SMS.**
    - Mockup: Ejemplo del correo/SMS recibido con el mensaje.
    - Interacción con el software: Notificación automática de entrega.
    - Sprint: Previsto para implementar en el **Sprint 3**
    - Estado de implementación: ⏳ Pendiente 

### 2.6. Gestión de fallecimientos

- **El usuario cliente y sus contactos de emergencia reciben una notificación o recordatorio si se detecta la falta de pago del plan pre-mortem.**
    - Mockup: Captura de la alerta enviada a los contactos de emergencia.
    - Interacción con el software: Sistema de notificaciones de la aplicación y envío por correo/SMS.
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente 
- **En caso de fallecimiento del usuario cliente, uno de sus contactos de emergencia sube el certificado de defunción para validarlo en la plataforma.**
    - Mockup: Captura de la pantalla de subida del certificado.
    - Interacción con el software: Página "Validación de Defunción" donde se sube el documento.
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente 
- **Si un usuario cliente desea realizar una esquela post-mortem, sube el certificado de defunción como requisito previo.**
    - Mockup: Captura de la opción de subida del certificado en la creación de esquelas.
    - Interacción con el software: Sección "Crear Esquela" con requisito de documento de defunción.
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente 
- **Tras la validación del certificado de defunción, el sistema procesa el envío de esquelas o mensajes previamente configurados por el usuario cliente.**
    - Mockup: Captura del estado de validación de defunción en la plataforma.
    - Interacción con el software: Notificación de aprobación del certificado y activación del envío automático.
    - Sprint: Previsto para implementar en el **Sprint 3**
    - Estado de implementación: ⏳ Pendiente

### 2.7. Gestión de planes

- **El usuario cliente lista los planes de precios disponibles en la plataforma.**
    - Mockup: Captura de la página donde se muestran los planes de suscripción.
    - Interacción con el software: Sección "Planes" con detalles de precios y beneficios.
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente
- **El usuario cliente selecciona un plan de precios, de acuerdo con sus necesidades.**
    - Mockup: Captura de la opción de selección de planes.
    - Interacción con el software: Página "Planes" con botón de selección.
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente
- **El usuario cliente elige un método de pago e introduce sus credenciales para completar la transacción.**
    - Mockup: Captura de la pasarela de pago.
    - Interacción con el software: Integración con Stripe/PayPal en la sección "Planes".
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente
- **Tras realizar un pago exitoso, el usuario cliente recibe un justificante de pago como confirmación.**
    - Mockup: Ejemplo del recibo de pago generado automáticamente.
    - Interacción con el software: Confirmación de pago en la plataforma y correo de recibo.
    - Sprint: Previsto para implementar en el **Sprint 2**
    - Estado de implementación: ⏳ Pendiente

## 3. Enlace a la Demo en Video
El siguiente enlace redirige a la demostración en video de la aplicación utilizada en la evaluación del Sprint 1:

 **[Demo de Caronte Sprint 1](URL_DEL_VIDEO_DEMO.mp4)**

Formato: `.mp4`  
Ubicación: Ejemplo: Almacenado en el repositorio de GitHub en la carpeta `/demos`.

## 4. Datos Realistas en la Demo
La demostración del software incluye datos realistas y escenarios de usuario con nombres y contenido verosímil, evitando información ficticia no representativa.

