# Cercalis Capability Model

Fundamento conceptual de Cercalis: un modelo basado en capacidades para conectar necesidades de negocio, orquestación, servicios, automatización, inteligencia artificial y tecnología.

## El principio

Cercalis no se organiza alrededor de funcionalidades ni de tecnologías.

**Se organiza alrededor de capacidades.**

El Capability Model proporciona un lenguaje común para conectar estrategia, producto, desarrollo, análisis, implementación y servicios, manteniendo la coherencia a medida que la plataforma evoluciona.

## ¿Qué es una Capability?

Una Capability representa una combinación concreta de conocimiento que la plataforma puede analizar, recomendar, implementar y mantener con un nivel de calidad conocido.

Una Capability constituye la **unidad mínima de evolución del sistema**.

> No se desarrollan funcionalidades.  
> Se desarrollan capacidades.

## Principios del modelo

### Single source of truth

Un único modelo de capacidades consumido por las distintas áreas.

### Evolución incremental

Una capacidad evoluciona manteniendo trazabilidad.

### Madurez conocida

Las capacidades tienen un ciclo de vida explícito.

### Evidence-driven

Una capacidad no llega a producción sin evidencia suficiente.

### Reutilización

Los componentes se diseñan para reutilizarse.

### Independencia

Una capacidad representa conocimiento reutilizable y no pertenece a un cliente concreto.

## Del negocio a la evolución

Una Capability conecta el contexto de negocio con la estructura, la validación, la acción y la evolución.

![Cercalis Capability Model]capability-model.svg

El modelo permite mantener relacionadas distintas capas de conocimiento sin convertirlas en una única cosa:

**Necesidad de negocio → Capability → Estructura → Validación → Acción → Servicios → Evidencia → Evolución**

La tecnología participa en este modelo como medio de implementación, no como punto de partida.

## De la evidencia a la acción

Cercalis separa explícitamente lo que observa, lo que interpreta y la acción que finalmente puede ejecutarse.

![Evidence to Action]evidence-to-action.svg

La cadena conceptual es:

**Regla → Evidencia → Hallazgo → Recomendación → Implementación**

- **Regla** define una condición verificable.
- **Evidencia** representa un hecho observado.
- **Hallazgo** interpreta el significado de una o varias evidencias.
- **Recomendación** establece qué debería hacerse.
- **Implementación** define cómo puede ejecutarse.

Esta separación permite mantener trazabilidad entre diagnóstico y acción.

## Implementación ≠ Servicio

El modelo distingue deliberadamente ambos conceptos.

Una **Implementación** corrige o mejora una solución existente.

Un **Servicio** amplía las capacidades disponibles para el cliente.

Esta separación permite que conocimiento, implementación y oferta de servicios puedan evolucionar de forma independiente pero coordinada.

## Evolución basada en evidencia

Las Capabilities no son elementos estáticos.

Evolucionan mediante un ciclo de vida explícito:

**Idea → Diseño → Desarrollo → Beta → Producción → Optimización → Obsoleta**

Llegar a producción no depende únicamente de que algo pueda construirse o desplegarse.

Requiere evidencia suficiente para alcanzar el nivel de confianza definido para la Capability.

El uso real genera nueva evidencia, la evidencia permite calibrar el conocimiento y esa calibración alimenta la evolución del modelo.

## Un roadmap de capacidades

El roadmap de Cercalis tampoco se construye como una lista de funcionalidades.

Cada incorporación representa:

- una nueva Capability, o
- la evolución de una Capability existente.

La demanda real, la reutilización del conocimiento existente y la madurez de las capacidades relacionadas forman parte del criterio de evolución.

## Documentación

La documentación pública del modelo se divide en cuatro áreas:

- [Principios](docs/principles.md) — principios que gobiernan el modelo.
- [Capability Model](docs/capability-model.md) — estructura conceptual de una Capability y sus relaciones.
- [De la evidencia a la acción](docs/evidence-to-action.md) — trazabilidad desde la validación hasta la implementación.
- [Evolución](docs/evolution.md) — madurez, evidencia, calibración y evolución de capacidades.

## Sobre este repositorio

Este repositorio presenta la **fundamentación conceptual pública** del Capability Model utilizado en Cercalis.

No contiene la implementación interna de la plataforma, reglas operativas, modelos de scoring, criterios de calibración, catálogos internos ni lógica propietaria.

Su objetivo es mostrar el enfoque utilizado para conectar necesidades de negocio, conocimiento reutilizable, tecnología y evolución de plataforma.

---

**First the criteria. Then the tool.**

**Understand before building. Build to validate.**

[Cercalis](https://cercalis.com)

---

# English

# Cercalis Capability Model

Conceptual foundation of Cercalis: a capability-driven model for connecting business needs, orchestration, services, automation, artificial intelligence and technology.

## The principle

Cercalis is not organized around features or technologies.

**It is organized around capabilities.**

The Capability Model provides a common language for connecting strategy, product, development, analysis, implementation and services while maintaining coherence as the platform evolves.

## What is a Capability?

A Capability represents a concrete combination of knowledge that the platform can analyze, recommend, implement and maintain with a known level of quality.

A Capability is the **minimum unit of evolution of the system**.

> We do not develop features.  
> We develop capabilities.

## Model principles

### Single source of truth

A single capability model consumed across the different areas of the platform.

### Incremental evolution

A capability evolves while maintaining traceability.

### Known maturity

Capabilities have an explicit lifecycle.

### Evidence-driven

A capability does not reach production without sufficient evidence.

### Reusability

Components are designed to be reused.

### Independence

A capability represents reusable knowledge and does not belong to a specific customer.

## From business to evolution

A Capability connects business context with structure, validation, action and evolution.

![Cercalis Capability Model](diagrams/capability-model.svg)

The model keeps different layers of knowledge connected without turning them into the same concept:

**Business Need → Capability → Structure → Validation → Action → Services → Evidence → Evolution**

Technology participates in this model as a means of implementation, not as the starting point.

## From evidence to action

Cercalis explicitly separates what is observed, what is interpreted and the action that can ultimately be executed.

![Evidence to Action](diagrams/evidence-to-action.svg)

The conceptual chain is:

**Rule → Evidence → Finding → Recommendation → Implementation**

- **Rule** defines a verifiable condition.
- **Evidence** represents an observed fact.
- **Finding** interprets the meaning of one or more pieces of evidence.
- **Recommendation** defines what should be done.
- **Implementation** defines how it can be executed.

This separation maintains traceability between diagnosis and action.

## Implementation ≠ Service

The model deliberately distinguishes between these two concepts.

An **Implementation** corrects or improves an existing solution.

A **Service** expands the capabilities available to the customer.

This separation allows knowledge, implementation and service offerings to evolve independently while remaining coordinated.

## Evidence-driven evolution

Capabilities are not static elements.

They evolve through an explicit lifecycle:

**Idea → Design → Development → Beta → Production → Optimization → Obsolete**

Reaching production does not depend solely on whether something can be built or deployed.

It requires sufficient evidence to reach the level of confidence defined for the Capability.

Real-world use generates new evidence, evidence enables calibration of knowledge, and that calibration feeds the evolution of the model.

## A capability-driven roadmap

The Cercalis roadmap is not built as a list of features either.

Each addition represents:

- a new Capability, or
- the evolution of an existing Capability.

Real demand, reuse of existing knowledge and the maturity of related capabilities are part of the evolution criteria.

## Documentation

The public documentation of the model is divided into four areas:

- [Principles](docs/principles.md) — principles governing the model.
- [Capability Model](docs/capability-model.md) — conceptual structure of a Capability and its relationships.
- [Evidence to Action](docs/evidence-to-action.md) — traceability from validation to implementation.
- [Evolution](docs/evolution.md) — maturity, evidence, calibration and capability evolution.

## About this repository

This repository presents the **public conceptual foundation** of the Capability Model used by Cercalis.

It does not contain the platform's internal implementation, operational rules, scoring models, calibration criteria, internal catalogs or proprietary logic.

Its purpose is to present the approach used to connect business needs, reusable knowledge, technology and platform evolution.

---

**First the criteria. Then the tool.**

**Understand before building. Build to validate.**

[Cercalis](https://cercalis.com)
