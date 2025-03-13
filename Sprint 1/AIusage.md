![logo_caronte_azul](https://github.com/user-attachments/assets/36631133-4715-4b20-91b8-5f07d96795c2)

# Informe del uso de la IA

# Sprint 1

# Grupo 9

**Realizado por:**

García Rivero, Andrés Francisco

**Revisado por:**

García Escudero, Ángel

# **Índice**

[**1\. Introducción**](#introducción)

[**2\. Aplicación de la IA en el Proyecto**](#aplicación-de-la-ia-en-el-proyecto)

[2.1. Documentación](#2.1.-documentación)

[Mejora de expresión escrita](#mejora-de-expresión-escrita)

[Redactar documentación](#redactar-documentación)

[Obtener los puntos de un plan de gestión de calidad basado en PMBOK](#obtener-los-puntos-de-un-plan-de-gestión-de-calidad-basado-en-pmbok)

[2.2. Backend](#2.2.-backend)

[Como crear un DTO en Spring](#como-crear-un-dto-en-spring)

[Creación del repositorio base de backend](#creación-del-repositorio-base-de-backend)

[Error en la base de datos](#error-en-la-base-de-datos)

[Convertir formato de fecha](#convertir-formato-de-fecha)

[Manejar errores en el controller](#manejar-errores-en-el-controller)

[Encriptar contraseña sólo si es necesario](#encriptar-contraseña-sólo-si-es-necesario)

[2.3. Frontend](#2.3.-frontend)

[Hacer responsiva la landing page](#hacer-responsiva-la-landing-page)

[Creación y edición de esquelas](#creación-y-edición-de-esquelas)

[Refactorizar un componente de react](#refactorizar-un-componente-de-react)

[Cambiar los colores por los colores globales establecidos](#cambiar-los-colores-por-los-colores-globales-establecidos)

[Añadir un desplegable en el navbar para el versionado en la landing page](#añadir-un-desplegable-en-el-navbar-para-el-versionado-en-la-landing-page)

[Mejorar estéticamente la landing page](#mejorar-estéticamente-la-landing-page)

[Estilo dependiendo de la etiqueta](#estilo-dependiendo-de-la-etiqueta)

[2.4. Otros](#2.4.-otros)

# 

 # **1. Introducción** 

Este informe recopila el uso de la Inteligencia Artificial en el desarrollo del proyecto, detallando cómo ha ayudado en distintas tareas de programación y documentación. Se incluyen casos como la generación de código, resolución de problemas, optimización de estilos y cualquier otra aplicación relevante. Además, se documentan los prompts utilizados para tener un registro claro de su impacto y utilidad en el proceso.

# **2. Aplicación de la IA en el Proyecto** 

## 2.1. Documentación

### **Mejora de expresión escrita**

**Documento:** No aplica.

**Aplicación utilizada:** ChatGPT

**Prompt:**

	Mejora la estructura del siguiente fragmento de texto:  {texto}

**Respuesta:**

	{Texto con estructura mejorada}

**Adicional:** Este prompt se ha usado en repetidas ocasiones durante las tareas de documentación.

### **Redactar documentación**

**Documento:** revision.md

**Aplicación utilizada:** ChatGPT

**Prompt:**

	dime como pondrias tu eso no de redactado si no que subpuntos pondrias:### 3.4. Gestión de esquelas
	- **El usuario cliente lista las esquelas personalizadas creadas en la plataforma.**
		- Mockup:
		- Sprint:
	- **El usuario cliente crea una esquela personalizada, introduciendo los datos requeridos.**
	- **El usuario cliente edita una esquela personalizada, modificando su contenido según sea necesario.**
	- **El usuario cliente envía una esquela personalizada, asegurando su entrega a los destinatarios configurados.**
	- **El destinatario recibe la esquela por correo electrónico o SMS.**



**Respuesta:**

	Aquí tienes cómo estructuraría los subpuntos para cada caso de uso en la Gestión de Esquelas, asegurando que toda la información necesaria para la evaluación del software esté clara y organizada:

	3.4. Gestión de Esquelas
	El usuario cliente lista las esquelas personalizadas creadas en la plataforma.

	Mockup: Captura de pantalla de la sección donde se listan las esquelas.
	Sprint: Implementado en el Sprint X (#S1, #S2, etc.).
	Interacción en el software: Página "Mis Esquelas" donde se muestran las esquelas creadas.
	Estado de implementación: ✅ Implementado / 🔄 En progreso / ⏳ Pendiente.
	El usuario cliente crea una esquela personalizada, introduciendo los datos requeridos.

	Mockup: Captura del formulario de creación de esquelas.
	Sprint: Implementado en el Sprint X.
	Interacción en el software: Botón "Crear Esquela" en la sección "Mis Esquelas".
	Datos requeridos: Nombre del difunto, mensaje personalizado, fecha de publicación, destinatarios.
	Estado de implementación: ✅ Implementado.
	El usuario cliente edita una esquela personalizada, modificando su contenido según sea necesario.

	Mockup: Captura de la pantalla de edición de esquelas.
	Sprint: Implementado en el Sprint X.
	Interacción en el software: Opción "Editar" en la vista de una esquela existente.
	Estado de implementación: ✅ Implementado.
	El usuario cliente envía una esquela personalizada, asegurando su entrega a los destinatarios configurados.

	Mockup: Captura del botón de envío en la vista de la esquela.
	Sprint: Implementado en el Sprint X.
	Interacción en el software: Botón "Enviar Esquela" en la vista previa de la esquela.
	Estado de implementación: ✅ Implementado.
	El destinatario recibe la esquela por correo electrónico o SMS.

	Mockup: Ejemplo de correo/SMS recibido con la esquela.
	Sprint: Implementado en el Sprint X.
	Interacción en el software: Mensaje generado y enviado al destinatario a través del sistema de notificaciones.
	Estado de implementación: ✅ Implementado.

**Adicional:** No aplica.

### **Obtener los puntos de un plan de gestión de calidad basado en PMBOK** 

**Documento:** Plan de gestión de calidad

**Aplicación utilizada:** ChatGPT

**Prompt:**

	Dime los puntos que debería incluir este documento (basándonos en el PMBOK)

**Respuesta:**

	Un Plan de Gestión de la Calidad basado en los estándares del PMBOK debería incluir los siguientes puntos clave:

	1. Introducción
	Propósito del documento.
	Alcance de la gestión de la calidad en el proyecto.
	Relación con otros planes del proyecto.
	2. Objetivos de Calidad
	Definición de los estándares de calidad esperados para los servicios de esquelas y mensajes personalizados.
	Alineación con las expectativas del cliente y normativas aplicables.
	3. Roles y Responsabilidades
	Identificación de los responsables de la gestión de la calidad.
	Responsabilidades del equipo en la planificación, ejecución y control de calidad.
	4. Enfoque de Gestión de la Calidad
	Aplicación de los principios de calidad según el PMBOK.
	Integración con otras áreas de gestión del proyecto.
	5. Control y Aseguramiento de la Calidad
	Definición de métricas e indicadores de calidad (KPIs).
	Inspecciones, auditorías y revisiones periódicas del servicio.
	Procesos de validación de mensajes y contenido personalizado.
	6. Mejora Continua
	Estrategias para la optimización del servicio.
	Mecanismos de recolección de feedback de usuarios y clientes.
	Implementación del ciclo PDCA (Plan-Do-Check-Act).
	7. Gestión de No Conformidades
	Procedimientos para identificar y corregir desviaciones de calidad.
	Acciones correctivas y preventivas.
	Registro y seguimiento de incidencias.
	8. Herramientas y Técnicas de Calidad
	Uso de diagramas de causa-efecto, listas de verificación, histogramas, etc.
	Aplicación de metodologías como Six Sigma o Lean, si aplica.
	9. Cumplimiento Normativo y Ético
	Legislación y normativas aplicables a servicios digitales y funerarios.
	Protección de datos personales y confidencialidad de la información.
	10. Cierre y Evaluación de la Calidad
	Criterios de aceptación final del proyecto.
	Lecciones aprendidas y documentación para futuros proyectos.



**Adicional:** Me ayudó a recordar algunos puntos que me faltaban para completar el documento.

## 2.2. Backend

### **Como crear un DTO en Spring**

**Requisito:** No aplica.

**Aplicación utilizada:** ChatGPT

**Prompt:**

	En Spring necesito hacer un listado de todos los usuarios de mi aplicación pero no pasar la contraseña en el endpoint

**Respuesta:**

	Perfecto, te explico cómo hacerlo paso a paso de forma clara.
	✅ Supongamos que tienes una entidad User así:

	@Entity
	public class User {
		@Id
		@GeneratedValue(strategy = GenerationType.IDENTITY)
		private Long id;

		private String username;
		private String email;
		private String password; // ⚠️ NO queremos mostrar esto
	}

	✅ Lo mejor es usar un DTO (Data Transfer Object) para controlar qué campos expones:

	public class UserDTO {
		private Long id;
		private String username;
		private String email;

		// Constructor
		public UserDTO(Long id, String username, String email) {
			this.id = id;
			this.username = username;
			this.email = email;
		}

		// Getters & Setters
	}

	✅ Luego en tu UserService, conviertes los usuarios a DTO:

	@Service
	public class UserService {
		@Autowired
		private UserRepository userRepository;

		public List<UserDTO> getAllUsers() {
			return userRepository.findAll().stream()
					.map(user -> new UserDTO(user.getId(), user.getUsername(), user.getEmail()))
					.collect(Collectors.toList());
		}
	}

	✅ Y en tu UserController haces el endpoint:

	@RestController
	@RequestMapping("/api/users")
	public class UserController {
		@Autowired
		private UserService userService;

		@GetMapping
		public List<UserDTO> getAllUsers() {
			return userService.getAllUsers();
		}
	}

	✅ Resultado:

	Cuando haces una petición GET a /api/users, no se devuelve el campo password, solo id, username y email.



**Adicional:** No aplica.

### **Creación del repositorio base de backend** 

**Requisito:** No aplica.

**Aplicación utilizada:** ChatGPT

**Prompt:**

	Necesito conocer las dependencias de SpringBoot más utilizadas para aplicaciones web. Será necesaria la conexión con una base de datos MySQL, cifrado de contraseñas, API REST.

**Respuesta:**

 [*Enlace*](https://chatgpt.com/share/67d163e7-9008-8010-9999-77802af62435)

**Adicional:** No aplica.

### **Error en la base de datos**

**Requisito:** FR-013

**Aplicación utilizada:** ChatGPT

**Prompt:**

	Hibernate: insert into receiver (email,message_id,name,obituary_id,telephone) values (?,?,?,?,?)
	2025-03-12 12:10:41 [http-nio-8080-exec-2] WARN  o.h.e.jdbc.spi.SqlExceptionHelper - SQL Error: 1062, SQLState: 23000
	2025-03-12 12:10:41 [http-nio-8080-exec-2] ERROR o.h.e.jdbc.spi.SqlExceptionHelper - Duplicate entry '3-123456789' for key 'UKtj119992w0wqs0rnq1pem9ae7' porque sucede este error?


**Respuesta:**

	El error que estás viendo es un "Duplicate entry" de MySQL, lo que significa que estás intentando insertar un valor duplicado en una columna que tiene una restricción de clave única (UNIQUE).

	Explicación del error:
	Código de error 1062: Indica que se está intentando insertar un valor que ya existe en una columna con una restricción UNIQUE.
	Clave 'UKtj119992w0wqs0rnq1pem9ae7': Es el nombre del índice único que está causando el problema.
	Valores conflictivos '3-123456789': Es el dato que está intentando insertarse nuevamente y que ya existe en la tabla receiver.


**Adicional:** Se usó flush para solucionar el problema.

### **Convertir formato de fecha**

**Requisito:** FR-11

**Aplicación utilizada:** ChatGPT

**Prompt:**

	"14/02/2004"
	quiero convertir este formato de fecha en tipo localdate de java

**Respuesta:**

	En Java, puedes convertir la fecha en formato "dd/MM/yyyy" a LocalDate usando la clase DateTimeFormatter. Aquí tienes un ejemplo:

	Código:
	java
	Copiar
	Editar
	import java.time.LocalDate;
	import java.time.format.DateTimeFormatter;

	public class Main {
		public static void main(String[] args) {
			String fechaStr = "14/02/2004";
			DateTimeFormatter formatter = DateTimeFormatter.ofPattern("dd/MM/yyyy");
			LocalDate fecha = LocalDate.parse(fechaStr, formatter);

			System.out.println("Fecha convertida: " + fecha);
		}
	}
	Explicación:
	Definimos la fecha como String en el formato "dd/MM/yyyy".
	Creamos un DateTimeFormatter con ese formato.
	Usamos LocalDate.parse(fechaStr, formatter) para convertir el String a LocalDate.
	Imprimimos el resultado.
	Salida:
	yaml
	Copiar
	Editar
	Fecha convertida: 2004-02-14



**Adicional:** No aplica.

### **Manejar errores en el controller**

**Requisito:** FR-11/ FR-13

**Aplicación utilizada:** ChatGPT

**Prompt:**

	modificame el update para que en el exception handler se recuperen los mensajes de error del dto

**Respuesta:**

	@ExceptionHandler({MethodArgumentNotValidException.class, IllegalArgumentException.class})
	public ResponseEntity<Map<String, String>> handleValidationExceptions(Exception ex) {
		Map<String, String> errors = new HashMap<>();

		// Si la excepción es de validación de argumento (MethodArgumentNotValidException)
		if (ex instanceof MethodArgumentNotValidException) {
			((MethodArgumentNotValidException) ex).getBindingResult().getFieldErrors().forEach(error ->
				errors.put(error.getField(), error.getDefaultMessage())
			);
		} else {
			errors.put("error", ex.getMessage());
		}

		// Devuelve una respuesta de error 400 (Bad Request) con los mensajes de error
		return ResponseEntity.badRequest().body(errors);
	}



**Adicional:** La conversación fue larga pero la parte clave es la mostrada anteriormente

### **Encriptar contraseña sólo si es necesario** 

**Requisito:** No aplica.

**Aplicación utilizada:** GitHub Copilot

**Prompt:**

	if(request.getPassword().equals(customerToUpdate.getPassword())) {
		customerToUpdate.setPassword(customerToUpdate.getPassword());
	} else {
		customerToUpdate.setPassword(this.passwordEncoder.encode(request.getPassword()));
	}

	está bien planteado?

**Respuesta:**

	Si tu intención es evitar re-codificar el mismo password en caso de que no haya cambios, deberías comparar usando el método adecuado del PasswordEncoder. Un ejemplo modificado:

	if(passwordEncoder.matches(request.getPassword(), companyToUpdate.getPassword())) {
		// Se mantiene la contraseña ya codificada
		companyToUpdate.setPassword(companyToUpdate.getPassword());
	} else {
		// Se codifica la nueva contraseña
		companyToUpdate.setPassword(this.passwordEncoder.encode(request.getPassword()));
	}
	return


**Adicional:** No aplica.

## 2.3. Frontend

### **Hacer responsiva la landing page**

**Requisito:** No aplica.

**Aplicación utilizada:** ChatGPT

**Prompt:**

	Estoy trabajando en la landing page de mi proyecto universitario en React. Necesito que me guíes en los pasos para transformar la pantalla home actual a una pantalla reactiva para móviles que se vea correctamente

**Respuesta:**

	¡Claro! Para hacer la landing page responsiva en React, te recomiendo usar CSS con media queries o una biblioteca como Tailwind CSS o styled-components.

	Algunas estrategias que podemos aplicar:

	Flexbox y Grid: Adaptar los layouts usando estas herramientas facilita la creación de estructuras que se ajustan automáticamente al tamaño de pantalla.
	Media Queries: Personalizar estilos según el ancho del dispositivo.
	Unidades relativas: Usa rem, em, % en lugar de px para que las dimensiones se ajusten mejor.
	¿Quieres que revise tu código actual o prefieres que te muestre un ejemplo básico de estructura responsiva en React?


**Adicional:** Principalmente use la recomendación de usar Media Queries para ajustar los estilos según los pixeles de ancho de cada dispositivo

### **Creación y edición de esquelas**

**Requisito:** FR-011 / FR-013

**Aplicación utilizada:** ChatGPT

**Prompt:**

	const authToken = await localStorage.getItem('authToken'); el token devuelto no es el correcto pq me sucede esto?

**Respuesta:**
	
	const authToken = await AsyncStorage.getItem('authToken');

**Adicional:** No aplica.

### **Refactorizar un componente de react** 

**Requisito:** FR-19-Sponsor List

**Aplicación utilizada:** GitHub Copilot

**Prompt:**

	Refactorízame este componente de los sponsor {{código del componente}}

**Respuesta:**

	{código refactorizado al que había que hacerle algún pequeño cambio}


**Adicional:** No aplica.

### **Cambiar los colores por los colores globales establecidos** 

**Requisito:** FR-007-Edit user profiles

**Aplicación utilizada:** GitHub Copilot

**Prompt:**

	Cámbiame los colores de la pantalla a los colores del global styles {{código del componente}} {{pantalla del global styles}}

**Respuesta:**

	{código del componente con los colores actualizados}

**Adicional:** No aplica.

### **Añadir un desplegable en el navbar para el versionado en la landing page** 

**Requisito:** No aplica.

**Aplicación utilizada:** ChatGPT

**Prompt:**

	como añadiria un desplegable en una navbar para que al clikar se despliegue varias secciones en react native?

**Respuesta:**

	{código de ejemplo de navbar con dropdown}

**Adicional:** [Enlace](https://chatgpt.com/share/67d21d49-5470-8002-bc4d-9c7b8700750e).

### **Mejorar estéticamente la landing page** 

**Requisito:** No aplica.

**Aplicación utilizada:** ChatGPT

**Prompt:**

	Quiero mejorar visualmente el landingpage para que se vea esteticamente mejor dame consejos y mejoras que podria aplicar y ejemplos en código teniendo en cuenta que esta realizado el codigo en react

**Respuesta:**

	{código actualizado con mejoras}


**Adicional:** [Enlace](https://chatgpt.com/share/67d224b4-eddc-8002-b3b9-fb375c7d85a1).

### **Estilo dependiendo de la etiqueta**

**Requisito:** No aplica.

**Aplicación utilizada:** GitHub Copilott

**Prompt:**

	if label = name que sea inputCompanyName si no inputCompany



**Respuesta:**

	style={field === 'name' ? styles.inputCompanyName : styles.inputCompany}



**Adicional:** No aplica.

## 2.4. Otros

No aplica.

[image1]: <data:image/png;base64,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>