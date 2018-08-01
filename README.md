---
services: Appservice
platforms: java
author: jianghaolu
---

## Getting Started with Appservice - Manage Web App Cosmos Db Through Key Vault - in Java ##


  Azure App Service basic sample for managing web apps.
   - Create a Cosmos DB with credentials stored in a Key Vault
   - Create a web app which interacts with the Cosmos DB by first
       reading the secrets from the Key Vault.
 
       The source code of the web app is located at
       https://github.com/Microsoft/todo-app-java-on-azure/tree/keyvault-secrets
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-java-access-key-vault-by-msi-for-web-apps.git

    cd app-service-java-access-key-vault-by-msi-for-web-apps

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.