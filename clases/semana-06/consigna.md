# Semana 6 — Bases de Datos Relacionales y SQL Puro (Supabase)

## Objetivo
Modelar datos relacionales con tablas, claves primarias (`PK`), claves foráneas (`FK`) y relaciones `1:N`, escribiendo **SQL puro** en el SQL Editor de Supabase (sin usar el editor visual de tablas).

## Diccionario de la Industria
- Base de Datos Relacional (SQL) vs. NoSQL
- Tablas, filas, columnas
- `Primary Key (PK)`, `Foreign Key (FK)` y relaciones `1:N`
- `CRUD` mapeado a SQL (`INSERT`, `SELECT`, `UPDATE`, `DELETE`) y `JOIN`

## Recursos Permitidos
- [SQLBolt — Lecciones 1 a 6](https://sqlbolt.com/)
- [PostgreSQL Tutorial](https://www.postgresqltutorial.com/)

## Consigna (Entregable 6)
Dentro de `entregas/<tu-usuario-github>/mvp/supabase/schema.sql` (y probado en tu proyecto de Supabase):

1. Diseñá el modelo relacional de tu MVP con **al menos 2–3 tablas relacionadas (`1:N`)** usando `CREATE TABLE`, tipos adecuados, `PRIMARY KEY`, `FOREIGN KEY (REFERENCES)` y restricciones `NOT NULL` / `CHECK`.
2. Agregá un bloque de **datos de prueba (`seed`)** con `INSERT INTO`.
3. Incluí en `entregas/<tu-usuario-github>/mvp/supabase/consultas.sql` **5 consultas reales de negocio** usando `WHERE`, `ORDER BY` y al menos 2 `INNER JOIN`.

## Cómo entregarla
Seguí [`docs/flujo-entregas.md`](../../docs/flujo-entregas.md) en la rama `entrega/semana-06` antes del **jueves a las 23:59**.
