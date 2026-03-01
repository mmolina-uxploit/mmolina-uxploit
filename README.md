![Hero Image](assets/banner.png "iOS Systems")

# iOS Engineering Portfolio

Exploración práctica de arquitectura y diseño de sistemas aplicada al desarrollo iOS moderno.

Los proyectos funcionan como ejercicios de ingeniería enfocados en decisiones estructurales y organización de sistemas.

---

## How to Read This Repository

Cada proyecto representa una parte específica del sistema dentro de una arquitectura modular.

---

## Core Architecture Projects

**Layer:** System Architecture / Composition

### [Feature Modular Architecture`](https://github.com/mmolina-uxploit/FavoritesFeature)

Arquitectura basada en features independientes orientada a escalabilidad de producto y equipos.

**Responsibility**

* definición de límites modulares
* dependency inversion
* composition root
* navegación desacoplada

---

**Layer:** Presentation / Domain Interaction

### [`Async State Management`](https://github.com/mmolina-uxploit/PredictiveSearch)

Gestión de estado usando Swift Concurrency para lograr flujos de datos predecibles.

**Responsibility**

* ownership del estado
* coordinación async
* cancelación de tareas
* consistencia UI

---
**Layer:** Networking Layer Design

### [`Infrastructure & Foundations`](https://github.com/mmolina-uxploit/neuro-fundations)

Diseño de una capa de red desacoplada y testeable.

**Responsibility**

* abstracción de transporte
* requests tipadas
* modelado de errores
* aislamiento de dependencias externas

---

## Design System Foundation

**Layer:** Presentation Foundation

* ### [`Base reusable de componentes UI`](https://github.com/mmolina-uxploit/DeterministicFeed)
* ### [`Tokens visuales en SwiftUI`](https://github.com/mmolina-uxploit/SemanticUI)

**Responsibility**

* design tokens
* componentes reutilizables
* consistencia visual
* independencia del dominio

---

## Stack

* Swift
* SwiftUI
* Swift Concurrency
* Combine
* Clean Architecture
* Feature Modularization
* Testing-oriented design

---

## Shared Architectural Structure

Todos los proyectos siguen la misma organización conceptual:

```id="p2k91x"
Presentation
Domain
Data
Infrastructure
```

Esto permite evolución independiente por capa y testing aislado.

---

## Navigation

Cada proyecto incluye:

* contexto del problema
* decisiones arquitectónicas
* trade-offs
* estructura interna

---
