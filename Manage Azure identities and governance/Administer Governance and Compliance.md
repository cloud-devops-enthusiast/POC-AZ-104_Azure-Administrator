**Azure Regions**
An Azure Region is a geographical area on the earth containing at least one, but potentially multiple datacenters. The datacenter's are in close proximity and networked together with a low-latency network.

![Azure Regions](https://docs.microsoft.com/en-us/learn/wwl-azure/configure-subscriptions/media/azure-regions-a31968fe.png "Azure Regions")

Above is the image for reference for the different azure regions like, West US, Canada Central, West Europe, Australia East and Japan West.

There are many things for refernce which you can know about the Azure Regions.
1. Azure has more global regions than any another cloud provider.
2. Regions provide customers the flexibility and scale needed to bring applications closer to their users.
3. Regions preserve data residency and offer comprehensive compliance and resiliency options for customers.
4. Whenever you choose a service, you have the option to choose the region where you want to deploy your services.
5. Some services or Virtual Machines features are restricted to certain region or available in certain regions of microsoft azure, these features can be specific virtual machine sizes and storage types as the availability of hardware in that region is a big issu.
6. Some Azure services that do not require you to select a region and also these services include Azure Active Directory, Microsoft Azure Traffic Manager and Azure DNS service.
7. Each Azure region is paired with another region within in same geography of that area as they will be making a regional pair.

There are some things to know about the *Regional Pair* like Physical isolation, Platform-provided replication, Region recovery order, Sequential updates and Data residency.

**Azure Subscription**
An Azure Subscription is similar to your wallet where you keep your all financial resources like cards and cash, Just like that azure subscription is something which is linked to your Azure Account for whom the billing happens for the Azure services on per-subscription basis.
These Subscriptions helps you to organize access to the cloud service resources, these also helps you to control how resource usage is reported, billed and paid for. Each subscription can have a different billing and payment setup so different plans by department, project, regional office and so on.

![Azure Subscription](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/d987b583920c5e1f1e7df46523e8e4e6b67f9390/Manage%20Azure%20identities%20and%20governance/Images/azure-subscription.PNG "Azure Subscription")

*Azure Account* is like an identity which is associated with an Azure Active Directory (Azure AD) or in the directory which is trusted by Azure AD. Subscriptions have accounts.

There are various ways to get an Azure Subscription:
1. Enterprise Agreement: an enterprise agreement customer can add Azure to their agreement by making an upfront monetary commitment to Azure.
2. Reseller
3. Partner: You can go to a Microsoft Partner who can design and implement your Azure cloud solution.
4. Personal free Account: You can choose a free trial account so you can get started with using the Azure right way, as you don't need to pay until you choose to upgrade you existing plan or model of payment.

*Azure Subscription Usage*
Azure has both paid and free subscriptions which are based on the different needs and requirements. The mostly used kind of subscriptions are:
1. Azure Free SUbscription
    This is the kind of subscriptions which is included with 200$ credits to spend on different Azure services in first 30 days, this also includes the free access to the popular Azure products for 12 months out of which access to more than 25 products is free for the lifetime.
2. Azure Pay-As-You-Go Subscription
    As if you use the pay as you go subcription charges you monthly for the services you used in that billing period. This Subscription type is better for the small or large sized businesses.
3. Azure Enterprise Agreement
    An Enterprise Agreement provides flexibility to buy cloud services and software licenses under one agreement with discounts for new licenses and software assurance. This kind of agreement are mostly focused over the enterprise-scale organizations.
4. Azure for Student Subscription
    An Azure for Student Subscription includes $100 worth of Azure credits which can be used over the period of 12 months plus they get access to the free services without requiring a credit-card at sign-up.

![Azure Subscription Usage](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/d987b583920c5e1f1e7df46523e8e4e6b67f9390/Manage%20Azure%20identities%20and%20governance/Images/azure-cost-analysis.PNG "Azure Subscription")

*Plan and Control your Expenses with Azure Subscriptions*
You can use Azure Subscriptions to control and forecast your Expenditure over your cloud resources. You can use cost management tools like Cost Analysis, Budgets, Recommendations and you can Export the Cost Management data. You can set a daily scheduled export of cost management report in csv format and store those files in Azure Storage.

*Resource Tagging*
You can use tags to your Azure Resources to make them easy to organize them by categories. Each Tag consits of two things as a name and a value.
There are some things which you need to remember about tagging:
1. There is maximum of 50 tag name/value pairs you can assign to each resource or resource group.
2. Tags doesn't support inheritance, like if you assign tag to any resource group that will not be inherited by the resources under that same resource group.

![Azure Resource Tag](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/d987b583920c5e1f1e7df46523e8e4e6b67f9390/Manage%20Azure%20identities%20and%20governance/Images/azure-tags.PNG "Azure Resources Tagging")

Apply Cost Savings
* Reservations: This helps you to save money by paying ahead. Reservations can significantly reduce your virtual machine, SQL database compute, Azure cosmos DB or other resource costs upto 72% on pay-as-you go prices. Reservation provide a billing discount and don't affect the runtime state of your resources.
* Azure Hybrid Benefits: This is a benefit for customers who have licenses with software assurance. This helps maximize the value of existing on-premises windows server or SQL server license investments when migrating to azure.
* Azure Credit: This is the monthly credit benefit that allows you to experiment with, develop and test new solutions on azure.
* Azure Region: The pricing can vary from one region to another, even in the US. Double check the pricing in various regions to see if you can save a little.
* Budgets: Azure Budgets helps you to plan for and drive organizational accountability. This helps you to inform other's about their spending to proactively manage costs, and to monitor how spending progresses over time. 
* Azure Pricing Calculator: The pricing calculator provides estimates in all areas of azure including compute, networking, storage, web and databases.
![Azure Pricing Calculator](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/d987b583920c5e1f1e7df46523e8e4e6b67f9390/Manage%20Azure%20identities%20and%20governance/Images/azure-pricing-calculator.PNG "Azure Pricing Calculator")

*Azure Management Group*
Azure Management group provide a level of scope over the subcriptions. You can use these Azure Management Groups for managing the subscriptions where these management act like the containers which can be used to further to apply the governance conditions to the management group.
These management groups enable you to do the following:
* Organizational alignment for your Azure subscriptions through custom hierarchies and grouping.
* Targeting of policies and spend budgets across subscriptions and inheritance down the hierarchies.
* Compliance and Cost reporting by the organization.

You can create the management group by using the portal, Powershell or Azure CLI.

![Azure Management Group](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/d7edbab10cd790f094e0e1c487d55955199357ca/Manage%20Azure%20identities%20and%20governance/Images/azure-management-group.PNG "Azure Management Group")

The *Management group ID* is the idenfier which is unique and is used to submit the commands on the Management Group. This identifier is not editable after the creation of the same as it is used throughout the whole azure system to identify the group.
The *Display Name* field is the name that is displayed within the Azure Portal.

![Azure Management Group Creation](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/d7edbab10cd790f094e0e1c487d55955199357ca/Manage%20Azure%20identities%20and%20governance/Images/azure-create_management-group.PNG "Azure Management Group Creation")

**Note** There can be nested management group, followed by the number of subscription in a single account.

There are certain advanatges of Azure Policy in the areas of enforcement and compliance, scaling and remediation.
1. *Enforcement and Compliance*: Managing the built-in policies or Making the custom policies for all the resource types.
2. *Apply policies at scale*: Applying policies over a single management group while having control across your entire organization.
3. *Remediation*: Real time remediation(Providing remedy or solution for that issue right in that time) and remediation on existing resources.

There are certain use-cases for Azure policies:
* Specify the resource types that your organization can deploy.
* Specify a certain set of virtual machines SKU's that your organization can depploy.
* Restrict the locations your organization can specify when deploying resources.
* Enforce a required tag and it's values.
* Audit if Azure Backup service is enabled for all virtual machines.

**Implementing Azure Policies**
1. Browse Policy Definitions: A policy definition expresses what to evaluate and what actions to take.
2. Create Initiative Definitions: An initiative definition is a set of policy definitions to help track your Compliance state for a larger goal. Example, You can say that a branch office of a certain organization is compliant to some compliances or standards.
3. Scope the initiative Definition: You can control the scope of the initiative definition to management group, Subscriptions or Resource Groups.
4. View policy Evaluation Results: Once an initiative definition is assigned, you can evaluate the state of compliance for all your resources, individual resources, resource groups and subscriptions within scope can be exempted from having policy rules affect it.

**Create Policy Definitions**
There are many Built-in policy definitions from which you can choose. Policy definitions have a specific JSON format.
* You can check what type of resources can be deployed.
* Geo-Compliance lock which helps you to deploy resources from allowed locations only.

![azure-policy-definitions](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/d7edbab10cd790f094e0e1c487d55955199357ca/Manage%20Azure%20identities%20and%20governance/Images/azure-policy-definitions.PNG "Azure policy definition")


**Create Initiative Definitions**
This definition includes one or more policies, whereas there will be a pick-list to make a selection.
The scope of the initiative definition determines what resources or grouping of resources the policy assignment gets enforced on.

![azure-policy-scope_of_initiative-definition](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/d7edbab10cd790f094e0e1c487d55955199357ca/Manage%20Azure%20identities%20and%20governance/Images/azure-policy-scope_of_initiative-definition.PNG "Azure policy scope of initiative definition")

![azure-policy-compliance](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/d7edbab10cd790f094e0e1c487d55955199357ca/Manage%20Azure%20identities%20and%20governance/Images/azure-policy-compliance.PNG "Azure Policy compliance")
*Note*: Policy evaluation occurs about once an hour.
 
 