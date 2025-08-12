# Iquique desde el aire

Sitio web promocional para "Iquique desde el aire" con video de fondo y dock de contacto interactivo.

## Características

- **Video de fondo:** Video local con reproducción automática y loop
- **Animaciones GSAP:** Efectos de escritura letra por letra y luminiscencia
- **Dock de contacto:** Botones flotantes con enlaces a redes sociales
- **Diseño responsive:** Optimizado para desktop y móvil
- **Framework:** Tailwind CSS + DaisyUI

## Tecnologías utilizadas

- HTML5
- Tailwind CSS
- DaisyUI
- GSAP (GreenSock Animation Platform)
- Font Awesome Icons

## Enlaces de contacto

- **Facebook:** https://www.facebook.com/iquiquedesdeelaire
- **Instagram:** https://www.instagram.com/iquiquedesdeelaire/
- **Email:** contacto@iquiquedesdeelaire.cl
- **Teléfono:** +56993469261

## 📁 Estructura del Proyecto

```
iqq/
├── index.html          # Página principal
├── video.mp4          # Video de fondo (opcional)
├── README.md          # Documentación
└── .gitignore         # Archivos excluidos de Git
```

## 🎥 Optimización de Video

### Configuración Actual
- **Precarga optimizada**: Solo metadatos inicialmente
- **Indicador de carga**: Spinner visual mientras carga
- **Detección de conexión**: Adapta calidad según velocidad
- **Fallback automático**: Video de respaldo si falla la carga
- **Timeout inteligente**: Oculta loader después de 10 segundos

### Recomendaciones para tu Video
1. **Formato**: MP4 con codec H.264
2. **Resolución**: Máximo 1920x1080 para web
3. **Bitrate**: 2-5 Mbps para balance calidad/velocidad
4. **Duración**: 10-30 segundos en loop
5. **Tamaño**: Máximo 10MB para carga rápida

### Herramientas de Compresión
- **FFmpeg**: `ffmpeg -i input.mp4 -c:v libx264 -crf 28 -c:a aac -b:a 128k output.mp4`
- **HandBrake**: Preset "Web Optimized"
- **Online**: CloudConvert, Compressor.io

## Instalación y uso

1. Clona el repositorio
2. Abre `index.html` en tu navegador
3. El video debe estar en la misma carpeta que el HTML

## Despliegue

Este proyecto está listo para ser desplegado en:
- Netlify
- Vercel
- GitHub Pages
- Cualquier hosting estático

## Notas importantes

- El archivo `video.mp4` debe estar presente para el correcto funcionamiento
- Las animaciones requieren conexión a internet para cargar GSAP desde CDN
- Compatible con navegadores modernos que soporten HTML5 video

---

**Desarrollado para Iquique desde el aire** 🚁