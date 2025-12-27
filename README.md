# Staff Platform Engineer (M.Sc.)

> "Applying Engineering Rigor to Cloud Infrastructure."

I am a **Staff Platform Engineer** specializing in **Reliability**, **Internal Developer Platforms (IDP)**, and **Control Planes**.

With a background in **Control Theory (M.Sc.)** and 12+ years in software, I treat infrastructure as a deterministic system. I apply feedback loops, state convergence, and stability analysis to build self-healing cloud platforms.

### 🧠 The Philosophy: LowOps
I build "Golden Paths" and automation tools that allow engineering teams to ship features without getting bogged down in operations.
- **Platform Engineering**: Architecting control planes that standardize the lifecycle of stateful workloads.
- **Reliability Engineering**: Designing systems that detect and resolve their own faults (Self-Healing).

## 🛠️ Technical Stack

**Platform & Automation**
- **Languages**: Python (Expert - FastAPI, Multithreading, State Machines), Go (Tooling/Providers).
- **Architecture**: Microservices, Event-Driven Architecture (EDA), RESTful APIs.
- **Orchestration**: Kubernetes (Workload Management), Terraform (Provider Dev), Ansible.
- **Observability**: OpenTelemetry, Prometheus/Grafana, SLI/SLO Design, RCA.

**Infrastructure & Systems**
- **Cloud**: Refactored OpenStack SDK logic into service API integrations.
- **Systems**: Linux Automation (`systemd`, Bash), IoT/Edge (Raspberry Pi).

## 🚀 Impact & Highlights

**Magalu Cloud (Staff-Track)**
- **DBaaS Control Plane**: Leading the implementation of the Python/FastAPI provisioning engine for the public cloud's database service. Refactored legacy OpenStack SDK logic into service API integrations for higher stability.
- **Terraform Provider**: Fixed and hardened DBaaS resources in the official Go provider, introducing **regression testing** patterns to eliminate recurring bugs.
- **Self-Healing Strategy**: Architecting a reconciliation layer based on Control Loop theory to automatically resolve stuck provisioning states.
- **Technical Strategy**: Authored **ADRs** and technical documentation to standardize architecture patterns across the DBaaS tribe.

**Tuna Payments**
- **Developer Experience (DX)**: Engineered a "Docs-as-Code" pipeline to auto-generate OpenAPI specs, streamlining partner integrations.
- **Integration Reliability**: Optimized the data bridge between merchant frontends and backend payment cores to ensure analytical accuracy.
- **External Integrations**: Developed .NET Core services to handle XML invoice signing and integration with municipal government APIs, ensuring compliance and reliability.

## 🧪 Open Source & PoCs

**1. Python Pipeline Framework (PyPI)**
- **Concept**: A thread-safe "Producer-Consumer" library for building concurrent background workers.
- **Links**: [📦 PyPI Page](https://pypi.org/project/umik-base-app) | [💻 Source Code](https://github.com/danielfcollier/py-umik-base-app)
- **Goal**: A **LowOps** tool to simplify async processing without heavy frameworks.

**2. LowOps Edge AI Telemetry**
- **Concept**: A "Zero-Touch" acoustic monitoring station for edge environments.
- **Links**: [💻 Source Code](https://github.com/danielfcollier/py-edge-ai-acoustic-monitoring-app)
- **Stack**: Python, `systemd` watchdogs, Google YamNet.
- **Status**: Production (Personal Use).

<!--
**3. DriftControl (Self-Healing Loop)**
- **Concept**: A proof-of-concept **Control Plane** component.
- **Logic**: Implements a `Look -> Compare -> Converge` loop (Feedback Control) to enforce configuration state.
- **Goal**: Eliminates "Configuration Drift" by automatically reverting manual changes without human intervention.
- **Status**: POC (Python).
-->

## 📜 Research & Honors

- **M.Sc. Electrical Engineering**: Focus on Modeling & Control of Wind Energy Conversion Systems (UFSC).
- **Innovation Award (1st Place)**: Awarded by **WEG Electric Corp.** for innovation in Motor Control.
- **Patent Holder**: Co-inventor of "Current Self-Control Applied to Three-Phase Electric Generators".

[LinkedIn](https://www.linkedin.com/in/danielfcollier/) | [ResearchGate](https://www.researchgate.net/profile/Daniel-A-F-Collier/research)
