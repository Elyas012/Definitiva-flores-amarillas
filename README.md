# 🌸 Flores — Página Interactiva / Collage

**Proyecto:** `Flores`  
**Autor:** Elías Jácome (`Elyaz`)  
**Descripción breve:**  
Una página web ligera y responsiva con un collage de imágenes de fondo, animaciones de texto y un botón atractivo. Pensada como una tarjeta interactiva para celebrar y transmitir un mensaje especial (ej.: *FELIZ 21 DE SEPTIEMBRE PRINCESA*).

---

## ✨ Características principales
- Collage de imágenes como fondo (capas posicionadas y mezcladas).
- Texto principal con efecto *glow* (animado por letra).
- Botón con gradiente y efectos táctiles (hover/active).
- Diseño responsive: adaptado a escritorio, tablet y móviles.
- Overlay sutil para asegurar legibilidad del contenido.
- Créditos siempre visibles en la esquina inferior izquierda.
- Fácil de personalizar: cambiar imágenes, mensajes o estilos en CSS.

---

## 🗂 Estructura del proyecto
Definitiva flores amarilla/
├─ css/
│ └─ style.css
├─ img/
│ ├─ 1.png
│ ├─ 2.png
│ └─ ... (tus imágenes del collage)
├─ flower.html
├─ index.html
├─ main.js
├─ sound/ (si usas audio)
└─ README.md

---

## 🚀 Cómo ejecutar (local)
1. Clona o descarga el repositorio.
2. Abre `index.html` (o `flower.html`) en tu navegador favorito.  
   - O, si usas VSCode, instala la extensión **Live Server** y haz clic en *Go Live* para ver cambios en caliente.
3. ¡Listo! La página debería verse con el collage y los efectos.

---

## 🛠 Personalizar el collage y el contenido
- **Imágenes:** coloca tus imágenes en la carpeta `img/` y renómbralas (ej.: `c1.jpg`, `c2.jpg`, …) o actualiza los `src` de los `<img class="c1" ...>` en el HTML.
- **Posición / rotación / tamaño:** edita las clases `.c1`, `.c2`, … en `css/style.css`. Ejemplo:
  ```css
  .c1 { top: -6%; left: -6%; width: 44vw; transform: rotate(-8deg); }

