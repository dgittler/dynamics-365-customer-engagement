---
title: "Enable languages for Dynamics 365 Customer Engagement | MicrosoftDocs"
ms.custom: ""
ms.date: "2017-08-31"
ms.reviewer: ""
ms.service: "crm-online"
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
applies_to: 
  - "Dynamics 365 (online)"
  - "Dynamics 365 Version 9.x"
ms.assetid: d5ac01dc-ebc6-455a-9a73-3367ff69eb1a
caps.latest.revision: 11
author: "Mattp123"
ms.author: "matp"
manager: "brycho"
---
# Enable languages
Enable languages in your organization to display the user interface and Help in a language that’s different from the base language. 

> [!IMPORTANT]
>  If you’re running [!INCLUDE[pn_crm_for_outlook_full](../includes/pn-crm-for-outlook-full.md)], before you can enable additional languages, you must download one or more [Language Packs](http://www.microsoft.com/download/details.aspx?id=40340) on the same computer.  
  
<a name="BKMK_Step2Provision"></a>   

## Enable the language  

 Before users can start using a Language Pack to display a language, the Language Pack must be enabled in your [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] organization.  
  
1.  Start the [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] web application. You’ll need a System Administrator security role or equivalent privileges for the [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] organization that you want to provision a Language Pack for.  
  
2. [!INCLUDE[proc_settings_administration](../includes/proc-settings-administration.md)]  
  
3.  Click **Languages** to open the **Language Settings** dialog box. Here you’ll see each Language Pack installed in your [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] deployment, with a check box to the left of each listed Language Pack  
  
4.  For each Language Pack that you want to provision (enable), select the check box next to it. For each Language Pack that you want to unprovision (disable), clear the check box.  
  
5.  Click **Apply**.  
  
6.  Click **OK** on any confirmation dialog boxes that open.  
  
    > [!NOTE]
    >  It may take several minutes for [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] to provision or unprovision the languages.  
  
7.  To close the **Language Settings** dialog box, click **Close**.  
  
 Repeat the previous steps for each organization in your [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] deployment.  
  
<a name="BKMK_Step3Select"></a>   
## Select the language to display the user interface and Help  
 Each user selects the language to display in both the [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] web client and [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)] applications.  
  
> [!IMPORTANT]
>  For [!INCLUDE[pn_microsoft_dynamics_crm_for_outlook](../includes/pn-microsoft-dynamics-crm-for-outlook.md)], you must download and install the Language Packs before you can select them. <!--[!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Install and enable a Language Pack](Install%20and%20enable%20a%20Language%20Pack.md)  -->
  
1.  Sign in to [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] and open the **Set Personal Options** page, as follows:  
  
    -   If you’re using the [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] web client, click the **Settings** button ![Settings button](../admin/media/settings-button.png "Settings button"), and then click **Options**.  
  
    -   If you are using [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)], on the top menu bar, choose **Dynamics 365**, and then click **Options**.  
  
2.  Choose the **Languages** tab.  
  
3.  In the **User Interface Language** list, select the language in which you want to display [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)].  
  
4.  In the **Help Language** list, select the language in which you want to display [!INCLUDE[pn_Microsoft_Dynamics_CRM_Help](../includes/pn-microsoft-dynamics-crm-help.md)].  
  
5.  To save your changes and close the dialog box, click **OK**.  
  
> [!NOTE]
>  In [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)], the user language settings only apply to [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)] features, such as the user interface display of the **Dynamics 365** menu, and don’t affect other areas of [!INCLUDE[pn_MS_Outlook_Full](../includes/pn-ms-outlook-full.md)]. To display all of the [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)] user interface or Help in multiple languages, you need to install one or more [!INCLUDE[pn_MS_Office](../includes/pn-ms-office.md)]Language Packs. More information: [Office 2013 Language Options](http://office.microsoft.com/language-packs/).  
  
<a name="knownissues"></a>   
## Known issues with Language settings  
  
### Distorted characters are displayed in some languages when you run Dynamics 365 for Outlook on Windows 10  
 By default, [!INCLUDE[pn_windows_10](../includes/pn-windows-10.md)] includes a limited number of available languages. If your language is not already available on [!INCLUDE[pn_windows_10](../includes/pn-windows-10.md)], you’ll need to download and install it before you install [!INCLUDE[pn_crm_for_outlook_short](../includes/pn-crm-for-outlook-short.md)]. More information: [Language packs](http://windows.microsoft.com/en-US/windows/language-packs#lptabs=win10).  
  
### See also  
 [Enable or disable languages](http://go.microsoft.com/fwlink/p/?LinkID=513230)