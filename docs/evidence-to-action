# Español

# De la evidencia a la acción

Uno de los fundamentos del Cercalis Capability Model es la separación entre **diagnóstico** y **acción**.

La plataforma no debería pasar directamente de una comprobación técnica a una propuesta de implementación.

En su lugar, mantiene una cadena trazable:

```text
Modelo estructural
        │
        ▼
      Regla
        │
        ▼
    Evidencia
        │
        ▼
     Hallazgo
────────────────
   DIAGNÓSTICO
────────────────
        │
        ▼
  Recomendación
        │
        ▼
 Implementación
────────────────
      ACCIÓN
────────────────
```

## Regla

Una Regla define una condición verificable sobre una arquitectura o un componente reutilizable.

Las Reglas representan conocimiento de validación reutilizable. No dependen de un cliente específico.

## Evidencia

La Evidencia es el resultado observable producido cuando una Regla se evalúa sobre un recurso concreto.

La Evidencia es un hecho. Se mantiene deliberadamente separada de la interpretación.

## Hallazgo

Un Hallazgo es la interpretación técnica de una o varias Evidencias relacionadas.

Responde a:

> ¿Qué significan conjuntamente estas observaciones?

El Hallazgo es el punto en el que la evidencia se convierte en diagnóstico.

## Recomendación

Una Recomendación traduce un Hallazgo en una dirección accionable.

Responde a:

> ¿Qué debería hacerse?

Todavía no prescribe la ejecución técnica exacta.

## Implementación

Una Implementación describe cómo puede ejecutarse una Recomendación.

Responde a:

> ¿Cómo puede hacerse?

Una Implementación deriva, por tanto, de una cadena y no aparece de forma aislada:

```text
Evidencia
    ↓
Hallazgo
    ↓
Recomendación
    ↓
Implementación
```

## Trazabilidad

La cadena conceptual más amplia es:

```text
Arquitectura
     ↓
Componente
     ↓
Regla
     ↓
Evidencia
     ↓
Hallazgo
     ↓
Recomendación
     ↓
Implementación
```

Cada nivel añade significado sin eliminar el nivel anterior.

Esto permite relacionar una decisión con la expectativa estructural y la evidencia que la originaron.

## Por qué es importante

Separar evidencia, interpretación y acción aporta varias propiedades al modelo:

- **Explicabilidad** — las recomendaciones pueden relacionarse con evidencia observable.
- **Consistencia** — evidencias similares pueden tratarse mediante conocimiento reutilizable.
- **Auditabilidad** — las acciones tienen un origen trazable.
- **Calibración** — el conocimiento diagnóstico puede mejorar a medida que se obtiene nueva evidencia real.
- **Automatización** — las acciones pueden automatizarse de forma selectiva sin ocultar por qué existen.

El objetivo no es automatizar por automatizar.

El objetivo es automatizar, coordinar o ejecutar aquello que puede gestionarse de forma fiable, manteniendo criterios y trazabilidad en las decisiones que importan.

---

# English

# Evidence to Action

One of the foundations of the Cercalis Capability Model is the separation between **diagnosis** and **action**.

The platform should not jump directly from a technical check to a proposed implementation.

Instead, it preserves a traceable chain:

```text
Structural model
      │
      ▼
     Rule
      │
      ▼
   Evidence
      │
      ▼
    Finding
────────────────
   DIAGNOSIS
────────────────
      │
      ▼
Recommendation
      │
      ▼
Implementation
────────────────
     ACTION
────────────────
```

## Rule

A Rule defines a verifiable condition over an architecture or reusable component.

Rules represent reusable validation knowledge. They do not depend on a specific customer.

## Evidence

Evidence is the observable result produced when a Rule is evaluated on a concrete resource.

Evidence is a fact. It is deliberately separated from interpretation.

## Finding

A Finding is the technical interpretation of one or more related pieces of Evidence.

It answers:

> What do these observations mean together?

A Finding is the point at which evidence becomes diagnosis.

## Recommendation

A Recommendation translates a Finding into an actionable direction.

It answers:

> What should be done?

It deliberately does not yet prescribe the exact technical execution.

## Implementation

An Implementation describes how a Recommendation can be executed.

It answers:

> How can it be done?

An Implementation is therefore derived rather than isolated:

```text
Evidence
   ↓
Finding
   ↓
Recommendation
   ↓
Implementation
```

## Traceability

The broader conceptual chain is:

```text
Architecture
    ↓
Component
    ↓
Rule
    ↓
Evidence
    ↓
Finding
    ↓
Recommendation
    ↓
Implementation
```

Each level adds meaning without erasing the level before it.

This makes it possible to relate a decision back to the structural expectation and the evidence that originated it.

## Why this matters

Separating evidence, interpretation and action supports:

- **Explainability** — recommendations can be related to observable evidence.
- **Consistency** — similar evidence can be treated through reusable knowledge.
- **Auditability** — actions have a traceable origin.
- **Calibration** — diagnostic knowledge can improve as more real evidence becomes available.
- **Automation** — actions can be automated selectively without hiding why they exist.

The objective is not automation for its own sake.

The objective is to automate, coordinate or execute what can be handled reliably while preserving criteria and traceability for the decisions that matter.
