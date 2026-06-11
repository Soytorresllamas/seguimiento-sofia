Modelo de seguimiento comercial
### Correos de Sofía Sánchez · Directora de Operaciones

Este repositorio contiene el modelo completo de automatización de correos de seguimiento para el pipeline comercial de Wesay. Los templates están listos para configurarse como **HubSpot Sequences**.

---

## Contenido

| Archivo | Para qué sirve |
|---|---|
| [`pipeline.md`](pipeline.md) | Estado actual del pipeline con todos los deals |
| [`secuencias/01-activacion-prospecto.md`](secuencias/01-activacion-prospecto.md) | Nuevo prospecto → conseguir primera reunión |
| [`secuencias/01b-reengagement.md`](secuencias/01b-reengagement.md) | Deals fríos (+30 días sin actividad) |
| [`secuencias/02-pre-reunion.md`](secuencias/02-pre-reunion.md) | Reunión agendada → preparar al prospecto |
| [`secuencias/03-post-reunion.md`](secuencias/03-post-reunion.md) | Reunión ocurrió → mantener momentum |
| [`secuencias/04-propuesta.md`](secuencias/04-propuesta.md) | Propuesta enviada → conseguir respuesta |
| [`secuencias/05-negociacion.md`](secuencias/05-negociacion.md) | En negociación → cerrar |
| [`configuracion-hubspot.md`](configuracion-hubspot.md) | Cómo configurar las secuencias en HubSpot |
| [`contactos-por-deal.md`](contactos-por-deal.md) | Qué deals tienen contacto y cuáles no — diagnóstico completo de 143 deals |
| [`benchmarks.md`](benchmarks.md) | Métricas esperadas por secuencia |

---

## Cómo usar este repo

1. **Leer primero [`pipeline.md`](pipeline.md)** para entender el estado actual y prioridades.
2. Cada archivo de secuencia incluye:
   - El trigger (qué activa la secuencia en HubSpot)
   - Los emails numerados con asunto, preview text y cuerpo completo
   - Variantes por industria donde aplica
   - Instrucciones de configuración
3. **Prioridad inmediata:** Seq 05 (Sanborns y Fraiche en negociación) y Seq 01b (80+ deals fríos).

---

## Tokens de personalización

En los templates, los siguientes tokens se reemplazan automáticamente en HubSpot:

| Token | Qué inserta |
|---|---|
| `[Nombre]` | Primer nombre del contacto |
| `[Empresa]` | Nombre de la empresa |
| `[Industria]` | Sector (ej. hotelería, logística) |
| `[Fecha]` | Fecha de la reunión agendada |
| `[Hora]` | Hora de la reunión |
| `[Producto/Servicio]` | Lo que discutieron en reunión |

---

## Contacto

**Sofía Sánchez** · Directora de Operaciones · Wesay
