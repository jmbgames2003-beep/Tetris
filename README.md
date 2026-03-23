# 🌿 Pandora Tetris — Na'vi Blocks

Un Tetris temático del universo Avatar con estética bioluminiscente de Pandora.  
Jugable en PC y móvil, **instalable como app** gracias a PWA.

## 🎮 Jugar en línea

`https://jmbgames2003-beep.github.io/Tetris`

---

## 📱 Instalar como app en el móvil

Una vez publicado en GitHub Pages:

**iPhone / iPad (Safari):**
1. Abre el enlace en Safari
2. Toca el botón Compartir (cuadrado con flecha)
3. "Añadir a pantalla de inicio"
4. ¡Aparece el icono de Pandora Tetris!

**Android (Chrome):**
1. Abre el enlace en Chrome
2. Menú ⋮ → "Añadir a pantalla de inicio"
   *(o aparece un banner automático "Instalar app")*
3. ¡Aparece el icono en tu escritorio!

> La app funciona **sin conexión** una vez instalada gracias al Service Worker.

---

## 🚀 Publicar en GitHub Pages

1. Sube todos los archivos a tu repositorio `Tetris`
2. Ve a **Settings → Pages → Source → main / (root)**
3. Guarda — en ~1 minuto el juego está en línea

**Estructura de archivos:**
```
Tetris/
├── index.html       ← El juego completo
├── manifest.json    ← Config PWA (icono, nombre, color)
├── sw.js            ← Service Worker (juego offline)
├── favicon.ico      ← Icono pestaña navegador
├── icons/
│   ├── icon-16.png
│   ├── icon-32.png
│   ├── icon-48.png
│   ├── icon-64.png
│   ├── icon-128.png
│   ├── icon-180.png  ← Apple Touch Icon
│   ├── icon-192.png  ← Android / PWA
│   └── icon-512.png  ← Splash screen PWA
└── README.md
```

---

## ✨ Características del juego

- Temática Avatar / Pandora bioluminiscente
- Dificultad progresiva (acelera cada 10 líneas)
- Puntuación con combos y bonificaciones
- Récords guardados localmente
- Pieza siguiente + Hold
- Ghost piece
- Partículas al limpiar líneas
- Sonidos generados en tiempo real
- Menú de pausa (Continuar / Reiniciar / Menú principal)
- Pantalla completa en móvil, sin scroll
- Controles táctiles: swipe ←→ mover · swipe ↓ bajar · tap rotar · swipe ↑ hard drop

## 🕹️ Controles PC

| Tecla | Acción |
|-------|--------|
| ← → | Mover |
| ↑ / X | Rotar |
| Z | Rotar antihorario |
| ↓ | Caída suave |
| Espacio | Hard drop |
| C | Hold |
| Esc / P | Pausa |

---

*Irayo — Na'vi para "Gracias"* 🌿
