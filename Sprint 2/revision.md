![logo_caronte_azul](https://github.com/user-attachments/assets/36631133-4715-4b20-91b8-5f07d96795c2)

# Revisión del Software - Entrega

## Sprint 2

## Grupo 9

**Realizado por:**

Rodríguez Reina, Javier 

**Revisado por:**



## 1. Información General
### 1.1. URL del Repositorio de GitHub
- **Repositorio de Github:** [GitHub - Caronte](https://github.com/ISPP-2425-G9)
- **Aplicación Desplegada(Sprint 1):** [Despliegue - Caronte - Sprint 1 ](https://sprint1.caronte.site/home)
- **Aplicación Desplegada(Sprint 2):** [Despliegue - Caronte - Sprint 2 ](https://sprint2.caronte.site/home)
- **Landing Page:** [Landing Page - Caronte](https://www.caronte.site/)
- **Clockify:** [Clockify](https://clockify.me/)
- **Devising a Project - Time Report:** [Devising a Project - Time Report](https://app.clockify.me/shared/67d358fa61753b24b9dc8224)
- **Sprint 1 - Time Report:** [Sprint 1 - Time Report](https://app.clockify.me/shared/67d356c106a063047edb3578)
- **Sprint 2 - Time Report:** [Sprint 2 - Time Report](https://app.clockify.me/shared/67e5b5eaf562c161b72c6dd3)
- **General - Time Report:** [General - Time Report](https://app.clockify.me/shared/67e5b64f492c8e6e4f27af13)
- **Aplicación de despligue:** : [Railway](https://railway.com)

### 1.2. Credenciales de Acceso de Prueba
---
Para evaluar la aplicación, se proporcionan las siguientes credenciales:

- Usuarios Clientes:
    - **Usuario 1:** cliente1@caronte.site / **Contraseña:** customer  
    - **Usuario 2:** cliente2@caronte.site / **Contraseña:** customer

- Usuario Administrador:
    - **Administrador:** admin@caronte.site / **Contraseña:** password

- Usuario Clockify:
    - Por motivos de seguridad y debido al funcionamiento de la plataforma Clockify, no es posible compartir estas credenciales. Si fueran interceptadas, podrían comprometer información sensible. Por esta razón, se ha decidido mantenerlas confidenciales para evitar cualquier riesgo de seguridad.

- Usuario aplicación de despligue:
    - Por motivos de seguridad y debido al funcionamiento de la plataforma Railway, no es posible compartir estas credenciales. Si fueran interceptadas, podrían comprometer información sensible, incluyendo el acceso a la cuenta bancaria personal de uno de los miembros del equipo. Por esta razón, se ha decidido mantenerlas confidenciales para evitar cualquier riesgo de seguridad.


### 1.3. Requisitos para el Uso del Sistema
---
Para garantizar una correcta experiencia de uso, se recomienda:
- Permitir el acceso a **notificaciones** en el navegador para recordatorios de mensajes.

## 2. Mapeo de Casos de Uso Core a Interacciones del Software

### 2.1. Gestión de Usuarios

- **El usuario selecciona su rol al momento de registrarse en la plataforma.**
    - Imagen: Captura de pantalla con la selección de roles.
    - ![Selección de Roles](https://github.com/user-attachments/assets/5d8e15e7-3f85-4b6b-9739-044eadf3c0b7)
    - Interacción con el software: Página previa al registro donde el usuario elige su rol.
    - Sprint: Implementado en el **Sprint 1**. Modificada en el **sprint 2**
    - Estado de implementación: ✅ Implementado.
- **El usuario cliente se registra en el sistema, proporcionando sus credenciales.**
    - Imagen: Captura del formulario de registro para el usuario.
     ![Registro de usuario](https://github.com/user-attachments/assets/40c86cd3-ff7c-4c92-85ec-437abba2efbc)
    - Interacción con el software: Página de registro con validación de datos.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
- **El usuario inicia sesión en la plataforma utilizando sus credenciales previamente registradas.**
    - Imagen: Captura de la pantalla de inicio de sesión.
      ![image](https://github.com/user-attachments/assets/49a50078-1ba1-4862-b94e-c51ff0f3473f)
    - Interacción con el software: Página de login con autenticación.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
- **El usuario edita la información de su perfil, actualizando sus datos personales según sea necesario.**
    - Imagen: Captura de la pantalla de edición de perfil.
    ![image](https://github.com/user-attachments/assets/a996ce58-25eb-4660-8d21-acc1a9a121e7)
    - Interacción con el software: Sección "Mi perfil" con opciones de edición.
    - Sprint: Implementado en el **Sprint 1**. Finalizado en el **Sprint 2**
    - Estado de implementación: ✅ Implementado.
- **El usuario elimina su cuenta, eliminando su perfil del sistema de manera permanente.**
    - Imagen: Captura de la opción de eliminación de cuenta en la configuración de perfil.
      ![image](https://github.com/user-attachments/assets/7cd07e83-10cf-48af-895d-deacc0d4ff59)
    - Interacción con el software: Sección "Mi Perfil" con opción de eliminar cuenta.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
 - **El usuario añade contactos de emergencia para que sean notificados en caso de fallecimiento.**  
    - **Imagen:** Captura de la opción para añadir contactos de emergencia.
      ![image](https://github.com/user-attachments/assets/090b6c4f-627f-4dee-9c63-9fe8a3dd1509)
    - Interacción con el software: Sección "Contactos de emergencia" con opción para gestionar contactos de emergencia.
    - Sprint: Implementado en el **Sprint 2**.  
    - Estado de implementación: ✅ Implementado. 

### 2.2. Gestión de administrador

- **El administrador inicia sesión en el sistema con sus credenciales de acceso.**
    - Imagen: Captura de la pantalla de login del administrador.
      ![image](https://github.com/user-attachments/assets/f46a5978-e473-4a20-a18e-d37a578f7f30)
    - Interacción con el software: Página de login con autenticación.
    - Imagen: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
- **El administrador visualiza y lista todos los clientes registrados en la plataforma.**
    - Imagen: Captura de la vista de listado de usuarios en el panel de administración.
      ![image](https://github.com/user-attachments/assets/a4e9bef5-0650-48ec-97dd-61af108c7e94)
    - Interacción con el software: Sección "Usuarios" en el panel de administración.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
- **El administrador visualiza y lista todos las empresas registradas en la plataforma.**
    - Imagen: Captura de la vista de listado de usuarios en el panel de administración.
      ![image](https://github.com/user-attachments/assets/dcdd5f97-d51e-4edb-809c-3d8294bdebf1)
    - Interacción con el software: Sección "Usuarios" en el panel de administración.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
- **El administrador edita la información de un cliente registrado, modificando sus datos según sea necesario.**
    - Imagen: Captura de la pantalla de edición de usuario en el panel de administración.
      ![image](https://github.com/user-attachments/assets/67c6bb21-5d41-452f-86ce-d07a96e31936)
    - Interacción con el software: Opción "Editar" dentro del panel de administración.
    - Sprint: Implementado en el **Sprint 1**. Finalizado en el **Sprint 2***
    - Estado de implementación: ✅ Implementado.
- **El administrador edita la información de una empresa registrada, modificando sus datos según sea necesario.**
    - Imagen: Captura de la pantalla de edición de usuario en el panel de administración.
      ![image](https://github.com/user-attachments/assets/1a35d105-c613-4056-8d3f-f6f30fb3b0ef)
    - Interacción con el software: Opción "Editar" dentro del panel de administración.
    - Sprint: Implementado en el **Sprint 1**. Finalizado en el **Sprint 2***
    - Estado de implementación: ✅ Implementado.
- **El administrador elimina un perfil de usuario, eliminando su perfil del sistema de manera permanente.**
    - Imagen: Captura de la opción de eliminación de usuario en el panel de administración.
      ![image](https://github.com/user-attachments/assets/62f97139-6bdb-4db9-8474-56a7c3054064)
    - Interacción con el software: Botón "Eliminar" en la vista de gestión de usuarios.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.

### 2.3. Gestión de patrocinadores

- **El usuario cliente lista y visualiza los detalles de cada una de las empresas patrocinadoras.**
    - Imagen: Captura de la pantalla de lista de patrocinadores.
      ![image](https://github.com/user-attachments/assets/4f25b064-9092-4cbd-ae32-4491eeb8d390)
    - Interacción con el software: Sección "Patrocinadores" con detalle de cada empresa.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
- **El usuario empresa registra su información relacionada con los servicios que ofrece, datos de contacto, entre otros.**
    - Imagen: Captura del formulario de registro de empresa patrocinadora.
      ![image](https://github.com/user-attachments/assets/0220eec8-d23a-476f-bc5f-ca79a1be7f49)
    - Interacción con el software: Sección "Registrarse" dentro del área de empresa.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
- **El usuario empresa edita su información sobre los servicios ofrecidos, datos de contacto, etc.**
    - Imagen: Captura de la pantalla de edición de patrocinador.
      ![image](https://github.com/user-attachments/assets/89b32455-3959-4a2d-8484-351b35bf2e5e)
    - Interacción con el software: Sección "Registro de Empresas" en el área de patrocinadores.
    - Sprint: Implementado en el **Sprint 1**. Finalizado en el **Sprint 2**
    - Estado de implementación: ✅ Implementado.
- **El usuario empresa elimina su información sobre los servicios ofrecidos.**
    - Imagen: Captura de la opción de eliminación en la configuración del patrocinador.
      ![image](https://github.com/user-attachments/assets/1336fd2e-df6b-4f05-b10d-d30702bd5915)
    - Interacción con el software: Botón "Eliminar Perfil" en la gestión de patrocinadores.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
- **El usuario empresa visualiza el listado de empresas patrocinadoras disponibles en la plataforma.**
    - Imagen: Captura de la pantalla de lista de patrocinadores en la plataforma.
      ![image](https://github.com/user-attachments/assets/465f1cb4-7e7a-4ed2-9eae-952998348999)
    - Interacción con el software: Página principal de "Servicios".
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.

### 2.4. Gestión de esquelas

- **El usuario cliente lista las esquelas personalizadas creadas en la plataforma.**
    - Imagen: Captura de pantalla de la sección donde se listan las esquelas.
      ![image](https://github.com/user-attachments/assets/a78e4edd-ccc4-4143-aa83-47fb79ac2763)
    - Interacción con el software: Página "Mis Esquelas" donde se muestran las esquelas creadas.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
- **El usuario cliente crea una esquela personalizada, introduciendo los datos requeridos.**
    - Imagen: Captura del formulario de creación de esquelas.
      ![image](https://github.com/user-attachments/assets/3b4cad37-e6cc-4d23-965c-28db0c550959)
    - Interacción con el software: Apartado de las plantillas de las esquelas y le damos a la plantilla que queramos crear.
    - Datos requeridos: Nombre del difunto, fecha de nacimiento, mensaje de despedida, frase de despedida, destinatarios.
    - Sprint: Implementado en el **Sprint 1**. Se finalizará en el **Sprint 3**
    - Estado de implementación: ⏳ Pendiente.
       - Porcentaje completado: 90%. 
- **El usuario cliente edita una esquela personalizada, modificando su contenido según sea necesario.**
    - Imagen: Captura de la pantalla de edición de esquelas.
      ![image](https://github.com/user-attachments/assets/1a762b3b-4f32-44d5-a280-04bda9a0eacb)
    - Interacción con el software: Opción "Editar" en la vista de una esquela existente.
    - Datos requeridos: Nombre del difunto, fecha de nacimiento, mensaje de despedida, frase de despedida, destinatarios.
    - Sprint: Implementado en el **Sprint 1**.  Finalizado en el **Sprint 2**.
    - Estado de implementación:✅ Implementado.
- **El usuario elimina una esquela de su perfil, eliminándola de manera permanente del sistema.**  
    - Imagen: Captura de la opción para eliminar una esquela en la sección de gestión de esquelas.  
      ![image](https://github.com/user-attachments/assets/434136fd-c4b2-46ba-a0ab-933e8735785e)
    - Interacción con el software: Sección "Mis Esquelas" con opción para eliminar esquelas creadas.  
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.


### 2.5. Gestión de mensajes

- **El usuario cliente lista los mensajes personalizados creados en la plataforma.**
    - Imagen: Captura de la sección donde se listan los mensajes.
    - Interacción con el software: Sección "Mis Mensajes" donde se muestra el historial de mensajes creados.
    - Sprint: Previsto para implementar en el **Sprint 2**. Se finalizará en el **Sprint 3**
    - Estado de implementación: ⏳ Pendiente.
         - Porcentaje completado: 70%.
- **El usuario cliente crea un mensaje personalizado, introduciendo el contenido deseado.**
    - Imagen: Captura del formulario de creación de mensajes personalizados.
      ![image](https://github.com/user-attachments/assets/4db88edf-0dbf-4572-991e-30f7f026a8ea)
    - Interacción con el software: Botón "Crear Mensaje" en la sección "Mis Mensajes".
    - Sprint: Previsto para implementar en el **Sprint 2**. Se finalizará en el **Sprint 3**
    - Estado de implementación: ⏳ Pendiente.
        - Porcentaje completado: 80%.
- **El usuario cliente edita un mensaje personalizado, modificando su contenido antes de su envío.**
    - Imagen: Captura de la pantalla de edición de mensajes.
    - Interacción con el software: Opción "Editar" en la vista de un mensaje guardado.
    - Sprint: Previsto para implementar en el **Sprint 2**.  Se finalizará en el **Sprint 3**
    - Estado de implementación: ⏳ Pendiente.
       - Porcentaje completado: 40%.
- **El usuario elimina un mensaje personalizado, eliminándolo de manera permanente del sistema.**
    - Imagen: Captura de la opción para eliminar un mensaje personalizado en la configuración de mensajes.  
      ![Eliminar Mensaje Personalizado](https://github.com/user-attachments/assets/delete-custom-message.png)  
    - Interacción con el software: Sección "Mensajes Personalizados" con opción para eliminar mensajes creados.  
    - Sprint: Implementado en el **Sprint 2**. Se finalizará en el **Sprint 3**
    - Estado de implementación: ⏳ En desarrollo.
        - Porcentaje completado: 80%.


### 2.6. Gestión de fallecimientos

- **En caso de fallecimiento del usuario cliente, una persona con acceso sube el certificado de defunción para validarlo en la plataforma.**
    - Imagen: Captura de la pantalla de subida del certificado.
      ![image](https://github.com/user-attachments/assets/2c65598d-2abe-4b93-8ef9-1470de0874f2)
    - Interacción con el software: Página "Validación de Defunción" donde se sube el documento.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
- **Si un usuario cliente desea realizar una esquela post-mortem, sube el certificado de defunción como requisito previo.**
    - Imagen: Captura de la opción de subida del certificado en la creación de esquelas.
      ![image](https://github.com/user-attachments/assets/68758c24-9fe7-44f9-b4b5-01e17f3bab02)
    - Interacción con el software: Sección "Crear Esquela" con requisito de documento de defunción.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
- **Tras la validación del certificado de defunción, el sistema procesa el envío de esquelas y mensajes previamente configurados por el usuario cliente.**
    - Imagen: Captura del estado de validación de defunción en la plataforma.
    - Interacción con el software: Notificación de aprobación del certificado y activación del envío automático.
    - Sprint: Previsto para implementar en el **Sprint 3**.
    - Estado de implementación: ⏳ Pendiente.
       - Porcentaje completado: 30%.
 - - **El usuario cliente y sus contactos de emergencia reciben una notificación o recordatorio si se detecta la falta de pago del plan pre-mortem.**
    - Imagen: Captura de la alerta enviada a los contactos de emergencia.
    - Interacción con el software: Sistema de notificaciones de la aplicación y envío por correo/SMS.
    - Sprint: Previsto para implementar en el **Sprint 3**.
    - Estado de implementación: ⏳ Pendiente.
      - Porcentaje completado: 20%.

### 2.7. Gestión de planes

- **El usuario cliente lista los planes de precios disponibles en la plataforma.**
    - Imagen: Captura de la página donde se muestran los planes de suscripción.
      ![image](https://github.com/user-attachments/assets/1b7a3bd9-bf13-4c3c-a84c-c4159df9c4a8)
    - Interacción con el software: Sección "Planes" con detalles de precios y beneficios.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
- **El usuario cliente selecciona un plan de precios, de acuerdo con sus necesidades.**
    - Imagen: Captura de la opción de selección de planes.
      ![image](https://github.com/user-attachments/assets/50178c34-f45e-4c28-afd8-32fa29d6993c)
    - Interacción con el software: Página "Planes" con botón de selección.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
- **El usuario cliente introduce sus credenciales para completar el pago.**
    - Imagen: Captura de la pasarela de pago.
      ![image](https://github.com/user-attachments/assets/e50a9797-ead8-4189-bef7-9a932e483d03)
    - Interacción con el software: Integración con Stripe en la sección "Planes".
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
- **Tras realizar un pago exitoso, el usuario cliente recibe un mensaje de confirmación.**
    - Imagen: Ejemplo del recibo de pago generado automáticamente.
      ![image](https://github.com/user-attachments/assets/be3e454c-17e6-43ef-86fe-b21a35d660ec)
    - Interacción con el software: Confirmación de pago en la plataforma y correo de recibo.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.

## 3. Enlace a la Demo en Video
El siguiente enlace redirige a la demostración en video de la aplicación utilizada en la evaluación del Sprint 1:

 **[Creación de esquelas](https://github.com/ISPP-2425-G9/docs/blob/main/Sprint%201/obituaryCreation.mp4)**

Formato: `.mp4`  
Ubicación: Almacenado en el repositorio de GitHub en la carpeta `/Sprint 1`.

## 4. Datos Realistas en la Demo
La demostración del software incluye datos realistas y escenarios de usuario con nombres y contenido verosímil, evitando información ficticia no representativa.

