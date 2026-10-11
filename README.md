# Repasos de sexto

Repasos interactivos para la Prueba Nacional Estandarizada de sexto año (Costa Rica).
Cada tema es una página estática donde el mapa conceptual se descubre pieza por pieza, con
preguntas para pensar y práctica al estilo de la prueba.

## Estructura

```
index.html              portada con la lista de materias
estudios-sociales/      una carpeta por materia
  index.html            portada de la materia (ruta de temas)
  tNN-<tema>.html       un repaso por tema
```

## Agregar una materia

1. Crear la carpeta `<materia>/` con sus páginas `tNN-*.html` y su `index.html`.
2. Agregar una entrada al bloque `materias` de `index.html`.

Las páginas se generan con el skill `concept-map-story` (plantilla, validación y portada por materia).

## Aviso

Material de estudio independiente; no es una publicación oficial del Ministerio de Educación
Pública. Las preguntas marcadas como «Práctica oficial MEP» provienen de su material público de práctica.
