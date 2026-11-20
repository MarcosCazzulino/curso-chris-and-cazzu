# Semana 10 — Backend Propio Seguro (Node.js + Express + TypeScript + JWT)

## Objetivo
Construir un servidor backend propio en **Node.js + Express con TypeScript**, configurando CORS y un middleware de autenticación que valide el `Authorization: Bearer <token>` enviado desde React antes de ejecutar lógica crítica de negocio.

## Diccionario de la Industria
- Backend propio (cuándo y por qué hace falta: secretos, reglas críticas — **"nunca confiar en el cliente"**)
- Validación de límites en servidor y **Rate Limiting** (`HTTP 429`)
- Endpoint, Routing, Middleware, CORS
- `Authorization: Bearer <token>` y validación de JWT

## Recursos Permitidos
- [Express Docs — Routing y Middleware](https://expressjs.com/es/guide/routing.html)

## Consigna (Entregable 10)
Dentro de `entregas/<tu-usuario-github>/mvp/backend/` (o carpeta `server/`):

1. Inicializá un servidor Express con TypeScript (`express`, `cors`, `@supabase/supabase-js`, `@types/express`, `@types/cors`).
2. Creá un **middleware de autenticación** que lea el header `Authorization: Bearer <token>` y verifique el usuario con `supabase.auth.getUser(token)` (devolviendo `401` si falta o es inválido, y `403` si el rol no corresponde).
3. Implementá al menos **1 o 2 endpoints propios** para reglas críticas de tu MVP (ej. validación antisolapamiento de turnos, cálculo de vencimientos, descuento atómico de stock o cierre de caja diario).
4. Consumí esos endpoints desde tu frontend React enviando el token de la sesión activa.

## Cómo entregarla
Seguí [`docs/flujo-entregas.md`](../../docs/flujo-entregas.md) en la rama `entrega/semana-10` antes del **jueves a las 23:59**.
