# ARM_Template
## 0. Use Bash/PowerShell to create a <MyResourceGroup> resource group.
         To check your resource group you can go to the Azure portal. 

### az group create -l eastus -n MyResourceGroup



## 1. Create a file named “storage-account-with-arm.json”


## 2. Write your code in the ARM template file to create
      ### (i)  a <MyStorageAccount> storage account in the resource group that you just created. 
     ###(ii) a <MyVirtualMachine> virtual machine in the resource group that you just created.



##3. Deploy your ARM template via Azure Portal.

### az deployment group create --resource-group MyResourceGroup  --template-file storage-account-with-arm.json
