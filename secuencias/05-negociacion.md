# Secuencia 05 — Negociación y cierre

**Trigger:** Deal en etapa "Negociación"
**Objetivo:** Cerrar el deal o definir con claridad los términos que faltan
**Duración:** 3 emails · 14 días
**Deals activos:**
- **Sanborns** — $18,000 USD · Retail / Tiendas departamentales
- **Fraiche** — Sin monto registrado · QSR / Alimentos

> **Acción inmediata:** Actualizar el monto de Fraiche en HubSpot antes de iniciar esta secuencia.
> Sin monto capturado es difícil priorizar y reportar correctamente el pipeline.

---

## Flujo

```
[Deal en Negociación]
        │
    Email 1 (Día 2) — Clarificar lo que falta para cerrar
        │
    Email 2 (Día 7) — Resolver la objeción principal
        │
    Email 3 (Día 14) — Cierre con fecha límite
        │
[Cierra] → Closed Won
[No cierra] → Proponer fecha futura o Closed Lost con nota
```

---

## Email 1 — Clarificar lo que falta

**Timing:** Día 2 desde que el deal entró a Negociación
**Asunto (opción A):** Para cerrar esto, ¿qué falta de tu lado?
**Asunto (opción B):** Retomando nuestra conversación sobre [Empresa]
**Preview text:** Quiero asegurarme de que no hay ningún pendiente de nuestra parte.

---

Hola [Nombre],

Retomo nuestra conversación sobre el programa de capacitación para [Empresa].

Quiero asegurarme de que tienes todo lo que necesitas para tomar la decisión:

- ¿Hay algún punto de la propuesta que necesite ajuste?
- ¿Falta información técnica sobre la implementación?
- ¿Hay alguien más en [Empresa] que necesite estar en la conversación?

Dime qué falta de nuestro lado y lo resuelvo esta semana.

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Email 2 — Resolver la objeción principal

**Timing:** Día 7
**Asunto (opción A):** Sobre [objeción específica que mencionaron]
**Asunto (opción B):** Una aclaración que puede ayudar a avanzar
**Preview text:** Quiero asegurarme de que esto no quede como un punto sin resolver.

---

Hola [Nombre],

En nuestra última conversación mencionaste [insertar objeción: ej. "el presupuesto es ajustado para Q3" / "necesitan ver cómo funciona antes de comprometerse" / "hay dudas sobre la implementación técnica"].

Quiero darte una respuesta concreta:

**[Insertar respuesta a la objeción — ver variantes abajo]**

¿Con esto queda resuelto, o hay algo más que necesiten para avanzar?

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Variantes por objeción común

### Si la objeción es precio / presupuesto
> Entiendo que el presupuesto para este trimestre tiene límites. Hay dos opciones que podemos explorar:
>
> 1. **Arrancar con un piloto acotado** — implementamos Wesay con un equipo o área específica (ej. [área concreta de la empresa]) a un costo menor, medimos resultados en 60 días, y a partir de ahí tomamos la decisión de escalar.
> 2. **Diferir el arranque a Q4 con condiciones actuales** — reservamos las condiciones de la propuesta actual para cuando el presupuesto esté disponible.
>
> ¿Cuál tiene más sentido para [Empresa]?

### Si la objeción es "queremos verlo funcionar primero"
> Es completamente razonable. Por eso ofrecemos un **período de prueba de 30 días** con un grupo acotado de colaboradores de [Empresa].
>
> Sin costo de implementación. Con acceso completo a la plataforma y acompañamiento semanal de nuestro equipo. Al final de los 30 días, [Empresa] decide si continúa con el programa completo.
>
> ¿Quieres que lo estructuremos así?

### Si la objeción es implementación técnica
> La implementación de Wesay no requiere integración con sistemas propios ni infraestructura adicional. Los colaboradores acceden desde su celular personal o corporativo con solo un enlace o descarga de la app.
>
> Del lado de [Empresa], el único requerimiento es designar a un administrador interno que reciba 2 horas de onboarding con nuestro equipo. Nosotros hacemos el resto.
>
> ¿Hay algún requerimiento técnico específico que no hayamos cubierto?

### Si la objeción es aprobación interna
> Entiendo que la decisión requiere pasar por [Director General / Dirección de RR.HH. / Comité de compras].
>
> ¿Te sería útil que te preparara un resumen ejecutivo de una página con los puntos clave — costo, alcance, beneficios esperados y casos de referencia — para facilitar esa aprobación interna?
>
> Con gusto lo preparo esta semana.

---

## Email 3 — Cierre con fecha límite

**Timing:** Día 14
**Asunto (opción A):** Las condiciones de la propuesta vencen el [Fecha]
**Asunto (opción B):** Necesito una respuesta esta semana para reservar tu lugar
**Preview text:** Sin presión artificial — hay una razón real para la fecha.

---

Hola [Nombre],

Te escribo porque las condiciones actuales de la propuesta — precio, período de implementación y disponibilidad de nuestro equipo — están vigentes hasta el **[Fecha: aprox. 7 días desde este email]**.

Después de esa fecha, no puedo garantizar las mismas condiciones porque tenemos otros proyectos entrando en agenda.

Si [Empresa] quiere avanzar con esto, necesito saberlo esta semana.

Si el timing no es el correcto, también me dices y lo dejamos para cuando sea el momento adecuado — sin problema.

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Notas específicas por deal

### Sanborns ($18,000 USD)
- Deal más valioso del pipeline activo
- Industria: Retail / Tiendas departamentales
- Argumento central: conocimiento de producto en piso = mayor conversión
- Variante de objeción más probable: aprobación interna (empresa grande, proceso de compras estructurado)
- Si hay silencio → escalar con llamada directa antes del Email 3

### Fraiche
- Actualizar monto en HubSpot antes de iniciar secuencia
- Industria: QSR / Alimentos
- Argumento central: consistencia en protocolos de punto de venta + reducción de errores
- Por ser empresa más pequeña, el decision-maker puede ser la misma persona de contacto

---

## Notas de configuración en HubSpot

- Trigger: deal movido a etapa "Negociación"
- Email 2: personalizar manualmente según la objeción real que mencionaron en la conversación
- Exit condition: deal pasa a Closed Won o Closed Lost
- Si llega al Email 3 sin respuesta → llamar directamente antes de cerrar el deal
