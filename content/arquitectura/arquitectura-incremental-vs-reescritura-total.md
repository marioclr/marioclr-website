---
date: 2022-03-02
draft: false

title: "Arquitectura incremental vs reescritura total: decidir sin romanticismo técnico"

description: "Reescribir un sistema desde cero puede parecer una solución elegante. Pero en entornos reales, las decisiones arquitectónicas responsables suelen favorecer evolución incremental sobre cambios espectaculares."

summary: "Reescribir desde cero puede parecer atractivo. Pero en sistemas reales, la decisión correcta rara vez es la más espectacular."

weight: 4

images:
  - /images/og/arquitectura/og-arquitectura-incremental.jpg

tags:
  - arquitectura de software
  - sistemas legacy
  - modernización de sistemas
  - decisiones arquitectónicas

---

En algún punto, todo sistema enfrenta la misma conversación:

“Hay que rehacerlo desde cero.”

La propuesta suele venir acompañada de argumentos razonables:
tecnología moderna,
arquitectura limpia,
eliminar deuda técnica,
comenzar sin las decisiones del pasado.

La idea es seductora.

Pero en entornos reales, la arquitectura no puede decidir desde la seducción.

Debe decidir desde el impacto.

---

## El atractivo de la reescritura

Reescribir promete:

- Código más limpio.
- Mejor estructura.
- Eliminación de complejidad histórica.
- Nuevas tecnologías.
- Mayor motivación técnica del equipo.

Lo que rara vez se menciona es el costo invisible:

- Reaprender reglas de negocio ya resueltas.
- Reproducir errores ya superados.
- Duplicar sistemas durante la transición.
- Riesgo operativo mientras ambos conviven.

Reescribir no elimina complejidad.
La traslada.

---

## El enfoque incremental

La arquitectura incremental parte de una premisa diferente:

El sistema actual funciona.
El negocio depende de él.
La operación no puede detenerse.

En lugar de reemplazar todo, se pregunta:

- ¿Qué parte genera mayor riesgo?
- ¿Dónde está el mayor acoplamiento?
- ¿Qué puede encapsularse primero?
- ¿Qué puede evolucionar sin romper?

La modernización ocurre por capas.
Controlada.
Medible.
Reversible cuando es necesario.

---

## Riesgos y compensaciones

La reescritura total puede ofrecer claridad conceptual.
La evolución incremental ofrece estabilidad operativa.

La primera optimiza elegancia.
La segunda optimiza continuidad.

La arquitectura debe decidir qué es más crítico en ese contexto.

En sistemas que sostienen operación real, la continuidad suele ser prioridad.

---

## Lo que esta decisión revela

Elegir evolución sobre revolución no es falta de ambición.

Es comprensión sistémica.

El arquitecto no diseña solo para el código.
Diseña para el ecosistema organizacional completo.

Y ese ecosistema incluye:

- Procesos.
- Personas.
- Dependencias.
- Restricciones institucionales.
- Riesgo financiero.

---

## Principio general

La reescritura total es una decisión técnica.

La arquitectura incremental es una decisión estratégica.

La primera busca comenzar de nuevo.

La segunda busca mejorar sin poner en riesgo lo que ya funciona.

Y en entornos reales, eso marca la diferencia entre innovación y responsabilidad.