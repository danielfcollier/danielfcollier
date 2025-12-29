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
- **Cloud**: Refactored OpenStack SDK logic into custom microservices API integrations.
- **Systems**: Linux Automation (`systemd`, Bash), IoT/Edge (Raspberry Pi).

## 🚀 Impact & Highlights

**Magalu Cloud (Staff-Track)**
- **DBaaS Control Plane**: Leading the implementation of a **proprietary** Python/FastAPI provisioning engine. Refactored legacy OpenStack SDK logic into custom service microservices API integrations for higher stability.
- **Terraform Provider**: Fixed and hardened DBaaS resources in the official Go provider, introducing **regression testing** patterns to eliminate recurring bugs.
- **Operational Excellence**: Leading **Root Cause Analysis (RCA)** initiatives for complex outages and providing Tier-3 technical support, translating critical customer incidents into permanent architectural improvements.
- **Self-Healing Strategy**: Architecting a reconciliation layer based on Control Loop theory to automatically resolve stuck provisioning states.
- **Technical Strategy**: Authored **ADRs** and technical documentation to standardize architecture patterns across the DBaaS tribe.

**Tuna Payments**
- **Developer Experience (DX)**: Engineered a "Docs-as-Code" pipeline to auto-generate OpenAPI specs, streamlining partner integrations.
- **Integration Reliability**: Optimized the data bridge between merchant frontends and backend payment cores to ensure analytical accuracy.
- **External Integrations**: Developed .NET Core services to handle XML invoice signing and integration with municipal government APIs, ensuring compliance and reliability.

## 🧪 Open Source & PoCs

**🎤 Python Audio Framework (`umik-base-app`)**
- **Concept**: A modular, multi-threaded framework for building professional audio applications with **MiniDSP UMIK** microphones.
- **Architecture**: Implements a **Producer-Consumer** model with a **Pipeline Pattern** to decouple hardware I/O ("The Ear") from DSP ("The Brain"), ensuring glitch-free recording even on embedded devices like Raspberry Pi.
- **Features**: Real-time **LUFS/dBSPL metering**, FIR calibration filtering, zero-allocation buffering, and a suite of forensic analysis CLI tools.
- **Tech Stack**: Built with modern tooling (`uv`, `ruff`, `mypy`) and scientific libraries (`numpy`, `scipy`, `sounddevice`).
- **Links**: [📦 PyPI Page](https://pypi.org/project/umik-base-app) | [💻 Source Code](https://github.com/danielfcollier/py-umik-base-app)

**🍓 LowOps Edge AI Telemetry**
- **Concept**: A "Zero-Touch" acoustic monitoring station for edge environments (Raspberry Pi).
- **Links**: [💻 Source Code](https://github.com/danielfcollier/py-edge-ai-acoustic-monitoring-app)
- **Stack**: Python, `systemd` watchdogs, Google YamNet.
- **Status**: Production (Personal Use).

**🔄 DriftControl (Self-Healing Infrastructure Agent)**

* **Concept**: A lightweight, **GitOps-driven infrastructure agent** designed to enforce declarative configuration state in local Docker environments.
* **Architecture**: Built on a **Feedback Control Loop** pattern (Reconciler) with **Multi-Service Isolation**, ensuring that failure in one service does not stall the entire agent. Features thread-safe state management for **Exponential Backoff** strategies to handle crash loops intelligently.
* **Features**: Automated drift remediation (self-healing), integrated **Prometheus Observability** for health metrics, declarative YAML configuration, and a built-in **Chaos Monkey** for resilience testing and fault injection.
* **Tech Stack**: Built with robust tooling (`pydantic`, `docker` SDK, `prometheus-client`) and modern CLI interfaces (`rich`).
* **Link**: [💻 Source Code](https://github.com/danielfcollier/py-drift-control)

## 📜 Research & Honors

- **M.Sc. Electrical Engineering**: Focus on Modeling & Control of Wind Energy Conversion Systems (UFSC).
- **Innovation Award (1st Place)**: Awarded by **WEG Electric Corp.** for innovation in Motor Control.
- **Patent Holder**: Co-inventor of "Current Self-Control Applied to Three-Phase Electric Generators".

[LinkedIn](https://www.linkedin.com/in/danielfcollier/) | [ResearchGate](https://www.researchgate.net/profile/Daniel-A-F-Collier/research)
