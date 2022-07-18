**Create User Accounts**

There are total three ways by which Azure AD defines user's in three ways:

Cloud Identities: These are the kind of user's which exist only inside the azure AD. These can be administrator accounts and users that you manage yourself.

Directory-Synchronized Identities: These are the user's which exist in the on-premises active directory. This whole process works with a synchronized activity that occurs via the azure AD connect which brings users to the Azure. Here the on-prem source is Windows Server AD.

Guest Users: These users exist outside of the Azure, For example account from another cloud providers or Microsoft account such as Xbox live account.

**Manage User Accounts**

**Azure Portal**

Azure Portal is the place from where you can access all the microsoft azure resources and manage them. Azure portal can be accessed by using the [Azure Portal](https://portal.azure.com/)

![Microsoft Azure Portal](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/3d484431040be1afef6879da63432519bdab5bb6/Manage%20Azure%20identities%20and%20governance/Images/azure-portal.png "Azure Portal")

*You can add users* using the above azure portal by accessing the user's option from the given options.

![Microsoft Azure User Portal](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/3d484431040be1afef6879da63432519bdab5bb6/Manage%20Azure%20identities%20and%20governance/Images/azure-portal-user.PNG "Azure User Portal")

From here you can find multiple options like add, invite, edit or delete opertions on your user's.

There are some things which we need to keep in mind while doing the same.

1. The logged-in user must be Global administrator to manage user's.
2. User profile is optional which can consists of picture, job or contact info.
3. Deleted user's from azure can be restored in the duration of 30 days.
4. Sign-in and audit log information is available.

*Adding Bulk User*

The Azure Active Directory supports bulk user create and delete operations this also supporting downloading list of the user's. For adding multiple user's at once you can download the .csv template from Azure AD portal. You can use Powershell for the same operation. 

![Microsoft Azure Bulk User Portal](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/2c6a6bf46583c6037a89cf3080d16c4f7d74002c/Manage%20Azure%20identities%20and%20governance/Images/azure-portal-bulk-user.PNG "Azure Bulk User Portal")

*Adding Group Accounts*

Azure AD allows you to create two types of group accounts.
1. Security Groups
    These security groups can be used to manage member and computer access to shared resources for a group of user's. This security group is also used to for specifying a security policy for certain set of user's.

2. Microsoft 365 Groups
    These Microsoft 365 groups provide collaboration to the different teams inside the organization which allows their member's access to a shared mailbox, calendar, files, sharepoint and more. Even you can give access to the people's outside the organization. For the reference both user's and admins can use the Microsoft 365 groups.

There are three different ways by which you can assign the access rights.
1. Assigned
    This let's you to add specific user's to the members of this group and to have unique permissions.

2. Dynamic User
    This let's you to use dynamic membership rules to automatically add or remove members.

3. Dynamic Device (Security groups only)
    Dynamic group rules allows you to automatically add or remove devices.