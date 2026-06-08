# Configuración en HubSpot

## Requisitos previos

- **HubSpot Sales Hub Starter** o superior (desde ~$20 USD/mes por usuario)
- Las **Sequences** requieren cuenta de pago — los Workflows gratuitos no se pausan automáticamente con respuesta
- Cuenta de correo de Sofía conectada a HubSpot (Gmail o Outlook)

---

## Diferencia clave: Sequences vs. Workflows

| | Sequences | Workflows |
|---|---|---|
| Se pausa si el contacto responde | ✅ Sí (automático) | ❌ No |
| Ideal para | Seguimiento 1:1 personalizado | Campañas masivas |
| Sale desde la cuenta de | Sofía (personal) | Wesay (empresa) |
| Límite de contactos | 50 por día (Starter) | Sin límite |
| **Recomendación** | **Usar para todas las secuencias de seguimiento** | No usar para esto |

---

## Paso a paso: Crear una Sequence en HubSpot

### 1. Ir a Sequences
`Sales > Sequences > Crear secuencia`

### 2. Configurar los pasos
- Agregar "Step: Automated Email" por cada email de la secuencia
- Definir el delay (días de espera entre emails)
- Marcar "Pause on reply" → siempre activado

### 3. Crear las plantillas de email
- Ir a `Conversations > Templates`
- Crear una plantilla por cada email (usar los textos de este repositorio)
- Agregar tokens de personalización: `{{contact.firstname}}`, `{{company.name}}`

### 4. Enrolar contactos

**Forma manual (recomendada para deals individuales):**
1. Abrir el deal o contacto en HubSpot
2. En el panel lateral → "Enroll in sequence"
3. Seleccionar la secuencia correcta
4. Revisar y personalizar los emails antes de activar

**Forma masiva (para Seq 01b — Re-engagement):**
1. Ir a `Contacts > Lists`
2. Crear lista activa: `Deal Stage = Prospecto` AND `Last Activity Date > 30 days ago`
3. Seleccionar todos los contactos de la lista
4. "Enroll in sequence" → Seq 01b

---

## Propiedades de deal que deben estar llenas

Para que las secuencias funcionen correctamente con personalización, cada deal necesita:

| Propiedad | Por qué importa | Dónde llenarla |
|---|---|---|
| Contact firstname | Token [Nombre] en emails | Record del contacto |
| Company name | Token [Empresa] | Record del deal |
| Industry | Para elegir variante de industria | Record de la empresa |
| Last activity date | Para filtro de Seq 01b | Se actualiza automático |
| Deal stage | Trigger de secuencias | Record del deal |
| Amount | Para reporte de pipeline | Record del deal — falta en varios |
| Close date | Para priorización | Record del deal — falta en varios |

**Deals con campos incompletos (acción requerida):**
- **Fraiche** — sin monto ni fecha de cierre
- **Viva Aerobus** — sin monto ni fecha de cierre
- **Grupo Hotelero Santa Fe** — sin monto ni fecha de cierre
- **Tim Hortons** — sin monto ni fecha de cierre
- La mayoría de los deals en Prospecto — sin monto

---

## Mapa de secuencias por etapa de deal

| Etapa del deal | Secuencia a activar |
|---|---|
| Prospecto (nuevo) | Seq 01 — Activación |
| Prospecto (+30 días sin actividad) | Seq 01b — Re-engagement |
| Primera Cita / Reunión agendada | Seq 02 — Pre-reunión |
| Contacto Establecido / Demo Programada | Seq 03 — Post-reunión |
| Propuesta Enviada | Seq 04 — Seguimiento propuesta |
| Negociación | Seq 05 — Cierre |

---

## Reglas globales

1. Un deal solo puede estar en una secuencia activa a la vez
2. Siempre activar "Pause on reply" en todas las secuencias
3. Si el contacto responde → Sofía toma la conversación manualmente
4. No cruzar Sequences con Workflows de marketing en los mismos contactos
5. Revisar el dashboard de Sequences cada lunes: ver quién respondió, quién abrió sin responder, quién no abrió

---

## Dashboard de seguimiento semanal

Revisar cada lunes en `Sales > Sequences`:

- **Replied:** Prioridad máxima — responder ese mismo día
- **Opened but not replied:** Considerar llamada directa
- **Not opened:** Verificar si el email es correcto; considerar cambiar asunto
- **Bounced:** Actualizar email del contacto en HubSpot

---

## Integración con el pipeline

Configurar en HubSpot las siguientes automatizaciones de etapa:

```
Seq 01 completa sin respuesta + 30 días → enrolar en Seq 01b
Seq 04 Email 4 sin respuesta → notificación a Sofía para evaluar
Seq 05 Email 3 sin respuesta → notificación a Sofía para llamada directa
```
