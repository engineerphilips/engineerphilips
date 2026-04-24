
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

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" alt="springboot" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
  <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/>
</p>

**Databases**

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/>
  <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/elastic/elastic-icon.svg" alt="elasticsearch" width="40" height="40"/>
</p>

**Cloud, DevOps & Infrastructure**

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/rabbitmq/rabbitmq-icon.svg" alt="rabbitMQ" width="40" height="40"/>
</p>

**Data Science & ML**

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/>
  <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/>
</p>

**Tools**

<p align="left">
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/xamarin.svg" alt="xamarin" width="40" height="40"/>
</p>

---

## 📊 GitHub Stats

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=engineerphilips&show_icons=true&locale=en&theme=tokyonight" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=engineerphilips&show_icons=true&locale=en&layout=compact&theme=tokyonight" alt="top langs" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=engineerphilips&theme=tokyonight" alt="streak" />
</p>

---

<p align="center"><i>"Building infrastructure that serves people — from distributed infrastructure to partographs in rural clinics."</i></p>
