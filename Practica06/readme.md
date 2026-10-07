# 🎵 Práctica 06 — Diagrama de Secuencia de Pantallas · Spotify

## 🚀 Descripción

Esta práctica consiste en el diseño de un **Diagrama de Secuencia de Pantallas para una aplicación móvil**, utilizando como plataforma elegida **Spotify**.

El proyecto representa de manera interactiva el flujo de navegación de la aplicación mediante **sketches / wireframes**, diferenciando dos roles principales:

- 🎧 **Usuario / Oyente**
- 🎤 **Artista / Creador**

El diagrama cuenta con **19 pantallas únicas**, organizadas en pantallas compartidas y recorridos específicos para cada rol.

## 🌌 Spotify UX Galaxy

La propuesta visual utiliza el concepto **"Spotify UX Galaxy"**, representando las diferentes pantallas como nodos conectados dentro de un mapa de experiencia.

El objetivo es mostrar cómo evoluciona la navegación desde el acceso a la aplicación hasta las funciones de reproducción, organización musical y gestión artística.

## 📱 Estructura del diagrama

### 01 · Pantallas compartidas

Estas pantallas forman parte del recorrido común:

1. Splash / Inicio
2. Inicio de sesión
3. Registro
4. Preferencias musicales
5. Home / Inicio
6. Buscador
7. Resultados de búsqueda
8. Perfil del usuario
9. Biblioteca / Tu biblioteca
10. Reproducción

### 02 · Usuario / Oyente

Flujo orientado a escuchar, descubrir y organizar música:

11. Playlist del usuario
12. Crear nueva playlist
13. Detalle de álbum / canción / artista
14. Cola de reproducción
15. Configuración de cuenta

### 03 · Artista / Creador

Flujo orientado a administrar el perfil artístico, contenido y estadísticas:

16. Perfil del artista
17. Panel de artista
18. Estadísticas / Analytics
19. Gestión de contenido / Lanzamientos

> **Nota:** El rol Artista/Creador se representa mediante funciones del ecosistema de **Spotify for Artists**.

## ✨ Características

El diagrama fue desarrollado como una experiencia web interactiva e incluye:

- 🎨 Diseño inspirado en interfaces modernas de Spotify.
- 📱 Sketches / wireframes representados dentro de smartphones.
- 🔗 Conexiones visuales entre las diferentes pantallas.
- 🟢 Diferenciación de roles mediante colores.
- ✦ Animaciones y efectos de iluminación.
- 🌌 Fondo con efectos visuales y partículas.
- 🧭 Navegación superior entre las diferentes secciones.
- 🗺️ Minimapa interactivo de las 19 pantallas.
- 📊 Indicador de progreso de pantalla.
- 🖱️ Tarjetas interactivas para consultar información.
- 🔍 Ventanas modales con información detallada de cada pantalla.
- ▶️ Modo presentación para recorrer el flujo.
- ◉ Modo interactivo para resaltar conexiones y animaciones.
- 📱 Diseño adaptable para computadora, tablet y móvil.
- ♿ Soporte básico de accesibilidad y reducción de movimiento.

## 🎯 Flujo general

```text
                    SPOTIFY
                       │
                PANTALLAS COMPARTIDAS
                       │
                      HOME
                       │
                ┌──────┴──────┐
                ↓             ↓
        USUARIO / OYENTE   ARTISTA / CREADOR
                │             │
             11 → 12       16 → 17
             → 13 → 14     → 18
             → 15          → 19
```

## 🖥️ Tecnologías utilizadas

El proyecto fue construido utilizando las siguientes tecnologías web:

| Tecnología | Uso en el proyecto |
|---|---|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) | Se utilizó para crear la **estructura y contenido** de las páginas. |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) | Se utilizó para definir los **estilos, colores, tamaños y diseño visual**. |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) | Se utilizó para agregar **interactividad, lógica y comportamiento dinámico**. |
| ![Canvas API](https://img.shields.io/badge/Canvas_API-000000?style=for-the-badge&logo=html5&logoColor=white) | Se utilizó para generar **partículas, efectos visuales y elementos gráficos dinámicos**. |
| ![CSS Animations](https://img.shields.io/badge/CSS_Animations-1572B6?style=for-the-badge&logo=css3&logoColor=white) | Se utilizó para crear **animaciones, transiciones y efectos visuales**. |
| ![CSS Grid](https://img.shields.io/badge/CSS_Grid-1572B6?style=for-the-badge&logo=css3&logoColor=white) | Se utilizó para organizar los elementos mediante **cuadrículas y estructuras responsivas**. |
| ![CSS Flexbox](https://img.shields.io/badge/CSS_Flexbox-1572B6?style=for-the-badge&logo=css3&logoColor=white) | Se utilizó para **alinear y distribuir los elementos** de la interfaz. |
| ![Responsive Design](https://img.shields.io/badge/Responsive_Design-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white) | Se utilizó para adaptar la interfaz a **computadoras, tablets y dispositivos móviles**. |

### 🛠️ Características principales

- ✨ **Interfaz visual y dinámica**
- 🎨 **Diseño moderno mediante CSS3**
- 🌌 **Partículas y efectos mediante Canvas API**
- 🎬 **Animaciones y transiciones**
- 📱 **Diseño completamente responsive**
- 🧩 **Organización mediante Grid y Flexbox**

No requiere frameworks como React, Vue o Angular.

## 🌐 GitHub Pages

### Ver el diagrama interactivo

👉 **[🚀 Abrir Spotify UX Galaxy](https://obedguzmanguz.github.io/Practicas_Integradora_230142/Practica06/)**

El enlace permite visualizar directamente el diagrama interactivo publicado mediante GitHub Pages.

## 📂 Estructura

```text
Practica06/
│
├── index.html
└── README.md
```

## 🎓 Datos de la práctica

**Práctica:** Diagrama de Secuencia de Pantallas (Sketches)

**Plataforma:** Spotify

**Modalidad:** Individual

**Roles:** 2

**Pantallas:** 19

**Tipo:** Aplicación móvil

**Representación:** Sketches / Wireframes

## 👨‍💻 Proyecto

**Spotify UX Galaxy — Diagrama de Secuencia de Pantallas**

Una representación interactiva del flujo de experiencia de usuario de Spotify, mostrando la navegación compartida y las rutas específicas para el Usuario/Oyente y el Artista/Creador.