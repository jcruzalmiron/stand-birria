# PROMPTS PREPARADOS — demos en vivo en la notebook

> Rol del operador: **informar y mostrar lo que le interese a cada persona**, no recitar.
> Preguntá "¿qué te gustaría que haga?" y elegí el prompt de acá. Todos están listos para copiar y pegar.
> Regla de oro: **que el visitante escriba o dicte su variante** apenas vea la primera demo — el momento "lo hice yo" vale más que diez demos tuyas.

---

## ⚡ WOW inicial (artifacts, 60 segundos)

Para abrir con cualquiera, en claude.ai:

```
Armame un juego simple para mi hija de 8 años: atrapar empanadas que caen,
con puntaje y sonido. Que se pueda jugar ya mismo acá.
```

```
Armame una ruleta para sortear quién lava los platos en casa.
Nombres editables, animación al girar, festejo al elegir.
```

**Narrar:** "No te describió un juego: lo FABRICÓ. Mirá el panel derecho — eso es un artifact, una app de verdad."

---

## 📐 SKILLS (documentos profesionales de verdad)

En claude.ai (con skills de documentos) o Claude Code:

```
Armame una presentación en PowerPoint de 6 diapositivas para pedirle un crédito
al banco para mi rotisería: portada, el negocio en números (inventalos razonables),
qué quiero comprar con el crédito, y cierre. Estilo sobrio, en español.
```

```
Armame en Excel una planilla de control de gastos para un kiosco: hojas por mes,
categorías típicas, totales automáticos y un gráfico de torta. Con datos de ejemplo.
```

**Narrar:** "Esto sale como archivo .pptx/.xlsx de verdad — lo abrís en tu compu, no es una imagen. Lo hace con *skills*: formas de trabajar que ya tiene aprendidas. Y vos podés enseñarle las tuyas: tu formato de presupuesto, tu estilo de redacción."

---

## 🤖 SUBAGENTES (trabajo en paralelo)

En Claude Code, dentro de una carpeta vacía:

```
Usá 3 subagentes en paralelo: uno que arme una landing page para una barbería,
otro que arme la lista de precios en una página aparte, y otro que escriba
los 5 posteos de Instagram del lanzamiento. Cuando terminen, mostrame todo.
```

**Narrar (mientras corre):** "Mirá: se dividió en tres ayudantes y están trabajando A LA VEZ. Como una brigada de cocina. Este stand entero se construyó así." — Es la demo más impactante de ver en vivo porque se ve el paralelismo en la terminal.

---

## 🔌 MCP (conectar datos reales)

⚠️ **Preparar ANTES del evento**: conectar en claude.ai una cuenta Gmail/Calendar/Drive de demo (cuenta del stand, no personal) con 4-5 mails y eventos cargados de mentira (un presupuesto de proveedor, un turno, una factura).

```
Buscá en mis mails el presupuesto que me mandó el proveedor de bebidas
y decime si me conviene contra lo que pago hoy (unos $4.500 por pack).
```

```
Mirá mi calendario de la semana y armame un resumen de compromisos,
con qué día me queda libre para recibir al técnico.
```

**Narrar:** "Esto es MCP: el enchufe entre Claude y TUS datos. No le conté nada — fue a mis mails y lo encontró solo. Vos autorizás qué puede ver, app por app."

**Fallback sin cuenta conectada:** mostrá el flujo de conexión en Configuración → Conectores y narrá: "se conecta una vez con tu permiso, y de ahí en más deja de ser un chat ciego."

---

## 🌐 CHROME CON LA EXTENSIÓN (Claude usa el navegador)

⚠️ **Preparar ANTES**: extensión "Claude in Chrome" instalada y logueada en el Chrome de la notebook.

```
Abrí Mercado Libre, buscá "freidora de aire 5 litros", compará las primeras
cinco opciones y decime cuál conviene por precio, envío y reputación del vendedor.
```

```
Entrá a la página de la AFIP/ARCA y explicame paso a paso, con lo que ves
en pantalla, dónde se saca la constancia de inscripción de un monotributista.
```

**Narrar (clave):** "Mirá el mouse — lo está moviendo Claude. Navega, lee y compara COMO VOS, con tu permiso y a la vista. Los pasos aburridos de internet los puede hacer él."

**Fallback si la extensión falla:** demo de visión — sacale foto a cualquier cosa del evento (el menú impreso, un folleto) y: `¿Qué dice acá y qué me conviene pedir si no como picante?`

---

## 👁️ VISIÓN (para todas las edades, infalible)

```
[foto de un ticket o factura] Pasame esto a una tabla: ítems, cantidades,
precios y total. Decime si el total está bien sumado.
```

```
[foto de una planta del evento o de la calle] ¿Qué planta es y cómo la cuido?
```

---

## 🧠 MEMORIA Y PROYECTOS (cierre para interesados)

```
Acordate de esto: tengo una peluquería en Lanús, atiendo martes a sábado,
y mi problema número uno son los turnos que se pisan. La próxima vez que
hablemos, retomá desde ahí.
```

**Narrar:** "La próxima conversación arranca sabiendo esto. Sumale un Proyecto con tus archivos y deja de ser un asistente nuevo cada día: es uno que ya conoce tu casa."

---

## Mapa rápido: qué mostrar según qué pregunta el visitante

| Si pregunta… | Mostrá | Prompt |
|---|---|---|
| "¿Hace páginas/apps?" | Artifacts | el juego o la ruleta |
| "¿Me sirve para el laburo?" | Skills | el PowerPoint del banco o el Excel |
| "¿Puede usar mis datos?" | MCP | los mails del proveedor |
| "¿Navega internet?" | Chrome | la comparación de Mercado Libre |
| "¿Cómo hicieron este stand?" | Subagentes | los 3 agentes en paralelo |
| "¿Y si le saco una foto?" | Visión | el ticket o la planta |
| "¿Se acuerda de mí?" | Memoria | el de la peluquería de Lanús |

**Cierre universal:** "Todo esto que viste está en el menú impreso — escaneá el QR de lo que te interesó y seguí en tu casa." → *"Mientras el resto conversa, Claude construye."*
