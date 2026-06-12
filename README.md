# Stand "3° Degustación Birria" — Manual de operación

**Concepto:** *Mientras el resto conversa, Claude construye.*
**Estructura:** tres capas.

- **Wow** (SHIP IT!) — atrae en 90 segundos y deja una idea del stack.
- **Utilidad** (PEDILO BIEN) — la persona se lleva su pedido profesional listo para usar.
- **Conocimiento** (EL MAPA DE CLAUDE) — explora 15 herramientas del ecosistema para entender qué más hay además del chat.

Todo es HTML autocontenido: funciona sin internet y se abre con doble clic en Chrome. Los QR necesitan una URL pública o una red local.

## Escenario recomendado: 1 notebook + 1 tele

Ese es el montaje principal pensado hoy.

- **Tele:** pantalla base del stand y apoyo visual para la conversación.
- **Notebook:** demos en vivo en Claude y cambio rápido entre piezas locales.
- **Celular del visitante:** entrada autónoma a experiencias con QR.
- **Material impreso:** menú QR para orientar sin depender tanto de quien atiende.

## Piezas principales

| Pieza | Archivo | Rol |
|---|---|---|
| **SHIP IT!** | `demos/claude-quest/index.html` | Pieza rápida de atracción para celular. |
| **PEDILO BIEN** | `demos/pedilo-bien/index.html` | Genera un pedido profesional para Claude a partir del caso de la persona. |
| **EL MAPA DE CLAUDE** | `demos/mapa-claude/index.html` | Explica herramientas y conceptos del ecosistema. |
| **Pantalla principal** | `pantalla-principal/index.html` | Pantalla base del tele. |
| **Menú QR imprimible** | `pantalla-principal/menu-qr.html` | Hoja o cartel para guiar escaneos por interés. |
| **Mini-apps de negocio** | `demos/negocio-en-vivo/*.html` | Apoyo para mostrar criterio por rubro. |
| **Gastos del evento** | `demos/gastos-evento/index.html` | Demo simple para conversación informal. |
| **Guion general** | `guion/GUION.md` | Flujo de conversación y argumentos. |
| **Prompts de demo** | `guion/PROMPTS-DEMO.md` | Prompts listos para artifacts, skills, agents, MCP y Chrome. |
| **Guía operativa** | `guion/GUIA-OPERATIVA.md` | Cómo operar el stand sin sobreexplicar. |
| **Pack para Drive** | `guion/PACK-DRIVE.md` | Qué compartir y cómo ordenarlo. |
| **Notas de setup** | `guion/SETUP_NOTES.md` | Estado actual, huecos y próximo paso. |

## Qué abrir en cada dispositivo

### Tele

- Base permanente: `pantalla-principal/index.html`
- Cambios puntuales cuando convenga:
  - `demos/pedilo-bien/index.html`
  - `demos/mapa-claude/index.html`
  - mini-apps de negocio según rubro

### Notebook

- `claude.ai` o `Claude Code`
- `guion/PROMPTS-DEMO.md` abierto
- piezas locales abiertas en pestañas para cambiar rápido con `Ctrl+Tab`

### Impresos

- `pantalla-principal/menu-qr.html`
- QR grande de SHIP IT! cerca del tele
- QRs de PEDILO BIEN y MAPA DE CLAUDE en mostrador o soporte

## Dinámica recomendada

1. El tele atrae con la pantalla principal.
2. La persona puede escanear sola una experiencia desde el menú QR.
3. Si aparece interés real, desde la notebook se muestra solo la capacidad que corresponde.
4. Si vale la pena profundizar, se usa un prompt preparado o una mini demo en vivo.

La clave no es mostrar todo. La clave es llevar a cada persona a una sola experiencia bien elegida.

## QR y publicación

Los QR deben apuntar a URLs accesibles desde el celular del visitante.

Opciones:

1. **Publicación web** con GitHub Pages, Netlify o Vercel.
   Es la opción recomendada.
2. **Servidor local + hotspot**
   Útil como plan B.

Conviene publicar al menos:

- `demos/claude-quest/`
- `demos/pedilo-bien/`
- `demos/mapa-claude/`

## Orden sugerido según interés

- **Quiere algo rápido:** SHIP IT!
- **Tiene un caso concreto:** PEDILO BIEN + prompt en vivo
- **Quiere entender más:** MAPA DE CLAUDE
- **Quiere algo más aplicado:** mini-app del rubro o prompt preparado

## Checklist pre-evento

- [ ] publicar `claude-quest`, `pedilo-bien` y `mapa-claude`
- [ ] generar e imprimir QRs
- [ ] completar e imprimir `pantalla-principal/menu-qr.html`
- [ ] abrir las piezas una vez y revisar consola
- [ ] probar desde al menos 2 celulares
- [ ] preparar `claude.ai` o `Claude Code` ya logueado
- [ ] preparar conectores o extensiones si se va a mostrar Chrome o MCP
- [ ] dejar abiertas las pestañas clave en la notebook
- [ ] subir a Drive la carpeta del proyecto y las guías

## Si algo falla

- **No carga el QR:** usar plan B local o pasar a la demo en notebook.
- **No hay audio:** tocar la página una vez para desbloquearlo.
- **Algo se cuelga:** F5.
- **No hay wifi:** las piezas locales siguen funcionando; lo publicado puede abrir con datos móviles.
