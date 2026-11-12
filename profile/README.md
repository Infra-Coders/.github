# 🚀 Infra-Coders

> **Building the Kubernetes-driven platform for the AI era**\
> Kubernetes • GitOps • Platform Engineering • AI Infrastructure • Operators • FinOps

------------------------------------------------------------------------

## 🌍 Who We Are

**Infra-Coders** is a community of Infrastructure, Platform and DevOps
engineers who learn by building.

We don't just talk about cloud-native and AI technologies. We build,
integrate and operate the platform capabilities that make them work.

**Our focus: build, integrate and operate the infrastructure that powers the AI era.**

------------------------------------------------------------------------

## 🧩 Platform Primitives

We develop a **modular, Kubernetes-driven platform** as a set of
reusable **platform primitives**. These are independent capabilities
that can be developed, deployed, integrated and operated on their own,
then combined into different platform configurations.

Each primitive:

-   Lives in its own repository and has its own version
-   Is deployed declaratively through GitOps
-   States what it depends on and what it provides
-   Has a named owner and its own roadmap

We build on established open-source projects. Where there's a real
gap, we write our own tools.

------------------------------------------------------------------------

## 🗺️ Areas of Development

### 🏗️ Platform Foundations & Shared Services

-   Deployment primitives
-   Observability: metrics, monitoring, distributed tracing
-   Logging: ELK, Grafana Loki, Vector
-   Security:
    -   Container runtime security
    -   eBPF-based visibility and enforcement
    -   Policy and compliance
    -   Network security

### 🌐 Networking & Traffic Management

-   Kubernetes Ingress
-   Gateway API: NGINX Gateway Fabric, Istio, Envoy Gateway
-   Service Mesh: Istio, Ambient Mesh, ztunnel
-   Routing, TLS and service-to-service communication

### 🤖 AI Infrastructure

-   Kubernetes-native AI workloads
-   GPU orchestration
-   LLM serving and inference
-   LLM gateways
-   RAG infrastructure:
    -   Vector databases
    -   Embedding services
    -   Ingestion pipelines
-   AI agent runtime:
    -   Agent orchestration
    -   Tool execution
    -   MCP integration

### ⚙️ Platform Engineering & GitOps

-   GitOps with Flux (Argo CD as an alternative)
-   Internal Developer Platform
-   Self-service provisioning
-   Platform APIs and service catalog
-   Lifecycle automation
-   Reusable deployment patterns

### 🧠 AI-driven Operations & Operators

-   AI-driven Kubernetes Operators
-   Intelligent reconciliation
-   AI-assisted troubleshooting and incident analysis
-   Automated remediation
-   Predictive maintenance
-   Self-healing platforms

*Deterministic Kubernetes controllers combined with AI-powered analysis
and decision support.*

### 💰 Platform Economics & FinOps

-   Cloud cost allocation
-   Kubernetes resource metering
-   Usage tracking and billing
-   Showback / Chargeback
-   Cost optimization
-   AI-assisted cost analysis
-   Cost anomaly detection

------------------------------------------------------------------------

## 🎯 Initiatives

| Initiative | Scope |
|------------|-------|
| **Platform Foundations** | Kubernetes, GitOps, observability, networking, security |
| **AI Infrastructure** | GPU workloads, LLM serving, RAG, agent runtime |
| **Platform Intelligence** | AI-driven operators, self-healing, FinOps |

Each initiative has its own maintainers, roadmap and development
lifecycle.

------------------------------------------------------------------------

## 💡 Use Cases

We grow the platform through **end-to-end use cases**. Two kinds are
welcome:

-   **Platform consumer**: run something *on top of* the platform,
    e.g. a RAG chatbot over team docs
-   **Platform builder**: build a capability *into* the platform,
    e.g. zero-touch cluster bootstrap from Git, or mTLS with Ambient Mesh

Have an idea or a goal you want to learn from?

👉 [**Propose a use case**](https://github.com/Infra-Coders/ic-initiatives/issues/new?template=use-case.yml)
· [Browse proposals](https://github.com/Infra-Coders/ic-initiatives/issues?q=label%3Atype%2Fuse-case)

------------------------------------------------------------------------

## 🧭 Where to Start

-   [**ic-initiatives**](https://github.com/Infra-Coders/ic-initiatives):
    use cases, tasks and how we organize the work
-   [**IC Platform v0.1**](https://github.com/Infra-Coders/ic-initiatives/issues/15):
    the platform foundation every other use case builds on
-   [**ic-gitops-central**](https://github.com/Infra-Coders/ic-gitops-central):
    the GitOps entry point (Flux) for all platform primitives

------------------------------------------------------------------------

## 🧭 Engineering Principles

-   **Kubernetes-native**: Kubernetes is the platform foundation
-   **API-driven**: standardized APIs and declarative configuration
-   **GitOps-first**: Git is the single source of truth
-   **Composable**: independent primitives, combined freely
-   **Open source**: integrate established projects and contribute back
-   **AI-enabled**: use AI where it adds real value
-   **Security by design, observability by default**

*We don't reinvent existing technologies. We build a coherent platform
ecosystem on top of them.*

------------------------------------------------------------------------

## 🔄 Operating Model

1.  Propose a primitive or capability
2.  Take ownership → Code → Pull Request
3.  Review → Merge → Automated reconciliation
4.  Demo, iterate, evolve

------------------------------------------------------------------------

## 🤝 Join Us

As a member you can:

-   Propose and lead platform capabilities
-   Build Kubernetes operators, controllers and automation tools
-   Experiment with different technology implementations
-   Share engineering knowledge and hands-on experience
-   Contribute to open-source projects
-   Build reusable solutions that are useful beyond our community

Participation is based on genuine interest, ownership and willingness
to contribute.

📩 Contact: infra-coders@googlegroups.com

------------------------------------------------------------------------

## 📌 Status

Infra-Coders is an evolving initiative. We are moving from shared
knowledge to shared engineering, building platform capabilities
together one primitive at a time.
