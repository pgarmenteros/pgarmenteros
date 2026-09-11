# 🧬 Patricia García Armenteros — Portafolio

Landing page personal de **Patricia García Armenteros**, bióloga y citogenetista formándose en bioinformática. Construida como página estática de una sola sección, con una identidad visual propia (verdes orgánicos, tipografía serif botánica, una doble hélice ilustrada y animada en canvas) pensada para presentar su trayectoria clínica y su primer proyecto computacional: el TFM del Máster en Bioinformática.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## 🌐 Ver el sitio

Activa GitHub Pages en `Settings → Pages → Deploy from branch (main)` y quedará publicado en `https://pgarmenteros.github.io/<nombre-del-repo>/`. En local, basta con abrir `index.html` en el navegador.

## 📐 Identidad visual

| Elemento | Elección |
|---|---|
| Paleta | Verde bosque (`#1f4b3f`), musgo (`#3e7a5d`), salvia (`#d3e2cf`) sobre fondo papel (`#f3f6f0`), con un acento cálido de arcilla (`#c07d3f`) reservado para el TFM |
| Tipografía | *Fraunces* (serif orgánica) para titulares, *Inter* para el resto del texto |
| Elemento distintivo | Doble hélice dibujada en `<canvas>`, animada suavemente — no decorativa de neón, sino con aspecto de diagrama científico |
| Estructura | Hero → Sobre mí → Formación/Experiencia (dos líneas de tiempo) → Herramientas → Formación complementaria → Proyecto destacado (TFM) → Contacto |

## 📁 Estructura

```
.
├── index.html      # Todo el sitio: HTML + CSS + JS en un único archivo
└── README.md
```

## ✏️ Cómo mantenerlo al día

Todo el contenido vive directamente en `index.html`, en texto plano y fácil de ubicar:

- **Línea de tiempo de formación/experiencia** → sección `id="formacion"`, bloques `.tl-item`
- **Herramientas y skills** → sección `id="herramientas"`, bloques `.pill-row`
- **Proyecto destacado** → sección `id="tfm"`. Cuando tengas nuevos proyectos, puedes duplicar este bloque `.tfm` para añadir uno nuevo debajo.
- **Contacto** → pie de página, `id="contacto"`

## 📄 Licencia

MIT — libre de adaptar.
