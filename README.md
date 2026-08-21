# ☁️ AJITPAL JOON

### 🚀 Cloud & DevOps Engineer | Microsoft Azure | Terraform | CI/CD

<p align="center">

<img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />

</p>

<p align="center">

<a href="https://github.com/ajitpaljoon-devops">
<img src="https://img.shields.io/github/followers/ajitpaljoon-devops?label=Followers&style=social" />
</a>

<a href="https://github.com/ajitpaljoon-devops">
<img src="https://img.shields.io/github/stars/ajitpaljoon-devops?label=Stars&style=social" />
</a>

</p>

---

## 👋 About Me

I'm a **Cloud & DevOps Engineer** focused on designing, deploying and automating secure and scalable cloud infrastructure.

My primary expertise is in **Microsoft Azure, Terraform, Git, GitHub, CI/CD and Cloud Networking**.

I enjoy transforming manual infrastructure and deployment processes into **automated, repeatable and reliable solutions** using Infrastructure as Code and DevOps practices.

### 🎯 What I Focus On

- ☁️ Microsoft Azure Infrastructure
- 🏗️ Infrastructure as Code with Terraform
- 🔄 CI/CD Automation
- 🌐 Azure Cloud Networking
- 🔐 Cloud Security & Access Management
- 📈 Scalability & High Availability
- 🤖 Infrastructure Automation
- 🐳 Containers & Kubernetes
- 🛡️ DevSecOps practices

---

## 🧰 Technical Skills

### ☁️ Cloud — Microsoft Azure

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

`Virtual Machines` `VNet` `Subnet` `NSG` `ASG`

`Load Balancer` `Application Gateway` `Storage Account`

`Azure Firewall` `VPN Gateway` `ExpressRoute`

`Private Endpoint` `DNS` `Azure Monitor`

`Microsoft Entra ID` `RBAC` `Azure Policy`

`Resource Locks` `Landing Zone`

---

### 🏗️ Infrastructure as Code

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)

`Terraform` `Terraform Modules` `Variables`

`tfvars` `Data Sources` `for_each`

`count` `locals` `outputs`

`Remote State` `State Locking`

`Terraform Plan` `Terraform Apply`

`Infrastructure Automation`

---

### 🔄 DevOps & CI/CD

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)

`Git` `GitHub` `GitHub Actions`

`Azure DevOps` `CI/CD`

`Build` `Test` `Deploy`

`Infrastructure Pipeline`

---

### 🐳 Containers & Orchestration

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

`Docker` `Docker Images` `Containers`

`Kubernetes` `Pods` `Deployments`

---

### 🌐 Networking

`VNet` `Subnet` `VNet Peering`

`Hub & Spoke Architecture`

`NSG` `ASG` `Load Balancing`

`Application Gateway`

`Azure Firewall`

`VPN Gateway` `ExpressRoute`

`DNS` `Private Connectivity`

---

### 🐧 Operating Systems

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows%20Server-0078D6?style=flat-square&logo=windows&logoColor=white)

`Linux` `Ubuntu` `Windows Server`

---

# 🚀 Featured Projects

## 🏗️ Azure Infrastructure Automation with Terraform

Designed and automated Azure infrastructure using **reusable Terraform modules**.

### Infrastructure Components

- ☁️ Resource Groups
- 🌐 Virtual Networks
- 🔹 Subnets
- 🔐 Network Security Groups
- 🛡️ Application Security Groups
- 🌍 Public IPs
- 🖥️ Virtual Machines
- 🔗 VNet Peering
- 💾 Storage Accounts

### Key Concepts

`Infrastructure as Code`

`Reusable Modules`

`Variables & tfvars`

`for_each`

`Data Sources`

`Terraform State`

---

## ☁️ Azure Hub & Spoke Architecture

Designed a scalable Azure network architecture based on the **Hub & Spoke model**.

### Architecture

```text
                    ┌───────────────────┐
                    │    HUB VNet       │
                    │                   │
                    │ Azure Firewall    │
                    │ VPN / ER Gateway  │
                    │ Shared Services   │
                    └─────────┬─────────┘
                              │
                 ┌────────────┼────────────┐
                 │            │            │
                 ▼            ▼            ▼
            ┌─────────┐  ┌─────────┐  ┌─────────┐
            │ Spoke 1 │  │ Spoke 2 │  │ Spoke 3 │
            │         │  │         │  │         │
            │  Apps   │  │  Data   │  │  Dev    │
            └─────────┘  └─────────┘  └─────────┘
