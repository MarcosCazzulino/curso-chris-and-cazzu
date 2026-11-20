# Semana 9 — Autenticación, Roles (`admin` / `usuario`), RLS y Zustand

## Objetivo
Implementar Registro y Login reales con **Supabase Auth**, diferenciar roles (`admin` vs. `usuario`/`cliente`) tanto en la interfaz como en PostgreSQL mediante **Row Level Security (RLS)**, y manejar estado global de cliente con **Zustand**.

## Diccionario de la Industria
- Autenticación (*quién sos* — Login, sesión, JWT) vs. Autorización (*qué podés hacer* — Roles y permisos)
- `RLS` (*Row Level Security*) y `auth.uid()` en PostgreSQL
- **`localStorage` / `sessionStorage` vs. `Cookies` (`HttpOnly`)** (dónde vive la sesión en el navegador)
- Estado global de cliente (**Zustand** / Redux) vs. estado de servidor (TanStack Query) vs. estado local (`useState`)

## Recursos Permitidos
- [Supabase Docs — Auth & Row Level Security](https://supabase.com/docs/guides/database/postgres/row-level-security)
- [Zustand Docs](https://zustand.docs.pmnd.rs/)

## Consigna (Entregable 9)
Sobre tu proyecto en `entregas/<tu-usuario-github>/mvp/`:

1. Agregá la tabla `perfiles` con columna `rol` (`'admin' | 'usuario'`) vinculada a `auth.users(id)` en `schema.sql`.
2. Habilitá **RLS** y escribí las políticas `CREATE POLICY` en SQL para que cada usuario solo vea/modifique lo permitido y el `admin` gestione el sistema.
3. Implementá Login y Registro con Supabase Auth y guardá el estado de sesión/rol (o carrito/filtros globales) en un store de **Zustand**.
4. Separá claramente la **Vista de Usuario/Cliente** y el **Panel de Administrador**.

## Cómo entregarla
Seguí [`docs/flujo-entregas.md`](../../docs/flujo-entregas.md) en la rama `entrega/semana-09` antes del **jueves a las 23:59**.
