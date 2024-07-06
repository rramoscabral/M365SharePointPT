---
layout: default
title: "Exercício: Sincronizar biblioteca de documentos do SharePoint"
nav_order: 4.3
has_children: true
---

# Exercício: Sincronizar biblioteca de documentos do SharePoint
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---


## Laboratório 03: Sincronizar biblioteca de documentos do SharePoint

**Atenção:** Os exercícios não estão escritos em português por norma todo o conteúdo criado pelo formador [Ricardo Cabral](https://www.rramoscabral.com/) é escrito em inglês utilizando a terminologia original.

<br/>

Sync a document library in SharePoint to you work directly in File Explorer and access files even when you're offline. And when you go back online, any changes made to those files will sync automatically.

## Microsoft 365 user interface

Given the dynamic nature of Microsoft cloud tools, you might experience UI (User Interface) changes that occur after the development of this training content. As a result, the lab instructions and lab steps might not align correctly.

Cloud updates occur frequently, so you might encounter UI changes before this training content updates. **If this occurs, adapt to the changes, and then work through them in the labs as needed.**


## Lab Scenario 

Sync an existing document library in SharePoint.


## Objectives

Sync an existing document library in SharePoint.

## Instructions

### Before you start

You must have access to a Microsoft 365 account with SharePoint Online.

#### Sign in to the lab environment

Use the credentials provider by the instructor.

<br/>


### Exercise 1: Sync document library

<br/>

**Requirements:** 
 - You have to complete the previous labs.
 - You must have OneDrive installed and updated.

<br/>

> **Note:** If you are using your own computer with an external account that you do not control, do not run this exercise.

<br/>

1. Go to **Department documents** document library.

1. Select Sync. (You only need to do this once on a computer to set up syncing on that computer. After you set up syncing, the files sync automatically.)

    ![SharePoint Document Library Sync](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibrarySync.png)

1. If your browser requests permission to use "Microsoft OneDrive," confirm that this is okay.

    > **Important:** If a screen appears stating "Which library do you want to sync?", your site hasn't been set up to sync with the OneDrive sync app. If you're the IT admin for your organization, see Let users sync SharePoint files with the new OneDrive sync app. If you're not the IT admin, and your screens don't look like the ones in this article, see Sync SharePoint files with the OneDrive sync app (Groove.exe), or contact your IT department.


    The files then sync to a folder on your PC that has the name of your organization (for example, %userprofile%\[organization-name]). This folder is automatically added to the left pane in File Explorer. You can’t select to sync to a different location.

1. To sync the files on another computer, go to that computer, and follow these steps again.

<br/>

### Exercise 2: Stop Sync document library

<br/>

> **Note:** If you are using your own computer with an external account that you do not control, do not run this exercise.

<br/>


1. Select the blue OneDrive cloud icon in the Windows taskbar notification area.

1. Select **Help & Settings** > **Settings**.

1. To see a list of all your syncing sites, select the Account tab.

1. To stop syncing a site, select **Stop sync** next to the site. (Copies of the files remain on your computer. You can delete them if you want.)


<br/>

### Exercise 3: Add shortcut to OneDrive


1. Go to **Department documents** document library.

1. Select Add shortcut to My files.

    ![SharePoint Document Library add shortcut to OneDrive](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryAddShortcuToOneDrive.png)


1. You will receive the following information message.

    ![Add shortcut to OneDrive info message](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryShortcutInfo.png)

1. Go to OneDrive. In the upper left corner of the window, select the app launcher ![App Launcher icon](https://www.rramoscabral.com/training/assets/MSMicrosoft365/IconAppLauncher.png) > **All apps** > **OneDrive**.

1. Check that the shortcut was created in OneDrive.

    ![Add shortcut to OneDrive info message](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryShortcutOneDrive.png)

**END OF LAB**
