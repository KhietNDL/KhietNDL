### Hi there, I'm Khiet Nguyen 👋

Software Engineering student at **FPT University** (graduating Nov 2026). I specialize in building scalable **Node.js** backend systems and have hands-on experience developing metadata-driven **SAP Fiori / SAPUI5 & React** enterprise applications integrated with **ABAP RAP / OData V4**.

- 🔭 **Open to:** Backend Developer (Intern / Fresher) & SAP Technical Fresher opportunities in Ho Chi Minh City.
- 🛠️ **Core Backend Stack:** JavaScript (ES6+), TypeScript, Node.js (Express.js), MySQL, PostgreSQL.
- 🏢 **Enterprise ERP & Frontend Stack:** React.js, SAPUI5 (UI5 Web Components), SAP Fiori Elements, OData V4, ABAP RAP / DDIC Concepts.
- 📫 **Contact:** [lekhietnguyenduc@gmail.com](mailto:lekhietnguyenduc@gmail.com)
---

### 🚀 Featured Web Backend Projects

#### 1. [AI EdTech Platform](https://github.com/KhietNDL/ten-repo-1)
`Node.js` `Express` `TypeScript` `MySQL (TiDB Cloud)` `Redis` `Coze LLM API` `SePay`
- Architected a layered backend (`Controller-Service-Model`) powering automated exam generation and classroom management SaaS.
- Implemented **Redis** for token revocation, rapid OTP lifecycle, and IP/session-based rate limiting to prevent brute-force attacks.
- Automated **SePay VietQR** payment reconciliation via asynchronous webhooks with cryptographic signature verification.
- Integrated **Coze LLM API** to digitize PDF/DOCX question banks and built dynamic PDF invoice & Excel gradebook exports (`PDFKit`, `SheetJS`).

#### 2. [CoursePilot (StudyPortal)](https://github.com/KhietNDL/ten-repo-2)
`Node.js` `Express` `PostgreSQL (Supabase)` `pgvector` `Gemini 2.5 Flash` `Docker`
- Designed **40+ RESTful APIs** documented with **Swagger/OpenAPI 3.0**, enforcing strict 3-tier Role-Based Access Control (**RBAC**).
- Built an AI academic counseling chatbot using **Gemini 2.5 Flash** and **pgvector** with Hybrid Search and Re-ranking.
- Integrated **MoMo Payment Gateway** (HMAC-SHA256 verification, IPN callbacks, refund flows) and real-time notifications via **Socket.io**.
- Containerized services with **Docker** and automated CI/CD deployment on **Railway**.

#### 3. [CineZone – Cinema Booking System](https://github.com/KhietNDL/ten-repo-3)
`Node.js` `Express` `MySQL` `Socket.io` `Stripe` `MoMo` `ZaloPay`
- Built a modular MVC backend managing multi-theater showtimes and real-time seat selection.
- Implemented **ACID database transactions with locking mechanisms** to eliminate race conditions and double-booking under concurrent requests.
- Integrated multi-gateway payments (**MoMo IPN, ZaloPay MAC, Stripe PaymentIntent**) and automated QR-code e-ticket emails.

---

### 🏢 Enterprise ERP Project (SAP Capstone)

#### [Z-MAINT – Universal Z-Table Data Maintenance System](https://github.com/KhietNDL/ztbl-maintenance-ui) *(Frontend / Fiori & QA)*
`SAPUI5` `React (UI5 Web Components)` `SAP Fiori Elements` `OData V4` `ABAP RAP`
- Developed a metadata-driven dynamic maintenance workspace packaged as an **SAPUI5 component** mounting a **React / UI5 Web Components** frontend, dynamically rendering columns, date/boolean controls, domain dropdowns, and foreign-key value helps from runtime DDIC metadata.
- Built governance applications using **SAP Fiori Elements** with custom extension controllers for Table Configuration, Approval Requests, Audit Log, and User/Table Permission Matrix, consuming **OData V4** services (`ZSB_TBL_CONFIG`, `ZSB_EXCEL_PL`).
- Integrated end-to-end frontend workflows for **XLSX bulk import/export with diff preview** (`NEW`, `CHANGED`, `UNCHANGED`, `DELETE`, `ERROR`), approval review, immutable audit rollback, and session lock conflict handling.
- Authored and executed **115 unit/component test cases** validating dynamic rendering, field validation, Excel error isolation, authorization fallback, and concurrency edge cases.

---

### 💼 Experience & Education

- **Software Engineer Intern (Backend)** @ **FPT Software Academy** *(May 2025 – Aug 2025)*
  - Developed end-to-end backend modules and optimized complex SQL queries in an Agile/Scrum environment with strict Git branching & code review workflows.
- **B.Sc. in Software Engineering** @ **FPT University** *(Oct 2022 – Aug 2026 | GPA: 3.1/4.0)*
