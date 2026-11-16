# Vendedor

Sistema de copywriting de respuesta directa para escribir textos de venta que no suenan a humo. Está construido sobre el **ADN de escritura de Monge Malo** y aplica un bucle obligatorio de **investigación real + doble auditoría anti-alucinación** antes de dar cualquier borrador por finalizado.

El objetivo: vender bots de WhatsApp / automatización de atención al cliente en nichos intercambiables (agencias de marketing, restaurantes, negocios locales/pymes, etc.), partiendo siempre de un hecho real y verificable.

---

## ¿Qué hay dentro?

```
vendedor/
├── README.md
├── adn-estilo-monge-malo.md          # FASE 1: estilo de escritura extraído (reglas, gancho, puente, tono, CTA)
├── prompt-crear-prompt-vendedor.txt  # Prompt del sistema: Analista + Redactor + Auditor de veracidad
├── mejoras.txt                       # Bucle de 4 pasos: Investigador → Auditor A → Redactor → Auditor B
└── borradores/
    ├── adn-monge-malo-agencias-marketing-bots-whatsapp.md   # Nicho: agencias de marketing (caso Air Canada)
    ├── restaurantes-whatsappbot-pro.md                      # Nicho: dueños de restaurantes (fatiga de decisión)
    └── whatsapp-bots-negocios-ia.md                         # Nicho: negocios locales / pymes (estudio HBR de 2011)
```

---

## Metodología

El sistema se compone de tres fases y un bucle de producción de 4 pasos.

### FASE 1 — ADN de escritura (Monge Malo)

Extraído de artículos reales del blog de Monge Malo. Las reglas clave son:

- **Gancho en 1-3 líneas**: diálogo *in medias res*, regla anti-intuitiva, promesa de secreto o imperativo que separa al lector del rebaño. Siempre en segunda persona ("tú").
- **Ritmo ultracorto**: oraciones breves, párrafos de 1-2 frases, saltos de línea constantes, anáfora como pulso, puntuación atípica (elipsis, guiones, paréntesis).
- **El Puente (Pivot)**: historia mundana que parece no tener nada que ver con el producto → abstracción-espejo → traslación al lector como conclusión lógica.
- **Tono**: cinismo seco sin desesperanza, humor sin muletillas, autoridad relajada, cero jerga de agencia ("solución 360", "potencia tu negocio", etc.).
- **Cierre y CTA**: después de la conclusión, en 1-3 líneas, directo, sin urgencia falsa. Framing de exclusividad + imperativo seco + botón.

### FASE 2 — Generación (variables intercambiables)

Cuando se entregan estas variables, se genera un artículo/correo aplicando al 100 % el estilo de la Fase 1:

| Variable | Ejemplo |
|---|---|
| `[NICHO]` | Clínicas dentales, SaaS B2B, agencias de marketing, dueños de restaurantes |
| `[PRODUCTO/SERVICIO A VENDER]` | Qué se vende y el resultado concreto que promete |
| `[PUNTO DE DOLOR / ENEMIGO COMÚN]` | El error del cliente o lo que odia de su mercado |
| `[IDEA/ANÉCDOTA SEMILLA]` | Hecho cotidiano o historia real de la que partir (opcional) |
| `[LLAMADA A LA ACCIÓN]` | Agendar llamada, comprar, responder el mail, escribir "BOT", etc. |

Reglas de redacción: cero jerga de agencia, párrafos ultracortos, la historia inicial parece irrelevante hasta el pivot, la venta es conclusión lógica no añadido artificial.

### FASE 3 — Auditor de veracidad

Antes de entregar cualquier borrador, el auditor evalúa:

1. **Filtro de reclamaciones**: ¿hay cifras o afirmaciones absolutas sin fundamento? Se cambian por realismo operativo.
2. **Coherencia técnica del nicho**: ¿describe problemas reales o cae en clichés superficiales?
3. **Detector de promesas imposibles**: reformula promesas borderline hacia beneficios tangibles y demostrables.

---

## Bucle de producción (4 pasos, obligatorio)

Según `mejoras.txt`, cada texto sigue este flujo antes de darse por terminado:

1. **Investigador de referencias reales y virales** — busca un hecho real, verificable y relacionado indirectamente con el nicho (caso empresarial documentado, noticia de prensa, hilo con alto volumen, experimento psicológico). Entregable: hecho exacto, protagonistas, fecha, fuente verificable. Prohibido decir "según estudios recientes".
2. **Auditor A (verificación de fuente)** — test de realidad. Si no es contrastable → `[RECHAZADO: FUENTE NO VERIFICABLE]`. Si es 100 % verificable → `[APROBADO: PROCEDER A REDACCIÓN]`.
3. **Redactor (ADN Monge Malo)** — escribe el texto con la referencia verificada: apertura *in medias res*, párrafos ultracortos, pivot, CTA directo.
4. **Auditor B (anti-alucinación y anti-hype)** — fidelidad al hecho, control de promesas del producto, veredicto final con informe de auditoría.

---

## Borradores disponibles

| Borrador | Nicho | Producto | Referencia real | CTA |
|---|---|---|---|---|
| `borradores/adn-monge-malo-agencias-marketing-bots-whatsapp.md` | Agencias de marketing | Bot de WhatsApp | Demanda contra Air Canada por chatbot erróneo (CRT, feb 2024) | "escribe bot y te fabrico un bot de whatsapp" |
| `borradores/restaurantes-whatsappbot-pro.md` | Dueños de restaurantes | WhatsAppBot Pro | Estudio de fatiga de decisión, PNAS 2011 (Danziger, Levav, Avnaim-Pesso) | "Mándame DEMO" |
| `borradores/whatsapp-bots-negocios-ia.md` | Negocios locales / pymes | Bot de WhatsApp para tu negocio | HBR, "The Short Life of Online Sales Leads", marzo 2011 | "Escribe BOT" |

Cada borrador incluye su **Entregable del Investigador**, **Informe del Auditor A**, **Borrador Persuasivo** y **Informe del Auditor B**.

---

## Cómo cambiar de nicho y contenido

El sistema está diseñado para ser intercambiable: el mismo ADN de escritura y el mismo bucle de 4 pasos sirven para cualquier nicho. Para generar un texto nuevo solo tienes que definir las **5 variables de entrada** de la FASE 2.

### Variables de entrada (obligatorias)

| Variable | Qué es | Ejemplos |
|---|---|---|
| `[NICHO]` | Sector y tipo de cliente al que hablas | Clínicas dentales, SaaS B2B, infoproductos de finanzas, inmobiliarias, gimnasios |
| `[PRODUCTO/SERVICIO A VENDER]` | Qué vendes y el resultado concreto que promete | "Bot de WhatsApp que responde precio y horario", "Sistema que agenda citas solo" |
| `[PUNTO DE DOLOR / ENEMIGO COMÚN]` | El error que comete el cliente o lo que odia de su mercado | "Leads que se enfrían mientras contesta a mano", "clientes que se van a la competencia por no responder rápido" |
| `[IDEA/ANÉCDOTA SEMILLA]` | Hecho cotidiano, historia curiosa o situación real de la que partir (opcional) | "Un mensaje escrito a las 11:02 que nadie contestó hasta la una y media" |
| `[LLAMADA A LA ACCIÓN]` | Qué quieres que haga el lector al final | "Escribe BOT", "Mándame DEMO", "Agenda una llamada", "Responde a este mail" |

> Si `[IDEA/ANÉCDOTA SEMILLA]` va vacía, el Investigador del Paso 1 buscará una referencia real adecuada al nicho y al punto de dolor. Si la aportas, el Investigador deberá igualmente verificar que existe y es contrastable antes de redactar.

### Plantilla para rellenar

```
[NICHO]: ...
[PRODUCTO/SERVICIO A VENDER]: ...
[PUNTO DE DOLOR / ENEMIGO COMÚN]: ...
[IDEA/ANÉCDOTA SEMILLA]: (opcional)
[LLAMADA A LA ACCIÓN]: ...
```

### Ejemplo de cambio de nicho

Con el mismo producto (bot de WhatsApp) y cambiando solo el nicho, el texto cambia por completo:

**Nicho actual — dueños de restaurantes** (ver `borradores/restaurantes-whatsappbot-pro.md`):
- Dolor: a las 9 de la noche, agotado, no puedes atender el mensaje 47 del día
- Referencia real: estudio de fatiga de decisión en una junta de libertad condicional (PNAS 2011)
- CTA: «Mándame DEMO»

**Mismo producto — clínicas dentales** (ejemplo hipotético):
- Dolor: las recepcionistas pierden la mitad del día repitiendo "¿tienen hueco?" y las citas se escapan
- Referencia real: buscar en el Paso 1 un caso documentado sobre sobrecarga en recepción o pérdida de citas por respuesta lenta
- CTA: «Escribe CITA y te enseño cómo el bot llena tu agenda»

### Flujo para generar texto nuevo

1. **Rellena las 5 variables** con la plantilla de arriba.
2. **Paso 1 — Investigador**: busca una referencia REAL y verificable ligada al nicho o al punto de dolor (no al producto). Entrega hecho exacto, protagonistas, fecha y fuente. Si la semilla que aportaste no es contrastable, descártala y busca otra.
3. **Paso 2 — Auditor A**: verifica la fuente. `[RECHAZADO: FUENTE NO VERIFICABLE]` → vuelve al Paso 1. `[APROBADO: PROCEDER A REDACCIÓN]` → continúa.
4. **Paso 3 — Redactor**: escribe con el ADN Monge Malo (gancho *in medias res*, párrafos ultracortos, pivot, CTA directo).
5. **Paso 4 — Auditor B**: revisa fidelidad al hecho, control de promesas (nada de "duplica ventas en 24h") y coherencia técnica del nicho. Si aprueba, entrega el texto pulido junto con el informe de auditoría.
6. **Guarda el resultado** en `borradores/` con un nombre que identifique el nicho (ej. `clinicas-dentales-whatsappbot.md`).

### Errores frecuentes al cambiar de nicho

- **Elegir la referencia del producto, no del dolor**: el hecho real debe hablar del problema del nicho (tiempo, respuestas, clientes que se van), no de bots. Si el hecho es "un chatbot metió la pata", es perfecto; si es "una empresa vendió bots", no.
- **Inventar la anécdota**: está prohibido. Si no hay referencia real verificable, se busca otra o se cambia el punto de dolor.
- **Prometer métricas absolutas**: "aumentarás un 300 %" → el Auditor B lo bloquea. Se sustituye por beneficios operativos ("responde en 5 minutos, 24/7, con tu carta y tu horario").
- **Mezclar jerga de agencia**: "solución 360", "potencia tu negocio", "transformación integral" → fuera. El estilo Monge Malo desprecia esos clichés.
- **CTA que presiona**: sin urgencia falsa ni cuentas atrás. Directo, en 1-3 líneas, después de la conclusión.

---

## Cómo usar

1. Lee `adn-estilo-monge-malo.md` para interiorizar el estilo.
2. Lee `prompt-crear-prompt-vendedor.txt` si vas a operar el sistema como agente de IA (Analista + Redactor + Auditor).
3. Elige un nicho y define las 5 variables de la Fase 2 (ver sección "Cómo cambiar de nicho y contenido").
4. Ejecuta el bucle de 4 pasos (`mejoras.txt`): investiga referencia real → audita fuente → redacta → audita borrador.
5. Solo entrega cuando el Auditor B emita veredicto final aprobado.

---

## Nota de veracidad

Este sistema prioriza la credibilidad sobre el hype. No se prometen métricas inventadas ("duplica tus ventas en 24 h", "300 % más"). Todas las cifras anecdóticas deben ser atribuidas y verificables; las promesas del producto deben ser beneficios operativos reales y contingentes, nunca garantías de resultado.

---

*Proyecto parte del ecosistema "portero de telegram y escritor de facturas".*