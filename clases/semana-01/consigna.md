# Semana 1 — TypeScript: Variables, Tipos Primitivos, Condicionales y Bucles

## Objetivo
Dar los primeros pasos en **TypeScript moderno** ejecutado nativamente con Node.js LTS (`node archivo.ts`), dominar variables, tipos primitivos explícitos, condicionales (`if/else`) y bucles (`for`, `while`), y afianzar el flujo de trabajo con **Git y Pull Requests**.

## Diccionario de la Industria
- Código fuente y terminal/consola
- TypeScript vs. JavaScript (tipado estático y transpilación)
- Control de versiones (`Git` vs. `GitHub`), repositorio, rama (*branch*), commit, Fork y Pull Request

## Recursos Permitidos
- [es.javascript.info — Fundamentos de JavaScript](https://es.javascript.info/first-steps)
- [TypeScript Handbook — Everyday Types](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html)

## Consigna (Entregable 1)
Creá dentro de `entregas/<tu-usuario-github>/semana-01/` los siguientes **12 ejercicios cortos** en archivos `.ts` (ejecutables con `node <archivo>.ts`), usando tipos explícitos (`string`, `number`, `boolean`) y **sin usar `any`**:

1. `01-presentacion.ts` — Declarar variables tipadas (`nombre`, `edad`, `ciudad`, `esEstudiante`) e imprimir una presentación formateada.
2. `02-calculadora-basica.ts` — Dados dos números y un operador (`'+' | '-' | '*' | '/'`), calcular y mostrar el resultado controlando división por cero.
3. `03-par-o-impar.ts` — Determinar si un número entero es par, impar y si es positivo, negativo o cero.
4. `04-mayor-de-tres.ts` — Dados tres números, determinar cuál es el mayor (sin usar `Math.max`).
5. `05-descuento-comercio.ts` — Dado el monto de una compra y si el cliente es socio (`boolean`), aplicar 15 % de descuento si supera \$20.000 o 20 % si además es socio.
6. `06-validador-nota.ts` — Dada una nota del 1 al 10, mostrar `"Desaprobado"` (< 7), `"Aprobado"` (7–8) o `"Excelente"` (9–10), validando que esté en rango.
7. `07-tabla-multiplicar.ts` — Imprimir la tabla de multiplicar del 1 al 10 de un número usando un bucle `for`.
8. `08-sumatoria-pares.ts` — Calcular la suma de todos los números pares entre 1 y `N` usando `for`.
9. `09-cuenta-regresiva.ts` — Hacer una cuenta regresiva desde `N` hasta `0` usando `while` y finalizar con `"¡Despegue!"`.
10. `10-factorial.ts` — Calcular el factorial de un número entero no negativo usando un bucle.
11. `11-fizzbuzz.ts` — Imprimir del 1 al 50: `"Fizz"` si es múltiplo de 3, `"Buzz"` si es múltiplo de 5, `"FizzBuzz"` si es múltiplo de ambos, o el número en caso contrario.
12. `12-piedra-papel-tijera.ts` — Simular 3 rondas entre jugador y computadora usando un bucle y mostrar el ganador final.

> **Nota sobre Git:** Subí tus avances en **al menos 3 commits separados** con mensajes descriptivos (ej. `feat: ejercicios 1 a 4 semana 1`).

## Cómo entregarla
1. Actualizá tu fork (`Sync fork` + `git pull origin main`).
2. Creá la rama `entrega/semana-01`.
3. Trabajá solo en `entregas/<tu-usuario-github>/semana-01/`.
4. Abrí el Pull Request antes del **jueves a las 23:59** siguiendo [`docs/flujo-entregas.md`](../../docs/flujo-entregas.md).
