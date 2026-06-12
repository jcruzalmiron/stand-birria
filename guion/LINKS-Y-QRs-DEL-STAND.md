# LINKS Y QRs DEL STAND

> Completá este archivo cuando las piezas estén publicadas. Es la referencia rápida del día del evento.

## Experiencias QR — URLs publicadas

```
🎮 SHIP IT!
URL:    ___________________________________________
QR PNG: 03-QR-E-IMPRESOS/qr-ship.png

✍️ PEDILO BIEN
URL:    ___________________________________________
QR PNG: 03-QR-E-IMPRESOS/qr-pedi.png

🗺️ EL MAPA DE CLAUDE
URL:    ___________________________________________
QR PNG: 03-QR-E-IMPRESOS/qr-mapa.png
```

## Cómo publicar (5 minutos)

**Opción A — Netlify Drop (recomendada):**
1. Entrá a https://app.netlify.com/drop sin cuenta.
2. Arrastrá la carpeta `stand-birria/`.
3. Te da una URL tipo `https://stand-birria-xxxx.netlify.app/`.
4. Las 3 experiencias quedan en:
   - `.../demos/claude-quest/`
   - `.../demos/pedilo-bien/`
   - `.../demos/mapa-claude/`

**Opción B — Hotspot local (plan B sin internet):**
- En la notebook: `python -m http.server 8080` dentro de `stand-birria/`.
- Hotspot del celular del operador → IP local de la notebook.
- Los QR apuntan a `http://<ip>:8080/demos/...`.

## Material para el evento

| Pieza | Dónde |
|---|---|
| Pantalla base del tele | `pantalla-principal/index.html` (F11) |
| Menú trifold A4 | 1 hoja apoyada en el mostrador |
| Carteles individuales A4 | 3 hojas en distintos puntos del stand |
| Prompts en vivo | `guion/PROMPTS-DEMO.md` abierto en la notebook |
| Mini-apps de apoyo | `demos/negocio-en-vivo/*.html` (peluquería, restaurante, kiosco) |
| Pieza de mano para curiosos | `demos/gastos-evento/index.html` |

## Checklist final

- [ ] SHIP IT! publicado y abre desde celular
- [ ] PEDILO BIEN publicado y abre desde celular
- [ ] MAPA DE CLAUDE publicado y abre desde celular
- [ ] URLs pegadas arriba en este archivo
- [ ] `menu-qr.html` configurado con las URLs reales
- [ ] PDF imprimibles guardados en `03-QR-E-IMPRESOS/`
- [ ] Hojas impresas (4 en total: 1 menú + 3 carteles)
- [ ] Prueba real desde 2 celulares distintos (Android + iPhone)
- [ ] Notebook con `claude.ai` o Claude Code logueado
- [ ] Si se va a mostrar MCP: conectores activos antes del evento
- [ ] Si se va a mostrar Chrome con extensión: extensión instalada y logueada

## Si algo falla en vivo

- **No carga el QR:** plan B con hotspot local, o pasar a la demo en notebook.
- **No hay audio:** un toque en la página lo desbloquea.
- **Se cuelga:** F5 — todo arranca de cero al instante.
