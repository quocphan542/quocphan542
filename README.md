# PHAN DINH QUOC
### **Product-Minded Java Backend Developer & DevOps Enthusiast**
📍 Ho Chi Minh City, Vietnam | 📧 Quocphan542@gmail.com | 📱 0862514331  
🔗 [LinkedIn](https://www.linkedin.com/in/quoc-phan-dinh-4a2521209/) | 💻 [GitHub](https://github.com/quocphan542)

---

## 🎯 PROFESSIONAL SUMMARY
> A solution-driven and product-minded Backend Engineer with a solid foundation in Java enterprise technologies[cite: 1]. Exceptional strength in architecting robust database schemas, engineering optimized business logic engines, and resolving high-concurrency race conditions. Proven hands-on capability in managing full-cycle deployments (Docker, Nginx, CI/CD) to deliver secure, high-performance, and production-ready enterprise software.

---

## 🛠️ TECHNICAL ARSENAL

| Layer | Technologies & Core Frameworks |
| :--- | :--- |
| **Backend Core** | **Java (17)**, **Spring Boot 3.x**, Spring Data JPA, **Spring Security (JWT)**, Hibernate |
| **Data & Performance**| **SQL Server In-Memory OLTP**, Optimistic Locking (`@Version`), Composite Key Indexing |
| **Frontend Integration**| **ReactJS**, Tailwind CSS (Industrial Skeuomorphism Design), JavaScript, HTML5/CSS3 |
| **DevOps & Infrastructure**| **Docker (Multi-Stage Builds)**, **Nginx (Reverse Proxy)**, **GitHub Actions (CI/CD)**, SSL/TLS |

---

## 💼 FEATURED ENTERPRISE PROJECT

### **Smart Internal Inventory & Supply Chain Management System**
*Full-Stack & DevOps Architect (Core Enterprise B2B Product)*

#### 📋 System Overview
A high-throughput, mission-critical B2B Inventory Management System engineered to streamline internal warehouse logistics. The system strictly governs physical stock movements (Lot-tracking, Zone/Shelf/Bin routing, and automated Auditing) while enforcing tight corporate financial data security and confidentiality.
<details>
<summary><b>👁️ Click để xem các Đột phá Kỹ thuật & Kiến trúc (Core Architecture)</b></summary>

*   **High-Precision Stock Calculation Engine**
    *   Designed and normalized a comprehensive **19-table database schema** on SQL Server. Engineered a real-time stock matrix utilizing a **Composite Key** `[product_id + location_id + batch_number]`, ensuring 100% data accuracy down to precise warehouse physical coordinates.
    *   *Problem Solved:* Eradicated stock discrepancies by implementing **Optimistic Locking (`@Version`)** to completely block concurrent edit overwrites (Race Conditions) when multiple operators scan and update the same lot simultaneously.
*   **Mission-Critical Data Security & Masking**
    *   Enforced strict **Role-Based Access Control (RBAC)** via Spring Security and JWT. Engineered dynamic data-masking layers that **completely abstract and hide cost prices (`base_price`)** from the Field Operators' UI, successfully preserving sensitive corporate financial data.
*   **Immutable Cryptographic Audit Trail**
    *   Developed an autonomous logging engine that captures every single stock delta (+/- quantity) into an **undeletable `inventory_logs` ledger**, stamping the exact User telemetry and cryptographic-like timestamps for anti-theft auditing.
*   **Automated Unit Conversion Engine**
    *   Built a flexible mathematical mapping engine that normalizes loose bulk supply orders (Pallets, Cases) into base operational units (Pieces) automatically during inbound protocols based on configurable `factor` rates.
*   **Industrial Skeuomorphic UI/UX with Responsive Morphing**
    *   Authored a custom ReactJS frontend reflecting an **Industrial Skeuomorphic** ethos (tactile neumorphic dual-shadow inputs for gloved operators, monospace telemetry).
    *   Integrated layout morphing to instantly adapt high-density desktop admin panels into single-column, touch-friendly cards for warehouse barcode scanning tablets.
</details>

<details>
<summary><b>📊 Click để xem Chỉ số Vận hành & DevOps Metrics</b></summary>

> *   **Image Optimization:** Leveraged **Docker Multi-Stage Builds**, reducing the production container footprint by **70%** (from 500MB+ down to ~150MB).
> *   **Traffic Routing:** Deployed onto hosting behind an **Nginx Reverse Proxy**, hardening the backend by obscuring Spring Boot ports and enforcing strict **HTTPS SSL/TLS encryption**.
> *   **Automation:** Established a fully automated **CI/CD pipeline via GitHub Actions**, enabling zero-downtime rolling updates upon code commits.
</details>

---

## 🎓 EDUCATION
**FPT Polytechnic College** (2020 - 2023)[cite: 1]  
*   **Degree:** Bachelor of Practice in Software Applications[cite: 1]  
*   **Academic Standing:** **GPA: 3.4 / 4.0** (Top Tier Graduate)[cite: 1]  

---

## 🌐 LANGUAGES
*   **Vietnamese:** Native
*   **English:** Professional Working Proficiency (Capable of reading complex technical documentation & participating in agile technical standups)
