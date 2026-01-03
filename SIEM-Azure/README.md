# SIEM/SOC in Azure

This project demonstrates the setup of a basic SIEM and partial SOC using Microsoft Azure services.  
The goal is to create a virtual machine, ingest data logs, and clearly present attack data in a cloud environment.

[Watch this walkthrough video!](https://youtu.be/ffyFnLsaAKQ)

## Project Architecture

This diagram illustrates how this project lures live attackers to a honeypot VM accessible via the public internet. This VM is tied to a Log Analytics Workspace and Microsoft Sentinel, allowing me to monitor log data and plot it on a worldwide VM Attack Map using Sentinel Workbooks. 

![SOC / SIEM Architecture](screenshots/azure-soc-siem-architecture.jpg)

## Technologies Used
- Microsoft Azure
- Azure Log Analytics
- Azure Monitoring Agent
- Microsoft Sentinel
- Windows Virtual Machine

## Key Skills Demonstrated
- Cloud security fundamentals
- Log ingestion and analysis
- SIEM configuration
- Visual representation via Sentinel Workbooks

## Environment
- Platform: Microsoft Azure
- Services: Azure Monitor, Log Analytics, Sentinel
- Scope: Dedicated resource group for lab isolation
