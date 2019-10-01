---
page_type: sample
languages:
- java
products:
- azure
description: "Azure Stack Storage sample for managing storage accounts"
urlFragment: hybrid-storage-java-manage-storage-accounts
---

# Manage hybrid storage accounts (Java)

  Azure Stack Storage sample for managing storage accounts -
   - Create a storage account
   - Get | regenerate storage account access keys
   - Create another storage account
   - Update Storage account by enabling encryption
   - List storage accounts
   - Delete a storage account.
 

## Running this Sample ##

To run this sample:

1. Clone the repository using the following command:

    git clone https://github.com/Azure-Samples/hybrid-storage-java-manage-storage-accounts.git

2. Create an Azure Stack service principal and assign a role to access the subscription. For instructions on creating a service principal, see [Use Azure PowerShell to create a service principal with a certificate](https://docs.microsoft.com/en-us/azure/azure-stack/azure-stack-create-service-principals).

3. Set the following required environment variable values:

    * AZURE_TENANT_ID

    * AZURE_CLIENT_ID

    * AZURE_CLIENT_SECRET

    * AZURE_SUBSCRIPTION_ID

    * ARM_ENDPOINT

    * RESOURCE_LOCATION

4. Change directory to sample:
    
    * cd hybrid-storage-java-manage-storage-accounts

5. Run the sample:
    * mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
