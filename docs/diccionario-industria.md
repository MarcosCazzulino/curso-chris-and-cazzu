# Diccionario Obligatorio de la Industria

Conceptos que debés poder explicar con tus propias palabras en los exámenes orales:

## Web y Red
- **Frontend (Cliente):** Código que corre en el navegador del usuario (React, HTML, CSS, TS).
- **Backend (Servidor):** Código que corre en un servidor privado, valida reglas de negocio, habla con la base de datos y protege secretos.
- **HTTP:** Protocolo de comunicación Request/Response entre cliente y servidor. Verbos principales: `GET`, `POST`, `PUT`/`PATCH`, `DELETE`. Códigos clave: `200` (OK), `201` (Created), `400` (Bad Request), `401` (Unauthorized), `403` (Forbidden), `404` (Not Found), `500` (Server Error).
- **API / API REST:** Interfaz de endpoints HTTP que intercambian datos (generalmente en JSON) siguiendo convenciones estándar.
- **CORS:** Mecanismo de seguridad del navegador que controla qué dominios tienen permiso para consultar un backend.
- **Dominio, DNS (`A` / `CNAME`) y HTTPS/SSL:** El nombre legible de un sitio (`negocio.com.ar`), el sistema que traduce ese nombre a la IP/servidor real, y el cifrado seguro de la conexión.

## Datos y React Moderno
- **TypeScript vs. JavaScript:** TypeScript agrega tipado estático a JavaScript para detectar errores antes de ejecutar el código; al final se transpila a JS para el navegador.
- **JSON:** Formato de texto estándar para intercambiar datos estructurados entre sistemas.
- **CRUD:** Las 4 operaciones básicas sobre datos: *Create, Read, Update, Delete*.
- **SQL vs. NoSQL:** Bases de datos relacionales (tablas con esquemas, `PK`, `FK`, `JOIN`, como PostgreSQL) vs. no relacionales (documentos, clave-valor).
- **Custom Hooks:** Funciones `use...` en React para encapsular y reutilizar lógica de estado o consumo de datos.
- **Server State vs. Client Global State:** Datos remotos cacheados y sincronizados con el servidor (**TanStack Query**) vs. estado global local del navegador (**Zustand**; alternativa histórica: **Redux**).

## Seguridad
- **Autenticación vs. Autorización:** Autenticación = *quién sos* (Login / JWT). Autorización = *qué tenés permiso de hacer* (Roles `admin`/`usuario`, políticas **RLS**).
- **Variables de entorno (`.env`):** Claves y configuraciones sensibles que viven fuera del código y jamás se suben a GitHub (`.gitignore`).

## Producto y Flujo de Trabajo
- **MVP (*Minimum Viable Product*):** Versión mínima funcional y vendible de un producto real.
- **Deploy:** Publicar la aplicación en servidores de producción (`localhost` -> internet).
- **Git, GitHub, Fork y Pull Request:** Control de versiones distribuido y flujo profesional de revisión de código.
