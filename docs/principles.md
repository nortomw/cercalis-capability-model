# Español (inglés abajo)

# Principios

El Cercalis Capability Model se construye alrededor de una idea sencilla:

> La plataforma no se organiza alrededor de funcionalidades ni de tecnologías. Se organiza alrededor de capacidades.

Una **Capability** es una unidad concreta de conocimiento reutilizable que la plataforma puede analizar, recomendar, implementar y mantener con un nivel de calidad conocido.

Una Capability constituye la unidad mínima de evolución del sistema.

> No se desarrollan funcionalidades.  
> Se desarrollan capacidades.

## 1. Single source of truth

Existe un único modelo de capacidades.

Estrategia, producto, desarrollo, análisis, implementación y servicios utilizan la misma referencia conceptual en lugar de mantener definiciones desconectadas.

El Capability Model no sustituye a la arquitectura técnica. La complementa proporcionando un lenguaje común de negocio y operación.

## 2. Evolución incremental

Las Capabilities evolucionan en lugar de ser sustituidas arbitrariamente.

Las nuevas versiones mantienen la trazabilidad para que la plataforma pueda comprender cómo evolucionan el conocimiento, la estructura y la implementación a lo largo del tiempo.

## 3. Madurez conocida

Cada Capability tiene un estado de madurez explícito.

Una Capability progresa mediante un ciclo de vida gobernado, en lugar de considerarse preparada para producción simplemente porque exista una implementación.

**Idea → Diseño → Desarrollo → Beta → Producción → Optimización → Obsoleta**

El objetivo es hacer visible el nivel de confianza existente en cada Capability.

## 4. Evolución basada en evidencia

Una Capability no alcanza Producción sin evidencia suficiente.

La evidencia puede proceder del análisis real, las implementaciones, la calibración y la validación manual.

Esto permite distinguir entre **ser técnicamente posible** y **estar suficientemente validado para ser confiable**.

## 5. Reutilización por diseño

Las Capabilities deben reutilizar el conocimiento arquitectónico, los componentes y las reglas de validación existentes siempre que sea posible.

Los elementos reutilizables se diseñan independientemente de clientes concretos.

## 6. Independencia

Una Capability no pertenece a un cliente específico.

Representa conocimiento reutilizable que puede dar soporte a múltiples implementaciones, servicios y contextos.

## 7. La tecnología como elección de implementación

La tecnología da soporte a una Capability; no define el propósito de la plataforma.

El contexto de negocio, el conocimiento estructural y la tecnología de implementación se mantienen como conceptos diferenciados.

## 8. Trazabilidad

El modelo conecta qué se esperaba, qué se ha observado, qué significa y qué debería hacerse.

El resultado es un sistema en el que las decisiones pueden relacionarse con criterios explícitos.

---

**First the criteria. Then the tool.**

---

# English

# Principles

The Cercalis Capability Model is built around a simple idea:

> The platform is not organized around features or technologies. It is organized around capabilities.

A **Capability** is a concrete unit of reusable knowledge that the platform can analyze, recommend, implement and maintain with a known level of quality.

A Capability is the minimum unit of evolution of the system.

> We do not develop isolated features.  
> We develop capabilities.

## 1. Single source of truth

There is one capability model.

Strategy, product, development, analysis, implementation and services use the same conceptual reference instead of maintaining disconnected definitions.

The capability model does not replace technical architecture. It complements it by providing a common business and operational language.

## 2. Incremental evolution

Capabilities evolve rather than being arbitrarily replaced.

New versions preserve traceability so that the platform can understand how knowledge, structure and implementation change over time.

## 3. Known maturity

Every Capability has an explicit maturity state.

A Capability progresses through a governed lifecycle rather than becoming “production ready” simply because an implementation exists.

`Idea → Design → Development → Beta → Production → Optimization → Obsolete`

The purpose is to make the level of confidence in each Capability visible.

## 4. Evidence-driven progression

A Capability does not reach Production without sufficient evidence.

Evidence can come from real analysis, implementations, calibration and manual validation.

This separates **being technically possible** from **being sufficiently validated to be trusted**.

## 5. Reuse by design

Capabilities should reuse existing architectural knowledge, components and validation rules whenever possible.

Reusable elements are designed independently from individual customers.

## 6. Independence

A Capability does not belong to a specific customer.

It represents reusable knowledge that can support multiple implementations, services and contexts.

## 7. Technology as an implementation choice

Technology supports a Capability; it does not define the purpose of the platform.

Business context, structural knowledge and implementation technology remain distinguishable concepts.

## 8. Traceability

The model connects what is expected, what is observed, what it means and what should be done.

The result is a system in which decisions can be related back to explicit criteria.

---

**First the criteria. Then the tool.**
