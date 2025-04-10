![logo_caronte_azul](https://github.com/user-attachments/assets/36631133-4715-4b20-91b8-5f07d96795c2)

# Revisión del Software - Entrega

## Sprint 3

## Grupo 9

**Realizado por:**

Rodríguez Reina, Javier

Solís Padilla, Isaac

**Revisado por:**



## 1. Información General
### 1.1. URL del Repositorio de GitHub
- **Repositorio de Github:** [GitHub - Caronte](https://github.com/ISPP-2425-G9)
- **Aplicación Desplegada(Sprint 1):** [Despliegue - Caronte - Sprint 1 ](https://sprint1.caronte.site/home)
- **Aplicación Desplegada(Sprint 2):** [Despliegue - Caronte - Sprint 2 ](https://sprint2.caronte.site/home)
- **Aplicación Desplegada(Sprint 3):** [Despliegue - Caronte - Sprint 3 ](https://sprint3.caronte.site/home)
- **Landing Page:** [Landing Page - Caronte](https://www.caronte.site/)
- **Clockify:** [Clockify](https://clockify.me/)
- **Devising a Project - Time Report:** [Devising a Project - Time Report](https://app.clockify.me/shared/67d358fa61753b24b9dc8224)
- **Sprint 1 - Time Report:** [Sprint 1 - Time Report](https://app.clockify.me/shared/67d356c106a063047edb3578)
- **Sprint 2 - Time Report:** [Sprint 2 - Time Report](https://app.clockify.me/shared/67e5b5eaf562c161b72c6dd3)
- **General - Time Report:** [General - Time Report](https://app.clockify.me/shared/67e5b64f492c8e6e4f27af13)
- **Aplicación de despligue:** [Railway](https://railway.com)

### 1.2. Credenciales de Acceso de Prueba
---
Para evaluar la aplicación, se proporcionan las siguientes credenciales:

- Usuarios Cliente:
    - **Cliente 1:** pedro@caronte.site / **Contraseña:** customer  
    - **Cliente 2:** jose@caronte.site / **Contraseña:** cliente
    
- Usuarios Empresa:
    - **Empresa 1:** florapalace@caronte.site / **Contraseña:** empresa  
    - **Empresa 2:** memora@caronte.site / **Contraseña:** empresa

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
      ![image](https://github.com/user-attachments/assets/aed5c40c-0d7f-431a-8c80-2b49b8a24323)
    - Interacción con el software: Página previa al registro donde el usuario elige su rol.
    - Sprint: Implementado en el **Sprint 1**. Modificada en el **sprint 2**
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente se registra en el sistema, proporcionando sus credenciales.**
    - Imagen: Captura del formulario de registro para el usuario.
     ![image](https://github.com/user-attachments/assets/11fa5db9-86e2-41da-a77c-46e792f57f81)
    - Interacción con el software: Página de registro con validación de datos.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente inicia sesión en la plataforma utilizando sus credenciales previamente registradas.**
    - Imagen: Captura de la pantalla de inicio de sesión.
      ![image](https://github.com/user-attachments/assets/040bf973-42d2-436b-95a7-ecda9d95c83c)
    - Interacción con el software: Página de login con autenticación.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente edita la información de su perfil, actualizando sus datos personales según sea necesario.**
    - Imagen: Captura de la pantalla de edición de perfil.
    ![image](https://github.com/user-attachments/assets/fdb30d73-9d3f-4690-9af9-390e1afc464c)
    - Interacción con el software: Sección "Mi perfil" con opciones de edición.
    - Sprint: Implementado en el **Sprint 1**. Finalizado en el **Sprint 2**
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente elimina su cuenta, eliminando su perfil del sistema de manera permanente.**
    - Imagen: Captura de la opción de eliminación de cuenta en la configuración de perfil.
      ![image](https://github.com/user-attachments/assets/33c5a6f2-ab9c-49c8-af52-8fc6aa420f05)
    - Interacción con el software: Sección "Mi Perfil" con opción de eliminar cuenta.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado. 

### 2.2. Gestión de administrador

- **El administrador inicia sesión en el sistema con sus credenciales de acceso.**
    - Imagen: Captura de la pantalla de login del administrador.
      ![image](https://github.com/user-attachments/assets/040bf973-42d2-436b-95a7-ecda9d95c83c)
    - Interacción con el software: Página de login con autenticación.
    - Imagen: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
      
- **El administrador visualiza y lista todos los clientes registrados en la plataforma.**
    - Imagen: Captura de la vista de listado de usuarios en el panel de administración.
      ![image](https://github.com/user-attachments/assets/d3b36a2b-0d14-471a-a1b4-9c30af4c8e93)
    - Interacción con el software: Sección "Usuarios" en el panel de administración.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
      
- **El administrador visualiza y lista todos las empresas registradas en la plataforma.**
    - Imagen: Captura de la vista de listado de usuarios en el panel de administración.
      ![image](https://github.com/user-attachments/assets/0941eaa9-0034-4c98-afee-db6c2f0e84c1)
    - Interacción con el software: Sección "Usuarios" en el panel de administración.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
      
- **El administrador edita la información de un cliente registrado, modificando sus datos según sea necesario.**
    - Imagen: Captura de la pantalla de edición de usuario en el panel de administración.
      ![image](https://github.com/user-attachments/assets/a42202c6-2025-416e-bd60-1f208631607b)
    - Interacción con el software: Opción "Editar" dentro del panel de administración.
    - Sprint: Implementado en el **Sprint 1**. Finalizado en el **Sprint 2***
    - Estado de implementación: ✅ Implementado.
      
- **El administrador edita la información de una empresa registrada, modificando sus datos según sea necesario.**
    - Imagen: Captura de la pantalla de edición de usuario en el panel de administración.
      ![image](https://github.com/user-attachments/assets/bfcee32d-4ae2-4c69-bef6-b136ec599eac)
    - Interacción con el software: Opción "Editar" dentro del panel de administración.
    - Sprint: Implementado en el **Sprint 1**. Finalizado en el **Sprint 2***
    - Estado de implementación: ✅ Implementado.
      
- **El administrador elimina un perfil de usuario, eliminando su perfil del sistema de manera permanente.**
    - Imagen: Captura de la opción de eliminación de usuario en el panel de administración.
      ![image](https://github.com/user-attachments/assets/ba22c5e2-41f5-421f-80b2-cd71ef51d85c)
    - Interacción con el software: Botón "Eliminar" en la vista de gestión de usuarios.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.

- **El administrador lista todos los certificados en el sistema.**  
    - Imagen: Captura de la opción de listado de certificados en el panel de administración.  
      ![image](https://github.com/user-attachments/assets/0a5dd5b7-dfc5-4a45-9dce-9ffd76f5251f)  
    - Interacción con el software: Vista de listado de certificados en la gestión administrativa.  
    - Sprint: Implementado en el **Sprint 3**.  
    - Estado de implementación: ✅ Implementado.  

- **El administrador visualiza los detalles de un certificado específico.**  
    - Imagen: Captura de la vista de detalle de un certificado.  
      ![image](https://github.com/user-attachments/assets/8119ed35-f6bf-4dcd-8ac3-4e2645a69319)  
    - Interacción con el software: Página de detalles del certificado dentro del sistema.  
    - Sprint: Implementado en el **Sprint 3**.  
    - Estado de implementación: ✅ Implementado.  

- **El administrador revisa las esquelas y mensajes vinculados a un certificado.**  
    - Imagen: Captura de la lista de esquelas y mensajes asociados.  
      ![image](https://github.com/user-attachments/assets/137efd66-bf10-44ee-a711-5fc64c050545)  
      ![image](https://github.com/user-attachments/assets/dc67cc2c-48eb-49f4-b43e-d1c03e96d8b5)  
    - Interacción con el software: Vista de esquelas y mensajes dentro del detalle del certificado.  
    - Sprint: Implementado en el **Sprint 3**.  
    - Estado de implementación: ✅ Implementado.   

- **El administrador acepta un certificado tras su revisión.**  
    - Imagen: Captura de la opción de aprobación de un certificado.  
      ![image](https://github.com/user-attachments/assets/3b21bd0c-6956-40ef-b0ce-060daeb2f0b6)  
    - Interacción con el software: Botón "Aceptar" en la vista de detalle del certificado.  
    - Sprint: Implementado en el **Sprint 3**.  
    - Estado de implementación: ✅ Implementado.  

- **El administrador deniega un certificado tras su revisión.**  
    - Imagen: Captura de la opción de denegación de un certificado.  
      ![image](https://github.com/user-attachments/assets/af2e53cb-af2e-49d6-ba53-1d35b4661fde)  
    - Interacción con el software: Botón "Denegar" en la vista de detalle del certificado.  
    - Sprint: Implementado en el **Sprint 3**.  
    - Estado de implementación: ✅ Implementado.  


### 2.3. Gestión de patrocinadores

- **El usuario cliente lista y visualiza los detalles de cada una de las empresas patrocinadoras.**
    - Imagen: Captura de la pantalla de lista de patrocinadores.
     ![image](https://github.com/user-attachments/assets/782a9b83-885a-42ec-aa2e-d9c331baa061)
    - Interacción con el software: Sección "Patrocinadores" con detalle de cada empresa.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
      
- **El usuario empresa registra su información relacionada con los servicios que ofrece, datos de contacto, entre otros.**
    - Imagen: Captura del formulario de registro de empresa patrocinadora.
      ![image](https://github.com/user-attachments/assets/dc56c440-729b-49f9-877c-02fbfe0ae88b)
    - Interacción con el software: Sección "Registrarse" dentro del área de empresa.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
      
- **El usuario empresa edita su información sobre los servicios ofrecidos, datos de contacto, etc.**
    - Imagen: Captura de la pantalla de edición de patrocinador.
      ![image](https://github.com/user-attachments/assets/38db5f78-d0fb-462d-b87e-d07657ecebfe)
    - Interacción con el software: Sección "Registro de Empresas" en el área de patrocinadores.
    - Sprint: Implementado en el **Sprint 1**. Finalizado en el **Sprint 2**
    - Estado de implementación: ✅ Implementado.
      
- **El usuario empresa elimina su información sobre los servicios ofrecidos.**
    - Imagen: Captura de la opción de eliminación en la configuración del patrocinador.
      ![image](https://github.com/user-attachments/assets/020faf8c-a751-4f91-ad06-95adc7431e15)
    - Interacción con el software: Botón "Eliminar Perfil" en la gestión de patrocinadores.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
      
- **El usuario empresa visualiza el listado de empresas patrocinadoras disponibles en la plataforma.**
    - Imagen: Captura de la pantalla de lista de patrocinadores en la plataforma.
      ![image](https://github.com/user-attachments/assets/0fc7082d-af86-40c2-927c-652fd72fd392)
    - Interacción con el software: Página principal de "Servicios".
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.

### 2.4. Gestión de esquelas

- **El usuario cliente lista las esquelas personalizadas creadas en la plataforma.**
    - Imagen: Captura de pantalla de la sección donde se listan las esquelas.
     ![image](https://github.com/user-attachments/assets/b9f58eba-8475-4bed-8a4c-353f9c19930e)
    - Interacción con el software: Página "Mis Esquelas" donde se muestran las esquelas creadas.
    - Sprint: Implementado en el **Sprint 1**.
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente crea una esquela personalizada, introduciendo los datos requeridos.**
    - Imagen: Captura del formulario de creación de esquelas.
      ![image](https://github.com/user-attachments/assets/44cee9bc-e7b0-4a50-af7c-62bd1a3d3938)
    - Interacción con el software: Apartado de las plantillas de las esquelas y le damos a la plantilla que queramos crear.
    - Datos requeridos: Nombre del difunto, fecha de nacimiento, mensaje de despedida, frase de despedida, destinatarios.
    - Sprint: Implementado en el **Sprint 1**. Finalizado en el **Sprint 3**
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente edita una esquela personalizada, modificando su contenido según sea necesario.**
    - Imagen: Captura de la pantalla de edición de esquelas.
      ![image](https://github.com/user-attachments/assets/aaabe7be-823c-40f7-9a47-ff3017c48a2e)
    - Interacción con el software: Opción "Editar" en la vista de una esquela existente.
    - Datos requeridos: Nombre del difunto, fecha de nacimiento, mensaje de despedida, frase de despedida, destinatarios.
    - Sprint: Implementado en el **Sprint 1**.  Finalizado en el **Sprint 2**.
    - Estado de implementación:✅ Implementado.
      
- **El usuario elimina una esquela de su perfil, eliminándola de manera permanente del sistema.**  
    - Imagen: Captura de la opción para eliminar una esquela en la sección de gestión de esquelas.  
     ![image](https://github.com/user-attachments/assets/368cbf27-3303-432b-8f5c-84c3cc9b163d)
    - Interacción con el software: Sección "Mis Esquelas" con opción para eliminar esquelas creadas.  
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.


### 2.5. Gestión de mensajes

- **El usuario cliente lista los mensajes personalizados creados en la plataforma.**
    - Imagen: Captura de la sección donde se listan los mensajes.
      ![image](https://github.com/user-attachments/assets/c35cdd15-d908-4ff8-bc60-cdc3bc2a9a5b)
    - Interacción con el software: Sección "Mis Mensajes" donde se muestra el historial de mensajes creados.
    - Sprint: Implementado en el **Sprint 2**. Finalizado en el **Sprint 3**
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente crea un mensaje personalizado, introduciendo el contenido deseado.**
    - Imagen: Captura del formulario de creación de mensajes personalizados.
      ![image](https://github.com/user-attachments/assets/09a4ed21-3c10-4435-b314-b76d1d871db5)
    - Interacción con el software: Botón "Crear Mensaje" en la sección "Mis Mensajes".
    - Sprint: Implementado en el **Sprint 2**. Finalizado en el **Sprint 3**
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente edita un mensaje personalizado, modificando su contenido antes de su envío.**
    - Imagen: Captura de la pantalla de edición de mensajes.
      ![image](https://github.com/user-attachments/assets/88c89c86-fe55-4089-8984-85873eddd0d9)
    - Interacción con el software: Opción "Editar" en la vista de un mensaje guardado.
    - Sprint: Implementado en el **Sprint 2**. Finalizado en el **Sprint 3**
    - Estado de implementación: ✅ Implementado.
      
- **El usuario elimina un mensaje personalizado, eliminándolo de manera permanente del sistema.**
    - Imagen: Captura de la opción para eliminar un mensaje personalizado en la configuración de mensajes.
      ![image](https://github.com/user-attachments/assets/23238a9c-8857-4377-ae51-5fe3f562c377)
    - Interacción con el software: Sección "Mensajes Personalizados" con opción para eliminar mensajes creados.  
    - Sprint: Implementado en el **Sprint 2**. Finalizado en el **Sprint 3**
    - Estado de implementación: ✅ Implementado.
 
### 2.6. Gestión de contactos de emergencia  

- **El usuario cliente añade contactos de emergencia para que sean notificados en caso de fallecimiento.**  
  - **Imagen:** Captura de la opción para añadir contactos de emergencia.  
    ![image](https://github.com/user-attachments/assets/84082bf6-a27c-4878-84e0-4c031d66c16e)
  - **Interacción con el software:** Sección "Contactos de emergencia" con opción para gestionar contactos de emergencia.  
  - **Sprint:** Implementado en el **Sprint 2**.  
  - **Estado de implementación:** ✅ Implementado.  

- **El usuario cliente edita un contacto de emergencia previamente añadido.**  
  - **Imagen:** Captura de la opción de edición de contactos de emergencia.  
    ![image](https://github.com/user-attachments/assets/f8d8482e-2ae2-466c-9bad-80bb52784d96)
  - **Interacción con el software:** Página "Contactos de emergencia" con botón de edición disponible.  
  - **Sprint:** Implementado en el **Sprint 2**.  
  - **Estado de implementación:** ✅ Implementado.  

- **El usuario cliente elimina un contacto de emergencia si ya no lo considera necesario.**  
  - **Imagen:** Captura de la opción de eliminación de contactos de emergencia.  
    ![image](https://github.com/user-attachments/assets/94ad18b2-7966-4200-a294-2b590136323e)
  - **Interacción con el software:** Sección "Contactos de emergencia" con botón de eliminación.  
  - **Sprint:** Implementado en el **Sprint 2**.  
  - **Estado de implementación:** ✅ Implementado. 


### 2.7. Gestión de fallecimientos

- **En caso de fallecimiento del usuario cliente, una persona con acceso sube el certificado de defunción para validarlo en la plataforma.**
    - Imagen: Captura de la pantalla de subida del certificado.
      ![image](https://github.com/user-attachments/assets/e4dd1da4-9e02-488c-91c0-fb020e8c4dc6)
    - Interacción con el software: Página "Validación de Defunción" donde se sube el documento.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
      
- **Si un usuario cliente desea realizar una esquela post-mortem, sube el certificado de defunción como requisito previo.**
    - Imagen: Captura de la opción de subida del certificado en la creación de esquelas.
      ![image](https://github.com/user-attachments/assets/ee8d60c7-5755-49f2-bb4a-eee513342973)
    - Interacción con el software: Sección "Crear Esquela" con requisito de documento de defunción.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
      
- **Tras la validación del certificado de defunción, el sistema procesa el envío de esquelas y mensajes previamente configurados por el usuario cliente.**
    - Imagen: Captura del estado de validación de defunción en la plataforma.
      ![image](https://github.com/user-attachments/assets/0060c08c-9500-4b85-b85b-01aec15b6715)
    - Interacción con el software: Notificación de aprobación del certificado y activación del envío automático.
    - Sprint: Implementado en el **Sprint 3**.
    - Estado de implementación: ✅ Implementado.
      
 - - **El usuario cliente y sus contactos de emergencia reciben una notificación o recordatorio si se detecta la falta de pago del plan pre-mortem.**
    - Imagen: Captura de la alerta enviada a los contactos de emergencia.
    - Interacción con el software: Sistema de notificaciones de la aplicación y envío por correo/SMS.
    - Sprint: Previsto para implementar en el **Sprint 4**.
    - Estado de implementación: ⏳ Pendiente.
      - Porcentaje completado: 50%.

### 2.8. Gestión de planes

- **El usuario cliente lista los planes de precios disponibles en la plataforma.**
    - Imagen: Captura de la página donde se muestran los planes de suscripción.
      ![image](https://github.com/user-attachments/assets/9173f7d3-91b5-42cc-8ec1-29ea29add8d6)
    - Interacción con el software: Sección "Planes" con detalles de precios y beneficios.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente selecciona un plan de precios, de acuerdo con sus necesidades.**
    - Imagen: Captura de la opción de selección de planes.
      ![image](https://github.com/user-attachments/assets/2cc089db-cc02-409a-ac45-c5f23a74ca7f)
    - Interacción con el software: Página "Planes" con botón de selección.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
      
- **El usuario cliente introduce sus credenciales para completar el pago.**
    - Imagen: Captura de la pasarela de pago.
      ![image](https://github.com/user-attachments/assets/b64c1bb2-e0cf-4ea5-814a-69d43619646b)
    - Interacción con el software: Integración con Stripe en la sección "Planes".
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
      
- **Tras realizar un pago exitoso, el usuario cliente recibe un mensaje de confirmación.**
    - Imagen: Ejemplo del recibo de pago generado automáticamente.
      ![image](https://github.com/user-attachments/assets/3af15abb-27b3-41f9-9235-508fe96a37aa)
    - Interacción con el software: Confirmación de pago en la plataforma y correo de recibo.
    - Sprint: Implementado en el **Sprint 2**.
    - Estado de implementación: ✅ Implementado.
 
### 2.9. Gestión de Últimos Deseos  

- **El usuario cliente crea un último deseo en la plataforma.**  
  - **Interacción con el software:** Sección "Últimos Deseos" con formulario para ingresar detalles del deseo.  
  - **Sprint:** Planificado para el **Sprint 4**.  
  - **Estado de implementación:** ⏳ Pendiente (0%).  

- **El usuario cliente edita un último deseo previamente creado.**   
  - **Interacción con el software:** Página "Últimos Deseos" con botón de edición disponible.  
  - **Sprint:** Planificado para el **Sprint 4**.  
  - **Estado de implementación:** ⏳ Pendiente (0%).  

- **El usuario cliente elimina un último deseo si ya no lo considera necesario.**  
  - **Interacción con el software:** Sección "Últimos Deseos" con botón de eliminación.  
  - **Sprint:** Planificado para el **Sprint 4**.  
  - **Estado de implementación:** ⏳ Pendiente (0%).  

- **El usuario cliente visualiza la lista de sus últimos deseos guardados.**  
  - **Interacción con el software:** Sección "Últimos Deseos" con listado de deseos creados.  
  - **Sprint:** Planificado para el **Sprint 4**.  
  - **Estado de implementación:** ⏳ Pendiente (0%). 

## 3. Enlace a la Demo en Vídeo
El siguiente enlace redirige a la demostración en video de la aplicación utilizada en la evaluación del Sprint 3:

 **[Demostración funcional de la aplicación](https://github.com/ISPP-2425-G9/docs/blob/main/Sprint%202/functionalDemo.mp4)**
 
 **[Demostración funcional de la aplicación (YouTube)](https://youtu.be/66dH-rnsPAY)**
 

Formato: `.mp4`  
Ubicación: Almacenado en el repositorio de GitHub en la carpeta `/Sprint 3`.

## 4. Datos Realistas en la Demo
La demostración del software incluye datos realistas y escenarios de usuario con nombres y contenido verosímil, evitando información ficticia no representativa.

