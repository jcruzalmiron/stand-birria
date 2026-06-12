# Stand "3° Degustación Birria" — Manual de operación

**Concepto:** *Mientras el resto conversa, Claude construye.*
Todo es HTML autocontenido: funciona **sin internet**, se abre con **doble clic** en Chrome.

## Qué abrir en qué pantalla

| Pantalla | Archivo | Cuándo |
|---|---|---|
| Monitor 55" | `pantalla-principal/index.html` | Siempre que no haya demo activa (pantalla de espera con terminal animada) |
| Monitor 55" | `demos/arena-rpg/index.html` | Demo estrella, en vivo con el visitante |
| Monitor 55" | `demos/negocio-en-vivo/*.html` | Dinámica "pedila en vivo" según el rubro del visitante |
| Tablet / 2.ª pantalla | `pantalla-principal/industrias.html` | Cartel rotativo permanente (cicla solo cada 8 seg) |
| Tablet | `demos/gastos-evento/index.html` | Demo de mano para curiosos generales |

> Tip: dejá **todas las pestañas ya abiertas** en Chrome y cambiá con `Ctrl+Tab` — el efecto "se generó recién" no se rompe.

## Orden de demos según el visitante

- **Chico / joven** → `arena-rpg` primero. Que juegue él/ella. Después el remate: "imaginá que en vez de un juego es el negocio de tus viejos".
- **Adulto con negocio** → preguntá el rubro y abrí directo su mini-app:
  - Peluquería / estética / consultorio → `turnos-peluqueria.html`
  - Restaurante / bar / rotisería → `pedidos-restaurante.html`
  - Kiosco / almacén / comercio → `stock-kiosco.html`
- **Curioso general / grupo de amigos** → `gastos-evento` ("¿quién pagó el asado?"), después el RPG si engancha.

El guion completo (5 y 15 minutos, remates y respuestas a objeciones) está en [guion/GUION.md](guion/GUION.md).

## Checklist pre-evento

- [ ] Copiar la carpeta `stand-birria/` completa a **las dos máquinas** (y a un pendrive de respaldo).
- [ ] Abrir cada HTML una vez y verificar que carga sin errores (F12 → consola limpia).
- [ ] **Probar el audio** del RPG: tocar la pantalla/clic una vez (los browsers bloquean el sonido hasta la primera interacción) y verificar volumen del monitor.
- [ ] **Probar touch** en la tablet: botones del RPG, mover comandas, registrar una venta en el kiosco.
- [ ] Chrome en **modo presentación: F11** en el monitor de 55" (salir con F11 también).
- [ ] **Brillo al máximo** en todas las pantallas; desactivar suspensión/protector de pantalla (Windows: Configuración → Energía → pantalla "Nunca").
- [ ] Desactivar notificaciones (Windows: Asistente de concentración / No molestar).
- [ ] Cargar tablet al 100% y llevar cargador.
- [ ] Dejar `pantalla-principal/index.html` corriendo en el monitor y `industrias.html` en la tablet antes de que llegue la gente.

## Si algo falla

- **No hay sonido** → hacé un clic en la página (desbloquea WebAudio) y revisá el volumen del sistema.
- **Se ve cortado en el 55"** → F11 (pantalla completa) y `Ctrl+0` para resetear el zoom.
- **Se tildó una demo** → F5. Todas arrancan de cero al instante, no dependen de nada.
- **No hay wifi** → no importa: nada de esta carpeta usa internet.
