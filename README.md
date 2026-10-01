# Hola Mundo - Despliegue Automático en la Nube

Este proyecto contiene una página web simple y elegante de tipo **"Hola Mundo"** configurada para desplegarse automáticamente en la nube mediante **GitHub Pages** cada vez que se realizan y envían cambios (`git push`) al repositorio de GitHub.

---

## Enlaces del Proyecto

- **Repositorio de GitHub:** [https://github.com/eduardtejada/hola-mundo-pages](https://github.com/eduardtejada/hola-mundo-pages)
- **Página Web en Vivo (GitHub Pages):** [https://eduardtejada.github.io/hola-mundo-pages/](https://eduardtejada.github.io/hola-mundo-pages/)

---

## Automatización del Despliegue

Cada vez que realizas un cambio en el código y ejecutas:

```bash
git add .
git commit -m "Actualizar contenido"
git push origin main
```

El pipeline de GitHub Actions se activa automáticamente y publica la nueva versión en GitHub Pages.

---
