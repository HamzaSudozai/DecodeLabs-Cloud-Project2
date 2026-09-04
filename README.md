# DecodeLabs Cloud Computing Internship - Project 2: The Server Commander

## Overview
Successfully provisioned, secured, and configured an IaaS Linux Virtual Machine on Microsoft Azure, hosting a custom Nginx web server.

## Architecture & Configuration
* **Cloud Provider:** Microsoft Azure (Azure for Students)
* **Region:** `uaenorth`
* **OS:** Ubuntu Server 24.04 LTS
* **VM Size:** `Standard_B2ats_v2`
* **Authentication:** SSH Key-Based (`.pem`)
* **Web Server:** Nginx (HTTP Port 80)
* **Public Access URL:** `http://40.123.212.142`

## Key Implementation Steps
1. **VM Provisioning:** Deployed Ubuntu 24.04 VM via Azure Portal with custom Network Security Group (NSG) rules allowing ports 22 (SSH) and 80 (HTTP).
2. **Remote Administration:** Secured private key permissions via PowerShell (`icacls`) and established SSH connection to `azureuser@40.123.212.142`.
3. **Web Server Deployment:** Updated system package repositories (`apt update`), installed Nginx (`apt install nginx`), and replaced default web root with customized Project 2 overview HTML.
4. ** Live at:** 
http://40.123.212.142/


---
*Deployed by Hamza | DecodeLabs Industrial Training Batch 2026*
