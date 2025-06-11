# Welcome to the FAIR Package Manager Project

The FAIR Package Manager is an open-source initiative backed by the Linux Foundation. Our goal is to rethink how software is distributed and managed in the world of open web publishing. We focus on decentralization, transparency, and giving users more control. Our community brings together developers, infrastructure providers, and open web contributors and advocates who all share the same mission: to move away from centralized systems and empower site owners and hosting providers with greater independence.

FAIR is governed through open working groups and consensus-driven processes, ensuring that its development reflects the needs of the broader community. Whether you're a contributor, a host, or an end user, FAIR invites participation at every level, from writing code and documentation, to community organisation and governance. As a community-led project, we aim to build public digital infrastructure that is both resilient and fair.

> [!TIP]
> [**Ready to try FAIR? Download the plugin now →**](https://github.com/fairpm/fair-plugin/releases)

### 🚀 Technology

The FAIR Package Manager is a decentralized alternative to the central WordPress.org plugin and theme ecosystem. Services on WordPress.org are expensive to maintain and centralized. In order to help strengthen the future of the whole WordPress ecosystem, FAIR was built to reduce reliance and burden on the central WordPress.org services. It operates as a drop-in WordPress plugin, seamlessly replacing existing centralized services with a federated, open-source infrastructure.

There are two core pillars of the FAIR system:

* **API Replacement:** FAIR provides replacement implementations of the key services that are currently centralized on WordPress.org. It replaces services such as update checks and event feeds with local or FAIR-governed alternatives. Some features—like browser version checks—are handled entirely within the plugin using embedded logic (e.g., browserslist).

* **Decentralized Package Management:** FAIR introduces a new package distribution model for themes and plugins. It supports opt-in packages that use the FAIR protocol and enables hosts to configure their own mirrors for plugin/theme data using AspirePress or their own domains. While stable plugins currently use mirrors of WordPress.org, future versions will fully support FAIR-native packages.

Hosts can distribute FAIR to their customers via:

* **Standalone Plugin:** Easily installed on existing WordPress sites.
* **FAIR Distro:** A full WordPress distribution with FAIR preinstalled—ideal for provisioning workflows.

Hosts may also configure their own repository mirrors and toggle settings like Gravatar use. With minimal setup and modular architecture, the FAIR system ensures technical independence, resilience, and long-term sustainability for WordPress deployments.

### 📚 Learn about the project

* [Getting Started Guide](https://github.com/fairpm/tsc/blob/main/getting-started.md) - Start here to learn about getting involved with the project!
* [Contributing Guide](https://github.com/fairpm/tsc/blob/main/contributing.md) - Learn about the project structure, Technical Steering Committee (TSC), working groups and the governance process.
* [Technical Steering Committee Charter](https://github.com/fairpm/tsc/blob/main/charter.md) - Our charter outlines our governance model.
* [Code of Conduct](https://github.com/fairpm/tsc/blob/main/code-of-conduct.md) - Our code of conduct outlines how we keep our open source project welcoming and safe.
* [Working Groups](https://github.com/fairpm/tsc/tree/main/working-groups) - Learn about our current project focuses.
* [FAQ](https://github.com/fairpm/tsc/blob/main/faqs/README.md) - Our FAQ. Because sometimes, starting with someone else's questions is easiest.

### ✏️ Working Groups Overview

#### [Community WG](https://github.com/fairpm/tsc)

* Focus: Documentation, onboarding, and contributor processes.
* Goal: Support newcomers and streamline project participation.

#### [Technical Independence](https://github.com/fairpm/fair-plugin)

* Focus: Create infrastructure to provide federated implementations of the WordPress.org services.
* Includes: Mirror API server, FAIR-enabled plugin, and WP distro packaging.

#### [FAIR](https://github.com/fairpm/fair-protocol)

* Focus: Long-term development and maintenance of the FAIR protocol and related systems.
* Includes: Protocol spec, aggregator, repository nodes, analytics, and connector plugin.

<sub>The FAIR Package Manager Project is hosted by the [Linux Foundation](https://www.linuxfoundation.org/) </sub>
