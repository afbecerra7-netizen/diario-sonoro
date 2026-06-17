# Diario Sonoro — Visuales Iris

Visual audio-reactivo (Three.js + GLSL) que arranca con la pista del proyecto **Diario Sonoro**.

## Uso

Sitio estático. Sírvelo por HTTP (el audio requiere contexto seguro: `localhost` o `https`).

- La pantalla de inicio reproduce `a.mp3` y activa el visual al tocarla.
- Controles en pantalla: temas, densidad, formación, pausa, modo domo y pantalla completa.
- Los botones **Mic** / **Audio File** permiten reaccionar a otra fuente de audio.

## Deploy en Vercel

Proyecto estático sin build. En Vercel: *New Project → Import* este repositorio; deja
*Framework Preset* en **Other** y *Output/Root* en la raíz. Vercel sirve `index.html` automáticamente.
