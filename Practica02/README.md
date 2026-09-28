# Práctica 02 · Arquitectura de Plataforma Móvil con Archify

**Valor:** 24 firmas

## Objetivo

Utilizar Codex CLI y Archify para generar un modelo de arquitectura interactivo que represente los componentes de una plataforma móvil y permita comprender cómo se comunican entre sí.

## ¿Qué hace?

Presenta un diagrama con componentes y conexiones en español: aplicación móvil, autenticación, API, bases de datos, mapas, contenedores y control de versiones. El visor incluye búsqueda de componentes, exploración de rutas, zoom, cambio de tema y opciones de exportación.

## ¿Para qué sirve?

Permite identificar las responsabilidades de cada componente, seguir el flujo de inicio de sesión y consulta de datos, y explicar la organización del sistema antes de desarrollarlo. El entregable es un modelo visual de la arquitectura propuesta.

## Tecnologías y herramientas

**Elaboración del diagrama:** Codex CLI y Archify. El resultado utiliza HTML, CSS, JavaScript y SVG para su visualización, y JSON para definir la arquitectura.

**Tecnologías representadas en el modelo:**

| Tecnología | Función dentro de la arquitectura |
| --- | --- |
| ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) | Aplicación móvil del usuario. |
| ![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white) | Autenticación y gestión de identidad. |
| ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) | API REST que conecta la aplicación con los datos. |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) | Almacenamiento relacional y documental. |
| ![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white) | Visualización de mapas. |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white) | Contenedores y organización del entorno local. |
| ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) | Control de versiones y repositorio remoto. |
## Cómo visualizar la práctica

1. Descarga la carpeta `Practica02`.
2. Abre `arquitectura-plataforma-movil.html` en un navegador.
3. Explora los componentes y sus conexiones mediante los controles del visor.

También puedes consultar la [arquitectura interactiva en GitHub Pages](https://obedguzmanguz.github.io/Practicas_Integradora_230142/Practica02/arquitectura-plataforma-movil.html).

## Archivos y evidencias

- [Diagrama interactivo](arquitectura-plataforma-movil.html): visualización de la arquitectura.
- [Modelo JSON](arquitectura-plataforma-movil.json): definición de componentes, conexiones y vistas.
- [Reporte de comprobación](arquitectura-plataforma-movil.visual-check.json): registro de la revisión automatizada del visor.
- [Evidencias de la práctica](Practica02_Evidencias_Codex_Archify.pdf): documento PDF que acompaña el trabajo.
