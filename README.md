# ⚡ TaskFlow CLI (Case Study)

> **🔒 Confidentiality Notice:** The source code of this tool is private and proprietary. This repository documents only the architecture, console interface design, execution metrics, and case study.

---

## 🎯 Overview
**TaskFlow CLI** is a command-line utility designed to accelerate and standardize repetitive technical tasks. It allows developers and system administrators to run automation routines, backup management, compilation, and environment provisioning without error-prone manual intervention.

---

## 🖥️ Interface & Execution Inspection

### 1. Command Console (CLI Terminal)
Displays direct execution of the tool on **Arch Linux**, highlighting compilation speed in **Rust** (`cargo release`), file synchronization, and metric breakdowns with step-by-step timing.

<p align="center">
  <img src="terminal.png" alt="TaskFlow CLI - Execution in Arch Linux Terminal" width="100%">
</p>

---

### 2. Maintenance & Event Dashboard
Explanatory view of the event control panel, showing environment sync status (`staging -> prod`), SHA-256 checksum integrity verification, and execution history.

<p align="center">
  <img src="dashboard-eventos.png" alt="TaskFlow CLI - Event Log and Environments" width="100%">
</p>

---

### 3. Deployment Report & Time Metrics
Graphical analysis of the pipeline completed in **1.42s with zero errors**, breaking down stage durations (environment variables, connectivity, Rust build, backups, and sync).

<p align="center">
  <img src="dashboard-despliegue.png" alt="TaskFlow CLI - General Deployment Report" width="100%">
</p>

---

## 🛠️ Tech Stack
<p align="left">
  <img src="https://skillicons.dev/icons?i=py,bash,rust,nodejs" alt="Tech Stack" />
</p>

- **Languages:** Python, Bash, Rust, Node.js
- **Environment:** CLI (Command Line Interface), Linux / POSIX Shells
- **Automation:** Scripting pipelines and system process management

---

## 🚀 Key Features

### 1. Workflow Automation
- Sequential and parallel execution of project setup tasks.
- Environment standardization and reusable scripts.

### 2. Synchronization & Maintenance
- Automated backups of configuration files and indices.
- Integrity verification and temporary file cleanup.
