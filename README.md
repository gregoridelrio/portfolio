# Portfolio · Laurea Gregori del Rio

Portfolio profesional orientado a desarrollo web full-stack, diseñado bajo una estética minimalista e ingenieril con foco en claridad, rendimiento y mantenimiento sencillo.

**Demo en producción:** [[https://gregoridelrio.vercel.app](https://laureagregori.vercel.app/)]

## Stack técnico

- **Framework:** [Astro](https://astro.build/)
- **Estilos:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Tipografía:** IBM Plex Sans e IBM Plex Mono
- **Despliegue:** Vercel (integración continua desde `main`)

## Estructura del proyecto

```text
src/
├── assets/          # Recursos optimizados en build
├── components/      # Secciones modulares (Navbar, Hero, Experience, Projects, Skills, Education, Contact)
├── layouts/         # Layout base, metadatos SEO y carga de fuentes
├── pages/           # Punto de entrada principal (index.astro)
└── styles/          # Configuración y tokens de Tailwind CSS
