
# Hi 👋, I'm Philip Baba

### Solutions Specialist · DBA · .NET/C# Engineer · From Ghana 🇬🇭

<p align="Left">
  <img alt="coding" width="400" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif" />
</p>

<p align="Left">
  <img src="https://komarev.com/ghpvc/?username=engineerphilips&label=Profile%20views&color=0e75b6&style=flat" alt="engineerphilips" />
  <a href="https://twitter.com/emper0rphil"><img src="https://img.shields.io/twitter/follow/emper0rphil?logo=twitter&style=flat" alt="emper0rphil" /></a>
  <img src="https://img.shields.io/badge/Mandela%20Washington%20Fellow-2024-gold?style=flat&logo=star" alt="MWF 2024" />
</p>

---

## 👨‍💻 About Me

I'm a **Solutions Specialist** and **Enterprise Database Administrator**, where I manage a large-scale **Distributed** environment, and **Co-Lead ICT Technical** at **Emperor Software LLC**, where I architect healthcare and enterprise platforms.

I'm a **2024 Mandela Washington Fellow** with an MSc in Computer Science. I've spent roughly a decade building with **.NET/C#** and operating mission-critical infrastructure, and I increasingly gravitate toward **Open source HA architectures**, **AI-assisted healthcare systems**, and **edge-deployed ML**.

---

## 🔭 What I'm Currently Working On

### 🏥 MAAME DROMO PARTOGRAPH
A `.NET MAUI` + `ASP.NET Core 8` offline-first labour/child bearing monitoring platform for the Ghana Health Service, built on a 96%-accuracy deep neural network.

### 👁️ Big Eye HR
A comprehensive HR platform for Ghanaian public-service organizations:

- **Web portal for HR administrators** — employee lifecycle, payroll, leave, discipline, training, and audit trails
- **Self-service web portal for employees** — profile, payslips, leave requests, training enrollment
- **Mobile app for employees** — attendance (**biometric + geofencing**), notifications, payslips on the go
- **Public Service Appraisal** — the full Ghanaian PSC appraisal workflow (objective setting, mid-year, end-of-year, moderation, sign-off)
- **Attendance engine** — biometric capture + mobile geofencing, designed around Ghana's **Data Protection Act (Act 843)**
- Plus the full breadth of modules you'd expect: organograms, job descriptions, onboarding, exit clearance, document management, and analytics dashboards

### 🗄️ PgEdge Multi-Master PostgreSQL HA (3-node)
A **true active-active** PostgreSQL cluster. Every node accepts reads *and* writes; workload is distributed evenly; any single-node failure is transparent to clients.

- **3 × PgEdge nodes** with **Spock** logical replication in a full mesh — conflicts resolved at the replication layer
- **Keepalived** managing **3 floating VIPs** via VRRP — each node owns one VIP by default, and when a node fails, its VIP automatically floats to one of the surviving nodes (so the cluster always exposes three reachable VIPs)
- **HAProxy** on each node, load-balancing across all three PgEdge backends with health checks
- **PgBouncer** in front of PostgreSQL on each node for connection pooling (transaction-mode)
- **dnsmasq** publishing a **single SCAN-style service name** that resolves round-robin to all three VIPs — giving applications *true* round-robin write distribution across the cluster, modeled directly on the Oracle Exadata SCAN pattern
- Result: one connection string, three live writers, zero-downtime failover

### 🏥 SMILE HMIS
Clean-architecture hospital management system, with **MedGemma**, **Meditron**, **OllamaSharp**, **ChromaDB RAG**, and **OpenMed NER** for clinical AI; regional Ghana dashboards via **Syncfusion Blazor Maps**; and full laboratory analyzer integration (ASTM/LIS2-A2, HL7 v2.x).

---

## 🌱 Exploring & Learning

**Postgres-XL** · **Apache APISIX** (Docker Swarm, host-based routing, Ansible playbooks) · **Patroni / etcd** · **Spring Boot** (for C# devs) · **Wearable biosensor architectures** · **Advanced Data Engineering** · **Kubernetes / Terraform / Ansible**

---

## 💬 Ask Me About

`.NET 8` · `ASP.NET Core` · `.NET MAUI` · `WPF` · **Spring Boot** · **Oracle RAC / Data Guard / GoldenGate / RMAN / ASM / Exadata** · **PostgreSQL HA (PgEdge, Spock, Patroni)** · **SQL Server** · **MongoDB replica sets** · **Apache APISIX** · **Clean Architecture** · **HL7 v2.x / ASTM / LIS2-A2** (lab analyzer integration) · **DHIS2** · **Python / Pandas / TensorFlow / scikit-learn**

---

## 📫 Connect

- 📧 **engineerphilips@outlook.com**
- 🐦 [Twitter / X](https://twitter.com/emper0rphil)
- 💼 [LinkedIn](https://www.linkedin.com/in/braa-phil/)
- 🧠 [Kaggle](https://kaggle.com/philbab)

> *Most of my work is in private repositories — happy to discuss architecture, design decisions, or specific challenges on request.*

---

## 🛠️ Languages & Tools

**Languages & Frameworks**
 
[![My Skills](https://skillicons.dev/icons?i=cs,dotnet,spring,java,python,js,html,css,react,angular,bootstrap)](https://skillicons.dev)

**Databases**

[![My Skills](https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,sqlite,elasticsearch,mssql,oracle)](https://skillicons.dev)
 
**Cloud, DevOps & Infrastructure**
 
[![My Skills](https://skillicons.dev/icons?i=aws,azure,gcp,docker,kubernetes,linux,git,rabbitmq,nginx,jenkins,bitbucket)](https://skillicons.dev)
 
**Data Science & ML**
 
[![My Skills](https://skillicons.dev/icons?i=tensorflow,sklearn,pytorch)](https://skillicons.dev)
 
**Tools**
 
[![My Skills](https://skillicons.dev/icons?i=postman,figma,vscode,visualstudio,idea)](https://skillicons.dev)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=engineerphilips&show_icons=true&locale=en&theme=tokyonight" alt="stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=engineerphilips&theme=tokyonight" alt="streak" />
</p>

---

<p align="center"><i>"Building infrastructure that serves people — from distributed infrastructure to partographs in rural clinics."</i></p>
