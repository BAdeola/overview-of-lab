# Creating Virtual Machine

In this lab, we will create a virtual machine (VM) using the Microsoft Azure. The followed steps below was used to create the VM.

- Log in to the Azure portal at [https://portal.azure.com](https://portal.azure.com).
- In the left-hand menu, click on "Create a resource".
- In the "Search the Marketplace" box, type "Virtual Machine" and select "Virtual Machine" from the list of results.
- Click on the "Create" button to start the VM creation process. 

![create](assets/create.png)

- In the "Basics" tab, fill in the required information:
  - Subscription: Select your Azure subscription.
  - Resource group: Create a new resource group or select an existing one.
  - Virtual machine name: Enter a name for your VM.
  - Region: Choose a region close to you or your users.
  - Image: Select the operating system image you want to use (in this caso Windows Server).
  - Size: Choose the size of the VM based on your requirements (CPU, RAM, etc.).
  - Administrator account: Set up a username and password or SSH public key for accessing the VM.
  - Inbound port rules: Select the ports you want to open (e.g., SSH for Linux, RDP for Windows).
  - Click Review + create to proceed.
  ![basic](assets/basics.png)
  - Wait for the validation to pass, then click "Create" to deploy the VM.
  - You can click go to resource to see the status of your VM deployment.
  - Once the deployment is complete, navigate to the VM resource.
  - Click in connect button to get the connection details, like the public ID or a Bastion conection.
  - Use the provided connection details to access your VM using Remote Desktop (RDP) for Windows or SSH for Linux. 
