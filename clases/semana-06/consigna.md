# Semana 6 — Arquitectura de Bases de Datos Relacionales y SQL Puro (Supabase)

## Objetivo
Diseñar la **arquitectura relacional** de un sistema real (entidades, relaciones `1:N` y `N:M`, normalización básica y reglas de integridad) y plasmarla escribiendo **SQL puro** en el SQL Editor de Supabase (sin usar el editor visual de tablas).

## Diccionario de la Industria
- Base de Datos Relacional (SQL) vs. NoSQL
- **Arquitectura y Modelado Relacional (DER):** entidades, tablas, filas, columnas
- `Primary Key (PK)`, `Foreign Key (FK)` y cardinalidad (`1:N`, `N:M` con tabla intermedia)
- **Normalización básica** (por qué no duplicar datos) y restricciones (`NOT NULL`, `UNIQUE`, `CHECK`)
- Índices básicos, `CRUD` mapeado a SQL (`INSERT`, `SELECT`, `UPDATE`, `DELETE`) y `JOIN`

## Recursos Permitidos
- [SQLBolt — Lecciones 1 a 6](https://sqlbolt.com/)
- [PostgreSQL Tutorial](https://www.postgresqltutorial.com/)

## Consigna (Entregable 6)
Dentro de `entregas/<tu-usuario-github>/mvp/supabase/` (y probado en tu proyecto de Supabase):

1. En `arquitectura.md`, describí brevemente las entidades de tu MVP, sus relaciones (`1:N` o `N:M`) y por qué decidiste separar cada tabla.
2. En `schema.sql`, implementá el modelo relacional con **al menos 2–3 tablas relacionadas** usando `CREATE TABLE`, tipos adecuados, `PRIMARY KEY`, `FOREIGN KEY (REFERENCES)` y restricciones `NOT NULL`, `UNIQUE` y `CHECK`.
3. Agregá al final de `schema.sql` (o en `seed.sql`) un bloque de **datos de prueba** con `INSERT INTO`.
4. Incluí en `consultas.sql` **5 consultas reales de negocio** usando `WHERE`, `ORDER BY` y al menos 2 `INNER JOIN`.

## Cómo entregarla
Seguí [`docs/flujo-entregas.md`](../../docs/flujo-entregas.md) en la rama `entrega/semana-06` antes del **jueves a las 23:59**.
