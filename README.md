# GitHub Pages Deployment Workflow

Este proyecto demuestra cómo configurar un flujo de trabajo de GitHub Actions para desplegar automáticamente una página web estática a GitHub Pages.

## Objetivo

Desplegar el archivo `index.html` a GitHub Pages **solo cuando se modifique**.

## Estructura

- `index.html`: Página web estática
- `.github/workflows/deploy.yml`: Workflow de GitHub Actions
- `README.md`: Documentación del proyecto

## URL del sitio

Una vez desplegado, el sitio estará disponible en:

https://yovidev.github.io/gh-deployment-workflow/

https://roadmap.sh/projects/github-actions-deployment-workflow

## Cómo funciona

Cada vez que se haga un push a la rama `main` que incluya cambios en `index.html`, el workflow se ejecutará y desplegará el contenido a GitHub Pages.

## Stretch goal

Puedes extender este proyecto usando un generador de sitios estáticos como:

- [Jekyll](https://jekyllrb.com/)
- [Hugo](https://gohugo.io/)
- [Astro](https://astro.build/)

Esto te permitirá crear un portafolio más completo y profesional.

## Conceptos aprendidos

- GitHub Actions
- GitHub Pages
- CI/CD (Integración y Despliegue Continuo)

- Automatización de flujos de trabajo
