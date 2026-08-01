# 🌾 Farm 2048

Juego puzzle mobile-first que combina mecánicas de 2048 con cosecha de frutas, power-ups especiales y ranking semanal.

## 🎮 Cómo jugar

- **Desliza** (móvil) o usa **flechas del teclado** para mover los tiles
- **Niveles numéricos**: une tiles del mismo número para duplicarlos. Llega al objetivo (64, 128, 256...)
- **Niveles de cosecha**: une 2 frutas iguales para cosecharlas. Completa la meta de cada fruta

## ⚡ Power-ups

| Power-up | Cómo obtenerlo | Efecto |
|----------|---------------|--------|
| 💣 Bomba | Combo ×3 automático | Explota en cruz eliminando 4 tiles adyacentes |
| ✨ Luz | Combo ×5 automático | Elimina TODOS los tiles del valor que elijas |
| 🌀 Mezclar | 50 monedas | Baraja todos los tiles del tablero |
| ⭐ Wild | Ranking / misión | Coloca un tile comodín del valor más alto |

## 🗺️ Niveles

- **Mundo 1 — La Granja** (niveles 1–5): Introducción numérica y primeras frutas
- **Mundo 2 — El Huerto** (niveles 6–10): Obstáculos 🪨, metas combinadas
- **Mundo 3 — El Mercado** (niveles 11–15): Cosecha mixta, mayor dificultad

## 🏆 Ranking semanal

- Top 10 jugadores por puntos acumulados en la semana
- Reinicia cada lunes a las 00:00
- Premios: 👑 500 monedas · 🥈 300 · 🥉 150 · 🎁 Top 10: 50

## 🚀 Despliegue en GitHub Pages

1. Sube esta carpeta a un repositorio GitHub
2. Ve a **Settings → Pages**
3. En **Source** selecciona `main` branch, carpeta `/` (root)
4. Guarda — en 1-2 minutos el juego estará en `https://TU_USUARIO.github.io/REPO/`

## 📱 Instalar como APK con PWABuilder

1. Despliega en GitHub Pages (ver arriba)
2. Ve a [pwabuilder.com](https://www.pwabuilder.com)
3. Ingresa tu URL de GitHub Pages
4. Selecciona **Android → Generate Package**
5. Descarga el `.aab` listo para Google Play Console

## 📦 Estructura de archivos

```
farm2048/
├── index.html        ← Juego completo (HTML + CSS + JS todo en uno)
├── manifest.json     ← PWA manifest (iconos, nombre, colores)
├── sw.js             ← Service Worker (modo offline)
├── README.md         ← Este archivo
└── icons/
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-192.png   ← Usada como apple-touch-icon
    ├── icon-384.png
    └── icon-512.png   ← Requerida por Play Store
```

## 🛠️ Tecnologías

- HTML5 + CSS3 + JavaScript vanilla (sin dependencias)
- PWA completa (manifest + service worker + offline)
- Google Fonts: Space Grotesk
- localStorage para guardar progreso

## 📝 Licencia

MIT — libre para modificar y distribuir.
