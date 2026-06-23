<div align="center">

# 🧭 SPVM Project

**Workforce & Shift Management System**

[![Java](https://img.shields.io/badge/Java-17-ED8B00.svg)](https://openjdk.org/)
[![JavaFX](https://img.shields.io/badge/JavaFX-UI-blue.svg)](https://openjfx.io/)
[![Maven](https://img.shields.io/badge/Maven-Build-C71A36.svg)](https://maven.apache.org/)

*Software Engineering — University of Palermo, 2022–2023*

</div>

---

## 📋 Overview

SPVM is a full-featured workforce management application built with **JavaFX** and **MariaDB**. It provides an integrated platform for managing employee profiles, scheduling shifts, handling absences and substitutions, and tracking salary-related operational data for a citizen-services company.

## ✨ Features

- 👤 **Employee Management** — Create, edit, and manage employee profiles and roles
- 📅 **Shift Planning** — Visual calendar-based shift scheduling with [CalendarFX](https://github.com/dlsc-software-consulting-gmbh/CalendarFX)
- 🔄 **Substitution Engine** — Automatic handling of absences and constraint-based replacements
- 💰 **Salary Tracking** — Operational data for payroll management
- 📧 **Email Notifications** — Automated notifications via Javax Mail

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Java 17 |
| UI Framework | JavaFX |
| Build Tool | Maven |
| Database | MariaDB (JDBC) |
| Calendar | CalendarFX |
| Email | Javax Mail |

## 🚀 Build & Run

```bash
cd SPVMProject_CODE
./mvnw clean package
./mvnw javafx:run
```

> On Windows, use `mvnw.cmd` instead of `./mvnw`.

## 📁 Project Structure

```
├── SPVMProject_CODE/       # JavaFX application source code
├── RAD.pdf                 # Requirements Analysis Document
├── SDD.pdf                 # System Design Document
├── ODD.pdf                 # Object Design Document
├── mockup/                 # UI/UX mockup designs
└── README.md
```

## 👥 Authors

- [Slenderman0039](https://github.com/Slenderman0039)
- [jackaljo](https://github.com/jackaljo)
- [ashenclock](https://github.com/ashenclock)
- [JovenLD](https://github.com/JovenLD)

## 🌐 Website

Project website: [spvmproject.github.io](https://spvmproject.github.io/)

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
