# PACK PARA DRIVE

## Objetivo

Subir un paquete que permita montar el stand sin depender del historial del chat ni de una sola persona. Tiene que servir para cualquiera del equipo.

## Estructura recomendada

```
3-DEGUSTACION-BIRRIA-STAND/
├── 01-STAND-BIRRIA/        ← carpeta completa del proyecto
│   └── stand-birria/
├── 02-GUIAS/                ← copias de los .md clave (para abrir en Drive)
│   ├── README.md
│   ├── GUION.md
│   ├── GUIA-OPERATIVA.md
│   ├── PROMPTS-DEMO.md
│   ├── PACK-DRIVE.md
│   └── SETUP_NOTES.md
├── 03-QR-E-IMPRESOS/        ← lo que se imprime
│   ├── menu-trifold.pdf     ← exportado desde menu-qr.html
│   ├── cartel-ship-it.pdf
│   ├── cartel-pedilo-bien.pdf
│   └── cartel-mapa.pdf
└── 04-URLS-PUBLICADAS/
    └── LINKS-Y-QRs-DEL-STAND.md  ← URLs reales + capturas de QR
```

## Cómo generar los PDFs imprimibles

1. Abrir `stand-birria/pantalla-principal/menu-qr.html` en Chrome.
2. Pegar las 3 URLs publicadas en el panel superior.
3. Tocar `💾 Guardar URLs en este navegador`.
4. `Ctrl+P` → "Guardar como PDF" → 4 páginas (1 menú + 3 carteles).
5. Subir el PDF a `03-QR-E-IMPRESOS/`.

## Checklist antes de compartir el pack

- [ ] Las 3 URLs abren desde celular (probado en Android y iPhone).
- [ ] Está claro cuál es la pantalla base del tele.
- [ ] `PROMPTS-DEMO.md` se ubica en segundos.
- [ ] `GUIA-OPERATIVA.md` se entiende sin contexto extra.
- [ ] Hay plan B documentado si falla internet o un QR.
- [ ] Los PDFs imprimibles están en la carpeta.

## Mensaje sugerido al compartir

```
Subí todo a Drive.
Para ubicarse rápido: abrir README + GUIA-OPERATIVA.
En el tele va pantalla-principal/index.html.
En la notebook conviene dejar Claude abierto + PROMPTS-DEMO.md.
Los impresos salen de menu-qr.html (ya generé los PDF en 03-).
Regla: a cada persona, UNA demo bien elegida. No mostrar todo.
```
