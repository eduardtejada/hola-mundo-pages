# 🌐 Hola Mundo - Despliegue Automático en la Nube

Este proyecto contiene una página web simple y elegante de tipo **"Hola Mundo"** configurada para desplegarse automáticamente en la nube (mediante **GitHub Pages** o **Cloudflare Pages**) cada vez que se realizan y envían cambios (`git push`) al repositorio de GitHub.

---

## 🚀 Características

- **Diseño Moderno:** Interfaz estilizada con efectos de desenfoque de fondo (glassmorphism), modo oscuro, fuentes modernas y tipografía responsiva.
- **CI/CD Integrado:** Flujo de trabajo de GitHub Actions (`.github/workflows/deploy.yml`) para despliegue continuo automático.
- **Hosting en la Nube:** Alojamiento gratuito, ultrarrápido y seguro con certificado SSL (HTTPS).

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & CSS3 moderno**
- **JavaScript (Vanilla)**
- **GitHub Actions & GitHub Pages** (o Cloudflare Pages)

---

## 🔄 Automatización del Despliegue

Cada vez que haces un cambio en el código y ejecutas:

```bash
git add .
git commit -m "Actualizar contenido"
git push origin main
```

El pipeline de GitHub Actions se activa automáticamente, empaqueta el contenido estático y publica la nueva versión en GitHub Pages en menos de 1 minuto.

---

## 📄 Licencia

MIT
