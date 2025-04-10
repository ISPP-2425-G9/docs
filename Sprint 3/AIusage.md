# ![logo caronte azul](https://github.com/user-attachments/assets/36631133-4715-4b20-91b8-5f07d96795c2)

# Informe del uso de la IA

# Sprint 3

# Grupo 9

**Realizado por:**

García Rivero, Andrés Francisco

**Revisado por:**

García Escudero, Ángel

# **Índice**

[**1\. Introducción**](#introducción)

[**2\. Lecciones aprendidas**](#lecciones-aprendidas)

[2.1. Principales beneficios aportados](#principales-beneficios-aportados)

[2.2. Aportación general de la IA](#aportación-general-de-la-ia)

[2.3. Alucinaciones encontradas](#alucinaciones-encontradas)

[2.4. Adicional](#adicional)

[**3\. Aplicación de la IA en el Proyecto**](#aplicación-de-la-ia-en-el-proyecto)

[3.1. Documentación](#3.1.-documentación)

[Agrupar y resumir lecciones aprendidas sobre el uso de la IA](#agrupar-y-resumir-lecciones-aprendidas-sobre-el-uso-de-la-ia)

[Convertir PDF o Word a Markdown](#convertir-pdf-o-word-a-markdown)

[3.2. Backend](#3.2.-backend)

[Detectar API Key de Stripe](#detectar-api-key-de-stripe)

[Concluir qué servicio usar para envío de emails](#concluir-qué-servicio-usar-para-envío-de-emails)

[Generar test para verificar excepciones](#generar-test-para-verificar-excepciones)

[Informarse sobre las funcionalidades de borrado de la API de Cloudinary](#informarse-sobre-las-funcionalidades-de-borrado-de-la-api-de-cloudinary)

[Ver porque no funciona el smtp con el correo corporativo](#ver-porque-no-funciona-el-smtp-con-el-correo-corporativo)

[Arreglar fallo en workflow](#arreglar-fallo-en-workflow)

[Explicar error de un test](#explicar-error-de-un-test)

[Realizar y corregir test](#realizar-y-corregir-test)

[Realizar test de backend](#realizar-test-de-backend)

[3.3. Frontend](#3.3.-frontend)

[Generar y comparar un mensaje de Pull Request](#generar-y-comparar-un-mensaje-de-pull-request)

[Generar versión inicial de una vista](#generar-versión-inicial-de-una-vista)

[Solucionar bug en las fechas](#solucionar-bug-en-las-fechas)

[Obtener ideas de cómo gestionar los códigos de los mensajes](#obtener-ideas-de-cómo-gestionar-los-códigos-de-los-mensajes)

[Añadir un footer en la web sin que quede estático](#añadir-un-footer-en-la-web-sin-que-quede-estático)

[Mostrar y ocultar contraseña](#mostrar-y-ocultar-contraseña)

[Aceptar certificados de defunción por parte del admin](#aceptar-certificados-de-defunción-por-parte-del-admin)

[Cambiar formato de tabla](#cambiar-formato-de-tabla)

[Integrar video en la Homepage](#integrar-video-en-la-homepage)

[Integrar carrusel de imágenes en la Homepage](#integrar-carrusel-de-imágenes-en-la-homepage)

[Integrar Cypress para pruebas end2end](#integrar-cypress-para-pruebas-end2end)

[Incrustar un mapa interactivo en la vista de contacto](#incrustar-un-mapa-interactivo-en-la-vista-de-contacto)

[Solucionar problema con el ancho de los botones](#solucionar-problema-con-el-ancho-de-los-botones)

[Añadir animaciones al footer](#añadir-animaciones-al-footer)

[Validar algoritmo de comprobación de DNIs y NIFs](#validar-algoritmo-de-comprobación-de-dnis-y-nifs)

[Explicar estructura de los test con Jest](#explicar-estructura-de-los-test-con-jest)

[3.4. Otros](#3.4.-otros)

[Generar DNIs de prueba](#generar-dnis-de-prueba)

[Generar diseño de mascotas para Caronte](#generar-diseño-de-mascotas-para-caronte)

# 

## 1. **Introducción**

Este informe recopila el uso de la Inteligencia Artificial en el desarrollo del proyecto, detallando cómo ha ayudado en distintas tareas de programación y documentación. Se incluyen casos como la generación de código, resolución de problemas, optimización de estilos y cualquier otra aplicación relevante. Además, se documentan los prompts utilizados para tener un registro claro de su impacto y utilidad en el proceso.

## 2. **Lecciones aprendidas**

## 1. Principales beneficios aportados 

A partir de los comentarios recopilados, los principales beneficios son:

**Generación y optimización de código**

- Automatiza la creación de tests, sugerencias de dependencias y refactorización.  
- Resuelve bugs y errores de manera rápida y eficiente.  
- Proporciona plantillas y soluciones iniciales para acelerar el desarrollo.

**Ahorro de tiempo y reducción de errores**

- Agiliza procesos repetitivos, como generación de secuencias estructuradas, minimizando fallos humanos.  
- Acelera comprobaciones triviales en testing.

**Asistencia en diseño y creatividad**

- Genera diseños de imágenes (ej.: mascotas para apps) sin necesidad de habilidades artísticas.

**Mejora en la comunicación y documentación**

- Facilita la redacción de mensajes y corrección de ortografía.

**Aprendizaje y soporte técnico**

- Brinda información rápida sobre APIs externas y frameworks.  
- Ofrece ejemplos sistemáticos y soluciones prácticas para problemas cotidianos en desarrollo de software.

**Inspiración y resolución ágil de problemas**

- Sugiere ideas y enfoques innovadores para resolver desafíos técnicos.  
- Acelera la obtención de soluciones en comparación con métodos tradicionales.

## 2. Aportación general de la IA

A partir de los comentarios recopilados, estas son las principales contribuciones:

**Mejora en la calidad y eficiencia del código**

- Proporciona mayor cobertura y limpieza en el código.  
- Ayuda en la generación de secuencias estructuradas y desarrollo de tests (especialmente en backend).  
- Resuelve rápidamente pequeños arreglos o mejoras que, de otro modo, llevarían horas.

**Aceleración del desarrollo y comprensión técnica**

- Facilita la interpretación de APIs con documentación confusa o poco clara.  
- Agiliza el aprendizaje y aplicación de herramientas (ej.: Jest) y resolución de problemas específicos (ej.: ajustes en el footer).  
- Permite realizar más tareas en menos tiempo, optimizando la productividad.

**Reducción de tiempos en tareas repetitivas o complejas**

- Automatiza procesos tediosos, evitando pérdidas de tiempo en soluciones manuales.  
- Acelera la implementación de funcionalidades similares a desarrollos previos (ej.: mensajes basados en esquemas ya existentes).

## 3. Alucinaciones encontradas

A partir de las experiencias compartidas, estos son los principales casos detectados:

**Respuestas incoherentes o fuera de contexto**

- Fallos al resolver problemas específicos (ej.: integración con Stripe en despliegues), donde la IA no proporcionó soluciones útiles.

**Errores en generación de código y testing**

- Métodos mal gestionados (ej.: MediaHandler en tests), requiriendo ajustes manuales.  
- Importaciones incorrectas por falta de contexto en la solicitud (aunque esto podría atribuirse a información insuficiente proporcionada por el usuario).

**Documentación obsoleta o soluciones inviables**

- Enlaces a documentación desactualizada.  
- Propuestas de soluciones repetitivas para problemas no resueltos (ej.: ajustes en el footer), ignorando que los cambios sugeridos no funcionaban.

**Falsos positivos en correcciones**

- Aunque no hubo alucinaciones graves en algunos casos, otros usuarios enfrentaron sugerencias persistentemente erróneas que no se adaptaban al problema real.

## 4. Adicional

**Potencial de mejora en la adopción de IA**

- Aunque el desarrollo está avanzado, aún hay oportunidades para explotar la IA de manera más eficiente, especialmente en automatización y optimización de tareas.

**Gran ayuda en búsqueda de información y documentación**

- Agiliza la localización de recursos técnicos, aunque se debe contrastar con las últimas versiones de las tecnologías.  
- Útil para obtener ejemplos rápidos en testing y desarrollo.

## 3. **Aplicación de la IA en el Proyecto** 

## 3.1. Documentación 

### **Agrupar y resumir lecciones aprendidas sobre el uso de la IA**

**Documento:** AIusage

**Aplicación utilizada:** DeepSeek

**Prompt:**

| *{Lecciones del sprint anterior} Siguiendo ese esquema, resume el siguiente feedback: {Feedback del sprint}* Por cada sección |
| :---- |

**Respuesta:**

| *{Feedback agrupado usando el esquema del anterior}* |
| :---- |

**Adicional:** No aplica

### **Convertir PDF o Word a Markdown** 

**Documento:** timeEffortReport

**Aplicación utilizada:** ChatGPT

**Prompt:**

| Tengo las siguientes trazas de tiempo de todos los integrantes de un equipo de desarrollo software, estas trazas hacen referencia al tiempo que han dedicado a cada tarea del proyecto durante este Sprint. Necesito que los transformes a un formato Markdown, teniendo en cuenta que se tiene que diferenciar a simple vista las distintas personas que conforman el equipo y las principales tareas que han desarrollado durante su trabajo. {Se pega las trazas extraídas del informe descargado desde Clockify} |
| :---- |

**Respuesta:**

| Te da un formato .md acorde a lo solicitado en el prompt. |
| :---- |

**Adicional:** No aplica

## 3.2. Backend 

### **Detectar API Key de Stripe** 

**Requisito:** Pagos

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *El backend no detecta la API Key de Stripe, a pesar de estar en el application.properties* |
| :---- |

**Respuesta:**

| Alucinaciones, no tenía sentido |
| :---- |

**Adicional:** No aplica

### **Concluir qué servicio usar para envío de emails** {#concluir-qué-servicio-usar-para-envío-de-emails}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *En Zoho Mail, tengo entendido de que no se puede utilizar con motivos empresariales, eso es cierto? Y hay alguna api que me permita de forma gratuita utilizarla para motivos empresariales? Incluyendo el tema de dominio propio* |
| :---- |

**Respuesta:**

| Me ha devuelto diferentes posibilidades de apis a usar para envío de emails y luego me ha podido explicar cómo funciona exactamente JavaMailSender |
| :---- |

**Adicional:** [Enlace](https://chatgpt.com/share/67ed61ff-51b8-8007-88f0-35aaacb64259)

### **Generar test para verificar excepciones** {#generar-test-para-verificar-excepciones}

**Requisito:** FR-16

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *{Código} hazme test que verifiquen las excepciones \---------------------------------------------------------------- pero comprueba también que se retornan bien*  |
| :---- |

**Respuesta:**

| *{Código de varios tests}* |
| :---- |

**Adicional:** No aplica

### **Informarse sobre las funcionalidades de borrado de la API de Cloudinary**  {#informarse-sobre-las-funcionalidades-de-borrado-de-la-api-de-cloudinary}

**Requisito:** FR-014-Message management

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Dime cómo funciona la API de Cloudinary para el borrado de imágenes en una carpeta concreta. Necesito saber el Public ID concreto que tengo que pasarle como parámetro para que la API sepa qué imagen debe borrar. Estoy utilizando Spring Boot.* |
| :---- |

**Respuesta:**

| *En Cloudinary, cada archivo subido tiene un Public ID, que es un identificador único que debes usar para referenciar la imagen al borrarla. Cómo obtener el Public ID Si al subir la imagen no especificas un public\_id, Cloudinary generará uno automáticamente. El public\_id suele tener la estructura: \<nombre-de-la-carpeta\>/\<nombre-del-archivo\> carpeta específica Para borrar una imagen en una carpeta en Spring Boot, usa la API de Cloudinary. 1\. Dependencias Asegúrate de tener la dependencia de Cloudinary en tu pom.xml 2\. Configurar el cliente de Cloudinary 3\. Uso del método Para borrar foto.jpg de la carpeta usuarios: cloudinaryService.deleteImage("usuarios", "foto"); Conclusión 	•	El public\_id debe incluir la carpeta si la imagen está dentro de una. 	•	Puedes guardar el public\_id en la base de datos para facilitar la eliminación. 	•	Usa uploader().destroy(publicId, options) para eliminar imágenes específicas. Si necesitas eliminar varios archivos a la vez, dime y te explico cómo hacer un batch delete en Cloudinary.* |
| :---- |

**Adicional:** No aplica

### **Ver porque no funciona el smtp con el correo corporativo** {#ver-porque-no-funciona-el-smtp-con-el-correo-corporativo}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Failed messages: jakarta.mail.MessagingException: Got bad greeting from SMTP host: smtp.zoho.eu, port: 465, response: \[EOF\]| que significa este error cuando intento enviar un correo con esto spring.mail.host=smtp.zoho.eu  spring.mail.port=465  spring.mail.username=info@caronte.site spring.mail.password=contraseña de aplicación* |
| :---- |

**Respuesta:**

| *Esta configuración indica cómo se establece la conexión con el servidor SMTP de Zoho para el envío de correos electrónicos desde una aplicación Spring. A continuación se detalla el significado de cada propiedad: {Código} En resumen, estas propiedades configuran una conexión segura y autenticada con el servidor SMTP de Zoho, lo que es necesario para enviar correos electrónicos de manera confiable y segura desde tu aplicación Spring.* |
| :---- |

**Adicional:** No aplica

### **Arreglar fallo en workflow** {#arreglar-fallo-en-workflow}

**Requisito:** Coverage

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Tengo este workflow: {Workflow} Y este fallo: {Fallo de la consola}* |
| :---- |

**Respuesta:**

| *El error se debe a que Codacy no encuentra el archivo de cobertura en la ruta indicada: {Partes del log explicadas y detalles para solucionarlo} Si luego de eso sigue sin funcionar, podríamos revisar: Que Jacoco esté generando realmente el archivo XML. Si se necesita el flag \--final para el reporte en caso de múltiples submódulos. ¿Querés que revise también cómo asegurar que Jacoco esté generando el XML correctamente desde Maven?* |
| :---- |

**Adicional:** Me encanta que me habla en argentino porque me resulta simpático, pero no me esperaba que sin venir a cuento lo hiciera. (Ha sucedido más de una vez, tanto al iniciar conversación como en mitad de la misma)

### **Explicar error de un test** {#explicar-error-de-un-test}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Estoy probando el codigo de la funcion testGetMessagesByCustomerId\_Error que me da error: \[ERROR\]   MessageControllerTest.testGetMessageById\_Forbidden:151 » Servlet Request processing failed: java.lang.RuntimeException: Forbidden, me sale forbbiden pero en teoria es lo que debe salir no? esque no se entonces por que no pasa la prueba* |
| :---- |

**Respuesta:**

| *¡Buena observación\! El error que estás viendo: makefile Copiar Editar MessageControllerTest.testGetMessageById\_Forbidden:151 » Servlet Request processing failed: java.lang.RuntimeException: Forbidden significa que MockMvc está lanzando una excepción no controlada (RuntimeException) y como no hay ningún handler que la traduzca en un código de estado (como 403), el resultado es que falla automáticamente la prueba con un error de ServletRequest processing. ….* |
| :---- |

**Adicional:** No aplica

### **Realizar y corregir test** {#realizar-y-corregir-test}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Como mockear un método de una entidad en springboot* |
| :---- |

**Respuesta:**

| *Mockear un método de una entidad en Spring Boot (o más específicamente en un entorno de prueba con Java y Spring) puede sonar raro porque normalmente no se mockean entidades directamente. Las entidades suelen ser POJOs (Plain Old Java Objects) sin lógica compleja, y el objetivo del mocking es simular comportamientos de servicios, repositorios o componentes externos, no de clases simples. Pero si realmente necesitas mockear un método de una entidad, es probablemente porque: Tu entidad tiene lógica (lo cual ya es un poco contra las buenas prácticas, pero puede pasar). Quieres testear alguna lógica que depende del comportamiento de ese método. Entonces, aquí te dejo varias formas de hacerlo, dependiendo del contexto: {Código}* |
| :---- |

**Adicional:** [Enlace](https://chatgpt.com/share/67f6771f-eea8-8007-b381-729054894ef9)

### **Realizar test de backend** {#realizar-test-de-backend}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Dado este service, (Le paso el service), hazme los test como estos (le paso una clase de test), No pongo el prompt entero porque no me deja* |
| :---- |

**Respuesta:**

| *{Código}* |
| :---- |

**Adicional:** No aplica

## 3.3. Frontend {#3.3.-frontend}

### **Generar y comparar un mensaje de Pull Request**  {#generar-y-comparar-un-mensaje-de-pull-request}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Dame un posible mensaje para una pull request en inglés basándose en los siguientes commits realizados :  @rafduqcol rafduqcol committed 3 days ago feat: added selectedImage preview hugborang committed 3 days ago Commits on Mar 24, 2025 feat: upload images only in png,jpg and jpeg \[más commits...\]* y luego le pedí que lo comparara con la versión que ya tenia hecha para ver si se me olvidaba algo |
| :---- |

**Respuesta:**

| *Description: This PR introduces multiple enhancements and fixes related to message creation and media selection: Enabled preview for selected images. Restricted image uploads to PNG, JPG, and JPEG formats. \[más detalles...\]* |
| :---- |

**Adicional:** No aplica

### **Generar versión inicial de una vista** {#generar-versión-inicial-de-una-vista}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *hazme una primera versión de la lista de certificados de defunción, la idea es que te va a llegar del backend un listado con nombre, apellidos y varias urls (entre ellas la de la foto del certificado de defunción). Utiliza una tabla como la utilizada en esta vista  {{código de la vista}}. {{Respuesta chatgpt}} No está implementado en backend así que genera unos casos de ejemplo para poder ir haciendo la vista. {{Casos de ejemplo}}* |
| :---- |

**Respuesta:**

| *{{Código inicial de la vista}} {{Casos de ejemplo amplios y variados}}* |
| :---- |

**Adicional:** No aplica

### **Solucionar bug en las fechas** {#solucionar-bug-en-las-fechas}

**Requisito:** FR-12-message-management

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Tengo el siguiente bug: Al ingresar una fecha futura, se actualiza a la fecha de hoy, si intento borrar más de 2 dígitos del año se vuelve a actualizar a la fecha de hoy sin dejarme borrar la fecha* |
| :---- |

**Respuesta:**

| *Para asegurarte de que la comprobación de la fecha solo se realice cuando el usuario haya ingresado el año completo (4 dígitos), puedes realizar la validación solo cuando la longitud del año sea de 4 caracteres.   if (year.length \=== 4\) {       const currentDate \= new Date();       const inputDate \= new Date(\`${year}-${month}-${day}\`);       // Comparar si la fecha ingresada es mayor que la fecha actual (en milisegundos)       if (inputDate.getTime() \> currentDate.getTime()) {         formatted \= ""; // Si la fecha es futura, dejar el campo vacío       }     }* |
| :---- |

**Adicional:** No aplica

### **Obtener ideas de cómo gestionar los códigos de los mensajes** {#obtener-ideas-de-cómo-gestionar-los-códigos-de-los-mensajes}

**Requisito:** FR-12-message-management

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *¿Cómo podría hacer que a esta pantalla pueda ingresar la persona que lo haya creado o alguien que tenga el código?* |
| :---- |

**Respuesta:**

| *Toda la vista se muestra solo si isOwner es true Si isOwner es false, solo se renderiza \<View style={styles.codeContainer} /\>. Formulario de creación de mensaje Siempre visible dentro del ScrollView. Contiene los campos de entrada (Título del mensaje, Texto personalizado) y botones (Seleccionar imágenes, Seleccionar contactos, Guardar mensaje).* |
| :---- |

**Adicional:** No aplica

### **Añadir un footer en la web sin que quede estático** {#añadir-un-footer-en-la-web-sin-que-quede-estático}

**Requisito:** Feedback de usuarios piloto

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Si quisiera añadir un footer que apareciera al fondo del scrollview de cada página, ¿cómo lo haría?* |
| :---- |

**Respuesta:**

| *{{Código}}* |
| :---- |

**Adicional:** No aplica

### **Mostrar y ocultar contraseña** {#mostrar-y-ocultar-contraseña}

**Requisito:** No aplica

**Aplicación utilizada:** GitHub Copilot

**Prompt:**

| *Quiero tener un icono de ojo que me permita mostrar la contraseña u ocultarla.* |
| :---- |

**Respuesta:**

| *{{Código CustomTextInput modificado}}* |
| :---- |

**Adicional:** No aplica

### **Aceptar certificados de defunción por parte del admin** {#aceptar-certificados-de-defunción-por-parte-del-admin}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Tengo que hacer una pestaña donde se muestran los mensajes (texto e imágenes) y las esquelas (texto e imágenes) relacionadas con una persona por el certificado de defunción. El caso es que quiero que me hagas una vista que tenga arriba dos botones que sea para elegir que ver si mensajes o esquelas. Después de eso, según lo que hagas te sale un listado u otro de esquelas y mensajes en formato de tabla (dos columnas una para información de la esquela/mensaje y otra para acciones que será un botón de eliminar para borrar de la base de datos la esquela o mensaje pq es inapropiada), todo el texto y todas las imágenes de una esquela o mensaje quiero que me lo muestres en la misma fila y en la otra columna d esa fila que haya un botón de borrado por contenido inapropiado. Además arriba del todo de la vista, quiero un botón de volver a la pantalla anterior. Ahora te doy más pautas. Tienes que hacerlo sobre esta vista: {{vista vacía}} Fíjate del formato y el estilo para hacer la tabla de la de esta vista: {{vista con buen formato de tabla}} Fíjate para los botones de cambiar d esquela a mensaje de esta vista (botones de cliente o empresa): {{vista con ese formato}} Los datos del backend vendrán de esta forma: {{forma en la que vienen los datos del backend}}* |
| :---- |

**Respuesta:**

| *{{Código de la versión inicial de la pantalla muy cerca de lo que buscaba estéticamente hablando}}* |
| :---- |

**Adicional:** Muy importante usarla para la primera versión de las vistas, ahorra mucho tiempo

### **Cambiar formato de tabla** {#cambiar-formato-de-tabla}

**Requisito:** Feedback usuarios piloto: Mejorar las tablas para dejarlas todas igual a la de contacto

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Tengo que hacer un cambio en varias vista de manera que se use una tabla que use los estilos y colores y tal de la tabla de esta vista: {{código de la vista en la que la tabla sale bien}} Teniendo en cuenta que quiero la tabla como esa, podrías ponerla en esta vista (mismo contenido de la que esta pero cambia el estilo y todo eso): {{código de la vista que tiene una tabla con un formato que no me gusta y quiero ponerle el formato de la vista que le he pasado anteriormente}}* |
| :---- |

**Respuesta:**

| Cambios que tengo que hacer paso a paso y explicados en detalle |
| :---- |

**Adicional:** No aplica

### **Integrar video en la Homepage** {#integrar-video-en-la-homepage}

**Requisito:** No aplica

**Aplicación utilizada:** DeepSeek

**Prompt:**

| *Como puedo integrar un video de yt en react native con un componente* |
| :---- |

**Respuesta:**

| *Esta librería ofrece mejor control sobre el reproductor: Instala la dependencia: bash Copy npm install react-native-youtube-iframe \# o yarn add react-native-youtube-iframe Implementación: javascript Copy import React from 'react'; import YoutubePlayer from 'react-native-youtube-iframe'; const YouTubeVideo \= ({ videoId }) \=\> {   return (     \<YoutubePlayer       height={300}       width={'100%'}       videoId={videoId}       play={false}       onChangeState={event \=\> console.log(event)}     /\>   ); }; // Uso: // \<YouTubeVideo videoId="dQw4w9WgXcQ" /\>* |
| :---- |

**Adicional:** No aplica

### **Integrar carrusel de imágenes en la Homepage** {#integrar-carrusel-de-imágenes-en-la-homepage}

**Requisito:** No aplica

**Aplicación utilizada:** DeepSeek

**Prompt:**

| *Realiza un carrousel de imagenes, con botones de anterior y siguiente, además de que se vayan cambiando cada 5 segundos* |
| :---- |

**Respuesta:**

| *{Código de ejemplo}* |
| :---- |

**Adicional:** No aplica

### **Integrar Cypress para pruebas end2end** {#integrar-cypress-para-pruebas-end2end}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| prompt nº1  *¿como integro cypress en un proyecto react?* prompt nº2  *dame un ejemplo de test en cypress* |
| :---- |

**Respuesta:**

| prompt nº1  *Integrar Cypress en un proyecto React es bastante sencillo. Cypress es una herramienta de pruebas end-to-end (E2E) que facilita la automatización de pruebas de interfaz de usuario (UI). A continuación, te guiaré paso a paso sobre cómo integrar Cypress en un proyecto de React: {Guía de instalación}* prompt nº2  *Claro, aquí tienes un ejemplo básico de prueba usando Cypress en un proyecto React. Este ejemplo verifica que tu aplicación cargue correctamente y que un elemento específico (por ejemplo, un texto) esté presente en la página. {Ejemplo de test en Cypress}* |
| :---- |

**Adicional:** No aplica

### **Incrustar un mapa interactivo en la vista de contacto** {#incrustar-un-mapa-interactivo-en-la-vista-de-contacto}

**Requisito:** No aplica

**Aplicación utilizada:** GitHub Copilot

**Prompt:**

| *Quiero generar un mapa interactivo usando Google Maps para destacar la ETSII en una vista de react native.* |
| :---- |

**Respuesta:**

| *{código} (se ha usado Copilot Edit Mode)* |
| :---- |

**Adicional:** No aplica

### **Solucionar problema con el ancho de los botones** {#solucionar-problema-con-el-ancho-de-los-botones}

**Requisito:** FR-12-message-management

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Como puedo cambiar este componente para poder pasar un parámetro con el ancho del container* |
| :---- |

**Respuesta:**

| *{código}* |
| :---- |

**Adicional:** No aplica

### 

### **Añadir animaciones al footer**  {#añadir-animaciones-al-footer}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *\*\*\* Código de los iconos \*\*\** |
| :---- |

**Respuesta:**

| *🧩 Paso a paso 1\. Importa Animated Agrega al inicio: import { Animated } from "react-native"; 2\. Crea un componente AnimatedIcon Dentro del mismo archivo Footer.tsx, justo antes del return del Footer, crea este componente: {código}* |
| :---- |

**Adicional:** No aplica

### **Validar algoritmo de comprobación de DNIs y NIFs** {#validar-algoritmo-de-comprobación-de-dnis-y-nifs}

**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *{Código} Que devolvería la función anterior en el caso de que reciba los siguientes NIF de manera individualizada. nif: A58818501 A28369395 A07044530 B46143913 F37033297 B41622143 No quiero que crees los test sino que me valides tu mismo si con esa función los nif que te he proporcionado se validarian correctamente* |
| :---- |

**Respuesta:**

| *La respuesta ofrecida por el modelo fue true en todos los casos, indicando que todos los NIFs son validados correctamente por el algoritmo implementado. Para cada caso, la IA detalló paso a paso todos los pasos llevados a cabo para determinar su validez*  |
| :---- |

**Adicional:** No aplica

### **Explicar estructura de los test con Jest** {#explicar-estructura-de-los-test-con-jest}

**Requisito:** Testing de frontend

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Buenas, dime la estructura general que tiene un test de frontend usando Jest* |
| :---- |

**Respuesta:**

| *🧪 Estructura general de un test con Jest (y React Testing Library) {Código} 🧱 Partes clave del test Parte	Qué hace describe()	Agrupa un conjunto de tests relacionados it() o test()	Define un caso de prueba específico render()	Muestra el componente en un entorno de prueba screen.getBy...	Selecciona elementos del DOM renderizado fireEvent	Simula interacciones del usuario (click, input, etc.) expect()	Hace las comprobaciones (matchers como toBe, toBeInTheDocument, etc.)* |
| :---- |

**Adicional:** No aplica

## 3.4. Otros {#3.4.-otros}

### **Generar DNIs de prueba** {#generar-dnis-de-prueba}

**Otro:** Usuarios piloto

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *672519XX, donde XX vaya desde 00 a 33 generame esta secuencia  Pon que sea correo: usuariopilotoxx@caronte.site contraseña: usuariopiloto y dni :  672519xx, donde XX vaya desde 00 a 33* |
| :---- |

**Respuesta:**

| *correo: usuariopiloto00@caronte.site, contraseña: usuariopiloto, dni: 67251900   correo: usuariopiloto01@caronte.site, contraseña: usuariopiloto, dni: 67251901   …* |
| :---- |

**Adicional:** No sirvió de mucho porque aunque pregunté más cosas al final resultó que no se podía.

### **Generar diseño de mascotas para Caronte** {#generar-diseño-de-mascotas-para-caronte}

**Otro:** Marketing

**Aplicación utilizada:** ChatGPT

**Prompt:**

| \-prompt1: *genérame una mascota para Caronte que se adapte a la temática de la app y que sea lo mas "formal" posible y serio.* \-prompt2: *podría ser una paloma, o un esqueleto o Caronte en una barca* \-prompt3: *genérame una imagen de la mascota si fuera una paloma* \-prompt4: *genérame una imagen de esqueleto que sea la mascota de la app* \-prompt5: *que sea mas serio y con capucha* \-prompt6: *otra de Caronte en una barca* \-prompt7: *otra de una paloma* \-prompt8: *una paloma blanca que representa la paz mejor* |
| :---- |

**Respuesta:**

| \-prompt3(imagen):  *https://ibb.co/v6NjpM5d* \-prompt4(imagen):  *https://ibb.co/zVp2b7LF* \-prompt5(imagen):  *https://ibb.co/MkxhGbY3* \-prompt6(imagen):  *https://ibb.co/Kp4DsMwX* \-prompt7(imagen):  *https://ibb.co/VYPSwtzj* \-prompt8(imagen):  *https://ibb.co/7xrwZszy* |
| :---- |

**Adicional:** No aplica

*"AIusage“. Se ha utilizado la IA para recopilar y generalizar las lecciones aprendidas aportadas por todos los miembros. Toda la información generada por IA ha sido revisada por el equipo Caronte.*
