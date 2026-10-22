# 🔥 FirePlay Launcher 3.0

**Launcher de juegos local, moderno y multi-perfil**  
Gestiona tu biblioteca de juegos con una interfaz limpia, temas personalizables, música de fondo y efectos de sonido.

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## ✨ Características

- 🎮 **Biblioteca de juegos** — Añade ejecutables, edita información, cambia portadas y organiza con etiquetas
- 👤 **Multi-perfil** — Varios usuarios independientes con su propia biblioteca y favoritos
- 🎨 **5 Temas visuales** — Violet Night, Ocean Deep, Ember, Forest y Midnight
- 🎵 **Audio integrado** — Música de fondo + efectos de sonido (click, hover, lanzar)
- ⭐ **Favoritos y recientes** — Acceso rápido a tus juegos preferidos y los últimos jugados
- 🔍 **Búsqueda y filtros** — Busca por nombre, autor o etiqueta. Ordena por diferentes criterios
- 🃏 **Tarjetas modernas** — Diseño con bordes redondeados, sombras y animaciones de hover
- 🎛 **Detección de mando** — Detecta automáticamente si usas teclado o gamepad
- 💾 **Datos locales** — Todo se guarda en JSON. Sin necesidad de internet ni cuentas
- 🛠 **Backups** — Crea copias de seguridad de tu biblioteca fácilmente

---

## 📸 Capturas de pantalla

> Añade aquí capturas de tu launcher

---

## 🚀 Instalación

### Requisitos
- Python 3.10 o superior
- Windows, Linux o macOS

### Pasos

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/fireplay-launcher.git
cd fireplay-launcher
```

2. (Opcional pero recomendado) Instala las dependencias:
```bash
pip install pillow pygame
```

3. Ejecuta el launcher:
```bash
python launcher.py
```

> **Nota:**  
> - `Pillow` → necesario para las portadas y tarjetas redondeadas  
> - `pygame` → necesario para la música y efectos de sonido  

---

## 📂 Estructura de datos

Todo se guarda en la carpeta del usuario:

```
~/.fireplay_launcher/
├── data/
│   ├── users/          # Perfiles de usuario
│   ├── games/          # Información de los juegos
│   ├── covers/         # Portadas
│   ├── avatars/        # Avatares de perfil
│   ├── music/          # Música de fondo (.mp3, .ogg, .wav)
│   ├── sounds/         # Efectos de sonido
│   ├── backups/        # Copias de seguridad
│   └── settings.json   # Configuración
```

---

## ⌨️ Atajos de teclado

| Atajo       | Acción                |
|-------------|-----------------------|
| `Ctrl + F`  | Buscar                |
| `Ctrl + N`  | Añadir juego          |
| `Ctrl + ,`  | Abrir configuración   |
| `F5`        | Recargar biblioteca   |
| `Esc`       | Limpiar búsqueda      |

---

## 🛠 Uso básico

1. Pulsa **＋ Añadir juego** y selecciona el ejecutable
2. (Opcional) Clic derecho en la tarjeta → Cambiar portada / Editar / Etiquetas
3. Usa las secciones de la izquierda para filtrar (Biblioteca, Favoritos, Recientes...)
4. Personaliza el tema y el audio desde **Configuración**

---

## 🎨 Temas incluidos

- **Violet Night** (predeterminado)
- **Ocean Deep**
- **Ember**
- **Forest**
- **Midnight**

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente.

---

## 🙏 Créditos

Desarrollado con ❤️ usando Python, Tkinter, Pillow y Pygame.
