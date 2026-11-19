# Semana 7 — React + Supabase, Custom Hooks, TanStack Query y `.env`

## Objetivo
Conectar el frontend de tu MVP a PostgreSQL mediante Supabase usando **Custom Hooks** y **TanStack Query** (`useQuery`, `useMutation`, `invalidateQueries`), protegiendo las credenciales con `.env` y `.gitignore`.

## Diccionario de la Industria
- Variables de entorno (`.env`) y `.gitignore`
- SDK / Cliente de base de datos (`@supabase/supabase-js`)
- *Server State* vs. *Client State*
- Custom Hooks (`use...`), caché e invalidación (`TanStack Query`)

## Recursos Permitidos
- [TanStack Query — Quick Start](https://tanstack.com/query/latest/docs/framework/react/quick-start)
- [Supabase JS Client Docs](https://supabase.com/docs/reference/javascript/introduction)
- [React — Reusing Logic with Custom Hooks](https://es.react.dev/learn/reusing-logic-with-custom-hooks)

## Consigna (Entregable 7)
Sobre tu proyecto en `entregas/<tu-usuario-github>/mvp/`:

1. Configurá `.env` (`VITE_SUPABASE_URL` y `VITE_SUPABASE_ANON_KEY`) y agregá `.env.example` (verificando que `.env` esté ignorado en `.gitignore`).
2. Reemplazá el estado en memoria de la Semana 5 por persistencia real en Supabase (`select`, `insert`, `update`, `delete`).
3. Encapsulá las operaciones en **Custom Hooks** propios usando `useQuery` y `useMutation` (con `invalidateQueries`).
4. Mostrá estados claros de carga (`isPending`) y error (`isError`) en la interfaz.

## Cómo entregarla
Seguí [`docs/flujo-entregas.md`](../../docs/flujo-entregas.md) en la rama `entrega/semana-07` antes del **jueves a las 23:59**.
