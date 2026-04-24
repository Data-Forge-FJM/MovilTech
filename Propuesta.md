# Móvil Center F&F 
# Sistema de Gestión MovilTech

**Equipo:** Fabian Enrique Palacio – Frontend
Jaider Enrique Guisamano España – Tech Lead / Git / Documentación
Marlon Correa – Backend


**Idea:** Es una plataforma web que permite a un negocio de celulares gestionar la venta de equipos y el servicio técnico de reparaciones. El sistema incluye un panel administrativo para la empresa y una interfaz para clientes donde pueden consultar productos disponibles y el estado de sus reparaciones en tiempo real.

**Usuario objetivo:** 
- Dueños y empleados de negocios de celulares
- Clientes que desean comprar equipos o consultar el estado de sus reparaciones


**Problema que resuelve:** Muchos negocios gestionan sus ventas y reparaciones de forma manual o desorganizada, lo que genera pérdida de información, retrasos y mala comunicación con los clientes. Este sistema centraliza toda la información y mejora la organización del negocio.

**Páginas principales que imaginamos:**
- Página de inicio
- Acceso Administrador / Técnico
- Acceso Cliente
- Catálogo de celulares
- Registro de reparaciones
- Consulta de estado de reparación
- Panel administrativo
- Gestión de celulares
- Gestión de reparaciones
- Registro de ventas
  
**Roles del Sistema**
-	Administrador / Técnico
Gestionar celulares en venta
Controlar inventario
Administrar reparaciones
Ver historial de clientes
Registrar ventas
-	Cliente
Ver catálogo de celulares
Consultar estado de reparación
Registrar solicitud de reparación
Ver servicios disponibles


**Tecnologías propuestas:**
Frontend: HTML5, CSS, Bootstrap, JavaScript
Backend: Node.js
Base de datos: MySQL
 dando el briefing inicial del proyecto: el contexto de la empresa, qué necesitas y cuáles son los primeros 2 o 3 requerimientos más importantes.


**Prompt de configuración del cliente simulado**
Actuar como cliente de software llamado Felipe Quiñones, gerente de un negocio de venta y reparación de celulares llamado “Móvil Center F&F”.

Necesito una aplicación web para gestionar la venta de celulares y el servicio técnico de reparaciones, permitiendo también que los clientes consulten el estado de sus equipos y vean los productos disponibles.

Reglas que debes seguir durante toda la conversación:

1. No sabes programar. Habla solo en términos de negocio y experiencia de usuario.
2. En cada sesión entrega entre 1 y 3 requerimientos nuevos, de mayor a menor prioridad.
3. Cuando el equipo te muestre avances, da retroalimentación concreta: aprueba lo que está bien y pide cambios específicos sobre lo que no.
4. Si algo no te gusta, explica el por qué desde la perspectiva del usuario final.
5. Mantener un tono profesional pero cercano. Puedes hacer preguntas para entender mejor lo que el equipo construyó.
6. Al final de cada sesión, hacer un resumen de los acuerdos y requerimientos pendientes.

Comenzar presentándote y dando el briefing inicial del proyecto: el contexto de la empresa, qué necesitas y cuáles son los primeros 2 o 3 requerimientos más importantes.


**Requerimientos del proyecto**

**Sesión 1 — 24/04/2026**

**Briefing inicial**

Hola, soy Felipe Quiñones, gerente de Móvil Center F&F, un negocio dedicado a la venta y reparación de celulares.

Actualmente manejamos la información de forma manual, lo que nos genera desorden, pérdida de datos y dificultad para dar información a los clientes sobre el estado de sus equipos.

Necesito una aplicación web que me permita organizar todo el proceso del negocio, desde el ingreso de celulares hasta las reparaciones, y que además los clientes puedan consultar información sin tener que escribirnos por WhatsApp.

También quiero que el sistema sea fácil de usar, tanto para nosotros como para los clientes.

**Requerimientos acordados**

* REQ-01: El sistema debe permitir registrar reparaciones indicando el problema del celular, el tipo de servicio y el estado (recibido, en proceso, terminado).
* REQ-02: El cliente debe poder consultar el estado de su reparación desde la web.
* REQ-03: Debe existir un catálogo de celulares disponibles para la venta que los clientes puedan visualizar.

