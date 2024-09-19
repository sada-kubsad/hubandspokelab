# Initialize:
```Log into Azure Cloud Shell
git clone https://github.com/sitarant/AVNM-secure-Hub-Spoke-multiregion
cd AVNM-secure-Hub-Spoke-multiregion/tf_code
#Set environment variable
## Either:
export ARM_SUBSCRIPTION_ID=0276702b-8348-4d6a-8aa2-f34cb186ad09
## OR:
### In main.tf set:
### provider "azurerm" {
###       subscription_id = "xxxxxxxxxxx5dd"  --> ID of the subscription that you want to use
###       features {}
### }
terraform init
terraform apply
When prompted, provide password for VMs
```
# Note the values generated at end of run:
```

```
