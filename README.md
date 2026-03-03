![Hero Image](assets/banner.png "iOS Systems Architecture")

# THE iOS ENGINEERING CORE
### Software Design Research | Mobile Systems Architecture

Repositorio central de investigación aplicada al desarrollo de sistemas móviles. Cada proyecto aquí listado es un nodo de evidencia técnica diseñado bajo dos principios innegociables: **Arquitectura Invisible** y **Reducción Radical de la Complejidad**.

---

## 🏗️ Core Architecture & Composition
*La capa superior donde se definen los límites del sistema y la inversión de dependencias.*

### [FavoritesFeature](https://github.com/mmolina-uxploit/FavoritesFeature)
**Tesis:** Gestión de fronteras y resiliencia al cambio de infraestructura.
* **Foco:** Arquitectura Hexagonal y aislamiento total del dominio.
* **Integridad:** Uso de TDD como linter arquitectónico para prevenir la erosión de límites.

---

## 🚦 State & Interaction Management
*El motor de ejecución. Cómo transformar el flujo de datos en estados predecibles.*

### [PredictiveSearch](https://github.com/mmolina-uxploit/PredictiveSearch)
**Tesis:** Determinismo en flujos de datos asíncronos.
* **Foco:** Swift Concurrency y gestión de propiedad del estado (*State Ownership*).
* **Resultado:** Eliminación de condiciones de carrera y efectos secundarios no controlados.

---

## 🛠️ Infrastructure & Foundations
*La base técnica. Abstracción de detalles volátiles y protocolos externos.*

### [neuro-foundations](https://github.com/mmolina-uxploit/neuro-fundations)
**Tesis:** Desacoplamiento de infraestructura y contratos de red inmutables.
* **Foco:** Networking modular, peticiones tipadas y modelado exhaustivo de errores.
* **Propósito:** Blindar el núcleo del sistema frente a cambios en proveedores externos.

---

## 🎨 Presentation & Design Systems
*La interfaz como detalle. Estética atómica desacoplada de la lógica de negocio.*

### [DeterministicFeed](https://github.com/mmolina-uxploit/DeterministicFeed)
**Tesis:** Reutilización de componentes bajo contratos de presentación estrictos.
* **Foco:** Feed dinámico basado en composición de componentes puros.

### [SemanticUI](https://github.com/mmolina-uxploit/SemanticUI)
**Tesis:** Tokens visuales y diseño sistémico en SwiftUI.
* **Foco:** Independencia del dominio y consistencia visual mediante abstracción semántica.

---

## 🧬 Engineering Principles

* **Inmutabilidad por diseño:** El estado es una constante hasta que la lógica de negocio dicta lo contrario.
* **Desacoplamiento Atómico:** Los frameworks son detalles de implementación, no el corazón del sistema.
* **Testing de Contrato:** Validación de fronteras para garantizar la estabilidad a largo plazo.

> "Mi objetivo no es escribir código rápido, sino diseñar sistemas tan claros que su complejidad resulte invisible."

---
