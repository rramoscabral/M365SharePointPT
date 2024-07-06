---
layout: default
title: "Exercício: Aprovações do SharePoint sem fluxo de trabalho"
nav_order: 5.1
has_children: false
---

# Exercício: Aprovações do SharePoint sem fluxo de trabalho
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

## Laboratório 04: Aprovações do SharePoint sem fluxo de trabalho

**Atenção:** Os exercícios não estão escritos em português por norma todo o conteúdo criado pelo formador [Ricardo Cabral](https://www.rramoscabral.com/) é escrito em inglês utilizando a terminologia original.

<br/>


Sync a document library in SharePoint to you work directly in File Explorer and access files even when you're offline. And when you go back online, any changes made to those files will sync automatically.

## Microsoft 365 user interface

Given the dynamic nature of Microsoft cloud tools, you might experience UI (User Interface) changes that occur after the development of this training content. As a result, the lab instructions and lab steps might not align correctly.

Cloud updates occur frequently, so you might encounter UI changes before this training content updates. **If this occurs, adapt to the changes, and then work through them in the labs as needed.**


## Lab Scenario 

Create SharePoint Approvals without workflow in an existing document library in SharePoint.


## Objectives

Create SharePoint Approvals without workflow in an existing document library in SharePoint.

## Instructions

### Before you start

You must have access to a Microsoft 365 account with SharePoint Online.

#### Sign in to the lab environment

Use the credentials provider by the instructor.

<br/>


### Exercise 1: Create a new document library named **Approvals**

<br/>

**Requirements:** 
 - You have to complete the previous labs.


1. Go to the SharePoint Team site you created.

1. On the menu bar, select **New**, and then select **Document library**.

    ![New Document Library](https://www.rramoscabral.com/training/assets/MSSharePoint/NewDocumentLibrary.png)

1. Enter a name for the new library.
    - **Name:** Approvals
    - **Description:** Approvals documents without workflow
    - **Show in site navigation:** Enabled

1. Select **Create**.

<br/>

### Exercise 2: Enabling versioning and content Approval

1. Go to **Settings** > **Library Settings** 

    ![Library Settings](https://www.rramoscabral.com/training/assets/MSSharePoint/LibrarySettings.png)

1. Select **Versioning settings**

    ![Versioning settings](https://www.rramoscabral.com/training/assets/MSSharePoint/LibrarySettingsVersioningSettings.png)


1. In the **Content Approval section**, select **Yes**.

1. Inthe **Who should see draft items in this document library?**, select **Only users who can approve items (and the author of the item)** it is set for you by default.

    ![Versioning Settings ContentApproval](https://www.rramoscabral.com/training/assets/MSSharePoint/VersioningSettingsContentApproval.png)

1. Select **OK** button.

1. Return to the library by clicking **Approvals** (library name).

1. You will see that a column named **Aproval Status**.

    ![Approval Status Column](https://www.rramoscabral.com/training/assets/MSSharePoint/ApprovalStatusColumn.png)


<br/>


### Exercise 3: Upload file to test content approval


1. Choose a file of your choice and upload or drag it to test content approval.

1. You will see that the file is in **pending** approval state.

<br/>


### Exercise 4: Approve the file

1. Select the file.
1. From the list of options select the **... (ellipses)**
1. Select **Aprove/Reject**
    
    ![Approval Status Column Approve Or Reject](https://www.rramoscabral.com/training/assets/MSSharePoint/ApprovalStatusColumnApproveOrReject.png)

1. You have to set the approval status which can be:

    | Approval Status | Description |
    | --- | --- |
    | Approved | This item will become visible to all users.|
    | Rejected | This item will be returned to its creator and only be visible to its creator and all users who can see draft items. |
    | Pending | This item will remain visible to its creator and all users who can see draft items. |


1. Set the approval status to **Approved**.


    ![Set Approval Status](https://www.rramoscabral.com/training/assets/MSSharePoint/SetApprovalStatus.png)

1. Click **OK** button.

1. You will see that the file is in **Approved** approval state.

**END OF LAB**
