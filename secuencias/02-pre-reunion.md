# Secuencia 02 — Pre-reunión

**Trigger:** Deal avanza a "Primera Cita" o reunión agendada en HubSpot
**Objetivo:** Llegar a la reunión con el prospecto preparado y comprometido
**Duración:** 2 emails · 48 horas antes de la reunión
**Deals activos:** Viva Aerobus, Grupo Hotelero Santa Fe, Tim Hortons

---

## Flujo

```
[Reunión agendada en HubSpot]
        │
    Email 1 (-48h) — Confirmación + contexto
        │
    Email 2 (-24h) — Recordatorio + dato que genera conversación
        │
[Reunión] → activar Seq 03 post-reunión el mismo día
```

---

## Email 1 — Confirmación y material de contexto

**Timing:** 48 horas antes de la reunión
**Asunto (opción A):** Confirmado: [Fecha] a las [Hora] — y algo para aprovechar mejor el tiempo
**Asunto (opción B):** Nos vemos el [Fecha] — te mando algo antes
**Preview text:** Tres preguntas que me ayudan a personalizar lo que te voy a mostrar.

---

Hola [Nombre],

Confirmado: nos vemos el **[Fecha] a las [Hora]**.

Para aprovechar bien los 30 minutos, te comparto tres preguntas que me gustaría que pensaras antes de nuestra conversación — no necesitas enviarme las respuestas, solo tenerlas en mente:

1. ¿Cuántas personas tienen en equipos operativos (piso, campo, ruta)?
2. ¿Qué métodos usan hoy para capacitarlos y qué tan satisfechos están con los resultados?
3. ¿Cuál es el mayor dolor que quieren resolver en los próximos 6 meses?

Con eso puedo mostrarte exactamente lo que es relevante para [Empresa], sin dar vueltas.

Nos vemos el [Fecha].

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Email 2 — Recordatorio + dato relevante

**Timing:** 24 horas antes de la reunión
**Asunto:** Mañana a las [Hora] — un dato rápido antes de vernos
**Preview text:** Algo que encontré que puede ser relevante para [Empresa].

---

Hola [Nombre],

Mañana a las **[Hora]** — aquí el enlace por si lo necesitas: [Enlace de videollamada]

Mientras tanto, un dato que encontré pensando en [Empresa]:

**[Insertar dato específico de industria — ver variantes abajo]**

Lo platicamos mañana.

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Variantes del dato por industria

Reemplazar el bloque `[dato específico]` según la empresa:

### Aerolíneas (Viva Aerobus)
> Las aerolíneas con programas de microlearning para tripulación reportan hasta **40% menos incidentes de servicio** en los primeros 90 días post-implementación. El diferencial está en la frecuencia del refuerzo, no en la duración del curso inicial.

### Hotelería (Grupo Hotelero Santa Fe, Holiday Inn, ACCOR)
> En hoteles con alta rotación de personal, el tiempo promedio para que un nuevo colaborador alcance estándares de servicio es de **6 a 8 semanas**. Las propiedades que usan microlearning lo reducen a **2-3 semanas** con mayor consistencia.

### QSR / Alimentos (Tim Hortons, Fraiche)
> En cadenas de alimentos y bebidas, el **62% de las quejas de cliente** se originan en brechas de entrenamiento en punto de venta — no en el producto. La capacitación continua en cápsulas cortas reduce ese número de forma consistente.

### Logística / Paquetería (DHL, Ryder)
> Los equipos de logística con programas de formación en celular reportan **30% menos accidentes operativos** y una reducción significativa en mermas por manejo incorrecto.

### Alimentos y bebidas / Planta (Lala, Pepsico, Alpura)
> En plantas de producción, el costo de un reproceso por falla de protocolo puede superar **3 veces el costo** del programa de capacitación que lo hubiera prevenido.

### Retail (Sanborns, Elektra)
> Los vendedores de piso que reciben refuerzo semanal de conocimiento de producto tienen **23% más tasa de conversión** que los que solo reciben entrenamiento inicial.

---

## Notas de configuración en HubSpot

- Trigger: deal avanza a etapa "Primera Cita" O se crea reunión en el deal
- Personalizar manualmente el dato de industria antes de enviar
- Al terminar la reunión: activar Seq 03 manualmente el mismo día
