# Hub and Spoke network Lab
This repo provides Terraform templates for a dual-region hub and spoke topology, connected to simulated on-prem datacenters.
![image](media/topology.png)

Before running the script, edit /templates/main.tf with the subscription ID to deploy into: 
```
maint.tf:
provider "azurerm" {
  subscription_id = "Subscription ID goes here"
  features {}
}
```
