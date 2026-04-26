# 🎹 Nordic Baka Theme

![Version](https://img.shields.io/badge/version-1.0.0-86cecb?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-d46a83?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Sway-ffd543?style=for-the-badge)

Un ecosistema visual minimalista basado en la paleta **Nord**, inspirado en el icónico trío **Triple Baka** (Hatsune Miku, Kasane Teto y Akita Neru).

Este ricing está diseñado para ofrecer una experiencia de desarrollo enfocada, silenciosa y estéticamente coherente en entornos Fedora + Sway.

---

## 🎨 La Paleta de Colores

| Personaje | Color | Hex | Uso Principal |
| :--- | :--- | :--- | :--- |
| **Miku** | Cian | `#86cecb` | UI, Lanzadores, Funciones, Conectividad |
| **Teto** | Rojo | `#d46a83` | Foco, Errores, Cadenas de texto, Workspaces activos |
| **Neru** | Amarillo | `#ffd543` | Advertencias, Operadores lógicos, Batería |
| **Nord** | Gris/Azul | `#2e3440` | Fondo base y calma visual |

---

## 🛠️ Componentes del Sistema

### 🔵 VS Code
El corazón del entorno. Configurado para resaltar la lógica de Spring Boot y Flutter.
- **Base:** Tema Nord oficial.
- **Customizations:** Incluidas en el archivo `vscode/settings.json`.
- **Destacado:** Operadores en Amarillo Neru y textos en Rojo Teto.

### 🔴 Waybar & Wofi
Interfaz de usuario para Sway.
- **Waybar:** Workspaces dinámicos (Rojo para el actual, Amarillo para alertas).
- **Wofi:** Lanzador minimalista con bordes redondeados (15px) y selección en Cian Miku.

### 🟡 Micro & Kitty
Herramientas de terminal sincronizadas para una transición sin fricción entre la GUI y la CLI.

---

## 🚀 Instalación

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/nordic-baka-theme.git](https://github.com/tu-usuario/nordic-baka-theme.git)
   cd nordic-baka-theme
