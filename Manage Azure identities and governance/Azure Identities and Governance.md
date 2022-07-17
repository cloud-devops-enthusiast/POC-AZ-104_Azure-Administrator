**Create User Accounts**

There are total three ways by which Azure AD defines user's in three ways:

Cloud Identities: These are the kind of user's which exist only inside the azure AD. These can be administrator accounts and users that you manage yourself.

Directory-Synchronized Identities: These are the user's which exist in the on-premises active directory. This whole process works with a synchronized activity that occurs via the azure AD connect which brings users to the Azure. Here the on-prem source is Windows Server AD.

Guest Users: These users exist outside of the Azure, For example account from another cloud providers or Microsoft account such as Xbox live account.

**Manage User Accounts**

**Azure Portal**

Azure Portal is the place from where you can access all the microsoft azure resources and manage them. Azure portal can be accessed by using the [Azure Portal](https://portal.azure.com/)

![Microsoft Azure Portal](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/3d484431040be1afef6879da63432519bdab5bb6/Manage%20Azure%20identities%20and%20governance/Images/azure-portal.png "Azure Portal")

You can add users using the above azure portal by accessing the user's option from the given options.

![Microsoft Azure User Portal](https://github.com/cloud-devops-enthusiast/POC-AZ-104_Azure-Administrator/blob/3d484431040be1afef6879da63432519bdab5bb6/Manage%20Azure%20identities%20and%20governance/Images/azure-portal-user.PNG "Azure User Portal")

From here you can find multiple options like add, invite, edit or delete opertions on your user's.

There are some things which we need to keep in mind while doing the same.

1. The logged-in user must be Global administrator to manage user's.
2. User profile is optional which can consists of picture, job or contact info.
3. Deleted user's from azure can be restored in the duration of 30 days.

