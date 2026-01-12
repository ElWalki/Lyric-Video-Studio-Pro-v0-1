# 🎬 Lyric Video Studio Pro v0.1

<div align="center">

![Lyric Video Studio Pro](https://img.shields.io/badge/version-0.1-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

**Editor profesional de videos con letras sincronizadas** - Crea videos musicales impresionantes con waveforms de audio, efectos de partículas y exportación en alta calidad.

[🚀 Demo en Vivo](#instalación) | [📖 Documentación](#características) | [🐛 Reportar Bug](https://github.com/ElWalki/Lyric-Video-Studio-Pro-v0-1/issues) | [✨ Solicitar Feature](https://github.com/ElWalki/Lyric-Video-Studio-Pro-v0-1/issues)

</div>

---

## ✨ Características Principales

### 🎵 Sistema de Sincronización Avanzado
- **Grabación en tiempo real**: Pulsa `Espacio` mientras escuchas la canción para marcar cada línea
- **Edición manual precisa**: Ajusta tiempos con precisión de milisegundos
- **Timeline profesional DAW-style**: Clips arrastrables, redimensionables y con waveform visual
- **70 líneas simultáneas**: Soporte para letras extensas
- **Detección automática**: El sistema ajusta duraciones basándose en la siguiente línea

### 🎨 Editor Visual Profesional
- **Fuentes personalizables**: 10 fuentes profesionales incluidas (Bebas Neue, Montserrat, Playfair Display, etc.)
- **Control total de estilos**: Tamaño, color, borde, posición vertical
- **Efectos de transición**: Fade in/out suavizados y personalizables
- **Fondo de imagen**: Escala, posición X/Y y efecto de oscurecimiento
- **Preview en tiempo real**: Ve los cambios al instante en el canvas 1920x1080

### 🌊 Waveform de Audio Profesional
- **Peak Waveform estilo DAW**: Visualización de picos mínimos y máximos
- **8000 samples de alta resolución**: Detalle profesional del audio
- **Progreso en tiempo real**: El waveform se ilumina mientras reproduce
- **Interpolación inteligente**: Funciona perfectamente con cualquier nivel de zoom
- **Título sticky**: El nombre del audio siempre visible al desplazarte

### ⚡ Efectos y Partículas
- **6 estilos de partículas**: Nieve, estrellas, círculos, corazones, música y personalizado
- **Audio-reactivas**: Las partículas responden al ritmo de la música
- **Pulsación sincronizada**: Texto que pulsa con el beat del audio
- **Viñeta ajustable**: Oscurece los bordes para enfoque central
- **Control total**: Cantidad, velocidad, tamaño, opacidad

### 📦 Sistema de Proyectos (.PVGW)
- **Guardado completo**: Audio, imagen, letras, tiempos, configuración, waveform
- **Formato JSON**: Archivo `.pvgw` fácil de compartir y editar
- **Autoguardado inteligente**: Sistema silencioso con indicador LED
- **Historial de versiones**: Hasta 20 backups automáticos en IndexedDB
- **Recuperación fácil**: Modal con lista de todas las versiones guardadas

### 🎥 Exportación de Alta Calidad
- **Múltiples resoluciones**: 1080p, 1440p, 4K
- **FPS configurables**: 24, 30, 60 fps
- **Calidad ajustable**: 5-16 Mbps de bitrate
- **Formatos**: WebM (VP9/VP8) y MP4
- **Preview durante exportación**: Ve el progreso en tiempo real
- **Opción de silenciar**: Exporta solo el video sin audio

### ⌨️ Atajos de Teclado
- `Espacio`: Play/Pause
- `Ctrl + Rueda`: Zoom en timeline
- `Click derecho`: Menús contextuales en clips, timeline y preview
- `Escape`: Cerrar modales
- `Del`: Eliminar clip seleccionado

### 🎯 Timeline Profesional
- **Zoom dinámico**: 5-500 px/segundo (Ctrl + Rueda del ratón)
- **Follow Playhead**: Toggle para seguir automáticamente la reproducción
- **Zoom to Fit**: Ajusta toda la canción en la vista
- **Menús contextuales**: Click derecho para editar, copiar, pegar, dividir clips
- **Colores de clips**: 6 colores diferentes (Morado, Azul, Verde, Rojo, Naranja, Rosa)
- **Arrastrar y soltar**: Reposiciona clips fácilmente
- **Resize inteligente**: Bordes arrastrables para ajustar duración

---

## 🖼️ Capturas de Pantalla

### Vista Principal
![Vista Principal](screenshots/Captura%20de%20pantalla%202026-01-12%20010816.png)
*Editor completo con timeline DAW-style, waveform de audio y preview en tiempo real*

### Sistema de Sincronización
![Sincronización](screenshots/Captura%20de%20pantalla%202026-01-12%20013024.png)
*Panel de sincronización con grabación en tiempo real y lista de líneas*

### Historial de Versiones
![Backups](screenshots/Captura%20de%20pantalla%202026-01-12%20013307.png)
*Sistema de autoguardado silencioso con historial de versiones*

---

## 🚀 Instalación

### Opción 1: Uso Directo (Recomendado)
1. Descarga `Lyric Video Studio Pro v0-1.html`
2. Abre el archivo en tu navegador moderno (Chrome, Edge, Firefox)
3. ¡Listo para usar! No requiere instalación ni servidor

### Opción 2: Clonar Repositorio
```bash
git clone https://github.com/ElWalki/Lyric-Video-Studio-Pro-v0-1.git
cd Lyric-Video-Studio-Pro-v0-1
# Abre el archivo HTML en tu navegador
```

### Requisitos
- Navegador moderno (Chrome 90+, Firefox 88+, Edge 90+)
- Mínimo 4GB RAM para exportación 4K
- Espacio en disco para archivos de audio/imagen

---

## 📖 Guía de Uso Rápido

### 1️⃣ Cargar Medios
1. Ve a la pestaña **Media**
2. Carga tu audio (MP3, WAV, OGG)
3. (Opcional) Carga una imagen de fondo
4. El waveform se generará automáticamente

### 2️⃣ Añadir Letras
1. Ve a la pestaña **Letra**
2. Pega tu letra en el área de texto (una línea por verso)
3. Click en **PROCESAR LETRA**

### 3️⃣ Sincronizar
1. Expande **SINCRONIZACIÓN**
2. Click en **GRABANDO... (ESPACIO)**
3. Reproduce el audio y pulsa `Espacio` en cada línea
4. O edita manualmente los tiempos en la lista

### 4️⃣ Personalizar Estilos
1. Pestaña **Estilo**: Configura colores, fuentes, tamaños
2. Pestaña **FX**: Añade partículas y efectos
3. Preview en tiempo real del resultado

### 5️⃣ Exportar
1. Click en **Exportar**
2. Selecciona resolución, FPS y calidad
3. Click en **Iniciar Exportación**
4. Descarga tu video cuando termine

---

## 🎨 Personalización Avanzada

### Colores de Clips
- Click derecho en cualquier clip → **Color del clip**
- 6 colores disponibles para organizar secciones (intro, verso, coro, etc.)

### Efectos de Partículas
- **Nieve**: Efecto invernal suave
- **Estrellas**: Destellos brillantes
- **Círculos**: Burbujas flotantes
- **Corazones**: Romántico y dulce
- **Notas musicales**: Temática musical
- **Personalizado**: Forma configurable

### Audio Reactivity
- Ajusta **Reactividad de audio** para que partículas y texto pulsen más o menos con el beat
- Activa **Pulsación de texto** para efecto de bounce sincronizado

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 Canvas**: Renderizado de video en alta calidad
- **Web Audio API**: Análisis de audio y generación de waveform
- **MediaRecorder API**: Exportación de video WebM/MP4
- **IndexedDB**: Sistema de backups persistente
- **CSS Grid & Flexbox**: Layout responsive moderno
- **Vanilla JavaScript**: Sin dependencias externas

---

## 🔧 Configuración Técnica

### Formato de Proyecto (.PVGW)
```json
{
  "magic": "PVGW",
  "version": "1.0",
  "name": "Mi Proyecto",
  "created": "2026-01-12T...",
  "modified": "2026-01-12T...",
  "settings": { /* Todos los parámetros visuales */ },
  "lyrics": [ /* Letras con tiempos */ ],
  "media": {
    "audioData": "data:audio/...",
    "imageData": "data:image/..."
  },
  "waveform": {
    "peaks": [ /* 8000 samples min/max */ ]
  },
  "timeline": {
    "zoom": 50,
    "followPlayhead": true
  }
}
```

### Sistema de Backups
- Guardado automático cada 60 segundos (si hay cambios)
- Máximo 20 backups (los más antiguos se eliminan automáticamente)
- Backups manuales nunca se eliminan automáticamente
- Almacenamiento local mediante IndexedDB
- Toggle para activar/desactivar autoguardado

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Si quieres mejorar el proyecto:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add: AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

### Ideas para Contribuir
- [ ] Soporte para subtítulos (.srt, .vtt)
- [ ] Más estilos de transición de texto
- [ ] Plantillas pre-diseñadas
- [ ] Exportación en lotes
- [ ] Integración con YouTube/TikTok
- [ ] Modo oscuro/claro
- [ ] Temas de color personalizables

---

## 📝 Roadmap

### v0.2 (Próximamente)
- [ ] Múltiples capas de texto
- [ ] Animaciones de texto avanzadas
- [ ] Soporte para video de fondo
- [ ] Filtros y efectos de imagen
- [ ] Exportación a GIF

### v0.3
- [ ] Colaboración en tiempo real
- [ ] Plantillas de estilos guardadas
- [ ] Integración con bibliotecas de música
- [ ] Editor de waveform interactivo

---

## 🐛 Problemas Conocidos

- En Firefox, la exportación a MP4 puede no funcionar (usa WebM)
- Safari tiene limitaciones con MediaRecorder (recomendado Chrome/Edge)
- Exportación 4K requiere navegador de 64 bits y suficiente RAM

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver archivo `LICENSE` para más detalles.

---

## 👨‍💻 Autor

**Walki-Dev** (también conocido como Walki-bass)

- Instagram: [@walkibassofficial](https://www.instagram.com/walkibassofficial)
- GitHub: [@ElWalki](https://github.com/ElWalki)

---

## 💖 Agradecimientos

Hecho con ❤️ para la comunidad musical.

Si este proyecto te fue útil, considera:
- ⭐ Darle una estrella al repositorio
- 🐛 Reportar bugs o sugerir mejoras
- 📢 Compartirlo con otros creadores de contenido
- ☕ [Invitarme un café](https://ko-fi.com/walkibass) (opcional)

---

<div align="center">

**¿Tienes preguntas o sugerencias?**

[Abrir un Issue](https://github.com/ElWalki/Lyric-Video-Studio-Pro-v0-1/issues) | [Contactar en Instagram](https://www.instagram.com/walkibassofficial)

</div>
