# Lab 13: Global multi-tenant management

Nerdio Manager allows you to create global views that best represent your workflows. For example, if you manage host pools, session hosts, and user sessions, there is no need to keep jumping back and forth between pages to manage these different resources. With global views, you can combine all the resource on a single page. 

In this lab, you'll be configuring global view for Backup using NMM portal.

## Task 1: Create Global view using NMM portal

1. click on the **Nerdio** logo to return to home page.

   ![](media/snmm2.jpg)

1. From the **Settings (1)** side blade, select **Global views (2)**.

   ![](media/snmm3.jpg)

1. Click on **Add global view**.

   ![](media/snmm4.jpg)

1. In the EDIT GLOBAL VIEW page, provide the following details to create a new global view.

   - NAME: **globalview-01** ***(1)***
   - VISIBLE TO: **Only mw** ***(2)***
   - ACCOUNTS: **Azure HOL (ID)** ***(3)***
   - Resource type: scroll down in the list and select **Backups** ***(4)*** from common.
   - Leave other options to default and click on **OK** ***(5)***

   ![](media/snmm5.jpg)   

1. Once the creation is completed. You'll be able to see the **globalview-01** global view in the side blade. select to open it.

   ![](media/snmm6.jpg)  

1. You'll be see BACKUP tab in the global view.

   ![](media/snmm7.jpg) 
