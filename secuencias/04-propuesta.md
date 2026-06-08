# Secuencia 04 — Seguimiento de propuesta

**Trigger:** Deal en etapa "Propuesta Enviada"
**Objetivo:** Conseguir respuesta (sí, no, o negociación activa) en máximo 3 semanas
**Duración:** 4 emails · 18 días
**Deal activo:** Cerebrum

---

## Flujo

```
[Propuesta enviada]
        │
    Email 1 (Día 2) — Confirmar recepción y abrir diálogo
        │
    Email 2 (Día 6) — ROI / impacto medible
        │
    Email 3 (Día 12) — Identificar objeciones
        │
    Email 4 (Día 18) — Decisión directa
        │
[Responde positivamente] → mover a Negociación + Seq 05
[No responde] → evaluar Seq 01b o Closed Lost
```

---

## Email 1 — Confirmar recepción

**Timing:** 2 días después de enviar la propuesta
**Asunto:** La propuesta que le compartí — ¿tiene preguntas?
**Preview text:** Solo quiero confirmar que llegó bien y que no quedó ninguna duda sin resolver.

---

Hola [Nombre],

Le escribo para confirmar que recibió la propuesta que le mandé el [Fecha].

¿Tuvo oportunidad de revisarla? Si tiene alguna pregunta sobre los alcances, el modelo de implementación o los costos, con gusto la resuelvo.

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Email 2 — ROI e impacto medible

**Timing:** Día 6 post-propuesta
**Asunto (opción A):** Un número que probablemente le interesa ver
**Asunto (opción B):** Lo que les costaría no resolver esto
**Preview text:** No es un argumento de venta. Es un cálculo que vale la pena hacer.

---

Hola [Nombre],

Mientras espero su respuesta sobre la propuesta, quiero compartirle un ejercicio que hacemos con nuestros clientes antes de arrancar:

**Costo de no capacitar vs. costo de hacerlo bien:**

En una empresa con [X] colaboradores operativos, si el 30% de ellos comete un error evitable por falta de entrenamiento al mes, y cada error cuesta en promedio [Y] en reprocesos, mermas o quejas de cliente — el costo anual supera con creces la inversión en un programa de microlearning.

No le pido que haga el cálculo ahora. Pero si quiere que lo hagamos juntos con los números de [Empresa], con gusto coordinamos una llamada rápida.

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Email 3 — Identificar objeciones

**Timing:** Día 12 post-propuesta
**Asunto (opción A):** ¿Hay algo que no cuadra en la propuesta?
**Asunto (opción B):** Quiero asegurarme de que la propuesta tenga sentido para ustedes
**Preview text:** Si algo no encaja, prefiero saberlo ahora para ajustarlo.

---

Hola [Nombre],

Llevo unos días esperando su respuesta sobre la propuesta y quiero ser directa.

Cuando hay silencio en este punto, usualmente es por alguna de estas razones:

- El precio no encaja con el presupuesto actual
- Necesita aprobación de alguien más antes de avanzar
- El timing no es el adecuado para implementar ahora
- Hay una duda técnica u operativa que no resolvimos

¿Cuál aplica en su caso?

Con esa información puedo ayudarle mejor — o ajustar la propuesta si hace falta.

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Email 4 — Decisión directa

**Timing:** Día 18 post-propuesta
**Asunto (opción A):** ¿Seguimos adelante o lo dejamos para otro momento?
**Asunto (opción B):** Necesito saber para organizar nuestra agenda
**Preview text:** Sin presión. Solo necesito una respuesta para saber cómo proceder.

---

Hola [Nombre],

Le he escrito varias veces desde que envié la propuesta y entiendo que la agenda operativa no siempre da espacio.

Solo necesito saber una cosa: ¿seguimos adelante con [Empresa] o es mejor retomarlo en otro momento?

Cualquiera de las dos respuestas está bien. Solo necesito saberlo para organizar nuestra agenda correctamente.

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Notas para Cerebrum (deal activo)

- Verificar fecha en que se envió la propuesta para calcular en qué email de la secuencia debería estar
- Si lleva más de 18 días sin respuesta desde el envío → considerar llamada directa antes de cerrar el deal
- Actualizar el monto en el deal de HubSpot si no está capturado

## Notas de configuración en HubSpot

- Trigger: deal movido a etapa "Propuesta Enviada"
- Exit: deal stage cambia a "Negociación" (respuesta positiva) o "Closed Lost"
- Si llega al Email 4 sin respuesta y tampoco responde → mover a Closed Lost con nota "Sin respuesta post-propuesta"
