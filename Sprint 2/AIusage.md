# ![logo caronte azul](https://github.com/user-attachments/assets/36631133-4715-4b20-91b8-5f07d96795c2)

# Informe del uso de la IA

# Sprint 2

# Grupo 9

**Realizado por:**

García Rivero, Andrés Francisco

**Revisado por:**

García Escudero, Ángel

# **Índice**

[**Índice**](#índice)

[**1. Introducción**](#introducción)

[**2. Lecciones aprendidas**](#lecciones-aprendidas)

[2.1. Principales beneficios aportados](#principales-beneficios-aportados)

[2.2. Aportación general de la IA](#aportación-general-de-la-ia)

[2.3. Alucinaciones encontradas](#alucinaciones-encontradas)

[2.4. Adicional](#adicional)

[**3. Aplicación de la IA en el Proyecto**](#aplicación-de-la-ia-en-el-proyecto)

[2.1. Documentación](#2.1.-documentación)

[Realizar storyboard](#realizar-storyboard)

[Mejorar redacción corrigiendo faltas y reformulando](#mejorar-redacción-corrigiendo-faltas-y-reformulando)

[Evitar cláusulas abusivas en el Customer Agreement](#evitar-cláusulas-abusivas-en-el-customer-agreement)

[Mejorar cláusulas que son abusivas para dejar de serlo](#mejorar-cláusulas-que-son-abusivas-para-dejar-de-serlo)

[Obtener ideas sobre cómo medir el rendimiento de un equipo de desarrollo](#obtener-ideas-sobre-cómo-medir-el-rendimiento-de-un-equipo-de-desarrollo)

[2.2. Backend](#2.2.-backend)

[Gestionar peticiones con userId](#gestionar-peticiones-con-userid)

[Crear expresión compleja para restringir valor de string](#crear-expresión-compleja-para-restringir-valor-de-string)

[Implementar de manera segura conexión con Cloudinary](#implementar-de-manera-segura-conexión-con-cloudinary)

[Estudiar posibilidades sobre el tratamiento de los vídeos en backend](#estudiar-posibilidades-sobre-el-tratamiento-de-los-vídeos-en-backend)

[Refactorizar código](#refactorizar-código)

[Crear test básico para aprender la estructura](#crear-test-básico-para-aprender-la-estructura)

[Modificar condición if](#modificar-condición-if)

[Hacer test de backend](#hacer-test-de-backend)

[2.3. Frontend](#2.3.-frontend)

[Realizar gestión de rutas de navegación](#realizar-gestión-de-rutas-de-navegación)

[Centrar texto en botón](#centrar-texto-en-botón)

[Crear componente de planes de usuario](#crear-componente-de-planes-de-usuario)

[Insertar animaciones](#insertar-animaciones)

[Crear nueva vista register](#crear-nueva-vista-register)

[Mejorar estilo de Términos y Condiciones](#mejorar-estilo-de-términos-y-condiciones)

[Implementar filtrado y paginación](#implementar-filtrado-y-paginación)

[Crear nuevo formato de string](#crear-nuevo-formato-de-string)

[Cambiar estilo de botones](#cambiar-estilo-de-botones)

[Limpiar formulario al refrescar](#limpiar-formulario-al-refrescar)

[Mejorar formulario de registro](#mejorar-formulario-de-registro)

[Obtener información sobre la librería que usada para cargar imágenes](#obtener-información-sobre-la-librería-que-usada-para-cargar-imágenes)

[Añadir animaciones tras finalizar pago](#añadir-animaciones-tras-finalizar-pago)

[Resolver problema al volver a la pantalla anterior](#resolver-problema-al-volver-a-la-pantalla-anterior)

[Aumentar tamaño de input](#aumentar-tamaño-de-input)

[Realizar navBar customizable](#realizar-navbar-customizable)

[2.4. Otros](#2.4.-otros)

[Recopilar quién responde encuestas de google sin almacenar  su correo](#recopilar-quién-responde-encuestas-de-google-sin-almacenar-su-correo)

# 

#  **1. Introducción**

Este informe recopila el uso de la Inteligencia Artificial en el desarrollo del proyecto, detallando cómo ha ayudado en distintas tareas de programación y documentación. Se incluyen casos como la generación de código, resolución de problemas, optimización de estilos y cualquier otra aplicación relevante. Además, se documentan los prompts utilizados para tener un registro claro de su impacto y utilidad en el proceso.

# **2.  Lecciones aprendidas**

  ## 1. Principales beneficios aportados

A partir de los comentarios recopilados, los principales beneficios son:

**Eficiencia y rapidez en la resolución de problemas**

- Agiliza la búsqueda de información, proporcionando respuestas rápidas y alternativas de solución.  
- Acelera la toma de decisiones al ofrecer análisis y sugerencias en tiempo real.

**Mejora en el desarrollo y depuración de código**

- Ayuda a debuggear y refactorizar código de manera más eficiente.  
- Facilita la implementación de pruebas (testing) con ejemplos prácticos, evitando consultar documentación extensa.  
- Optimiza el desarrollo con herramientas como Copilot, generando código de forma automática.

**Automatización de tareas repetitivas**

- Detecta y corrige errores en documentos legales (como cláusulas abusivas) mejor que herramientas tradicionales.   
- Simplifica la combinación de condiciones lógicas (ej. estructuras condicionales complejas).

**Inspiración y mejora en el diseño**

- Permite implementar animaciones y diseños front-end complejos sin necesidad de un alto nivel de expertise.  
- Sugiere mejoras en la estructura y seguridad del código.

**Ahorro de tiempo y reducción de errores**

- Evita pérdidas de tiempo en pruebas y búsquedas manuales.  
- Reduce la frustración al resolver bugs de manera más rápida y efectiva.

**Aprendizaje acelerado y soporte en tecnologías nuevas**

- Facilita la comprensión y aplicación de frameworks o lenguajes desconocidos (ej. React-Native).  
- Proporciona ejemplos funcionales que aceleran la curva de aprendizaje.

   ## 2. Aportación general de la IA

A partir de los comentarios recopilados, estas son las principales contribuciones:

**Optimización del tiempo y aumento de la productividad**

- Ha permitido trabajar más rápido, reduciendo el tiempo en tareas repetitivas o de investigación.  
- Ahorra tiempo en la resolución de bugs, generación de código y pruebas, acelerando el desarrollo.

**Mejora en la calidad del código y buenas prácticas**

- Ayuda a identificar y corregir errores, bugs y malas prácticas (como bad smells detectados por Codacy).  
- Facilita la refactorización y legibilidad del código, ofreciendo soluciones más limpias y eficientes.  
- Proporciona ejemplos de patrones de diseño, expresiones regulares (regex) y testing, mejorando la estructura del proyecto.

**Aprendizaje y adaptación a nuevas tecnologías**

- Ha sido clave para entender frameworks o lenguajes desconocidos (como React-Native, Lombok o SpringBoot).  
- Ofrece explicaciones claras y ejemplos prácticos, acelerando la curva de aprendizaje.

**Automatización y mejora en documentos legales**

- Detecta y corrige cláusulas abusivas en documentos legales (términos de uso, políticas de privacidad), mejorando su cumplimiento normativo.

**Innovación en diseño front-end**

- Permite implementar animaciones y estilos profesionales sin requerir un nivel avanzado en diseño.  
- Optimiza la interfaz de usuario, haciendo que las pantallas sean más atractivas y funcionales.

**Soporte en testing y estructura de proyectos**

- Aclara dudas básicas pero importantes, como la ubicación de tests (ej. carpeta tests/).  
- Proporciona ejemplos de pruebas unitarias, facilitando el desarrollo de test cases.

   ## 3. Alucinaciones encontradas

A partir de las experiencias compartidas, estos son los principales casos detectados:

**Información técnica incorrecta**

**Errores en herramientas o frameworks:**

- Sugerir funciones o métodos inexistentes en librerías como React-Native o CSS.

**Soluciones no funcionales o ambiguas**

**Propuestas de código inválidas:**

- Ofrecer soluciones para valores no nulos (non-nullable) que no funcionan, obligando a cambios manuales (ej. hacer el campo nullable y gestionarlo en servicios).  
- Refactorizaciones poco óptimas, con alta complejidad algorítmica o código redundante.

**Falta de precisión en detalles clave**

**Ambigüedad en documentos legales:**

- En correcciones de cláusulas abusivas, a veces usa términos vagos como "un corto tiempo" en lugar de plazos concretos.  
- Omite información necesaria para cumplir con regulaciones, aunque detecta correctamente el problema base.

**Limitaciones en diseño responsive y contexto**

**CSS/UI no adaptativo:**

- Recomienda estilos que no consideran tamaños de pantalla (ej. móvil vs. escritorio), aunque esto puede deberse a prompts poco específicos.  
- No siempre optimiza layouts complejos sin guía explícita.

**Insuficiencia en casos complejos**

**Pruebas (testing) incompletas:**

- En tests unitarios o de integración, a veces se queda corto en funcionalidades avanzadas (ej. creación de un obituary con múltiples requisitos).

   ## 4. Adicional

**Hallazgos clave sobre la IA en el trabajo:**

- Buena para inspirar, pero necesita revisión humana.  
- Mejor que herramientas legales especializadas en contexto, pero a veces imprecisa.  
- Funciona mejor en front-end complejo que en soluciones simples.  
- Depende mucho del prompt (más detalles \= mejores resultados).  
- Ideal como asistente, no como reemplazo humano.

# **3. Aplicación de la IA en el Proyecto**

## 2.1. Documentación

### **Realizar storyboard**

	**Documento:** Storyboard

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Vale tengo que hacer un storyboard que poner esto: Incluir en el modelo de negocio una presentación de impacto, para cada tipo de usuarios, cliente e inversor debe haber un anuncio (storyboard) debemos diseñar que queremos grabar para vender. Guión de forma visual de historia para anunciarle la app a ese tipo de usuario y a los inversores. debemos contar la rentabilidad y el riesgo a los inversores y para los clientes que te compren.* |
| :---- |

**Respuesta:**

| *Perfecto, vamos a organizar un storyboard para dos tipos de destinatarios:     Clientes/usuarios de la app (quienes usarán o comprarán el producto)     Inversores (quienes pueden poner dinero en el proyecto) Voy a darte un guión visual tipo storyboard para cada uno, con escenas simples, ideas claras y un enfoque narrativo que puedas grabar fácilmente. Luego puedes elegir si hacer una grabación real, un prototipo animado o una presentación con imágenes y voz en off. 🎯 Storyboard 1 \- CLIENTES/USUARIOS     Objetivo: Hacer que el cliente sienta que la app le va a solucionar un problema real y quiera descargarla o usarla. 🎬 ESCENA 1 – "Problema cotidiano"     Imagen: Persona con cara de frustración frente al móvil o al escritorio.     Voz en off: "¿Te ha pasado que intentas organizarte y al final acabas con mil cosas sin terminar?" 🎬 ESCENA 2 – "La solución aparece"     Imagen: Se muestra la app en acción (pantallas simples, tareas organizadas, interfaz bonita).     Voz en off: "Con \[Nombre de la App\], organizar tus tareas es fácil, rápido y motivador." 🎬 ESCENA 3 – "Beneficio emocional"     Imagen: Persona sonriente, tranquila, viendo su progreso.     Voz en off: "Ahorra tiempo, reduce el estrés y alcanza tus metas con un método que sí funciona." 🎬 ESCENA 4 – "Funcionalidades destacadas"     Imagen: Interfaz mostrando Pomodoro, estadísticas, logros desbloqueados, tareas completadas.     Voz en off: "Método Pomodoro, logros, estadísticas, prioridades… todo en un solo lugar." 🎬 ESCENA 5 – "Llamada a la acción"     Imagen: Pantalla con botón de descarga o usuario usando la app feliz.     Voz en off: "Descárgala ya y empieza a organizar tu vida de forma inteligente." 💼 Storyboard 2 \- INVERSORES     Objetivo: Mostrar el potencial del negocio, rentabilidad, escalabilidad y gestión del riesgo. 🎬 ESCENA 1 – "Inicio impactante"     Imagen: Estadísticas de crecimiento de apps de productividad.     Voz en off: "El mercado de productividad crece un 12% anual. Y aún hay espacio para soluciones reales y efectivas." 🎬 ESCENA 2 – "La propuesta"     Imagen: App en pantalla con datos claros y visuales.     Voz en off: "\[Nombre de la App\] es una solución completa para usuarios que buscan eficiencia, motivación y control." 🎬 ESCENA 3 – "Modelo de negocio"     Imagen: Esquema visual (freemium, suscripción premium, logros desbloqueables, gamificación).     Voz en off: "Modelo freemium escalable, ingresos por suscripciones premium y funciones exclusivas gamificadas." 🎬 ESCENA 4 – "Rentabilidad proyectada"     Imagen: Gráficas de ingresos esperados, usuarios activos, CAC vs LTV.     Voz en off: "Proyección: \+50.000 usuarios en 2 años, retorno de inversión en el tercer trimestre del segundo año." 🎬 ESCENA 5 – "Gestión del riesgo"     Imagen: Lista de estrategias de mitigación (equipo técnico, pruebas de mercado, escalado progresivo).     Voz en off: "Riesgos controlados: validación con usuarios reales, escalado progresivo y bajo coste de adquisición." 🎬 ESCENA 6 – "Cierre convincente"     Imagen: Logo de la app \+ frase de impacto.     Voz en off: "Invertir en \[Nombre de la App\] es apostar por un modelo sólido, escalable y con impacto real en la vida de las personas."*  |
| :---- |

**Adicional:** Hay más prompts pero ese es el primero de todos.

### **Mejorar redacción corrigiendo faltas y reformulando** 

	**Documento:** Retrospectiva

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *redactalo mejor manteniendo el formato y corrigiendo las faltas: \*\* Mala comunicación entre el frontend y el backend. Hay tareas de frontend que se retrasan o no se completan porque el backend no está terminado \*\* Cambios en la base de datos que modifican funcionalidad y rompen la aplicación, se debería de evitar estos cambios, o en caso de que sean estrictamente necesarios, avisar con tiempo para que se pueda adaptar la funcionalidad de nuevo. \*\* Cuando la tarea involucre a más gente se debe de hablar con ellas y estar informado e informar de como va la cosa por parte de cada uno. \*\* Retrasos en el cumplimiento de algunos deadlines.* |
| :---- |

**Respuesta:**

| *\*\* Comunicación deficiente entre frontend y backend. Algunas tareas de frontend se retrasan o no pueden completarse porque el backend no está terminado, lo que afecta el desarrollo y la coordinación entre equipos.   \*\* Cambios en la base de datos que alteran funcionalidades y generan fallos en la aplicación. Se deberían evitar estos cambios siempre que sea posible o, en caso de ser estrictamente necesarios, comunicarlos con antelación para permitir la adaptación de la funcionalidad afectada.   \*\* Falta de coordinación en tareas compartidas. Cuando una tarea involucre a varias personas, es esencial que haya comunicación constante, manteniendo a todos informados sobre el progreso y evitando malentendidos o bloqueos.   \*\* Retrasos en el cumplimiento de deadlines. Se han producido incumplimientos en algunos plazos de entrega, lo que afecta la planificación y el progreso del proyecto.* |
| :---- |

**Adicional:** En varias secciones de varios documentos, se ha seguido un procedimiento similar. Se toma este como ejemplo para evitar tener que repetirlo constantemente.

### **Evitar cláusulas abusivas en el Customer Agreement** 
	**Documento:** Customer Agreement 

**Aplicación utilizada:** CLAUDETTE

**Prompt:**

| *Se le pasa el contenido del documento traducido al inglés y te devuelve las cláusulas abusivas que contiene el texto*  |
| :---- |

**Respuesta:**

| *El documento tenía algunas cláusulas abusivas, un ejemplo de una de ellas es: “CARONTE reserves the right to modify this Agreement at any time , whether to adapt it to legal or operational changes or to improve the user experience . Unfairness categories: Unilateral Change, Unilateral Termination”* |
| :---- |

**Adicional:** No aplica.

### **Mejorar cláusulas que son abusivas para dejar de serlo**

	**Documento:** Políticas de privacidad y Términos de condiciones y uso

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *{{Se mandan varias cláusulas\]}* |
| :---- |

**Respuesta:**

| *{{Devuelve las cláusulas corregidas\]}* |
| :---- |

**Adicional:** No aplica.

### 

### **Obtener ideas sobre cómo medir el rendimiento de un equipo de desarrollo**

	**Documento:** Commitment Agreement 

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Necesito que me digas cómo puedo medir el rendimiento de un equipo de desarrollo de software* |
| :---- |

**Respuesta:**

| *Medir el rendimiento de un equipo de desarrollo de software puede hacerse desde diferentes enfoques, dependiendo de los objetivos del equipo y la organización. Aquí hay varias métricas y enfoques clave: 1\. Métricas de Productividad Velocidad (Velocity): Cantidad de puntos de historia completados en un sprint. Tiempo de ciclo (Cycle Time): Tiempo desde que se inicia una tarea hasta que se completa. Tiempo de entrega (Lead Time): Tiempo desde que se solicita una funcionalidad hasta que se entrega. Tasa de finalización de tareas: Número de tareas completadas versus las planificadas. 2\. Métricas de Calidad del Código Defectos en producción: Número de errores encontrados después del despliegue. Cobertura de pruebas: Porcentaje del código cubierto por pruebas automatizadas. Debt Ratio (Deuda técnica): Cantidad de código refactorizado versus código nuevo. 3\. Métricas de Colaboración y Cultura Tiempo de retroalimentación: Tiempo que tarda un desarrollador en recibir feedback sobre su código. Participación en revisiones de código: Cantidad de revisiones de código realizadas por cada miembro. Índice de rotación del equipo: Frecuencia con la que el equipo cambia de miembros. 4\. Métricas de Entrega y DevOps Frecuencia de despliegues: Cuántas veces se libera código en producción. Tiempo medio de recuperación (MTTR \- Mean Time To Recovery): Tiempo que tarda el equipo en resolver fallos en producción. Porcentaje de despliegues fallidos: Proporción de despliegues que requieren correcciones inmediatas. 5\. Métricas de Satisfacción y Motivación Encuestas de satisfacción: Evaluaciones periódicas sobre el ambiente de trabajo y herramientas utilizadas. NPS interno: Preguntar a los miembros del equipo qué tan probable es que recomienden trabajar en el equipo. Consejos para medir correctamente: No usar métricas de manera aislada; combinarlas para obtener una visión realista. Evitar métricas que fomenten comportamientos no deseados (ej. medir solo líneas de código). Hacer seguimiento con retrospectivas para mejorar continuamente. ¿Quieres que te ayude a implementar alguna métrica en particular?* |
| :---- |

**Adicional:** No aplica.

## 2.2. Backend

### **Gestionar peticiones con userId**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *{Código} ¿Dado este código, omitirías la parte del parámetro y que en vez de ello lo que se hiciera fuera coger el id del jwt directamente o crees que puede servir de algo?* |
| :---- |

**Respuesta:**

| *Depende de cómo quieres manejar la seguridad y la claridad en la API. Aquí hay algunas consideraciones: {Consultar enlace}* |
| :---- |

**Adicional:** [Enlace.](https://chatgpt.com/share/67d2ffea-049c-8007-acaf-663b298b4dea)

### **Crear expresión compleja para restringir valor de string**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *yo quiero un pattern que sea que deben ser 3 numeros de entre 1y 3 digitos separados por coma vale ahora quiero que los digitos sean de 0 a 255*  |
| :---- |

**Respuesta:**

| *Si necesitas que los valores sean estrictamente números entre 0 y 255, separados por comas, la mejor opción es esta expresión regular: @Pattern(regexp \= "^(25\[0-5\]|2\[0-4\]\\\\d|1\\\\d{2}|\\\\d{1,2}),(25\[0-5\]|2\[0-4\]\\\\d|1\\\\d{2}|\\\\d{1,2}),(25\[0-5\]|2\[0-4\]\\\\d|1\\\\d{2}|\\\\d{1,2})$",           message \= "Debe tener el formato R,G,B con valores entre 0 y 255 (ej. 255,0,128)") private String wordColor;* |
| :---- |

**Adicional:** Se comprobó que funcionara tal y como se precisaba.

### **Implementar de manera segura conexión con Cloudinary** 

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Quiero gestionar las llamadas a la API de la BBDD externa Cloudinary en un proyecto a través de su API Key, quiero que permanezca privada pues contiene la id de la cuenta y las claves pública y privada de esta para acceder mediante peticiones a su API. Actualmente, tengo esta API Key almacenada en el .env local del proyecto, pero a la hora del despliegue de la aplicación necesito sacarlo de allí porque no existe ese archivo en despliegue. ¿Sería posible utilizar el archivo application.properties, hay alguna otra opción viable y que funcione de la misma manera?* |
| :---- |

**Respuesta:**

| *Sí, es completamente viable almacenar las claves de API y otras configuraciones sensibles de tu aplicación en el archivo application.properties (si estás usando Spring Boot u otro framework similar que soporte esta configuración). Sin embargo, aquí te proporciono la mejor alternativa para mantener las claves privadas y seguras, especialmente cuando tu aplicación está desplegada en un entorno de producción: Usar Variables de Entorno (Environment Variables): Una opción más segura es utilizar variables de entorno para almacenar estas claves. Esto mantiene las claves fuera del código y evita riesgos si se suben a repositorios. En lugar de usar un archivo .env, puedes configurar las variables de entorno en tu servidor o servicio de despliegue. Por ejemplo, en tu archivo application.properties podrías configurarlo de la siguiente forma: cloudinary.api\_key=${CLOUDINARY\_API\_KEY} cloudinary.api\_secret=${CLOUDINARY\_API\_SECRET} cloudinary.cloud\_name=${CLOUDINARY\_CLOUD\_NAME} Luego, simplemente configura las variables de entorno en el entorno de producción de tu aplicación: export CLOUDINARY\_API\_KEY=your-api-key export CLOUDINARY\_API\_SECRET=your-api-secret export CLOUDINARY\_CLOUD\_NAME=your-cloud-name En este caso, las claves se cargarán automáticamente a partir de las variables de entorno configuradas en el entorno de ejecución.* |
| :---- |

**Adicional:** No aplica.

### **Estudiar posibilidades sobre el tratamiento de los vídeos en backend**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *La idea es que cuando llegue al backend lo que le va a llegar es un base 64 pero tenemos una función de que te va a transformar el base 64 en una url el problema es que por ejemplo para postman si hay que meterle en el json del body un base 64* |
| :---- |

**Respuesta:**

| *Para trabajar con base64 en Postman y evitar problemas con la longitud de los datos (especialmente en el caso de videos que generan grandes cadenas de base64), una solución práctica sería utilizar un archivo base64 en lugar de pegar directamente el string en el cuerpo del JSON. Aquí te detallo cómo hacerlo: 1\. Subir el archivo a una variable en Postman Puedes cargar el video en base64 a través de una variable en Postman utilizando el Pre-request Script y luego enviar esta variable en el cuerpo del JSON. Pasos: Convertir el archivo MP4 a base64 (fuera de Postman): Utiliza herramientas externas (por ejemplo, base64 en la terminal o una herramienta online) para convertir el video MP4 a base64. Cargar la cadena base64 en una variable: En Postman, ve a la pestaña Pre-request Script y define una variable con la cadena base64. Ejemplo de código en el Pre-request Script: javascript Copiar // Suponiendo que el base64 del video está almacenado en una variable let videoBase64 \= 'data:video/mp4;base64,...'; // Tu base64 aquí pm.environment.set("videoBase64", videoBase64); // Guarda la cadena base64 como una variable de entorno Utilizar la variable en el cuerpo de la solicitud: Luego, en el cuerpo de tu solicitud (JSON), puedes usar la variable de entorno que contiene el base64 del video: json Copiar {   "video": "{{videoBase64}}" } 2\. Alternativa: Utilizar un archivo en lugar de base64 Si prefieres no lidiar con cadenas de texto tan largas, otra opción sería subir el archivo directamente en Postman como archivo adjunto (como un form-data en lugar de base64). Esto puede ser útil si tu API espera un archivo binario o un archivo de video y no una cadena base64. Pasos para hacerlo: Seleccionar tipo de cuerpo como form-data: En lugar de raw, selecciona form-data como tipo de cuerpo en Postman. Subir el archivo: Asegúrate de que la clave sea el nombre de campo que espera el backend (por ejemplo, video), y luego selecciona el archivo en lugar de usar base64. Ejemplo: Key: video Value: \[Selecciona tu archivo MP4\] Enviar la solicitud: Esto enviará el archivo binario directamente al backend sin tener que lidiar con la conversión base64. Resumen: Para Postman con base64: Utiliza un script pre-request para almacenar el base64 como una variable y luego inyecta esa variable en el cuerpo del JSON. Para evitar base64: Considera usar form-data para cargar el archivo directamente. Ambas soluciones deberían ayudarte a manejar grandes archivos sin perder información o enfrentar problemas de longitud en Postman.* |
| :---- |

**Adicional:** No aplica.

### **Refactorizar código**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Que diferencia hay entre uso de Random y SecuriteRandom en java* |
| :---- |

**Respuesta:**

| *Me explica la diferencia entre uso de la clase Random y SecuriteRandom en java para saber cuál es más indicada de usar a la hora de generación de contraseñas aleatorias* |
| :---- |

**Adicional:** [Enlace.](https://chatgpt.com/share/67e1e5ed-deb8-8007-9be8-05fe870e3191)

### **Crear test básico para aprender la estructura**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *@Transactional(readOnly \= true)     public Obituary getObituaryById(Long obituaryId) {         Obituary obituary \= obituaryRepository.findById(obituaryId)                 .orElseThrow(() \-\> new IllegalArgumentException("Obituary not found"));         if(obituary.getWordColor() \== null){             obituary.setWordColor("0,0,0");         }         return obituary;     } hazme un test para este servicio que sea de @SpringBootTest y que utilice mocks* |
| :---- |

**Respuesta:**

| *import static org.junit.jupiter.api.Assertions.\*; import static org.mockito.Mockito.\*; import java.util.Optional; import org.junit.jupiter.api.Test; import org.springframework.beans.factory.annotation.Autowired; import org.springframework.boot.test.context.SpringBootTest; import org.springframework.boot.test.mock.mockito.MockBean; @SpringBootTest class ObituaryServiceTest {     @Autowired     private ObituaryService obituaryService;     @MockBean     private ObituaryRepository obituaryRepository;     @Test     void testGetObituaryById\_WhenObituaryExists() {         // Arrange         Long obituaryId \= 1L;         Obituary mockObituary \= new Obituary();         mockObituary.setId(obituaryId);         mockObituary.setWordColor(null);         when(obituaryRepository.findById(obituaryId)).thenReturn(Optional.of(mockObituary));         // Act         Obituary result \= obituaryService.getObituaryById(obituaryId);         // Assert         assertNotNull(result);         assertEquals("0,0,0", result.getWordColor()); // Verifica que el color por defecto se asigna         verify(obituaryRepository, times(1)).findById(obituaryId);     }     @Test     void testGetObituaryById\_WhenObituaryNotFound() {         // Arrange         Long obituaryId \= 1L;         when(obituaryRepository.findById(obituaryId)).thenReturn(Optional.empty());         // Act & Assert         Exception exception \= assertThrows(IllegalArgumentException.class, () \-\> {             obituaryService.getObituaryById(obituaryId);         });         assertEquals("Obituary not found", exception.getMessage());         verify(obituaryRepository, times(1)).findById(obituaryId);     } }* |
| :---- |

**Adicional:** No aplica.

### **Modificar condición if**

	**Requisito:** FR-15

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *la funcion update manda error cuando intento editar unicamente el email o telefono, dime como modifico el if para que no tenga en cuenta al elemento que se quiere editar* |
| :---- |

**Respuesta:**

| *// Verifica si el teléfono está cambiando y si es así, comprueba si ya está registrado     if (\!existingContact.getTelephone().equals(emergencyContactDTO.telephone())) {         checkIfTelephoneIsDuplicate(emergencyContactDTO.telephone(), email);     }     // Verifica si el email está cambiando y si es así, comprueba si ya está registrado     if (\!existingContact.getEmail().equals(emergencyContactDTO.email())) {         checkIfEmailIsDuplicate(emergencyContactDTO.email(), email);     }* |
| :---- |

**Adicional:** No aplica.

### **Hacer test de backend**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *{{Código de service}}* |
| :---- |

**Respuesta:**

| *A continuación te muestro un ejemplo de cómo podrías escribir los tests para el método updateObituaryWithReceivers. En este ejemplo se incluye un test para el caso exitoso y algunos tests para los casos en los que se lanza excepción (por ejemplo, cuando isMine es false, cuando el customer no coincide y cuando se intenta cambiar la propiedad isMine). {{Código de test}}* |
| :---- |

**Adicional:** [Enlace.](https://chatgpt.com/share/67e1e5ed-deb8-8007-9be8-05fe870e3191)

## 2.3. Frontend

### 	**Realizar gestión de rutas de navegación**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Estoy utilizando en mi proyecto "expo-router": "\~4.0.17", cómo puedo realizar en gestionado de las rutas* |
| :---- |

**Respuesta:**

| *En expo-router, la gestión de rutas se basa en la estructura de archivos dentro de la carpeta app/. Expo Router utiliza un sistema de enrutamiento basado en archivos, similar a Next.js. Aquí te dejo una guía rápida para manejar las rutas en un proyecto gestionado: {Guía}* |
| :---- |

**Adicional:** [Enlace.](https://chatgpt.com/share/67d2ff58-ed7c-8007-9f9f-ed7d862271a6)

### **Centrar texto en botón**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Al importar custom button sobreescribe los estilos y el texto no se centra como puedo solucionarlo?* |
| :---- |

**Respuesta:**

| *Para evitar la repetición de textAlign: 'center' y otros estilos que se aplican tanto al contenedor del botón como al texto dentro de él, puedes reorganizar los estilos en tu código para que textAlign: 'center' solo se aplique una vez y se herede de los estilos del contenedor. Una forma de hacerlo es separar los estilos comunes y aplicarlos tanto al contenedor (button) como al texto (textWhite, textGrey). Así puedes reutilizar esos estilos sin necesidad de escribirlos varias veces. Aquí tienes una solución: {}* |
| :---- |

**Adicional:** Fue muy útil porque estuvimos mucho tiempo para resolverlo.

### **Crear componente de planes de usuario**

	**Requisito:** FR-09-Plan Management

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Me gustaría hacer un componente en mi proyecto de react native, en un archivo .tsx, que sea como uno de estos recuadros que te he pasado por la foto. {{foto de como está puesto en la landing page}} Además quiero que uses estos colores del global style: {{colores del global styles}} Por último, quiero que las entradas sean: rol del usuario y el plan que tiene el usuario y dependiendo del rol y del plan que tenga se muestran unos u otros recuadros de las descripción de los planes.* |
| :---- |

**Respuesta:**

| *Componente básico al que hay que mejorarle varias cosas pero que sirve como punto de partida y ahorra el trabajo inicial en gran medida: import React from 'react'; import { View, Text, StyleSheet } from 'react-native'; import { GlobalStyles } from '../styles/GlobalStyles'; interface PlanCardProps {   role: 'user' | 'business';   plan: 'digital' | 'monthly' | 'advertisement'; } const PlanCard: React.FC\<PlanCardProps\> \= ({ role, plan }) \=\> {   const getPlanDetails \= () \=\> {     if (role \=== 'business' && plan \=== 'advertisement') {       return {         title: 'PUBLICIDAD PARA EMPRESAS',         description:           'Publicita tu empresa relacionada con el sector funerario (funeraria, notaría, floristería, etc.) para que más clientes puedan conocer tus servicios.',         price: '9.99€/mes',         borderColor: GlobalStyles.red,       };     }     if (plan \=== 'monthly') {       return {         title: 'PLAN MENSUAL',         description:           'Deja mensajes totalmente personalizados que serán enviados tras la confirmación de tu fallecimiento.',         price: '0.99€/mes',         borderColor: GlobalStyles.blue,       };     }     return {       title: 'ESQUELAS DIGITALES',       description:         'Crea y envía cuando quieras esquelas personalizadas para tus seres queridos.',       price: '1.99€/esquela',       borderColor: GlobalStyles.blue,     };   };   const { title, description, price, borderColor } \= getPlanDetails();   return (     \<View style={\[styles.card, { borderColor }\]}\>        \<Text style={styles.title}\>{title}\</Text\>       \<Text style={styles.description}\>{description}\</Text\>       \<Text style={styles.price}\>{price}\</Text\>     \</View\>   ); }; const styles \= StyleSheet.create({   card: {     borderWidth: 2,     padding: 16,     borderRadius: 8,     backgroundColor: GlobalStyles.white,     marginVertical: 10,     alignItems: 'center',   },   title: {     fontSize: 18,     fontFamily: GlobalStyles.fontBold,     color: GlobalStyles.darkGrey,     marginBottom: 8,     textAlign: 'center',   },   description: {     fontSize: 14,     fontFamily: GlobalStyles.font,     color: GlobalStyles.grey,     textAlign: 'center',     marginBottom: 8,   },   price: {     fontSize: 16,     fontFamily: GlobalStyles.fontBold,     color: GlobalStyles.blue,   }, }); export default PlanCard;* |
| :---- |

**Adicional:** Seguí con el Prompt para ir ajustando ciertas cosas ya relacionadas con el estilo en sí, de la lógica me encargué yo

### **Insertar animaciones**

	**Requisito:** Improve frontend with feedback from pilot users

**Aplicación utilizada:** DeepSeek

**Prompt:**

| *¿Cómo puedo hacer que el formulario aparezca con una animación?* |
| :---- |

**Respuesta:**

| *Para agregar una animación al formulario y hacer que aparezca de manera suave y atractiva, puedes utilizar la API de Animated de React Native. Aquí te muestro cómo puedes implementar una animación de desvanecimiento (fade-in) y un ligero desplazamiento hacia arriba para que el formulario aparezca de manera dinámica. Pasos para agregar la animación: Importar Animated desde React Native: javascript Copy import { Animated, Platform, StyleSheet, View } from 'react-native'; Crear un valor animado: Usa useRef para mantener el valor animado y evitar que se reinicie en cada renderizado. Inicializa un valor animado para la opacidad y otro para la posición vertical. Ejecutar la animación cuando el componente se monta: Usa useEffect para iniciar la animación cuando el componente se monta. Aplicar los valores animados al estilo del formulario: Usa transform para mover el formulario y opacity para controlar su visibilidad.* |
| :---- |

**Adicional:** No aplica.

### **Crear nueva vista register**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Haz esta vista reactiva para dispositivos móviles* |
| :---- |

**Respuesta:**

| *{Edición del código añadiendo los estilos responsive}* |
| :---- |

**Adicional:** No aplica.

### **Mejorar estilo de Términos y Condiciones**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Mejora el estilo de esta sección para que esté justificada y remarcando en negrita los títulos* |
| :---- |

**Respuesta:**

| *{Hoja de estilos modificada y títulos en bold}* |
| :---- |

**Adicional:** No aplica.

### **Implementar filtrado y paginación**

**Requisito:** FR-19 Sponsors list view (mejorado gracias al feedback de los usuarios pilotos)

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Tengo la vista y los componentes en el frontend de esta manera {{varios archivos de frontend}}. Quiero mejorar la vista general del listado añadiéndole un filtrado y paginación teniendo en cuenta que se han hecho cambios en el backend y que ahora mismo se encuentra así {{todos los archivos relacionados con las empresas del backend}}.* |
| :---- |

**Respuesta:**

| *{{Código con los cambios a añadir en la pantalla y la explicación de porque añadir esos cambios y que hace cada uno}}* |
| :---- |

**Adicional:** No aplica.

### **Crear nuevo formato de string**

	**Requisito:** No aplica.

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *quiero que el company type, sustituir \_ por un espacio y que sea la primera letra en mayuscula y el resto en minuscula* |
| :---- |

**Respuesta:**

| *Para lograr que los valores de companyType se muestren con \_ reemplazado por un espacio y con la primera letra en mayúscula y el resto en minúscula, puedes usar una función de formato. Esta función puede transformar cada valor antes de renderizarlo en el componente Picker. Solución: Crea una función para formatear los valores de companyType. Usa esta función al mapear los valores en el componente Picker. Código actualizado: const formatCompanyType \= (type: string) \=\> {   return type     .toLowerCase()     .replace(/\_/g, ' ') // Reemplaza "\_" por un espacio     .replace(/\\b\\w/g, (char) \=\> char.toUpperCase()); // Convierte la primera letra de cada palabra a mayúscula }; \<Picker   selectedValue={companyType}   onValueChange={(itemValue) \=\> {     setCompanyType(itemValue);     setPage(0);   }}   style={styles.picker} \>   \<Picker.Item label="Tipo de empresa" value="" /\>   {companyTypes.map((type) \=\> (     \<Picker.Item key={type} label={formatCompanyType(type)} value={type} /\>   ))} \</Picker\>* |
| :---- |

**Adicional:** No aplica.

### **Cambiar estilo de botones**

	**Requisito:** No aplica

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Ajustame el estilo para que se centren los botones: verticalButtonContainer: {   flexDirection: 'column',   gap: 10,   width: '100%',   marginTop: 10, },* |
| :---- |

**Respuesta:**

| *verticalButtonContainer: {   flexDirection: 'column',   gap: 10,   width: '100%',   alignItems: 'center', // 🔥 esto los centra horizontalmente   marginTop: 10, },* |
| :---- |

**Adicional:** [Enlace.](https://chatgpt.com/share/67d2ff58-ed7c-8007-9f9f-ed7d862271a6)

###  	**Limpiar formulario al refrescar**

	**Requisito:** No aplica

**Aplicación utilizada:** GitHub Copilot

**Prompt:**

| *Necesito restablecer el contenido de los formularios de registro cuando se ingrese nuevamente a la vista (por ejemplo, al cerrar sesión y volver a registrarme)* |
| :---- |

**Respuesta:**

| *{Código editado, ya que se hizo con Copilot Edits}* |
| :---- |

**Adicional:** No aplica.

### 	**Mejorar formulario de registro**

	**Requisito:** No aplica

**Aplicación utilizada:** GitHub Copilot

**Prompt:**

| *Quiero que se compruebe que el DNI, el número de télefono y el zip tienen un formato correcto. Por ejemplo, no quiero que el usuario pueda introducir más de 9 dígitos en el campo número de teléfono, ni tampoco introducir caracteres no numéricos.* |
| :---- |

**Respuesta:**

| *{código corregido, ya que se ha hecho uso de Copilot Edits}* |
| :---- |

**Adicional:** No aplica.

### **Obtener información sobre la librería que usada para cargar imágenes**

	**Requisito:** Creación de esquelas/mensajes

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Dame detalles sobre el funcionamiento de la librería expo image picker* |
| :---- |

**Respuesta:**

| *La librería expo-image-picker es un módulo de Expo que permite a los desarrolladores seleccionar imágenes y videos desde la galería del dispositivo o capturar nuevos con la cámara. Es muy útil en aplicaciones de React Native que necesitan subir o manipular imágenes. 🚀 Principales Características Selección de imágenes y videos desde la galería. Captura de fotos y videos con la cámara. Configuración de calidad y tamaño de imagen/video. Permisos de cámara y galería gestionados automáticamente en Expo. Compatible con Managed Workflow de Expo y con apps Ejectadas (bare workflow). 📌 Instalación Si estás usando Expo Managed Workflow: npx expo install expo-image-picker 🎯 Opciones Útiles Cuando llamas a launchImageLibraryAsync o launchCameraAsync, puedes configurar opciones: Propiedad	Descripción mediaTypes	Images (solo imágenes), Videos (solo videos) o All (ambos). allowsEditing	Permite recortar la imagen antes de seleccionarla. aspect	Relación de aspecto del recorte, por ejemplo \[4, 3\]. quality	Calidad de la imagen (0 a 1). base64	Si true, devuelve la imagen en base64. (MENSAJE RECORTADO)* |
| :---- |

**Adicional:** No aplica.

### **Añadir animaciones tras finalizar pago**

	**Requisito:** FR-10 Payment management view

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *en el planCard al cancelar la suscripción quiero que me añadas una ventana con animaciones como el que hay al suscribirse a un plan cuando finalice la cancelación.* |
| :---- |

**Respuesta:**

| *{{PlanCard modificado con animaciones}}* |
| :---- |

**Adicional:** No aplica.

### **Resolver problema al volver a la pantalla anterior**

	**Requisito:** RF-11 (Obituaries)

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Rendered fewer hooks than expected. This may be caused by an accidental early return statement. Explciame porque es este error y como puedo solucionarlo* |
| :---- |

**Respuesta:**

| *El error "Rendered fewer hooks than expected" suele ocurrir cuando el número de hooks llamados dentro de un componente cambia en cada renderizado, lo que no es válido en React. Este comportamiento generalmente ocurre cuando: Un hook se llama condicionalmente: Si llamas a hooks dentro de condicionales (if), su ejecución podría cambiar dependiendo del flujo, lo cual causa que React no pueda predecir de forma confiable cuántos hooks se están utilizando en cada renderizado. Un retorno anticipado en un renderizado: Si dentro del componente se realiza un retorno anticipado (return) en alguna condición, puede haber un renderizado en el que algunos hooks no se ejecutan, lo que también genera el error.* |
| :---- |

**Adicional:** No aplica.

### **Aumentar tamaño de input**

	**Requisito:** FR-12 (messages)

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *Como puedo hacer que el input ocupe mas espacio en pantalla?* |
| :---- |

**Respuesta:**

| *\<CustomTextInput   style={{ width: "75%", height: 120, textAlignVertical: 'top' }}   placeholder="Texto personalizado"   maxLength={20000}   multiline={true}   value={formData.title}   onChangeText={(text) \=\> handleChange("title", text)} /\> Si quieres que además se vea como "textarea" (para escribir varias líneas), verifica si CustomTextInput permite la prop multiline.* |
| :---- |

**Adicional:** No aplica.

### **Realizar navBar customizable**

	**Requisito:** No aplica.

**Aplicación utilizada:** DeepSeek

**Prompt:**

| *Estoy desarrollando una aplicación con React-native y txs, quiero hacer un componente customNavbar para navegar entre las distintas rutas.* |
| :---- |

**Respuesta:**

| *{{Guía para crear un componente CustomNavbar\]}* |
| :---- |

**Adicional:** No aplica.

## 2.4. Otros

### **Recopilar quién responde encuestas de google sin almacenar  su correo**

	**Otro:** Feedback interno.

**Aplicación utilizada:** ChatGPT

**Prompt:**

| *¿Cómo puedo saber quiénes han rellenado un formulario de Google Docs con las respuestas limitadas a 1 y de forma anónima?* |
| :---- |

**Respuesta:**

| *Si el formulario de Google está configurado para recopilar respuestas de forma anónima y con el límite de una respuesta por persona, entonces Google Forms no almacena ni muestra los correos electrónicos de los encuestados. Sin embargo, aquí hay algunas opciones para verificar quién ha respondido: 1\. Revisar la cantidad de respuestas Abre el formulario en Google Forms. Ve a la pestaña "Respuestas". Comprueba cuántas respuestas se han recibido. 2\. Verificar en Google Sheets En la pestaña "Respuestas", haz clic en el icono de "Vincular con Hojas de cálculo de Google". Esto abrirá un Google Sheet con todas las respuestas registradas. Si el formulario no recopila correos electrónicos, las respuestas seguirán siendo anónimas. 3\. Usar el registro de respuestas en Google Forms Si el formulario está restringido a una respuesta por usuario dentro de un dominio de Google Workspace, es posible que en la configuración de respuestas aparezca quién lo ha rellenado. Si es completamente anónimo y no recopilaste correos electrónicos, no hay manera de saber quién ha respondido. Si necesitas identificar a los encuestados en el futuro, puedes: Habilitar la recopilación de correos electrónicos en la configuración del formulario. Pedir a los encuestados que ingresen su nombre o identificador en una pregunta obligatoria. ¿Necesitas ayuda con la configuración del formulario?* |
| :---- |

**Adicional:** No sirvió de mucho porque aunque pregunté más cosas al final resultó que no se podía.

*"AIusage“. Se ha utilizado la IA para recopilar y generalizar las lecciones aprendidas aportadas por todos los miembros. Toda la información generada por IA ha sido revisada por el equipo Caronte.*
