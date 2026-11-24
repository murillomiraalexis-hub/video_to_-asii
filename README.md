# # 🎬 Video to ASCII Player

Reproductor de video en la terminal que convierte cualquier archivo multimedia en arte ASCII a color en tiempo real utilizando Python y OpenCV.

## 📋 Requisitos

- Python 3.7 o superior
- Una terminal con soporte para colores ANSI TrueColor (Windows Terminal, iTerm2, GNOME Terminal, VS Code, etc.)

## 🚀 Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com
   cd tu-repositorio
   ```

2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

## 💻 Uso

Ejecuta el script pasando la ruta de tu video:

```bash
python ascii_player.py ruta/de/tu_video.mp4
```

### Opciones adicionales

- **Cambiar el ancho (resolución):**
  ```bash
  python ascii_player.py video.mp4 -c 120
  ```
- **Modo blanco y negro:**
  ```bash
  python ascii_player.py video.mp4 --no-color
  ```

Presiona `Ctrl + C` en cualquier momento para detener la reproducción.
