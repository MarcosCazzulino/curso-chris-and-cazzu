# Semana 5 — React + Vite + TypeScript + Tailwind CSS

## Objetivo
Dar el salto a **React** con Vite (`react-ts`) y Tailwind CSS (kit mínimo de clases utilitarias), construyendo componentes reutilizables con `props` tipadas, estado local inmutable (`useState<T>`) y formularios controlados.

## Diccionario de la Industria
- SPA (*Single Page Application*)
- **DOM imperativo vs. React declarativo** (`UI = f(state)`)
- Componentes y `TSX`
- Estado (`useState<T>`) y `Props` tipadas (flujo unidireccional) e inmutabilidad
- **Responsive básico (*mobile-first*)** y contraste/accesibilidad mínima

## Recursos Permitidos
- [es.react.dev/learn — Describir la UI](https://es.react.dev/learn/describing-the-ui)
- [es.react.dev/learn — Agregar interactividad](https://es.react.dev/learn/adding-interactivity)
- [es.react.dev/learn — Usar TypeScript](https://es.react.dev/learn/typescript)

## Consigna (Entregable 5)
Iniciá tu **Proyecto Integrador (MVP)** aprobado en `entregas/<tu-usuario-github>/mvp/`:

1. Inicializá el proyecto con `npm create vite@latest . -- --template react-ts` e instalá Tailwind CSS.
2. Implementá un **CRUD completo en memoria** (usando únicamente `useState`, sin `any` y sin `useEffect` todavía):
   - **Alta** mediante formulario controlado (`value` + `onChange`).
   - **Listado** en componentes separados con `props` tipadas y `key` estable.
   - **Filtro / búsqueda** como estado derivado (sin duplicar arrays en `useState`).
   - **Edición y borrado** de forma inmutable (`.map()` y `.filter()`).

## Cómo entregarla
Seguí [`docs/flujo-entregas.md`](../../docs/flujo-entregas.md) en la rama `entrega/semana-05` antes del **jueves a las 23:59**.
