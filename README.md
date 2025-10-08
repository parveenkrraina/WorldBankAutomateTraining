# World Bank Power Automate Training

Welcome to the **World Bank Power Automate Training** repository! This resource is designed to guide you through hands-on automation training using Microsoft Power Automate, Dataverse, SharePoint, and related Microsoft 365 tools. The repository is organized to help you build practical automation skills through structured modules and labs.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Setup & Prerequisites](#setup--prerequisites)
3. [Lab Overview](#lab-overview)
4. [Training Modules](#training-modules)
5. [Resources](#resources)
6. [Changelog](#changelog)

---

## Introduction

This repository provides step-by-step labs and reference materials for automating business processes. Whether you are new to Power Platform or looking to deepen your automation expertise, these modules will help you learn by doing.

---

## Setup & Prerequisites

Before starting, ensure you have access to the following environments and tools:

### SharePoint Lists

- **Employee_Onboarding**:  
   Columns – Title, EmployeeName, Role, StartDate
- **PurchaseOrders**:  
   Columns – Title, Amount, Department, Status
- **Expenses**:  
   Columns – Title, Employee, Amount, Status

### OneDrive Folders

- `/Training/Invoices_Inbox`
- `/Training/SalesReports`
- `/Training/EmployeeDocs`

### Microsoft Teams

- **Team:** Automation Training  
- **Channel:** ops-alerts

### Additional Requirements

- **Power BI Dataset:** Publish a sample dataset named `OpsDashboard`.
- **Azure Storage:** Create a blob container named `linux-logs`.

---

## Lab Overview

The repository includes practical labs covering a range of automation scenarios:

- **Lab 1:** Send automated welcome emails to new employees.
- **Lab 2:** Automatically save invoice attachments from emails to OneDrive.
- **Lab 3:** Create and manage SharePoint lists for business data.
- **Lab 4:** Build approval workflows for SharePoint items.
- **Lab 5:** Design button-triggered flows for instant actions.
- **Lab 6:** Schedule flows to automate recurring SharePoint data processing.

Each lab provides detailed, step-by-step instructions and sample data where applicable.

---

## Training Modules

### Create Cloud Flows

- **Objective:** Learn to create cloud flows using templates and custom logic.
- **Lab:** [Practice Lab 1 – Create Cloud Flows](Labs/M01L01_Create_flows.md)

### Data Modeling

- **Objective:** Build Dataverse tables, columns, and relationships for structured data storage.
- **Lab:** [Practice Lab 2 – Data Model](Labs/M02L01_Data_model.md)

### SharePoint Integration and Approval Flows

- **Objective:** Integrate Power Automate with SharePoint and implement approval processes.
- **Labs:**
   - [Practice Lab 3 – SharePoint](Labs/M03L01_SharePoint.md)
   - [Practice Lab 4 – Approval Flow](Labs/M03L02_Approval_flow.md)

### Button Flows

- **Objective:** Create instant flows triggered by user actions.
- **Lab:** [Practice Lab 5 – Button Flow](Labs/M04L01_Button_flow.md)

### Scheduled Flows

- **Objective:** Automate recurring tasks using scheduled flows.
- **Lab:** [Practice Lab 6 – Scheduled Flow](Labs/M05L01_Scheduled_flow.md)

---

## Resources

### Power Platform Development Tools

- [Power Platform ALM Tools](https://learn.microsoft.com/en-us/power-platform/developer/tools-alm)

### Dataverse Developer Tools

- [Download Dataverse Developer Tools (NuGet)](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/download-tools-nuget)

---

Feel free to explore the repository, follow the lab instructions, and contribute your feedback or improvements. For questions or support, contact @parveenkrraina or open a discussion.
