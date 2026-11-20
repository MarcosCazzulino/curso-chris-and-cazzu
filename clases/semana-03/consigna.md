# Semana 3 — Arquitectura Web, HTTP, APIs REST y Asincronía

## Objetivo
Comprender cómo se comunican Cliente y Servidor mediante HTTP, consumir APIs REST reales usando `fetch()`, `async / await` y `try / catch` con respuestas tipadas en TypeScript, e inspeccionar peticiones en la pestaña **Network** de DevTools.

## Diccionario de la Industria
- **DOM (*Document Object Model*)**, árbol de nodos, eventos del navegador y DevTools (*Elements* + *Network*)
- **Single-thread y Event Loop** conceptual (por qué existe la asincronía para no congelar la interfaz)
- Frontend (Cliente) vs. Backend (Servidor)
- Protocolo HTTP (*Request/Response*, verbos `GET`/`POST`, headers, status codes `200`, `400`, `401`, `404`, `500`)
- API y API REST
- Promesas (`Promise<T>`), `async / await`, `try / catch`

## Recursos Permitidos
- [es.javascript.info — Async/await](https://es.javascript.info/async-await)
- [es.javascript.info — Fetch](https://es.javascript.info/fetch)
- [MDN — Códigos de estado HTTP](https://developer.mozilla.org/es/docs/Web/HTTP/Status)

## Consigna (Entregable 3)
Trabajá dentro de `entregas/<tu-usuario-github>/semana-03/`:

1. **Parte 1 (Consola Node.js):** Creá `api-consola.ts` que consuma una API pública (ej. Rick & Morty API o PokéAPI), tipe la respuesta con `interface`, maneje errores con `try / catch` y valide `response.ok`.
2. **Parte 2 (Esqueleto Web con Vite `vanilla-ts`):** Completá el código TypeScript para:
   - Consultar la API pública al cargar y al buscar/filtrar.
   - Mostrar estado de carga (`"Cargando..."`) mientras se resuelve la promesa.
   - Mostrar un mensaje de error claro si falla la red o devuelve `404`/`500`.
   - Renderizar los resultados filtrados en pantalla.

## Cómo entregarla
Seguí los 5 pasos de [`docs/flujo-entregas.md`](../../docs/flujo-entregas.md) en la rama `entrega/semana-03` antes del **jueves a las 23:59**.
