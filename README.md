# 💼 Personal Portfolio & Professional Showcase

[![Deploy to GitHub Pages](https://github.com/DarienTejedor/portfolio/actions/workflows/deploy.yml/badge.svg)](https://github.com/DarienTejedor/portfolio/actions/workflows/deploy.yml)
![Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20JS-blue)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-green)

Portafolio web profesional desarrollado como una *Landing Page* responsiva, optimizada para ofrecer una navegación ágil sobre mi perfil profesional, stack tecnológico, proyectos principales y vías de contacto.

---

## 🚀 Arquitectura & Características

- **Nivel 1 — Frontend:**
  - Estructura semántica con **HTML5** optimizada para motores de búsqueda (**SEO básico**) y tarjetas de previsualización (**Open Graph**).
  - Estilos modernos en **CSS3** orientados a *Responsive Design*, asegurando adaptabilidad en múltiples dispositivos.
  - Inclusión de animaciones ligeras y favicon personalizado.

- **Nivel 2 — Control de Versiones:**
  - Flujo de trabajo estructurado basado en ramas (`feature/structure`, `feature/cicd-setup`).
  - Historial de commits semánticos y flujo de integración mediante **Pull Requests** hacia `main`.

- **Nivel 3 — CI/CD & Automatización:**
  - Automatización del despliegue continuo mediante **GitHub Actions** (`.github/workflows/deploy.yml`).
  - Publicación automatizada hacia **GitHub Pages** tras cada integración en la rama principal.

---

## 🛠️ Stack Tecnológico

| Componente | Tecnología |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Control de Versiones** | Git, GitHub |
| **CI/CD** | GitHub Actions |
| **Hosting** | GitHub Pages |

---

## ⚙️ Flujo de Despliegue (CI/CD Pipeline)

```text
Git Push (main) ──► GitHub Actions Workflow ──► Build & Validation ──► Deployment ──► GitHub Pages

portfolio/
├── .github/
│   └── workflows/
│       └── deploy.yml      # Workflow de despliegue automático
├── img/                    # Recursos gráficos e imágenes
├── styles/                 # Archivos de estilos CSS
├── index.html              # Landing page principal
└── README.md               # Documentación del proyecto
