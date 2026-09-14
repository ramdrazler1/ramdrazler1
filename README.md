<div align="center">

<a href="https://github.com/ramdrazler1">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0D1117,50:161B22,100:21262D&text=RAMKUMAR&fontColor=58A6FF&fontSize=54&fontAlignY=38&desc=DEVOPS%20ENGINEER%20%7C%20CLOUD%20%7C%20KUBERNETES%20%7C%20PLATFORM%20ENGINEERING&descColor=C9D1D9&descSize=17&descAlignY=61&animation=fadeIn" width="100%"/>
</a>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=19&duration=2800&pause=700&color=58A6FF&center=true&vCenter=true&width=900&lines=Cloud+Infrastructure+Engineer;Kubernetes+%7C+AWS+%7C+Terraform+%7C+Jenkins;CI%2FCD+%7C+Docker+%7C+GitHub+Actions;Platform+Engineering+%7C+DevSecOps+%7C+SRE;Automate+%E2%86%92+Secure+%E2%86%92+Deploy+%E2%86%92+Observe+%E2%86%92+Improve" />

<br/><br/>

<a href="https://github.com/ramdrazler1">
<img src="https://img.shields.io/badge/GitHub-ramdrazler1-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://aws.amazon.com/">
<img src="https://img.shields.io/badge/AWS-Cloud-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
</a>
<a href="https://kubernetes.io/">
<img src="https://img.shields.io/badge/Kubernetes-EKS-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
</a>
<a href="https://www.jenkins.io/">
<img src="https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
</a>
<a href="https://www.terraform.io/">
<img src="https://img.shields.io/badge/Terraform-IaC-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
</a>

</div>

---

## ⚡ Engineering at a Glance

<div align="center">

<table>
<tr>
<td align="center" width="20%"><b>☁️ CLOUD</b><br/><sub>AWS · EKS · EC2 · VPC · IAM</sub></td>
<td align="center" width="20%"><b>🚀 DELIVERY</b><br/><sub>Jenkins · GitHub Actions</sub></td>
<td align="center" width="20%"><b>☸️ PLATFORM</b><br/><sub>Kubernetes · Helm · KEDA</sub></td>
<td align="center" width="20%"><b>🏗️ IaC</b><br/><sub>Terraform · Terragrunt · Ansible</sub></td>
<td align="center" width="20%"><b>📊 SRE</b><br/><sub>Prometheus · Grafana · Alerting</sub></td>
</tr>
</table>

</div>

---

# 👨‍💻 About Me

I'm a **DevOps Engineer focused on cloud infrastructure, CI/CD engineering, Kubernetes platforms, infrastructure automation, and production reliability**.

I design systems around a simple principle:

> **Developers should have a paved road from code to production, while infrastructure teams retain control over security, reliability, scalability, and cost.**

### What I care about

- ⚡ Faster and safer software delivery
- ☁️ Scalable AWS infrastructure
- ☸️ Production-grade Kubernetes platforms
- 🔄 Reproducible Infrastructure as Code
- 🔐 Security throughout the delivery lifecycle
- 📊 Observable systems and actionable alerting
- 💰 Continuous cloud cost optimization
- 🤖 Automation of repetitive operational work
- 🧩 Internal Developer Platforms

---

# 🌌 The Platform I Engineer

<div align="center">

<img src="https://raw.githubusercontent.com/ramdrazler1/devops-portfolio/main/assets/platform-architecture.svg" width="96%" alt="Platform architecture"/>

</div>

> If the custom architecture image is not available in the repository, the section below provides the same architecture in Markdown.

<div align="center">

```mermaid
flowchart TB
    Developer["👨‍💻 Developer"] --> Git["Git / Pull Request"]
    Git --> CI["🚀 CI/CD"]

    CI --> Test["Unit Tests"]
    CI --> Security["Security"]
    CI --> Quality["Quality Gates"]

    Test --> Build["🐳 Container Build"]
    Security --> Build
    Quality --> Build

    Build --> Registry["📦 Container Registry"]
    Registry --> Platform["☸️ Kubernetes Platform"]

    Platform --> Workloads["Application Workloads"]
    Platform --> Scaling["HPA / KEDA / Karpenter"]
    Platform --> Network["Ingress / Gateway / Service Mesh"]

    Workloads --> Observe["📊 Observability"]
    Scaling --> Observe
    Network --> Observe

    Observe --> Metrics["Prometheus"]
    Observe --> Dashboards["Grafana"]
    Observe --> Alerts["Alerting"]

    Alerts --> Engineering["Engineering Feedback"]
    Engineering --> CI
```

</div>

---

# 🔄 DevOps Automation Loop

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=16&duration=2200&pause=500&color=58A6FF&center=true&vCenter=true&width=950&lines=PLAN+%E2%86%92+CODE+%E2%86%92+BUILD+%E2%86%92+TEST+%E2%86%92+SECURE;PACKAGE+%E2%86%92+DEPLOY+%E2%86%92+OBSERVE+%E2%86%92+OPTIMIZE+%E2%86%92+REPEAT;Infrastructure+%2B+Automation+%2B+Observability+%3D+Reliable+Delivery" />

</div>

---

# ☁️ AWS Cloud Engineering

<table>
<tr>
<td width="50%" valign="top">

### Infrastructure

- EC2
- VPC
- Private Subnets
- ALB
- Route 53
- IAM
- Security Groups

</td>
<td width="50%" valign="top">

### Containers & Delivery

- Amazon EKS
- Amazon ECR
- Jenkins
- GitHub Actions
- Docker
- Terraform

</td>
</tr>
</table>

### AWS Architecture

<div align="center">

```mermaid
flowchart TB
    Internet((Internet)) --> ALB["Application Load Balancer"]
    ALB --> VPC["VPC / Private Subnets"]
    VPC --> EKS["Amazon EKS"]

    IAM["IAM / Least Privilege"] -.-> EKS
    Terraform["Terraform"] -.-> VPC
    Terraform -.-> EKS

    EKS --> Pods["Application Pods"]
    Karpenter["Karpenter"] --> Nodes["EC2 Nodes"]
    Nodes --> Pods

    Pods --> Prometheus["Prometheus"]
    Prometheus --> Grafana["Grafana"]
```

</div>

---

# ☸️ Kubernetes Platform Engineering

<div align="center">

<table>
<tr>
<td width="33%" align="center">

### 🧩 Workloads

Deployments  
StatefulSets  
Jobs  
CronJobs  
ConfigMaps  
Secrets

</td>
<td width="33%" align="center">

### 🌐 Networking

Services  
Ingress  
Gateway API  
HTTPRoute  
Istio  
Load Balancing

</td>
<td width="33%" align="center">

### 📈 Scaling

HPA  
KEDA  
Karpenter  
Resource Policies  
Node Provisioning  
Capacity Planning

</td>
</tr>
</table>

</div>

### Kubernetes Operating Model

```text
APPLICATION
    │
    ├── Deployment / StatefulSet / Job
    │
    ▼
SERVICE
    │
    ├── Service / Ingress / Gateway API
    │
    ▼
SCALING
    │
    ├── HPA → Pod capacity
    ├── KEDA → Event-driven capacity
    └── Karpenter → Node capacity
    │
    ▼
OBSERVABILITY
    │
    ├── Metrics
    ├── Logs
    ├── Events
    └── Alerts
```

---

# 🚀 CI/CD Engineering

### Jenkins

**Jenkins + Groovy + Shared Libraries + Multibranch + Remote Jenkinsfiles**

- Declarative and scripted pipelines
- Dynamic build agents
- Pipeline approvals
- Lockable resources
- Timeouts
- Docker builds
- ECR integration
- Artifact publishing
- Slack notifications
- Deployment workflows
- Pipeline troubleshooting

### GitHub Actions

**PR validation + Unit Tests + Coverage + Quality Gates**

- Self-hosted runners
- Changed-application workflows
- Unit-test automation
- Coverage reporting
- Artifact publishing
- Branch-based workflows
- Required PR checks
- Merge protection

### Delivery Pipeline

<div align="center">

```mermaid
flowchart LR
    Code["💻 Code"] --> PR["Pull Request"]
    PR --> CI["CI"]
    CI --> Tests["Tests"]
    CI --> Security["Security"]
    CI --> Quality["Quality"]
    Tests --> Image["🐳 Image"]
    Security --> Image
    Quality --> Image
    Image --> ECR["Amazon ECR"]
    ECR --> EKS["Amazon EKS"]
    EKS --> Observe["📊 Observe"]
    Observe --> Improve["⚙️ Improve"]
    Improve --> CI
```

</div>

---

# 🐳 Container Engineering

| Area | Focus |
|---|---|
| Dockerfiles | Optimization and maintainability |
| BuildKit | Efficient builds |
| Multi-stage builds | Smaller production images |
| Private dependencies | Secure package access |
| SSH authentication | Secure build-time access |
| Environment management | Build vs runtime separation |
| Registry | ECR / artifact workflows |
| Runtime | Kubernetes container operations |

---

# 🏗️ Infrastructure as Code

<div align="center">

<table>
<tr>
<td align="center" width="33%">

### Terraform

AWS infrastructure  
EKS  
EC2  
IAM  
Networking  
Reusable modules

</td>
<td align="center" width="33%">

### Terragrunt

DRY configuration  
Environment separation  
Remote state  
Multi-environment orchestration

</td>
<td align="center" width="33%">

### Ansible

Server configuration  
Packages  
Application setup  
Operational automation

</td>
</tr>
</table>

</div>

> **Version Controlled → Reviewable → Reproducible → Automated → Auditable**

---

# 📊 Observability & Reliability

<div align="center">

```mermaid
flowchart LR
    App["Application"] --> Metrics["Metrics"]
    App --> Logs["Logs"]
    App --> Events["Events"]

    Metrics --> Prom["Prometheus"]
    Prom --> Grafana["Grafana"]

    Logs --> LogPlatform["Log Platform"]
    Events --> Alerting["Alerting"]

    Grafana --> Alerting
    LogPlatform --> Alerting

    Alerting --> Team["Engineering Team"]
    Team --> Action["Troubleshoot → Fix → Automate"]
```

</div>

### Observability Questions

> **What failed?**  
> **When did it fail?**  
> **What changed?**  
> **Why did it fail?**  
> **Is it recovering?**  
> **How do we prevent it from happening again?**

---

# 🔐 DevSecOps

Security is designed into the delivery path.

<div align="center">

**SOURCE** → **PR** → **TEST** → **QUALITY** → **SECURITY** → **BUILD** → **REGISTRY** → **KUBERNETES** → **MONITOR**

</div>

### Security Focus

- IAM
- Least privilege
- Secret handling
- Secure CI/CD
- Container security
- Dependency security
- Registry authentication
- SSH authentication
- Security gates
- Secure infrastructure

---

# 🧠 Engineering Principles

<table>
<tr>
<td width="50%" valign="top">

### 01 — Automate First
If a task is repeated, automate it.

### 02 — Infrastructure as Code
Infrastructure belongs in version control.

### 03 — Security by Default
Security is part of engineering, not a final checklist.

### 04 — Observable by Design
Systems should explain what happened.

</td>
<td width="50%" valign="top">

### 05 — Design for Failure
Assume components will fail.

### 06 — Scale Automatically
Scale workloads and infrastructure with demand.

### 07 — Optimize Continuously
Improve reliability, performance, developer experience and cost.

</td>
</tr>
</table>

---

# 🧪 Troubleshooting Philosophy

<div align="center">

```mermaid
flowchart TD
    Incident["🚨 Incident"] --> Data["Collect Data"]
    Data --> Logs["Logs"]
    Data --> Metrics["Metrics"]
    Data --> Events["Events"]
    Logs --> Hypothesis["Form Hypothesis"]
    Metrics --> Hypothesis
    Events --> Hypothesis
    Hypothesis --> Reproduce["Reproduce"]
    Reproduce --> RCA["Root Cause"]
    RCA --> Fix["Fix"]
    Fix --> Prevent["Automate Prevention"]
    Prevent --> Monitor["Monitor"]
```

</div>

> **Don't just fix the incident. Fix the system that allowed the incident to happen.**

---

# 🧩 Technology Matrix

<div align="center">

| Domain | Technologies |
|---|---|
| ☁️ Cloud | AWS · EKS · EC2 · VPC · ALB · ECR · IAM |
| ☸️ Kubernetes | Kubernetes · Helm · HPA · KEDA · Karpenter · Istio · Gateway API |
| 🚀 CI/CD | Jenkins · Groovy · GitHub Actions · Docker · Nexus |
| 🏗️ IaC | Terraform · Terragrunt · Ansible |
| 🐧 Systems | Linux · Bash · Git |
| 📊 Observability | Prometheus · Grafana · Alertmanager |
| 🔐 Security | IAM · Least Privilege · Secure CI/CD · Container Security |
| 🧩 Platform | GitOps · Developer Platforms · Automation · Reliability |

</div>

---

# 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,terraform,ansible,linux,docker,kubernetes,helm,jenkins,github,git,groovy,bash,python,go,js,prometheus,grafana" />

</div>

---

# 📂 Featured Projects

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### 🔥 Jenkins Engineering

<a href="https://github.com/ramdrazler1/lm-jenkins">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=ramdrazler1&repo=lm-jenkins&theme=tokyonight&hide_border=true" width="100%"/>
</a>

**Groovy · Jenkins · CI/CD**

Pipeline engineering and Jenkins automation experiments.

</td>
<td width="50%" valign="top">

### ☁️ DevOps Portfolio

<a href="https://github.com/ramdrazler1/devops-portfolio">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=ramdrazler1&repo=devops-portfolio&theme=tokyonight&hide_border=true" width="100%"/>
</a>

**HTML · DevOps**

Personal DevOps portfolio and engineering showcase.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧪 Code Coverage

<a href="https://github.com/ramdrazler1/code-cov">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=ramdrazler1&repo=code-cov&theme=tokyonight&hide_border=true" width="100%"/>
</a>

**Go · Testing · Coverage**

Automated code coverage experimentation.

</td>
<td width="50%" valign="top">

### 📊 Node.js Coverage

<a href="https://github.com/ramdrazler1/nodejs-coverage">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=ramdrazler1&repo=nodejs-coverage&theme=tokyonight&hide_border=true" width="100%"/>
</a>

**Node.js · JavaScript · Testing**

Node.js testing and coverage implementation.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧪 APM

<a href="https://github.com/ramdrazler1/apm">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=ramdrazler1&repo=apm&theme=tokyonight&hide_border=true" width="100%"/>
</a>

**JavaScript**

Application experimentation and testing.

</td>
<td width="50%" valign="top">

### 🌐 Iqube

<a href="https://github.com/ramdrazler1/Iqube">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=ramdrazler1&repo=Iqube&theme=tokyonight&hide_border=true" width="100%"/>
</a>

**HTML · CSS**

Web application project.

</td>
</tr>
</table>

</div>

---

# 📈 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ramdrazler1&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramdrazler1&layout=compact&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" width="49%" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=ramdrazler1&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58A6FF&fire=FF7B72&currStreakLabel=58A6FF" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ramdrazler1&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FFFFFF&area=true&hide_border=true" width="96%" />

</div>

---

# 🏆 GitHub Achievements

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=ramdrazler1&theme=darkhub&no-frame=true&no-bg=true&margin-w=8&column=6" width="90%" />

</div>

---

# 🚀 Current Engineering Focus

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### ☁️ Cloud

- AWS
- EKS
- Cloud Architecture
- Cost Optimization

### ☸️ Kubernetes

- Cluster Operations
- Karpenter
- KEDA
- HPA
- Gateway API
- Istio

</td>
<td width="50%" valign="top">

### 🚀 CI/CD

- Jenkins
- GitHub Actions
- Shared Libraries
- Self-hosted Runners
- Pipeline Optimization

### 🏗️ Infrastructure

- Terraform
- Terragrunt
- Ansible
- Infrastructure Automation

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Observability

- Prometheus
- Grafana
- Alerting
- Kubernetes Monitoring

</td>
<td width="50%" valign="top">

### 🧩 Engineering

- Platform Engineering
- DevSecOps
- Reliability
- Automation

</td>
</tr>
</table>

</div>

---

# 🔭 Platform Engineering Direction

<div align="center">

```mermaid
flowchart LR
    Developer["👨‍💻 Developer"] --> Portal["Developer Portal"]
    Portal --> Templates["Service Templates"]
    Templates --> Platform["Internal Developer Platform"]

    Platform --> CI["CI/CD"]
    Platform --> Infra["Infrastructure"]
    Platform --> K8s["Kubernetes"]
    Platform --> Security["Security"]
    Platform --> Observe["Observability"]
    Platform --> Cost["Cost Management"]

    CI --> Production["🚀 Production"]
    Infra --> Production
    K8s --> Production
    Security --> Production
    Observe --> Production
    Cost --> Production
```

</div>

### The goal

> **Give developers a paved road from code to production without requiring them to become infrastructure experts.**

---

# 🎓 Certifications

> **Add verified certifications here as they are earned.**

| Certification | Provider | Status |
|---|---|---|
| AWS Certified Solutions Architect | AWS | 🔄 Planned / Verify |
| AWS Certified DevOps Engineer | AWS | 🔄 Planned / Verify |
| Certified Kubernetes Administrator | CNCF | 🔄 Planned / Verify |
| Terraform Associate | HashiCorp | 🔄 Planned / Verify |

---

# 🤝 Let's Connect

<div align="center">

**AWS · Kubernetes · DevOps · CI/CD · Terraform · Jenkins · Docker · Platform Engineering · Observability · Cloud Architecture**

<br/><br/>

<a href="https://github.com/ramdrazler1">
<img src="https://img.shields.io/badge/GitHub-ramdrazler1-181717?style=for-the-badge&logo=github"/>
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=ramdrazler1&style=for-the-badge&color=0e75b6"/>

</div>

---

<div align="center">

<a href="https://github.com/ramdrazler1">
  <img src="https://capsule-render.vercel.app/api?type=waving&section=footer&height=140&color=0:21262D,50:161B22,100:0D1117&animation=fadeIn"/>
</a>

### ⚡ `AUTOMATE EVERYTHING THAT SHOULD BE AUTOMATED.`

### `OBSERVE EVERYTHING THAT MATTERS.`

### `DESIGN FOR FAILURE.`

<br/>

**🚀 Build → Automate → Secure → Deploy → Observe → Improve**

<br/>

<i>Infrastructure is code. Delivery is automation. Reliability is a feature.</i>

</div>
