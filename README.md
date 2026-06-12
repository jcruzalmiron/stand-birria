# Stand "3° Degustación Birria" — Manual de operación

**Concepto:** *Mientras el resto conversa, Claude construye.*
**Estructura:** dos capas — **wow** (juegos generados en vivo) y **comprensión** (el stack real de Claude: Prompt · Skill · MCP · Agents · Claude Code).
Todo es HTML autocontenido: funciona **sin internet**, se abre con **doble clic** en Chrome.

## Piezas principales

| Pieza | Archivo | Rol |
|---|---|---|
| ⭐ **SHIP IT!** (QR / celular) | `demos/claude-quest/index.html` | Capa wow: arcade de 90 seg, un pulgar, donde los 5 módulos del stack son power-ups. Termina con el mapa mental. |
| ⭐ **PEDILO BIEN** | `demos/pedilo-bien/index.html` | Capa utilidad: 4 preguntas y el visitante se lleva su pedido profesional para Claude (copiar / WhatsApp) + el stack recomendado con razones. Sirve en pantalla grande y en tablet. |
| **Pantalla de espera** | `pantalla-principal/index.html` | Frase central + terminal que narra en loop el criterio de stack + lugar para pegar el QR impreso. |
| **Cartel industrias** | `pantalla-principal/industrias.html` | Rotativo de casos por rubro (tablet secundaria). |
| Mini-apps de negocio | `demos/negocio-en-vivo/*.html` | Apoyo de la capa comprensión: peluquería (prompt+Code), restaurante (entra MCP), kiosco. |
| Gastos del evento | `demos/gastos-evento/index.html` | Demo de mano para curiosos. |
| Guion | [guion/GUION.md](guion/GUION.md) | Guiones de 5 y 15 min, glosario y objeciones. |

## Qué abrir en qué pantalla

- **Monitor 55"** → `pantalla-principal/index.html` en F11 (espera) · cambiar a `pedilo-bien` o mini-apps durante la demo (tener pestañas abiertas, `Ctrl+Tab`).
- **Tablet de apoyo** → `pantalla-principal/industrias.html`.
- **Celular del visitante** → SHIP IT! vía QR (ver abajo).

## El QR de SHIP IT! (importante, hacer ANTES del evento)

El juego es un único archivo, pero un QR necesita una **URL accesible desde el celular del visitante**. Opciones, de mejor a peor:

1. **Publicarlo** (GitHub Pages / Netlify Drop / Vercel): arrastrás la carpeta `demos/claude-quest/` y obtenés una URL pública. El celular del visitante usa SUS datos móviles → no dependés del wifi del evento. **Recomendada.**
2. **Hotspot local**: una notebook con `python -m http.server 8080` + hotspot del teléfono del stand; el QR apunta a `http://<ip-local>:8080/demos/claude-quest/`. Funciona sin internet, pero el visitante debe conectarse a tu red.
3. Generar el QR con cualquier generador (apuntando a la URL elegida), **imprimirlo grande** y pegarlo en el marco punteado que muestra la pantalla de espera, más uno en el mostrador.

> Probalo desde un celular real antes del evento: tap, arrastre, sonido y pantalla final.
> Tip: `index.html?t=30` hace runs de 30 segundos si hay fila de gente.

## Orden de demos según el visitante

- **Cualquiera con celular** → QR de SHIP IT! primero. Es la pieza que se llevan puesta.
- **Chico / joven** → SHIP IT! de nuevo (van a querer superar el puntaje) y la pantalla grande con la terminal.
- **Adulto con negocio** → su mini-app + la explicación de stack del guion ("para esto alcanza prompt+Code; para aquello entra MCP").
- **Curioso general** → gastos del evento o SHIP IT! de nuevo (van a querer mejorar el puntaje).

## Checklist pre-evento

- [ ] Publicar SHIP IT! y **probar el QR desde 2 celulares distintos** (Android + iPhone).
- [ ] Imprimir el QR (mínimo A5) y pegarlo en el marco de la pantalla de espera.
- [ ] Copiar la carpeta `stand-birria/` a las dos máquinas + pendrive de respaldo.
- [ ] Abrir cada HTML y verificar consola limpia (F12).
- [ ] Probar audio de SHIP IT! (el sonido arranca con el primer tap — los browsers lo bloquean antes).
- [ ] Probar touch en la tablet (SHIP IT!, PEDILO BIEN, comandas, kiosco).
- [ ] Chrome en F11 en el 55", `Ctrl+0` de zoom, brillo al máximo.
- [ ] Desactivar suspensión de pantalla y notificaciones en todas las máquinas.
- [ ] Cargar tablet y llevar cargadores.

## Si algo falla

- **No hay sonido** → un clic/tap en la página lo desbloquea; revisar volumen del sistema.
- **El QR no carga** → plan B: hotspot local (opción 2 de arriba); plan C: pasar el juego por la tablet del stand.
- **Algo se tildó** → F5. Todo arranca de cero al instante.
- **No hay wifi** → las pantallas y demos locales no lo necesitan; solo el QR depende de la URL publicada (que usa los datos del visitante).
