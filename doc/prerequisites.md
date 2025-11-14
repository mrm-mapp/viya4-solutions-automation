[← Back to README](../README.md)

# Prerequisites

Before deploying SAS solutions to Azure, ensure you meet the following requirements:

- **Azure Subscription Access:**  
  You must have an Azure subscription with permissions to create resources and managed applications.

- **Resource Provider Registration:**  
  In the Azure Portal, select your subscription and navigate to **Settings → Resource Providers**. Register the following providers:
  - Microsoft.Storage
  - Microsoft.Solutions
  - Microsoft.ManagedIdentity
  - Microsoft.Network
  - Microsoft.DBforPostgreSQL
  - Microsoft.ContainerService
  - Microsoft.Compute
  - Microsoft.Quota (optional, but recommended if you encounter quota issues)

- **Resource Availability:**  
  Ensure your subscription has sufficient quotas limits (VMs, IP addresses, storage, etc.) for your chosen environment size. 
  Refer to the [Environment Sizing](#environment-sizing) section for details.

- **SAS Solution Assets:**  
  Download SAS solution assets, license, and certificates for your SAS Software Order ID and cadence from [my.sas.com](https://my.sas.com).

- **Recommended Skills:**  
  Familiarity with Azure Resource Manager (ARM templates), Azure Kubernetes Service (AKS), and managed applications is beneficial.

- **GitHub Workflow Requirements:**  
  If deploying via GitHub workflows, upload SAS solution assets, license, and certificates to an Azure Storage Account accessible by the workflow.

---

[← Back to README](../README.md)