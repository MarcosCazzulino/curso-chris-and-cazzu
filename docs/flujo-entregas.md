# Cómo Entregar Tareas (Flujo Fork + Pull Request)

Durante el curso nunca subís código directo a `main`. Trabajás en tu **Fork** y enviás cada entrega como un **Pull Request (PR)** antes del **jueves a las 23:59**.

---

## Una sola vez (Clase 0)
1. Entrá al repositorio del curso en GitHub y hacé clic en **Fork** (arriba a la derecha).
2. Cloná **tu fork** en tu computadora:
```bash
git clone https://github.com/<TU-USUARIO>/curso-repo.git
cd curso-repo
```

---

## Todas las semanas (los 5 pasos)

### 1. Actualizá tu repo antes de arrancar
En GitHub (dentro de **tu fork**), hacé clic en **Sync fork → Update branch**. Después, en tu PC:
```bash
git checkout main
git pull origin main
```

### 2. Creá una rama nueva para la semana
```bash
git checkout -b entrega/semana-01
```

### 3. Trabajá SOLO dentro de tu carpeta
Guardá todos tus archivos dentro de:
```text
entregas/<tu-usuario-github>/semana-01/
```
*(Si tocás archivos en `clases/`, `docs/` o la carpeta de un compañero, el evaluador automático bloqueará el PR).*

### 4. Guardá y subí tus cambios a tu fork
```bash
git add .
git commit -m "feat: entrega semana 01"
git push origin entrega/semana-01
```

### 5. Abrí el Pull Request
1. Entrá a tu fork en GitHub y hacé clic en **Compare & pull request**.
2. Completá la plantilla del PR (qué hiciste y declaración honesta de uso de IA).
3. Verificá que el check automático **`evaluar-pr`** quede en verde.
4. En la clase del finde defendés tu código y el instructor mergea el PR.
