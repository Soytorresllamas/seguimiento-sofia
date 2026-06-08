# Secuencia 01 — Activación de Prospecto

**Trigger:** Deal creado o movido a etapa "Prospecto"
**Objetivo:** Conseguir una primera reunión en los primeros 10 días
**Duración:** 4 emails · 10 días
**Pausa si:** El contacto responde o agenda reunión

---

## Flujo

```
[Deal en Prospecto]
        │
    Email 1 (Día 0) — Apertura con pregunta
        │
    Email 2 (Día 3) — Insight de industria
        │
    Email 3 (Día 7) — CTA directa
        │
    Email 4 (Día 10) — Cierre respetuoso
        │
[Secuencia completa → mover a Seq 01b en 30 días si no responde]
```

---

## Email 1 — Apertura

**Asunto (opción A):** ¿Cómo entrena [Empresa] a sus equipos operativos?
**Asunto (opción B):** Capacitar a equipos en campo es otro mundo
**Preview text:** No es lo mismo que entrenar a personas de oficina, y los métodos tampoco.

---

Hola [Nombre],

Sé que capacitar a equipos operativos en [Empresa] — los que están en piso, en campo, en ruta — es completamente diferente a entrenar a personas de escritorio.

Los cursos largos no funcionan. La gente no los completa. Y cuando hay rotación, el conocimiento se va con las personas.

En Wesay resolvemos exactamente eso: formación práctica, en celular, en menos de 5 minutos por sesión, que los equipos realmente terminan.

¿Tiene sentido que hablemos 15 minutos esta semana?

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Email 2 — Insight de industria

**Asunto (opción A):** El problema que tiene [Industria] con la capacitación
**Asunto (opción B):** Por qué el 70% del personal operativo no completa sus cursos
**Preview text:** No es falta de interés. Es que el formato no está diseñado para ellos.

---

Hola [Nombre],

Te comparto un dato que aparece en casi todas las empresas con equipos operativos grandes:

**El 70% del personal de campo, piso o ruta no completa los programas de capacitación tradicionales.** No porque no quieran aprender — sino porque los formatos (cursos de 45 minutos, plataformas de escritorio, materiales impresos) no encajan con su realidad.

En [Industria], esto se traduce en errores operativos, inconsistencia en el servicio, y un costo enorme de re-entrenamiento cada vez que hay rotación.

Wesay funciona diferente: microvideos de 3-5 minutos, desde el celular, con seguimiento en tiempo real para los líderes.

¿Te cuento cómo lo hemos implementado en empresas similares a [Empresa]?

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Email 3 — CTA directa

**Asunto (opción A):** 15 minutos — te muestro algo concreto
**Asunto (opción B):** Una demo rápida vale más que esta descripción
**Preview text:** Sin presentaciones largas. Te enseño el producto en funcionamiento real.

---

Hola [Nombre],

Te he escrito un par de veces sobre cómo Wesay ayuda a empresas como [Empresa] a capacitar equipos operativos de forma efectiva.

Quiero ser directa: 15 minutos en videollamada y te muestro la plataforma funcionando con un caso real de [Industria].

Sin pitch largo. Sin presentación de 40 slides. Solo te enseño el producto y tú decides si tiene sentido para [Empresa].

¿Esta semana o la siguiente te funciona?

[Enlace de agenda aquí]

Sofía Sánchez
Directora de Operaciones · Wesay

---

## Email 4 — Cierre respetuoso

**Asunto (opción A):** Última nota de mi parte por ahora
**Asunto (opción B):** Cerrando este ciclo — sin compromiso
**Preview text:** Si el momento no es ahora, no hay problema. Aquí seguimos.

---

Hola [Nombre],

Te he escrito varias veces sin respuesta — lo entiendo perfectamente. Las agendas operativas no dan respiro.

Si la capacitación de equipos no es una prioridad ahora mismo, no hay problema. Te dejo este mensaje por si en los próximos meses el tema sube en la lista.

Cuando sea el momento, aquí estamos.

Sofía Sánchez
Directora de Operaciones · Wesay

*PD: Si prefieres que no te escriba más, me dices y con gusto lo respeto.*

---

## Notas de configuración en HubSpot

- Crear como **Sequence** (no Workflow) para que se pause automáticamente con respuesta
- Sender: cuenta de correo de Sofía
- Enrollment: manual al crear deal, o automático por etapa
- Exit condition: deal stage cambia a cualquier etapa mayor a Prospecto
