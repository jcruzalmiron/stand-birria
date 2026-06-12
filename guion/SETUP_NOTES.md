# SETUP NOTES

## Estado actual

El stand está pensado para operar con:

- 1 tele (pantalla-principal/index.html como base, demos puntuales cuando convenga).
- 1 notebook (Claude abierto + `PROMPTS-DEMO.md` para demos en vivo).
- Material impreso (menú trifold + 3 carteles individuales, ver `menu-qr.html`).
- Celular del visitante (escaneo de QR).

## Decisiones tomadas

- La experiencia principal no depende de "muchas demos espectaculares" sino de tres capas:
  - **Wow** (SHIP IT!) — atrae y deja una idea.
  - **Utilidad** (PEDILO BIEN) — la persona se lleva algo usable.
  - **Conocimiento** (EL MAPA DE CLAUDE) — entiende el ecosistema.
- La documentación se dejó general para el equipo, no personalizada para una sola persona.
- El menú con QR funciona como puerta de entrada autónoma: la gente puede arrancar sin depender del operador.
- El rol del operador es **guiar** (detectar interés → llevar a una sola pieza fuerte), no recitar.

## Rutas clave

| Archivo | Para qué |
|---|---|
| `README.md` | Visión general y operación |
| `guion/GUION.md` | Flujo de conversación de 5 y 15 min |
| `guion/GUIA-OPERATIVA.md` | Cómo operar sin sobreexplicar |
| `guion/PROMPTS-DEMO.md` | Prompts listos para demos en vivo |
| `guion/PACK-DRIVE.md` | Cómo armar el paquete compartible |
| `guion/LINKS-Y-QRs-DEL-STAND.md` | URLs publicadas + checklist |
| `pantalla-principal/menu-qr.html` | Genera e imprime menú + carteles |

## Huecos pendientes (los únicos)

1. Publicar las 3 experiencias QR (`claude-quest`, `pedilo-bien`, `mapa-claude`) — Netlify Drop o GitHub Pages.
2. Pegar las URLs en `menu-qr.html` (panel superior) → imprimir las 4 hojas.
3. Probar el flujo completo desde 2 celulares reales (Android + iPhone).
4. Si vas a mostrar MCP o Chrome con extensión: dejar logueado y conectado **antes** del evento.

## Siguiente paso recomendado

Publicar las 3 experiencias QR, completar el menú con las URLs, imprimir y hacer una pasada de prueba con alguien que no conozca el stand. Si entiende qué hacer sin que le expliques, el stand está listo.
