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

El proyecto fue construido utilizando tecnologías web:

- HTML5
- CSS3
- JavaScript
- Canvas API para partículas y efectos
- CSS Animations
- CSS Grid
- CSS Flexbox
- Diseño Responsive

No requiere frameworks como React, Vue o Angular.

## 🌐 GitHub Pages

### Ver el diagrama interactivo

👉 **[🚀 Abrir Spotify UX Galaxy](https://obedguzmanguz.github.io/Practicas_Integradora_230142/Practica06/)**

El enlace permite visualizar directamente el diagrama interactivo publicado mediante GitHub Pages.

## 📂 Estructura

```text
Practica06/
│
├── diagram.html
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