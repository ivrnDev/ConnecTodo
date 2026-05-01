# 🏢 Barangay Management System (ConnecTodo)

## 📌 Overview

**ConnecTodo** is a **JavaFX-based desktop application** designed to streamline barangay operations such as resident management, employee records, inventory tracking, request processing, events, and health appointments.

It provides a centralized system for barangay administrators to efficiently manage day-to-day community services and generate reports for decision-making.

---

## ⚙️ Features

### 👤 User Management

- Account creation and login system
- Role-based access control

### 🏡 Resident Management

- Add, update, and manage resident profiles
- Maintain complete resident records

### 👷 Employee Management

- Employee records management
- Application handling for staff

### 📦 Inventory System

- Track barangay items and assets
- Borrow and return management
- Inventory reports

### 📄 Requests & Certificates

- Issue barangay certificates and documents
- Process resident requests and cedulas

### 📅 Events Management

- Create and manage community events
- Track event-related items

### 🏥 Health Services

- Schedule health appointments
- Manage patient records

### 📊 Complaints & Analytics

- Record and manage complaints
- Generate reports and system analytics

### 📤 Export Features

- Export data to **Excel (Apache POI)**
- Export reports to **PDF (PDFBox)**

---

## 🧱 Tech Stack

- **Language:** Java (JDK 23)
- **UI Framework:** JavaFX
- **Build Tool:** Maven (with wrapper support)
- **Architecture:** MVC-inspired modular structure

### 📚 Libraries Used

- Jackson (JSON processing)
- Lombok (boilerplate reduction)
- OkHttp (HTTP client)
- Apache POI (Excel export)
- PDFBox (PDF generation)
- JavaCV (media processing)
- Jakarta Mail (email services)

---

## 📁 Project Structure

### 🚀 Entry Point

- `App.java`
  👉 [View file](src/main/java/com/econnect/barangaymanagementapp/App.java)

- `MainApplication.java`
  👉 [View file](src/main/java/com/econnect/barangaymanagementapp/MainApplication.java)

---

### 📂 Core Modules

- **Controllers:**
  `src/main/java/com/econnect/barangaymanagementapp/controller`

- **Domain Models:**
  `src/main/java/com/econnect/barangaymanagementapp/domain`

- **Configuration:**
  `Config.java`

- **Resources (UI, styles, assets):**
  `src/main/resources/com/econnect/barangaymanagementapp`

---

## 📦 Requirements

- **JDK:** Java 23+
- **Maven:** Optional (wrapper included)
- **OS:** Windows / macOS / Linux with GUI support

---

## 🚀 Setup Instructions

### 1. Clone the repository

```bash id="clone_repo"
git clone <repo-url>
cd barangay-management-system
```

---

### 2. Verify Java installation

```bash id="java_version"
java -version
```

Ensure it matches **Java 23+**

---

### 3. Build the project

#### Using Maven Wrapper (Recommended)

```bash id="mvnw_build_unix"
./mvnw clean package
```

```bash id="mvnw_build_windows"
mvnw.cmd clean package
```

---

#### Using system Maven

```bash id="maven_build"
mvn clean package
```

---

## ▶️ Running the Application

### Option 1: Run via IDE (Recommended)

Run:

```
MainApplication.main()
```

---

### Option 2: Run JAR file

```bash id="run_jar"
java -jar target/ConnecTodo-1.0.jar
```

> ⚠️ Note: JavaFX may require module-path configuration depending on your setup.

---

## 📦 Build & Packaging

The project supports **Maven packaging** with optional bundling via JavaPackager.

- Generates executable JAR
- Can include bundled JRE (platform-specific builds)

---

## 🧠 Architecture Notes

- MVC-inspired modular structure
- Separation of concerns:
  - Controllers → UI logic
  - Domain → Data models
  - Services → Business logic (if applicable)

- JavaFX used for UI rendering and event handling

---

## 🐞 Troubleshooting

### ❌ Java version issues

Ensure:

```bash
java -version
```

Outputs **Java 23+**

---

### ❌ JavaFX runtime errors

- Run via IDE instead of JAR
- Or use packaged build with JavaFX dependencies included

---

### ❌ Maven issues

Use wrapper instead:

```bash
./mvnw clean install
```

---

## 🏁 Summary

**ConnecTodo** is a full-featured barangay management system built with JavaFX, designed to digitize and streamline local government operations including residents, employees, inventory, and community services.

---
