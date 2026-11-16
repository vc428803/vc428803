
## 🌌 GitHub Snake

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Vic428-human/Vic428-human/output/github-snake.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vic428-human/Vic428-human/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Vic428-human/Vic428-human/output/github-snake.svg" />
</picture>

# Hi, I'm Builder 👋

### Software Engineer | Full-Stack Development

I am a software engineer focused on building and maintaining enterprise applications, with practical experience in **C# / .NET, WinForms, ASP.NET Core, React / TypeScript, and relational databases**.

My professional work involves translating complex business requirements into reliable software, including booking and order management, warehouse operations, customer and contract management, authentication, and approval workflows.

I particularly enjoy solving problems involving **business logic, database transactions, data consistency, access control, and legacy system refactoring**.

Beyond professional development, I independently build projects using **Go, PostgreSQL, React, and Unity / VR**, exploring concurrency, realtime communication, domain modelling, and modular system architecture.

---

## 🛠️ Technical Stack

| Category | Technologies |
| --- | --- |
| Backend | C#, .NET, ASP.NET Core, EF Core, REST APIs, Go, Gin |
| Frontend | React, TypeScript, Vite, Tailwind CSS |
| Desktop | Windows Forms (WinForms) |
| Databases | SQL Server, Oracle, PostgreSQL (Neon) |
| Authentication | Session Authentication, JWT, Password Hashing |
| Architecture | Service / Repository Patterns, Layered Architecture, API Integration |
| Data Integrity | SQL Transactions, Rollback, Row-Level Locking, Unique Constraints |
| Additional | Java, Unity 6, XR Interaction Toolkit, WebSocket, SSE |

---

## 💼 Professional Experience

My professional development experience focuses on enterprise applications where business rules, operational workflows, and database consistency are essential.

### 01. Banquet Booking & Venue Operations Systems

**C# · WinForms · SQL · Legacy System Refactoring**

Developing and maintaining enterprise applications for venue reservations, booking operations, and order management.

**Key Responsibilities & Contributions**

- Developed and maintained booking workflows involving master orders, sub-orders, venues, equipment, and catering services.
- Implemented venue availability and booking conflict validation.
- Handled time-based pricing, overtime calculations, and booking status transitions.
- Integrated database transactions to maintain consistency across related records.
- Gradually separated business logic from large WinForms forms into reusable Service and Repository components.
- Preserved existing business behaviour while improving code maintainability and extensibility.

**Engineering Focus:** Business Rules · Transaction Management · Legacy Refactoring · Data Consistency

### 02. PDA / RFID Warehouse & Inventory Systems

**C# · REST APIs · SQL · System Integration**

Worked on warehouse and inventory management applications supporting device-driven operational workflows.

**Key Responsibilities & Contributions**

- Developed functionality supporting receiving, stocktaking, and inventory return processes.
- Implemented IMEI validation, duplicate inventory detection, and quantity verification.
- Integrated backend validation with PDA / RFID operational workflows.
- Applied transaction and rollback mechanisms to prevent partially completed inventory updates.
- Worked with relational data structures to maintain consistency between warehouse operations and inventory records.

**Engineering Focus:** Inventory Validation · API Integration · Database Transactions · Operational Reliability

### 03. Accounting Customer & Contract Management System

**ASP.NET Core · EF Core · React · TypeScript · SQL Server**

Developing an internal enterprise application integrating employee information, customer management, authentication, and group-based access control.

**Key Responsibilities & Contributions**

- Designed employee and department data structures supporting internal HR synchronisation.
- Implemented batch employee synchronisation from staging data with duplicate checks and transaction handling.
- Applied database unique constraints to prevent duplicated employee identifiers.
- Developed session-based authentication with verification codes and secure password hashing.
- Implemented first-login password change requirements.
- Designed group-based module permissions with Read / Write access levels.
- Developed customer information management interfaces supporting multiple contact records.
- Structured authorisation components to support future special permissions and data-level access rules.

**Current Development Focus**

- Data Scope Authorisation.
- Customer ownership and access restrictions.
- Contract approval permissions and workflow integration.

**Engineering Focus:** Authentication · Authorisation · HR Integration · Database Integrity · Enterprise Architecture

### 04. Foundation Management & Approval Workflow System

**ASP.NET Core · React · TypeScript · EF Core**

Designed an internal management system architecture involving organisational structures, approval rules, and payment workflows.

**Key Responsibilities & Contributions**

- Modelled approval requirements based on departments, organisational roles, and monetary thresholds.
- Designed approval-step records to represent the routing of individual requests.
- Introduced current-approver tracking to identify pending approval responsibilities.
- Considered self-approval prevention and exceptions for designated management roles.
- Structured workflow-resolution concepts to separate business decisions from application and persistence concerns.

**Engineering Focus:** Workflow Design · Business Rule Modelling · Approval Architecture

---

## 🚀 Personal Side Projects

Outside professional work, I independently develop applications to explore backend architecture, transactional reliability, realtime systems, and immersive technologies.

These projects provide opportunities to experiment with different languages and frameworks while applying engineering principles learned from enterprise development.

### 01. NEXELYTH Marketplace

**React · TypeScript · Go · Gin · Neon PostgreSQL**

**[View GitHub Repository](https://github.com/vc428803/nexelyth-marketplace)**

A virtual-item marketplace and auction platform designed around item ownership, competitive bidding, wallet balances, and transaction-safe settlement.

**Implemented Features**

- User authentication using JWT and HttpOnly Cookies.
- Inventory ownership validation and auction listing management.
- Auction bidding APIs with minimum-increment and expiry checks.
- PostgreSQL row-level locking using `SELECT ... FOR UPDATE`.
- Wallet fund reservation and release using `BID_HOLD` and `BID_RELEASE`.
- Transaction-safe auction settlement and item ownership transfer.
- Background worker for processing expired auctions.
- Basic end-to-end transaction and settlement verification.

**Currently Developing**

- Auction-specific Server-Sent Events (SSE).
- Realtime bidding notifications.
- Frontend bidding integration.
- Extended concurrency and rollback testing.

**Key Engineering Concepts**

`Database Transactions` · `Row-Level Locking` · `Concurrency Control` · `Idempotency` · `Background Workers` · `Data Integrity`

### 02. NEXELYTH — Unity VR World Prototype

**Unity 6 · C# · URP · XR Interaction Toolkit**

**[View GitHub Repository](https://github.com/vc428803/Nexelyth)**

An experimental VR world exploring immersive interaction, modular gameplay systems, multi-scene world transitions, and player-state management.

**Implemented Features**

- Portal-based teleportation between virtual worlds.
- Additive scene loading with a persistent XR Origin.
- Shared world-travel service abstraction.
- Centralised player-location management.
- Three-slot memo teleportation system.
- World Space UI and immersive in-game menu interactions.
- XR player awakening and visual transition effects.

**Future Development**

- ASP.NET Core backend integration.
- Database-backed player-state persistence.
- Cross-platform inventory synchronisation.
- Expanded VR world interactions.

**Key Engineering Concepts**

`C# Architecture` · `Service Abstraction` · `State Management` · `Scene Lifecycle` · `XR Interaction`

---

## 🧠 Engineering Strengths

### Business Logic & Workflow Design

I focus on understanding how systems operate in real business environments before translating requirements into application logic.

This includes booking restrictions, approval routing, inventory validation, and access-control rules.

### Database Transactions & Data Consistency

I use validation, relational constraints, transactions, and rollback mechanisms to reduce the risk of inconsistent application states.

My personal projects further explore concurrency control, row-level locking, and idempotent processing.

### Maintainable System Architecture

I prefer separating presentation, business logic, and data access responsibilities.

When working with existing systems, I favour incremental refactoring that preserves behaviour while improving maintainability and testability.

### Backend Integration & Security

I have practical experience designing REST APIs, authentication flows, group-based permissions, and synchronisation processes between internal systems.

---

## 📌 Current Technical Focus

| Area | Current Focus |
| --- | --- |
| C# / ASP.NET Core | Enterprise workflows, authentication, authorisation, system architecture |
| SQL Server / EF Core | Data consistency, relational modelling, transaction handling |
| Go / PostgreSQL | Concurrent bidding, transaction-safe settlement, realtime event integration |
| React / TypeScript | Enterprise interfaces, API integration, frontend state management |
| Unity / C# | Modular VR systems, persistent runtime state, XR interactions |

---

### Building reliable business systems and exploring new technologies through hands-on engineering.

*Clean Architecture · Business Logic · Data Integrity · Continuous Improvement*
