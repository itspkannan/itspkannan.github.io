# Priyesh Kannan

**Senior Software Engineer**  
📍 San Jose, CA  
📧 priyesh.kannan@gmail.com
🌐 https://itspkannan.github.io

---

## 🛠 Skills

- **Languages**: Python, Java, Groovy, C#, JavaScript  
- **Cloud**: AWS, Azure, GCP  
- **Containers**: Kubernetes (EKS/AKS/GKS, K3D), Docker  
- **Databases**: Oracle, MySQL, MongoDB, Cassandra, BigQuery, Spanner  
- **Messaging**: RabbitMQ, Kafka, AWS SQS, GCP Pub/Sub  
- **DevOps**: Jenkins, GitLab CI/CD, Terraform, Helm, Argo CD  
- **Security**: Open Policy Agent(OPA)/Rego, OAuth2, IAM, MFA  
- **Monitoring**: Prometheus, Grafana, Splunk, Datadog, Jaeger, OTEL  
- **Frameworks**: Spring/Spring Boot/Spring JPA, GraphQL, REST, CQRS, gRPC, Event-driven  
- **Testing**: Pytest, JUnit, Groovy, Mock/Powermock

--- 

## 🛠️ Personal Projects

### ☁️ AWS Microservices Lab – Local AWS Prototyping with Spring Boot & LocalStack

A modular, developer-friendly lab for building and testing AWS microservices **locally** using **Spring Boot**, **Terraform**, and **LocalStack**. Simulates real AWS services like messaging, storage, and config management—ideal for fast iteration and testing.

* 📬 Asynchronous messaging with **SNS → SQS** for event-driven flows
* 🗂️ File handling with **S3**, and runtime configuration using **SSM Parameter Store**
* 🔐 Simulated **IAM-based access control** for service-to-service auth workflows
* 🧪 Uses `LocalStack` to mock AWS services, with Docker Compose for orchestration
* 🛠️ Infra as code via **Terraform** for reproducible setup
* 🧰 Includes REST APIs (e.g. `POST /api/orders`) and example curl scripts to test flows
* 📁 Structured as a Gradle-based monorepo with shared libraries and clear service boundaries

[View on GitHub](https://github.com/itspkannan/aws-microservices-workshop-localstack) for code, infra scripts, and API examples.

### 🔐 Open Policy Agent(OPA) Workshop – Rest API Authorization using OPA

Built a modular proof-of-concept workshop demonstrating Open Policy Agent (OPA) integration in modern microservices architectures:

- ✅ Covers local, bundle server, and S3-based policy loading
- 🔒 Enforces field-level access control using Rego policies
- 🧪 Includes JWT/OAuth2-based authorization flows
- 🚀 Deployed via Docker and Helm with K3d for Kubernetes simulation

🔗 [View on GitHub](https://github.com/itspkannan/OPA-Workshop)

### Kubernetes Lab

A portfolio of Kubernetes hands-on labs, including:
- K3d setup
- NGINX ingress configuration
- Helm-based deployment of microservices

🔗 [View on GitHub](https://github.com/itspkannan/kubernetes_lab)

### 📚 Financial Studies

Exploring quantitative studies in trading, finance, and market behavior.

#### 📈 [Simulation Models](https://github.com/itspkannan/financial-models-lab)

- 🔄 Stochastic Models: Includes Random Walk and Monte Carlo Simulation techniques
- 📈 Use Cases: Applied for asset price modeling and strategy simulation in quantitative finance (TODO)

####  📰 [Event Studies](https://github.com/itspkannan/event-studies) 

- 📰 News & Events Impact: Market reactions to earnings, breaking news, and macroeconomic surprises (TODO)

#### 🧠 [Quantitative Strategy Prototyping](https://github.com/itspkannan/quant-lab)

* 📊 Technical signal prototyping using **R/Python**, **PineScript**, and **walk-forward backtesting**
* 🔁 Built strategies include **Linear Regression Curves**, **SMA Crossovers**, and **Stop‑Loss Optimization**
* 🧪 Used `quantstrat`’s **walk.forward** for repeated in/out‑of‑sample parameter optimization&#x20;
* 🌐 Developed **PineScript indicators** for visual signal alignment on TradingView
* 🧠 Conducted **ETF** & **volatility‑event research** (e.g. **VIX spikes**, **macro announcements**)

### 🛠️ Tinkerpad — Developer Tools & Learning Notes 

A growing collection of **handy scripts and snippets** that streamline common developer workflows:

* **System Design**: Generate visual diagrams from plain architecture descriptions.
* **Python + Poetry**: Rapid scaffolding of new projects (`pyproject.sh`).
* **macOS Setup**: Automate environment setup and configuration tasks.
* **Temporal Microservices**: Bootstrap and manage Temporal workflows and workers.
* **Gradle Snippets**: Reusable `build-static-analysis.gradle` for linting and quality checks.

🔗 [View on GitHub](https://github.com/itspkannan/tinkerpad)
