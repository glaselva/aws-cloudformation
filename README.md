# AWS High Availability Infrastructure & IaC

![AWS](https://img.shields.io/badge/AWS-CloudFormation-orange) ![EC2](https://img.shields.io/badge/Compute-EC2-blue) ![Infrastructure](https://img.shields.io/badge/Type-Infrastructure%20as%20Code-green)

[🇮🇹 Versione Italiana](#panoramica-del-progetto) | [🇬🇧 English Version](#project-overview)

---

## Panoramica del Progetto
Questa repository contiene la soluzione di **Infrastructure as Code (IaC)** per il deployment di un'infrastruttura web scalabile e fault-tolerant su AWS. Il progetto simula uno scenario reale focalizzato su **Alta Disponibilità (HA)**, **Disaster Recovery** e provisioning automatico tramite **AWS CloudFormation**.

### 📂 Contenuto della Repository
*   `challenge-final.yaml`: Il template CloudFormation che automatizza la creazione di VPC, Subnet, Security Groups e istanze EC2 [file:1].
*   `Giuseppe_AWS_Infrastructure_Report.pdf`: Un case study tecnico dettagliato che analizza l'architettura, le scelte progettuali e l'implementazione della sicurezza [file:2].

### 🚀 Funzionalità Chiave
*   **Deployment Automatizzato:** Provisioning dell'intero stack (Rete + Compute) via CloudFormation.
*   **Design High Availability:** Architettura migrata da Single-AZ a **Multi-AZ** per eliminare i Single Point of Failure (SPoF) [file:2].
*   **Self-Healing:** Istanze EC2 configurate con script `UserData` per la configurazione automatica del web server all'avvio [file:1].
*   **Security First:** Implementazione del controllo accessi "Least Privilege" tramite Security Groups e isolamento VPC.

### 🛠️ Tech Stack
*   **Servizi AWS:** VPC, EC2, CloudFormation, CloudTrail.
*   **Scripting:** YAML (IaC), Bash (User Data).
*   **OS:** Amazon Linux 2023.

---

## Project Overview
This repository contains the **Infrastructure as Code (IaC)** solution for deploying a scalable and fault-tolerant web infrastructure on AWS. The project simulates a real-world scenario focusing on **High Availability (HA)**, **Disaster Recovery**, and automated provisioning using **AWS CloudFormation**.

### 📂 Repository Contents
*   `challenge-final.yaml`: The CloudFormation template that automates the creation of the VPC, Subnets, Security Groups, and EC2 instances [file:1].
*   `Giuseppe_AWS_Infrastructure_Report.pdf`: A detailed technical case study analyzing the architecture, design choices, and security implementation [file:2].

### 🚀 Key Features
*   **Automated Deployment:** Full stack provisioning (Network + Compute) via CloudFormation.
*   **High Availability Design:** Architecture migrated from Single-AZ to **Multi-AZ** to eliminate Single Points of Failure (SPoF) [file:2].
*   **Self-Healing:** EC2 instances configured with `UserData` scripts for automatic web server configuration upon launch [file:1].
*   **Security First:** Implementation of "Least Privilege" access control via Security Groups and VPC isolation.

### 🛠️ Tech Stack
*   **AWS Services:** VPC, EC2, CloudFormation, CloudTrail.
*   **Scripting:** YAML (IaC), Bash (User Data).
*   **OS:** Amazon Linux 2023.

---
*Project developed by Giuseppe as part of the AWS Cloud Security Portfolio.*
