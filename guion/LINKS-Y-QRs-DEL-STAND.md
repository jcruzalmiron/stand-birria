# LINKS Y QRs DEL STAND

> **Publicado en GitHub Pages.** Todo funciona desde cualquier celular con datos.

## Experiencias QR — URLs activas

```
🎮 SHIP IT!  (arcade · 90 seg)
https://jcruzalmiron.github.io/stand-birria/demos/claude-quest/

✍️ PEDILO BIEN  (wizard · 60 seg)
https://jcruzalmiron.github.io/stand-birria/demos/pedilo-bien/

🗺️ EL MAPA DE CLAUDE  (15 herramientas · 5 min)
https://jcruzalmiron.github.io/stand-birria/demos/mapa-claude/
```

## Pieza secundaria también accesible

```
💸 GASTOS DEL EVENTO  (pieza de mano)
https://jcruzalmiron.github.io/stand-birria/demos/gastos-evento/

📺 PANTALLA DEL TELE  (también se puede mostrar online)
https://jcruzalmiron.github.io/stand-birria/pantalla-principal/

🎨 CARTEL DE INDUSTRIAS  (rotativo para tablet secundaria)
https://jcruzalmiron.github.io/stand-birria/pantalla-principal/industrias.html

📜 CARTA DE DEGUSTACIÓN  (para regenerar QR si hace falta)
https://jcruzalmiron.github.io/stand-birria/pantalla-principal/menu-qr.html
```

## Cómo imprimir el menú con los QR ya cargados

1. Abrir https://jcruzalmiron.github.io/stand-birria/pantalla-principal/menu-qr.html
2. Pegar las 3 URLs en el panel superior:
   - `https://jcruzalmiron.github.io/stand-birria/demos/claude-quest/`
   - `https://jcruzalmiron.github.io/stand-birria/demos/pedilo-bien/`
   - `https://jcruzalmiron.github.io/stand-birria/demos/mapa-claude/`
3. Tocar `💾 Guardar URLs en este navegador` (quedan persistentes).
4. `Ctrl+P` → guardar como PDF de 4 páginas (1 carta + 3 carteles).
5. Imprimir.

## Repo del proyecto

https://github.com/jcruzalmiron/stand-birria

- Cualquier cambio que pushees a `main` se actualiza online en ~1 minuto.
- Para editar localmente: `git pull` → editar → `git push`.

## Material físico del stand

| Pieza | Dónde |
|---|---|
| Carta de degustación A4 | 1 hoja en el mostrador |
| Carteles individuales A4 | 3 hojas (uno por experiencia QR) en distintos puntos |
| Pantalla base del tele | abrir el link de la pantalla del tele en F11 |
| Prompts en vivo | `guion/PROMPTS-DEMO.md` abierto en la notebook |

## Checklist final pre-evento

- [x] SHIP IT! publicado y abre desde celular
- [x] PEDILO BIEN publicado y abre desde celular
- [x] MAPA DE CLAUDE publicado y abre desde celular
- [x] URLs activas en GitHub Pages
- [ ] Carta + 3 carteles impresos
- [ ] Prueba real desde 2 celulares distintos (Android + iPhone)
- [ ] Notebook con `claude.ai` o Claude Code logueado
- [ ] Si se va a mostrar MCP: conectores activos antes del evento
- [ ] Si se va a mostrar Chrome con extensión: extensión instalada y logueada

## Si algo falla en vivo

- **No carga el QR:** verificar conexión del visitante (no hace falta wifi del stand, sus datos móviles alcanzan).
- **GitHub Pages caído (raro):** plan B es servir localmente con `python -m http.server 8080` dentro de la carpeta y hotspot.
- **No hay audio en SHIP IT!:** un toque en pantalla lo desbloquea.
- **Se cuelga:** F5 — todo arranca de cero al instante.
