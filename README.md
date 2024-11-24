# Tiktok Video Enhancer

**Tiktok Video Enhancer** es una solución completa para mejorar la calidad de audio y video en archivos multimedia. Este script de Python extrae el audio del video, mejora su calidad eliminando ruido, ajusta el brillo y contraste del video, y luego reintegra el audio mejorado con el video original para producir un resultado de alta calidad.

## Características

- **Reducción de ruido (audio):** Utiliza algoritmos avanzados para eliminar sonidos no deseados del audio.
- **Mejora del audio:** Aplica filtros de paso alto y bajo, normalización y exportación a alta calidad.
- **Mejora del video:** Elimina el ruido visual, escala a 1080p, y ajusta el brillo y contraste.
- **Reintegración:** Combina el audio procesado con el video original sin pérdida de calidad.

## Requisitos

- Python 3.7+
- FFmpeg instalado en tu sistema.
- Bibliotecas de Python:
  - `pydub`
  - `noisereduce`
  - `numpy`

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/audio-video-enhancer.git
   cd audio-video-enhancer
   
2. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   apt-get install ffmpeg

### Uso
Coloca tu archivo de video en la carpeta del proyecto.

Ejecuta el script con las rutas del archivo de entrada y salida:
python enhancer.py

El video mejorado estará disponible en la ubicación especificada.

### Contribuciones
Las contribuciones son bienvenidas. Si tienes ideas para nuevas características o mejoras, no dudes en abrir un issue o enviar un pull request.

