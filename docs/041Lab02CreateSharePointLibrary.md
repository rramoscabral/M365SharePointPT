---
layout: default
title: "Exercício: Criar uma biblioteca SharePoint"
nav_order: 4.1
has_children: true
---

# Exercício: Criar uma biblioteca SharePoint 
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

## Laboratório 02: Criar uma biblioteca SharePoint

**Atenção:** Os exercícios não estão escritos em português por norma todo o conteúdo criado pelo formador [Ricardo Cabral](https://www.rramoscabral.com/) é escrito em inglês utilizando a terminologia original.

<br/>

Create a document library in SharePoint to securely store files, work on them together, and access them from any device at any time. 

SharePoint team sites include a document library by default, however, you can add additional document and other libraries to a site as needed.

## Microsoft 365 user interface

Given the dynamic nature of Microsoft cloud tools, you might experience UI (User Interface) changes that occur after the development of this training content. As a result, the lab instructions and lab steps might not align correctly.

Cloud updates occur frequently, so you might encounter UI changes before this training content updates. **If this occurs, adapt to the changes, and then work through them in the labs as needed.**


## Lab Scenario 

With the new SharePoint site created it is necessary to have the possibility to share documents between the members of the site.


## Objectives

Create a new SharePoint library.

## Instructions

### Before you start

You must have access to a Microsoft 365 account with SharePoint Online.

#### Sign in to the lab environment

Use the credentials provider by the instructor.

<br/>

### Exercise 1: Create SharePoint document library

**Requirements:** You must complete the Create a team site in SharePoint lab.

1. Go to the SharePoint Team site you created.

1. On the menu bar, select **New**, and then select **Document library**.

    ![New Document Library](https://www.rramoscabral.com/training/assets/MSSharePoint/NewDocumentLibrary.png)

1. Enter a name for the new library.
    - **Name:** Department documents
    - **Description:** Internal department documents
    - **Show in site navigation:** Enabled

1. Select **Create**.

    - The new document library named ***Department documents*** is available on site navigation.

<br/>


### Exercise 2: Upload files to a library

You can drag files and folders from your computer to upload them to your OneDrive library or SharePoint team site with the modern experience. You can also browse and upload your files using the classic version.

1. In document library ***Department documents*** create a folder named **Invoices**.

    ![Document Library New Folder](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryNewFolder.png)


1. Download the zip file containing the sample course files and unzip the files to a location of your choice. .
    - If you don't have the download link, ask the instructor to provide it.

1. Upload the contents of the **Invoices** folder to the Invoices folder created in the document library.
    1. On menu select **Upload** > **Files**
    1. Open the Invoice folder from unzip file.
    1. Select all the files and confirm.

        ![Document Library Upload Invoices](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryUploadInvoices.png)


1. Return to the Document Library root and drag and drop all the files from unzip file to the root. 
    - SharePoint will create all folders and subfolders and upload the files.


<br/>

### Exercise 3: Adding columns

Add three columns.

1. In the **Department documents** library select the Invoices folder.

1. Add a column with data type **Single line of text** with the following parameters
    - **Name:** Customer
    - **Desciption:** Invoice customer
    - **Type:** Single line of text
    - **Default value** `empty`
    - **Use calculated value:** not enabled

        ![Document Library Add Column](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryAddColumn.png)



1. Add another column with data type **Number (1, 1.0, 100)** with the following parameters
    - **Name:** Invoice
    - **Desciption:** Invoice #
    - **Type:** Single line of text

    > **Note:** To view more data type select **More...**


1. Add another column with data type **Choice** with the following parameters
    - **Name:** Status
    - **Desciption:** Invoice Status
    - **Type:** Choice
        - Choices:
            - Submitted
            - Paid
    - **Default value:** Submitted


    ![Document Library AddColumn Choice](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryAddColumnChoice.png)

<br/>

### Exercise 4: Edit values

Depending on the type of data a column can change the value in all documents or manually in each document.

First you will change all status to Submited then you change one row manually.

1. Toggle selection for all items.

    ![Toggle selection for all items Icon](![Document Library AddColumn Choice](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryToggleSelectionForAllItems.png)

1. Open the details pane.
    
    ![Document Library Details Pane Icon](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryDetailsPaneIcon.png)


1. Set the **Status** to **Submitted**

1. Save.


You can edit the values in several ways two ways.
    - Using details pane
    - Or proprites


1. Select the first invoice.
    - Right click and them select **Details**.
    - Or open details pane..
    - Right click and them select **properties**.

1. Change the **Status** to **Paid**. 


### Exercise 5: Edit and Delete columns

Change the Invoice column then delete it.

1. Select the Invoice column header then select **Column settings** > **Edit** 

    ![Document Library Edit Column](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryEditColumn.png)

1. Change the symbol to dollar '**$**' then clik save.

1. Select the Invoice column then > **Column settings** > **Edit** 

1. Delete the Invoice column.
    1. Select the column header, and from the menu, select **Column settings** > **Edit**.
    1. At the bottom of the Edit Column pane, select **Delete**.
    1. To delete the column and the data in the column permanently, select **Delete**..


<br/>

### Exercise 6: Create a new view


1. Switch view options to **Create a new view**

    ![Document Library Create New View](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryCreateNewView.png)

1. Set with:
    - **Name:** Invoices Status
    - **Show as:** List
    - **Make this a public view:** Enabled

1. When you're finished, select Create.


1. To edit the current view switch view options to **Edit current view**

1. Unckeck **Modified**, **Modified By**, and **Customer**.

1. Click **OK** button.

<br/>

### Exercise 7: Set up alert

Create an alert when the folder is changed in a SharePoint document library. 

1. Go to **Department documents** library. 
1. From the library of options select the **... (ellipses)**, and then select **Alert Me**.

    ![Document Library Alert Me](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryAlertMe.png)


1. In the **Alert me when items change** dialog view the options available and won't change anything.

1. To save, select OK.


**END OF LAB**
