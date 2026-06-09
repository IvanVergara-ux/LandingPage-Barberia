# BLVCK CUTS — Landing Page

Sitio web de una página para barbería premium. Diseño oscuro y moderno con animaciones de scroll, formulario de reservas y secciones optimizadas para conversión.

**Demo en vivo:** [Ver sitio](https://ivanvergara-ux.github.io/LandingPage-Barberia/)

---

## Vista previa

> Agrega una captura de pantalla aquí: `assets/preview.png`

---

## Tecnologías

- HTML5 semántico
- CSS3 — variables, grid, flexbox, animaciones
- JavaScript vanilla — Intersection Observer API
- Google Fonts — Bebas Neue, DM Serif Display, Inter
- Sin frameworks, sin dependencias externas

---

## Características

- Diseño completamente responsivo (móvil, tablet, escritorio)
- Animaciones de aparición al hacer scroll con `IntersectionObserver`
- Navbar fija con efecto `backdrop-filter: blur`
- Sección hero con estadísticas y tipografía display
- Grilla de servicios con precios y efecto hover
- Galería interactiva con overlay
- Sección de testimonios
- Formulario de reserva de citas con selección de servicio, fecha y hora
- Respeta `prefers-reduced-motion` para accesibilidad

---

## Estructura

```
landing-barberia-blvck/
├── index.html       # Página principal (HTML + CSS + JS)
├── README.md        # Este archivo
└── assets/
    └── preview.png  # Captura de pantalla del proyecto
```

---

## Cómo ejecutar localmente

No requiere instalación ni servidor. Abre directamente en el navegador:

```bash
git clone https://github.com/IvanVergara-ux/landing-barberia-blvck.git
cd landing-barberia-blvck
# Abre index.html en tu navegador
```

O con Live Server en VS Code:
1. Instala la extensión Live Server
2. Clic derecho en `index.html` → Open with Live Server

---

## Despliegue en GitHub Pages

1. Ve a **Settings** → **Pages**
2. En Source selecciona **Deploy from a branch**
3. Selecciona la rama `main` y carpeta `/ (root)`
4. Guarda — en 1-2 minutos el sitio estará en vivo

---

## Decisiones de diseño

**Paleta:** Negro profundo `#0a0a0a` como base con dorado `#c9a84c` como acento único. Evita el contraste blanco puro para no fatigar en pantallas oscuras.

**Tipografía:** Bebas Neue para los titulares de impacto, DM Serif Display en itálica para el contraste editorial, Inter para el cuerpo. Tres familias con roles distintos y personalidad clara.

**Animaciones:** Solo `IntersectionObserver` para revelar secciones al hacer scroll. Sin librerías externas, sin animaciones innecesarias.

**Sin frameworks:** El proyecto es intencionalmente vanilla para demostrar dominio del lenguaje base sin depender de herramientas.

---

## Autor

**Iván David Vergara Mercado**  
Full Stack Developer — Ingeniería de Software  
[GitHub](https://github.com/IvanVergara-ux) · [Workana](https://workana.com) · ivandavidvergaram@gmail.com
