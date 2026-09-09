---

# 👨‍💻 About Me

```text
┌──────────────────────────────────────────────────────────────────────────┐
│                          BIJENDRA KUMAR PATEL                            │
├──────────────────────────────────────────────────────────────────────────┤
│ Role        : Full Stack .NET & Industrial IoT Developer                 │
│ Experience  : 1+ Years Enterprise & Hardware Telemetry Experience        │
│ Focus       : Enterprise Applications + Industrial IoT + Automation      │
│ Backend     : C# | .NET 8 | ASP.NET Core | REST APIs | Microservices     │
│ Frontend    : Blazor | Avalonia UI | React.js | Next.js | Razor Pages    │
│ Database    : SQL Server | MySQL | MariaDB | Entity Framework Core       │
│ IoT         : MQTT | Modbus RTU/TCP | RS485 | SNMP v2c | LoRaWAN          │
│ Security    : JWT | ASP.NET Core Identity | RBAC                         │
│ DevOps & OS : Git | GitHub | Docker | Linux (AlmaLinux/Ubuntu) | PM2     │
└──────────────────────────────────────────────────────────────────────────┘

```

I am a **Full Stack .NET Developer and Industrial IoT Specialist** dedicated to bridging the gap between high-performance backends and real-world industrial hardware.

My expertise spans **.NET 8, ASP.NET Core Web APIs, and Avalonia UI desktop architectures**, combined with low-level hardware protocols (**MQTT, Modbus RTU/TCP, RS485, SNMP**) to engineer scalable cloud platforms and process high-frequency telemetry in real time.

---

# ⚡ Professional Overview

| Domain | Technical Focus & Capabilities |
| --- | --- |
| 💻 **Backend Engineering** | C#, .NET 8, ASP.NET Core Web API, Asynchronous Background Services, LINQ |
| 🌐 **Web & Desktop UI** | Blazor, Avalonia UI, Razor Pages, React.js, Next.js |
| 🗄️ **Database Systems** | SQL Server, MySQL, MariaDB, Entity Framework Core, Query Optimization |
| 📡 **Industrial IoT** | MQTT, Modbus RTU/TCP, RS485, SNMP v2c, LoRaWAN |
| 🔐 **Security Architecture** | JWT Authentication, ASP.NET Core Identity, Fine-grained RBAC |
| 🏗️ **Architecture & Design** | REST APIs, Microservices, Clean Code, SOLID Principles |
| 🐳 **DevOps & Linux** | Git, GitHub, Docker, AlmaLinux Target Boot Configuration, PM2 Management |

---

# 🛠️ Technology Stack

### 💻 Languages & Frameworks

### 🗄️ Databases & ORM

### 📡 Industrial IoT & Protocols

### 🛠️ Tools & Infrastructure

---

# 🏢 Work Experience

### 💼 .NET Developer — Hbeonslabs Technology Pvt. Ltd.

**Noida, India | 01/2025 – Present**

* Engineered production enterprise applications and API services using **C#, .NET 8, ASP.NET Core, and Avalonia UI**.
* Implemented bi-directional hardware communication layers over **MQTT, Modbus RTU/TCP, and RS485** to interface directly with solar inverters, industrial gateways, and VFDs.
* Built asynchronous background processing services capable of parsing high-frequency sensor telemetry streams.
* Designed secure authentication architecture utilizing **JWT Authentication, ASP.NET Core Identity, and Role-Based Access Control (RBAC)**.
* Deployed Node.js and .NET backend services on AlmaLinux production servers with multi-user target setups and PM2 process management.

---

# 🏗️ Featured Production Projects

### ☀️ 01. VayuSolar — Solar Plant Monitoring System

* **Tech Stack:** C#, .NET 8, ASP.NET Core, EF Core, MySQL, MQTT, Modbus RTU/TCP
* **Overview:** High-availability monitoring platform designed to control autonomous cleaning robots and aggregate live solar panel telemetry metrics.
* **Impact:** Developed backend services in ASP.NET Core, integrated Modbus/MQTT hardware layers, and built real-time fault detection alerts.

### ☀️ 02. UTL Solar Testing Automation Platform

* **Tech Stack:** C#, .NET 8, Avalonia UI, MQTT, Dynamic Report Engine
* **Overview:** Automated desktop testing suite built for production testing of solar inverter dataloggers.
* **Impact:** Implemented asynchronous MQTT client communication to parse telemetry, match IMEI credentials, and automatically generate verification certificates.

### 🚉 03. Amrit Bharat Station Scheme — IoT Infrastructure

* **Tech Stack:** C#, .NET, ASP.NET Core, Modbus RTU, SCADA Telemetry
* **Overview:** Infrastructure monitoring and hardware control solution deployed across railway utility networks.
* **Impact:** Built byte-level hex parsing logic and Modbus `#READ` communication drivers to normalize raw field telemetry for SCADA monitoring platforms.

### ⚡ 04. Centralized Network Platform (CNP)

* **Tech Stack:** .NET 8, ASP.NET Core Web API, SQL Server, JWT, RBAC
* **Overview:** Enterprise networking system for real-time tracking of variable frequency drives (VFDs) and heavy machinery.
* **Impact:** Architected scalable SQL Server schemas, implemented JWT authentication workflows, and enforced strict Role-Based Access Control.

### 💡 05. Smart Luminaire Control Studio

* **Tech Stack:** React.js, Web APIs, Telemetry Synchronization, Digital Dimming
* **Overview:** Interactive lighting control platform engineered for smart commercial fixture monitoring and telemetry sync.
* **Impact:** Built dynamic dimming sliders, color temperature switches, and driver state diagnostics with real-time feedback.

### 📊 06. Vandebharat Desktop Log Management Application

* **Tech Stack:** C#, Avalonia UI, Storage Provider APIs, File I/O
* **Overview:** Cross-platform desktop log utility for industrial field operators to aggregate and inspect system event files.
* **Impact:** Engineered native OS directory pickers, fast CSV streaming engines, and non-blocking multi-threaded processing.

### 🏭 07. Industrial Gateway Systems — Delta VFD & Statcon Dataloggers

* **Tech Stack:** C#, .NET, MQTT, RS485, Linux Services
* **Overview:** Edge gateway applications enabling remote power conversion management and automated fault diagnosis.
* **Impact:** Developed bi-directional command processing, reliable serial data parsing over RS485, and cloud state synchronization routines.

### 🏢 08. Enterprise Resource Planning (ERP) Platform

* **Tech Stack:** ASP.NET Core, Blazor, Entity Framework Core, SQL Server
* **Overview:** Modular ERP solution processing sales invoicing, inventory ledgering, freight calculations, and bag count tracking.
* **Impact:** Created backend workflows for tax rate calculations, automated PDF invoice outputs, and optimized SQL database indexes.

---

# 📡 Industrial IoT Architecture Workflow

```text
┌─────────────────┐       Modbus RTU/TCP       ┌──────────────────┐
│  Field Devices  ├───────────────────────────►│ Industrial Gate  │
│ Sensors/VFD/PLC │                            │ C# / .NET Service│
└─────────────────┘                            └────────┬─────────┘
                                                        │ MQTT
                                                        ▼
┌─────────────────┐        REST / WebSockets   ┌──────────────────┐
│  Web & Desktop  │◄───────────────────────────┤ ASP.NET Core API │
│ Blazor/Avalonia │                            │ Background Worker│
└─────────────────┘                            └────────┬─────────┘
                                                        │ EF Core
                                                        ▼
                                               ┌──────────────────┐
                                               │   Database Engine│
                                               │ SQL Server/MySQL │
                                               └──────────────────┘

```

---

# 📈 GitHub Analytics

---

# 🌐 Connect With Me

📧 **Email:** [bijendrakumarpatel9@gmail.com](https://www.google.com/search?q=mailto%3Abijendrakumarpatel9%40gmail.com)  |  📱 **Phone:** +91 7050588400  |  📍 **Location:** Noida / Delhi NCR, India
