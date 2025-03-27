# ![logo caronte azul](https://github.com/user-attachments/assets/36631133-4715-4b20-91b8-5f07d96795c2)

# Feedback usuarios piloto

# Sprint 2

# Grupo 9

**Realizado por:**

García Escudero, Ángel

# 

# **Índice**

[**1\.Semana 10/03**](#semana-1003)

[1.1 Página de inicio](#página-de-inicio)

[1.2 Navbar](#navbar)

[1.3 Vista de esquelas](#vista-de-esquelas)

[1.4 Vista de destinatarios](#vista-de-destinatarios)

[1.5 Vista de perfil de usuario](#vista-de-perfil-de-usuario)

[1.6 Vista de formularios](#vista-de-formularios)

[**2\.Semana 17/03](#semana-1703)**

[2.1 Página de inicio](#página-de-inicio-1)

[2.2 Vista de esquelas](#vista-de-esquelas-1)

[2.3 Vista de destinatarios](#vista-de-destinatarios-1)

[2.4 Vista de servicios](#vista-de-servicios)

[2.5 Vista de certificado de defunción](#vista-de-certificado-de-defunción)

[2.6 Vista de perfil de usuario](#vista-de-perfil-de-usuario-1)

[2.7 Vista de formularios](#vista-de-formularios-1)

# **Semana 10/03**

### Página de inicio

* Uso predominante de ordenadores (70%) para el uso de la aplicación.  
* Valoración de la primera impresión de la aplicación: 3.85/5  
* Mejorar la **homepage** en cuanto estilos e información mostrada en ella.  
* Mostrar únicamente las secciones disponibles y accesibles para cada semana. No tiene sentido incluir una vista vacía a la que no se tiene permisos de acceso.  
* Incluir un **footer** en la aplicación que incluya:  
  * Nombre, banner y slogan de la empresa.  
  * Aviso legal, Política de privacidad y Términos de uso.  
  * Sección Sobre nosotros y Contacto.  
  * Redes sociales.

### Navbar

* Buena organización de las secciones pero es necesario **incluir sus nombres en la navbar** para mejorar la experiencia del usuario.  
* **Cambiar los iconos de la navbar** para que sean más representativos.

### Vista de esquelas

* Valoración de esquelas personalizadas: 3.56/5  
* Mejorar la vista de esquelas para que no sea tan simple.  
* Crear una sección para ver las esquelas directamente.  
* Comprobar que todos los campos se editan correctamente.  
* Corregir todos los botones de la vista de creación y edición para que funcionen (**no funcionan**).  
* Añadir más modelos de esquelas.  
* Eliminar la fecha de fallecimiento en la creación de esquelas propias.  
* Añadir **validadores** y **restricciones** a todos los campos.  
* Arreglar la pérdida del último carácter en el formulario de la vista móvil. (hola \= hol)  
* Mejorar la transición entre creación de esquela y selección de contactos.  
* Cambiar para que el botón “Guardar y seleccionar contactos” cumpla con la parte de guardar.  
* Arreglar que el mensaje de despedida y frase son cosas muy similares. Y visualmente demasiado pequeños.  
* Arreglar que las letras de la esquela no se entienden bien con el tema oscuro.  
* Mejorar la vista móvil para que se puedan crear las esquelas correctamente.  
* Cambiar el contenido de los botones para que únicamente contengan información esencial (actualizar, guardar, etc.).


### Vista de destinatarios

* Mejorar la vista para que no sea confusa, el botón de añadir un nuevo destinatario no debe estar al lado del usuario que creas.  
* Mostrar algún indicio de que se ha creado la esquela al final del proceso.

### Vista de perfil de usuario

* Mejorar la vista para que se adapte a la vista de móviles.  
* Revisar que se pueda modificar el perfil de usuario.  
* Guardar mis cambios al cambiar de pantalla de edición de los datos del perfil.  
* Al cambiar de una cuenta a otra, aparecen los datos del perfil de la cuenta anterior.


### Vista de formularios

* Mejorar la gestión de errores (no lanzar errores generales en la parte superior sino errores en los inputs de manera individual).  
* Mejorar la consistencia en los nombres de los botones (primera letra en mayúscula nada más).  
* Hacer que la visualización del número de teléfono sea de la forma 123 45 67 89\.  
* Hacer que el campo de contraseña muestre el número mínimo de caracteres necesarios.  
* Hacer que los campos tengan el número máximo de caracteres permitido (núm. de teléfono: 9\) y sólo se puedan introducir los símbolos requeridos (código postal: sólo números).  
* Reordenar los campos del formulario de creación de Empresa para que siga un orden lógico.

# **Semana 17/03**

### Página de inicio
* Uso predominante de ordenadores (65%) y dispositivos móviles (30%) para el uso de la aplicación.
* Valoración de la primera impresión de la aplicación: 3.89/5
* Mejorar la homepage en cuanto estilos e información mostrada en ella.
* Mostrar únicamente las secciones disponibles y accesibles para cada semana. No tiene sentido incluir una vista vacía a la que no se tiene permisos de acceso.
* Incluir un footer en la aplicación que incluya:
    * Nombre, banner y slogan de la empresa.
    * Aviso legal, Política de privacidad y Términos de uso.
    * Sección Sobre nosotros y Contacto.
    * Redes sociales.

### Vista de esquelas
* Corregir las vistas en móvil (scroll) realizando despliegues de prueba.
* Arreglar la visualización de las imágenes en la creación de esquelas (vista móvil).
* Incluir información descriptiva en cada sección para explicar qué se hace en cada vista.
* Implementar validadores en los campos de creación de una esquela.
* Revisar los formatos para meter las imágenes.
* Mejorar el tamaño del texto y su espacio dentro de la esquela.
* Quitar la fecha de fallecimiento en la creación de tu propia esquela, un campo que no se tiene que rellenar en un formulario no debería de aparecer en este.
* Visualizar las esquelas creadas sin obligar a su edición.
* Cambiar el botón Subir certificado por Subir certificado de defunción.
* Cambiar el botón Cambiar color por Cambiar color de texto.
* Conservar la elección del color si se cambia la plantilla de la esquela.
* Cambiar el mensaje de validación tras pulsar el botón Subir certificado al crear una esquela para un ser querido.

### Vista de destinatarios
* Centrar las columnas en la tabla de creación de destinatarios.
* Quitar el placeholder de sin prefijo.
* Mostrar los errores de la misma forma que se muestran en el formulario de creación de usuarios.
* Alternar los botones Editar y Eliminar.

### Vista de servicios
* Intentar mostrar más de una empresa por fila si el ancho de la pantalla lo permite
* Cambiar el orden de la información mostrada en cada empresa (la descripción es un campo importante como para estar en el último lugar, visualizar el número de teléfono de la misma forma que se realiza en la vista de destinatarios.
* Mejorar los filtros (si no hay información que se muestre un mensaje informativo, si se aplica un filtro desde la pestaña 2 los resultados se mueven a la primera pestaña 

### Vista de certificado de defunción
* Limitar la subida de archivos a: .png, .jpeg y .jpg
* Incluir una sección en la parte superior 
* Indicar qué formatos de archivos se pueden subir como certificado.

### Vista de perfil de usuario
* Separar el campo del teléfono para una mejor visualización
* Cambiar el botón Cerrar sesión por Eliminar cuenta (no se puede poner que para borrar una cuenta se tenga que editar el perfil.
* Arreglar el nombre de usuario de la navbar para que se actualice siempre (al editar el nombre de usuario este no se actualiza hasta un nuevo inicio de sesión).
* Cambiar el orden de los botones de Eliminar cuenta.
* El desplegable de Mi perfil y Cerrar sesión no desaparece sino se cierra manualmente, aunque se esté navegando por otras secciones.

### Vista de formularios
* Separar el campo del teléfono para una mejor visualización
* Cambiar el botón Cerrar sesión por Eliminar cuenta (no se puede poner que para borrar una cuenta se tenga que editar el perfil.
* Arreglar el nombre de usuario de la navbar para que se actualice siempre (al editar el nombre de usuario este no se actualiza hasta un nuevo inicio de sesión).
* Cambiar el orden de los botones de Eliminar cuenta.
* El desplegable de Mi perfil y Cerrar sesión no desaparece sino se cierra manualmente, aunque se esté navegando por otras secciones.
