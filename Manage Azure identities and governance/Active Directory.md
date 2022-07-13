**Azure Active Directory**

Azure active directory is more of like a library which keeps all types of hard-binded and digital books managed in one place.

![Azure Active Directory](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/b23c9c859fb8edefa8929cbab1ae8f5dd6796c23/Manage%20Azure%20identities%20and%20governance/Images/azure-active-directory.png "Azure Active Directory")

This directory manages and keeps the directory in-sync with the identity and access management.

There are many benefits or features of Azure Active Directory:

1. SSO (Single Sign-On) to any Cloud and On-Premises running applications

2. Works with almost every devices like iOS, macOS, Android and Windows devices.

3. Protection of the on-premises applications over the secure remote access.

4. You can easily extend the Active Directory to the Cloud by making them Syncronizable with another on-premises directories.

5. Makes the whole process safe and protected of acessing and interacting with data by showing reports over the suspicious sign-on's or potential vulnerabilities. This feature provides an advanced advantage like Advanced Security Reports, Notifications, Remediation Recommendations and risk-based policies.

6. This also helps in reducing the costs and enhancing the security by integrating various verification and validation steps which also helps to reduce the number of tickets raised and helpdesk calls.

There are some Azure Active Directory concepts which you need to understand:

1. Identity which can be a user with a Username or Password, Identity can also be the secret key or certificates which require authentication.

2. Account is something like an identity with has some data associated to the same. Similarly an additional concept of Account can be Azure AD Account which is more about the type of identity created to sign-in into the services or applications. These identities are stored into the Azure Active Directory and allows you to access to your organizational cloud service.

3. Azure Subscription is similar to your amazon prime or netflix subscription which allows you to access the cloud services which can be linked to your credit card or it can be your organizational structure.

4. Azure Tenant/Directory is a dedicated shelf to store your cloud resources in which you can add more tenants just like shelfs in racks. This enables you to create or add more and more instances of azure AD. These both terms Tenant or Directory are often used interchangebly.

**Azure AD Join**

Azure Active Directory (Azure AD) enables you to SSO to the devices, apps and services from anywhere by the IT Team which always look after to protect the corporate assets and look into the devices comply to meet the standards for security and compliance. Azure AD join is designed to provide access to the organizational apps and resources.

AD Join has some benfits like: Single-Sign-On(SSO), Enterprise Compliant Roaming(This enables you sync the settings over all the devices under your organization), Access to Microsoft's Store(This enables you to choose the applications from the pre-selected by the organization), Windows Hello(For secure and convenient acess to devices), Restriction of Apps(There can be some apps which can be accessed by the devices who comply those complicance policy) and Seamless access to the on-premises resources(When the device has access to the on-premises domain controller)