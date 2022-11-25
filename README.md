# Festive Tech Calendar 2022

### Overview
The Festive Tech Calendar is a technical community initiative geared towards sharing information. Throughput December there will be lots of new content published from people all over the globe.

### Supporting the Missing People Charity
This year the Festive Tech Calendar Team are raising money for the charity **[missingpeople](https://www.missingpeople.org.uk/)**. We believe its important to support charities who do great work. Without fundraising Missing People wouldn’t be able to find vulnerable missing people and reunite families. Please, if you can, donate to this very worthy cause.

### Prerequisites - What do you need?
Below is a list of things you will need to complete this lab.
- An Azure subscription, with credit available, it ain't free :)
- **Please note** - Not all regions support all ANF features, i.e UK West does not currently support ANF standard network features. Make sure, when you choose which region(s) you are going to be deploying into that those regions support your requirements.
- The Azure NetApp Files **Resource Provider** registered in your subscription. Link to do that [HERE](https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-register)
- Azure CLI installed on your system.
- A code editor, I prefer **VSCode**, link [HERE](https://code.visualstudio.com/Download)
- I also like to use GitHub Desktop, link [HERE](https://desktop.github.com/)
- VSCode extensions help as well. I use Terraform, Azure CLI, Powershell, GitHub and few others.
- Latest version of Terraform installed (Windows users use x64 version), link [HERE](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)
- I use **Chocolatey** to manage my apps, link [HERE](https://chocolatey.org/install)

### What are we going to do?
We are going to build out a lab using Terraform. The lab will include the following services and features.
- Resource Groups
- Virtual Networks
- Subnets
- Virtual Network Peers
- Virtual Machines
- Azure Keyvault
- ANF Accounts
- ANF Capacity Pools
- ANF Volumes

### Schematic
Below is a high-level visual overview of what we are going to deploy into Azure.

<img src="https://github.com/anthonymashford/Events/blob/main/FestiveTechCalendar2022/TF-Deploy%20ANF%20using%20Terraform/images/TerraformLab-FTC2022.png">

### Deploying the Lab
Next, we will go through the steps required to deploy the ANF Lab using Terraform and the code in this repo.
