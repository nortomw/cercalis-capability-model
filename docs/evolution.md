# Español

# Evolución

Las Capabilities no son elementos estáticos.

El Cercalis Capability Model considera la evolución, la madurez y la evidencia como parte del diseño de la plataforma.

## Ciclo de vida de una Capability

Una Capability progresa mediante un ciclo de vida explícito:

```text
Idea
  ↓
Diseño
  ↓
Desarrollo
  ↓
Beta
  ↓
Producción
  ↓
Optimización
  ↓
Obsoleta
```

La progresión está gobernada.

Una Capability no avanza únicamente porque su desarrollo haya terminado.

Cada estado representa un nivel diferente de definición estructural, implementación y confianza.

## De la definición a producción

A nivel conceptual:

- **Idea → Diseño** requiere una Capability suficientemente definida y diferenciable.
- **Diseño → Desarrollo** requiere que su modelo estructural esté definido.
- **Desarrollo → Beta** requiere conocimiento de validación y una vía de implementación ejecutable.
- **Beta → Producción** requiere evidencia suficiente.
- **Producción → Optimización** está impulsada por nueva evidencia procedente del uso real.
- **Obsolescencia** debe preservar la trazabilidad de dependencias y migraciones.

Los umbrales operativos detallados permanecen dentro de Cercalis.

## Calibración

La calibración representa el nivel de confianza de la plataforma en una Capability a partir de la evidencia acumulada.

> Producción es un estado de evidencia, no únicamente un estado de despliegue.

Por tanto, una Capability técnicamente desplegada y una Capability suficientemente validada no se consideran equivalentes.

La calibración se versiona para que la nueva evidencia pueda mejorar el modelo sin eliminar su historia.

## Aprendizaje a partir del uso real

La evolución de una Capability se alimenta de lo que ocurre en entornos reales:

```text
Capability
    ↓
Uso real
    ↓
Evidencia
    ↓
Calibración
    ↓
Aprendizaje
    ↓
Evolución de la Capability
```

Esto crea un ciclo controlado de retroalimentación entre lo que la plataforma conoce y lo que ocurre en entornos reales.

El conocimiento no permanece aislado de la ejecución: puede evolucionar a partir de nueva evidencia sin perder la trazabilidad de lo aprendido anteriormente.

## La reutilización como criterio de roadmap

El roadmap se organiza alrededor de Capabilities y no de funcionalidades aisladas.

Una entrada en el roadmap representa:

1. una nueva Capability, o
2. la evolución de una Capability existente.

La priorización considera factores como:

- evidencia de demanda real,
- reutilización de arquitectura, componentes y conocimiento de validación existentes,
- y madurez de las Capabilities relacionadas.

La reutilización no es únicamente una técnica de implementación.

También forma parte del criterio utilizado para decidir cómo evoluciona la plataforma.

## Evolución sin sustitución arbitraria

Cuando una Capability cambia, se mantiene la trazabilidad.

El objetivo es evitar reconstruir repetidamente el mismo conocimiento bajo diferentes implementaciones o tecnologías.

Esto resulta especialmente importante en una plataforma con arquitectura agnóstica: la tecnología puede cambiar mientras el conocimiento de negocio y estructural representado por la Capability continúa siendo comprensible y reutilizable.

## Obsolescencia gobernada

La obsolescencia también forma parte de la evolución.

Una Capability no debería desaparecer mientras existan servicios o implementaciones activas que dependan de ella sin una vía de migración o una resolución explícita de esas dependencias.

De esta forma, la evolución de una parte de la plataforma no rompe la coherencia del conjunto.

## El ciclo de evolución

El principio puede resumirse como:

```text
Comprender
    ↓
Estructurar
    ↓
Validar
    ↓
Implementar
    ↓
Medir
    ↓
Aprender
    ↓
Evolucionar
```

La tecnología participa en este ciclo.

No sustituye los criterios que lo gobiernan.

---

**Understand before building. Build to validate.**

---

# English

# Evolution

Capabilities are not static elements.

The Cercalis Capability Model treats evolution, maturity and evidence as part of the design of the platform.

## Capability lifecycle

A Capability progresses through an explicit lifecycle:

```text
Idea
  ↓
Design
  ↓
Development
  ↓
Beta
  ↓
Production
  ↓
Optimization
  ↓
Obsolete
```

Progression is governed.

A Capability does not advance simply because its development has been completed.

Each state represents a different level of structural definition, implementation and confidence.

## From definition to production

At a conceptual level:

- **Idea → Design** requires a sufficiently defined and distinguishable Capability.
- **Design → Development** requires its structural model to be defined.
- **Development → Beta** requires validation knowledge and an executable implementation path.
- **Beta → Production** requires sufficient evidence.
- **Production → Optimization** is driven by new evidence from real-world use.
- **Obsolescence** must preserve dependency and migration traceability.

Detailed operational thresholds remain internal to Cercalis.

## Calibration

Calibration represents the platform's level of confidence in a Capability based on accumulated evidence.

> Production is an evidence state, not merely a deployment state.

A technically deployed Capability and a sufficiently validated Capability are therefore not treated as equivalent.

Calibration is versioned so that new evidence can improve the model without erasing its history.

## Learning from real-world use

The evolution of a Capability is informed by what happens in real environments:

```text
Capability
    ↓
Real-world use
    ↓
Evidence
    ↓
Calibration
    ↓
Learning
    ↓
Capability evolution
```

This creates a controlled feedback loop between what the platform knows and what happens in real environments.

Knowledge does not remain isolated from execution: it can evolve through new evidence while preserving the traceability of what has previously been learned.

## Reuse as a roadmap criterion

The roadmap is organized around Capabilities rather than isolated features.

A roadmap entry represents:

1. a new Capability, or
2. the evolution of an existing Capability.

Prioritization considers factors such as:

- evidence of real demand,
- reuse of existing architecture, components and validation knowledge,
- and maturity of related Capabilities.

Reuse is therefore not only an implementation technique.

It is also part of the criteria used to determine how the platform evolves.

## Evolution without arbitrary replacement

When a Capability changes, traceability is preserved.

The objective is to avoid repeatedly rebuilding the same knowledge under different implementations or technologies.

This is particularly important in a platform with a technology-agnostic architecture: technology can change while the business and structural knowledge represented by the Capability remains understandable and reusable.

## Governed obsolescence

Obsolescence is also part of evolution.

A Capability should not disappear while active services or implementations still depend on it without a migration path or an explicit resolution of those dependencies.

In this way, the evolution of one part of the platform does not break the coherence of the whole.

## The evolution cycle

The underlying principle can be summarized as:

```text
Understand
    ↓
Structure
    ↓
Validate
    ↓
Implement
    ↓
Measure
    ↓
Learn
    ↓
Evolve
```

Technology participates in this cycle.

It does not replace the criteria that govern it.

---

**Understand before building. Build to validate.**
