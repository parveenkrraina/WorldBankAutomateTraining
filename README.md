---

# WorldBankAutomateTraining

This repository contains reference materials and lab exercises for automation training using Power Automate, Microsoft Dataverse, SharePoint, and related tools. It is structured to help trainees learn and practice automation workflows step-by-step.

---

## Table of Contents

1. [Setup](#setup)
2. [Labs Overview](#labs-overview)
3. [Training Modules](#training-modules)
    - [Module 1: Create Cloud Flows](#module-1-create-cloud-flows)
    - [Module 2: Data Modeling](#module-2-data-modeling)
    - [Module 3: SharePoint Integration and Approval Flows](#module-3-sharepoint-integration-and-approval-flows)
    - [Module 4: Button Flows](#module-4-button-flows)
    - [Module 5: Scheduled Flows](#module-5-scheduled-flows)
4. [Resources](#resources)

---

## Setup

Before starting, ensure you have access to the necessary tools and environments:

### SharePoint Lists
1. **Employee_Onboarding**  
   - Columns: Title, EmployeeName, Role, StartDate
2. **PurchaseOrders**  
   - Columns: Title, Amount, Department, Status
3. **Expenses**  
   - Columns: Title, Employee, Amount, Status

### OneDrive Folders
- `/Training/Invoices_Inbox`
- `/Training/SalesReports`
- `/Training/EmployeeDocs`

### Microsoft Teams
- **Team:** Automation Training  
- **Channel:** ops-alerts

### Prerequisites for Labs
- Power BI Dataset: Publish a sample dataset named **OpsDashboard**.
- Azure Storage: Create a blob container named `linux-logs`.

---

## Labs Overview

This repository includes hands-on labs that cover a variety of Power Automate use cases:

- **Lab 1:** Sending automated welcome emails.
- **Lab 2:** Auto-saving invoice attachments.
- **Lab 3:** SharePoint list creation.
- **Lab 4:** Approval workflows for SharePoint items.
- **Lab 5:** Button-triggered flows.
- **Lab 6:** Scheduled flows for SharePoint data processing.

---

## Training Modules

### Module 1: Create Cloud Flows
- **Objective:** Learn to create cloud flows from templates and from scratch.  
- **Lab:** [Practice Lab 1 – Create Cloud Flows](Labs/M01L01_Create_flows.md)

### Module 2: Data Modeling
- **Objective:** Learn to create Dataverse tables, columns, and relationships.  
- **Lab:** [Practice Lab 2 – Data Model](Labs/M02L01_Data_model.md)

### Module 3: SharePoint Integration and Approval Flows
- **Objective:** Build SharePoint lists and create approval workflows.  
- **Labs:**
  - [Practice Lab 3 – SharePoint](Labs/M03L01_SharePoint.md)
  - [Practice Lab 4 – Approval Flow](Labs/M03L02_Approval_flow.md)

### Module 4: Button Flows
- **Objective:** Create instant button flows with user input.  
- **Lab:** [Practice Lab 5 – Button Flow](Labs/M04L01_Button_flow.md)

### Module 5: Scheduled Flows
- **Objective:** Automate recurring tasks with scheduled flows.  
- **Lab:** [Practice Lab 6 – Scheduled Flow](Labs/M05L01_Scheduled_flow.md)

---

## Resources

### Power Platform Development Tools
- [Power Platform ALM Tools](https://learn.microsoft.com/en-us/power-platform/developer/tools-alm)

### Dataverse Developer Tools
- [Download Dataverse Developer Tools (NuGet)](https://learn.microsoft.com/en-us/power-apps/developer/data-platform/download-tools-nuget)

---

Feel free to explore the repository and follow the lab instructions to enhance your Power Automate skills. For any issues or contributions, please contact @parveenkrraina or open a discussion.

--- 