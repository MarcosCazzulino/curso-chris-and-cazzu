# Semana 2 — Funciones Tipadas, Interfaces, Arrays y JSON

## Objetivo
Escribir funciones puras tipadas en TypeScript, modelar datos con `interface` y *union types* modernos (sin `enum`), leer archivos `JSON` reales desde Node.js (`fs.readFileSync` + `JSON.parse`) y dominar `.map()`, `.filter()`, `.find()` y `.forEach()`.

## Diccionario de la Industria
- Estructuras de datos, `interface` y `type` (*union types*, ej. `'pendiente' | 'completado'`)
- **Paso por valor vs. paso por referencia** y mutabilidad vs. inmutabilidad
- `JSON` (*JavaScript Object Notation*) vs. objeto en memoria

## Recursos Permitidos
- [TypeScript Handbook — Object Types](https://www.typescriptlang.org/docs/handbook/2/objects.html)
- [MDN — Métodos de Array](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array)

## Consigna (Entregable 2)
Trabajá dentro de `entregas/<tu-usuario-github>/semana-02/`:

1. Creá (o copiá el archivo provisto en clase) `datos.json` con al menos **30 registros** de productos de un comercio (con `id`, `nombre`, `categoria`, `precio`, `stock`, `activo`).
2. En `index.ts`, definí las interfaces y *union types* correspondientes (`Categoria`, `Producto`) — **sin usar `enum` ni `any`**.
3. Leé `datos.json` usando `fs.readFileSync` y `JSON.parse`.
4. Implementá funciones puras tipadas para:
   - Filtrar productos por categoría y por rango de precio (`.filter()`).
   - Buscar un producto por `id` devolviendo `Producto | undefined` (`.find()`).
   - Devolver un nuevo array con precios actualizados en un porcentaje dado sin mutar el array original (`.map()`).
   - Calcular el valor total del inventario activo y listar productos con bajo stock (`stock <= 5`).

## Cómo entregarla
Seguí los 5 pasos de [`docs/flujo-entregas.md`](../../docs/flujo-entregas.md) en la rama `entrega/semana-02` antes del **jueves a las 23:59**.
