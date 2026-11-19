# Entregas de Alumnos

Cada alumno trabaja exclusivamente dentro de su propia carpeta con su **usuario de GitHub en minúsculas**:

```text
entregas/
└── <tu-usuario-github>/
    ├── clase-00/
    ├── semana-01/
    ├── semana-02/
    ├── semana-03/
    └── mvp/
```

El evaluador automático (`evaluar-pr`) bloqueará cualquier Pull Request que modifique archivos fuera de tu carpeta.

## Enlazar tu MVP desplegado en el Campus
Cuando tengas tu proyecto publicado en Vercel, agregá un archivo `entregas/<tu-usuario-github>/mvp/proyecto.json` con este formato para que aparezca automáticamente en la galería del Campus:

```json
{
  "nombre": "Nombre de tu sistema",
  "url": "https://tu-proyecto.vercel.app"
}
```
