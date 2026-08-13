# Jaime Ortega Rivas — Portfolio

Portfolio profesional de Jaime Ortega Rivas, Full Stack Developer en Madrid.

Sitio estático de una sola página (HTML + CSS + JS vanilla, sin dependencias ni build step), pensado para desplegarse directamente en GitHub Pages.

## Estructura

```
index.html      Contenido y estructura semántica
css/styles.css  Sistema de diseño (tema oscuro, tokens, layout responsive)
js/main.js      Menú móvil, animaciones de scroll, año dinámico
assets/         Recursos estáticos (foto de perfil pendiente de subir)
```

Tipografías vía Google Fonts (Space Grotesk, Inter, JetBrains Mono) — necesita conexión a internet para cargarlas correctamente.

## Desarrollo local

No requiere build. Basta con abrir `index.html` en el navegador, o servirlo con cualquier servidor estático:

```bash
npx serve .
```

## Pendiente

- Sustituir el placeholder de avatar por la foto de perfil (carpeta `assets/`).
- Desplegar en GitHub Pages (`github.com/jortegarj`).
- Opcional: añadir CV en PDF descargable si se quiere ofrecer esa opción.
