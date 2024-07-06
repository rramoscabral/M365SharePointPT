---
layout: default
title: "Exercício: Criar site de equipa do SharePoint"
nav_order: 3.2
has_children: false
---

# Exercício: Criar site de equipa do SharePoint
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

## Laboratório 01: Crie um site de equipa no SharePoint


**Atenção:** Os exercícios não estão escritos em português por norma todo o conteúdo criado pelo formador [Ricardo Cabral](https://www.rramoscabral.com/) é escrito em inglês utilizando a terminologia original.

<br/>

## Microsoft 365 user interface

Given the dynamic nature of Microsoft cloud tools, you might experience UI (User Interface) changes that occur after the development of this training content. As a result, the lab instructions and lab steps might not align correctly.

Cloud updates occur frequently, so you might encounter UI changes before this training content updates. **If this occurs, adapt to the changes, and then work through them in the labs as needed.**


## Lab Scenario 

The organization requires that a new SharePoint team site be created for a new department. This site will be used to share documentation and requires it to be shared with members of that department. 

The organization does not want to create a new Microsoft 365 group for the department in question and use the group to create the SharePoint team site.


## Objectives

Create a new SharePoint team site and share the site.

## Instructions

### Before you start

You must have access to a Microsoft 365 account with SharePoint Online.

#### Sign in to the lab environment

Use the credentials provider by the instructor.

<br/>

### Exercise 1: Create SharePoint Modern site team or communication site

1. Go to office portal [https://portal.office.com](https://portal.office.com), and sign in to your work or school account.

1. In the upper left corner of the window, select the app launcher ![App Launcher icon](https://www.rramoscabral.com/training/assets/MSMicrosoft365/IconAppLauncher.png) > All apps > SharePoint  ![SharePoint logo](https://www.rramoscabral.com/training/assets/MSMicrosoft365/IconSharePoint.png).
    - Tip: If you don't see the SharePoint app under All apps, use the Search box near the top of the window to search for SharePoint.

        ![App Launcher All Apps](https://www.rramoscabral.com/training/assets/MSMicrosoft365/AppLauncherAllApps.png)


1. In the upper left corner of the window select **+ Create site**.

1. There are two site options to choose from:

    | Team site |  Communication site |
    | --- | --- |
    | - Collaborate on projects<br/> - Read team-related news<br/> - Stay on track with a shared calendar and managed tasks | - Share news or information broadly<br/> - Engage with a large audience<br/> - Use modern, visual layouts| 

    Should I create a team site or a communication site?
    - Use a team site when you want to collaborate with other members of your team or with others on a specific project. With a team site, typically all or most members can contribute content to the site and the information is limited to only the members of the team or project and specific stakeholders. 
    - If your intention is to simply broadcast information out to a broad audience, a communication site is the better choice. With a communication site, typically only a small set of members contribute content that is consumed by a much larger audience.


1. Select **Team site**.

    ![Create ShrarePoint Site](https://www.rramoscabral.com/training/assets/MSSharePoint/CreateSite.png)

1. Type in a site name and see if it's available.

    > Note: 
    >    - A corresponding Microsoft 365 group is created with every team site in Microsoft 365 so there's no need to make an email distribution list. Anyone can contact your entire team with this email address.
    >   - If Microsoft 365 Groups are disabled in SharePoint in Microsoft 365, the Email address field won't appear.

1. Type in a description for your site.

1. Select **Public** as privacy setting.
    - Privacy settings:
        - Private, only members can access this site.
        - Public, anyone in the organization can access this site.

1. Select **English** as select language.
    > Note: 
    >  - Once you select a default language for your site and create the site, you can't change the language to something else later. You can, however, add alternate supported languages.
    >  - Your admin can disable this feature.

1. When you're ready, select **Next**.
    > Note: In some Microsoft 365 tenant you can select a sensitivity level. To select data sensitivity, your admin must have this feature enabled.

1. Add additional site owners and group members as needed. Select one or more classmates if available.

1. Select Finish.

1. After creation, select the option **Maybe later**.

    ![Create Site Created](https://www.rramoscabral.com/training/assets/MSSharePoint/CreateSiteCreated.png)

<br/>

### Exercise 2: Share site

1. Select Settings ![Create Site Created](https://www.rramoscabral.com/training/assets/MSSharePoint/IconSettings.png), and then select Site permissions.
    
    ![Site Permissions](https://www.rramoscabral.com/training/assets/MSSharePoint/SiteTeamSitePermissions.png)

1. Select **Share site** 

    ![Share site](https://www.rramoscabral.com/training/assets/MSSharePoint/SiteTeamSitePermissionsShareSite1.png)

1. You can add users, Microsoft 365 Groups, or security groups to give them access to the site.
    
    1. Select one classmate if available.

    1. Select Full control or Edit.

        - Permissions level:
            - Full - Full control of site content, theme, permission settings, site settings, and hub associations.
            - Edit - Can view and edit site content.

    1. Enter an optional message to send with the email notification that will be sent when the site is shared, or clear the Send email checkbox if you don't want to send an email.

        ![Share site](https://www.rramoscabral.com/training/assets/MSSharePoint/SiteTeamSitePermissionsShareSite2.png)

    1. Then click **Add**.


1. You can see the Site owners, site members and site vistors. 

    - Permissions level:
        - Site owners - full control: Full control of site content, theme, permission settings, site settings, and hub associations.
        - Site members - limited control: Can view and edit site content
        - Site visitors - no control: Can view site content


1. You can change how members can share at **Site Sharing**.

<br/>

> **Note:** The site owner can delete the site 
>    1. Select **Setting**.
>    1. Select **Site information**.
>    1. Select **Delete site**.
>    1. Confirm and then select **Delete**.
>
>   **Warning:** If you delete the site all resources including the site, files, conversations, calendar, etc will be deleted.

<br/>

You if are not Microsoft 365 Global Admin or 


### Exercise 2: Create SharePoint Classic site

**WARNING: If you are not a Microsoft 365 global admin or a SharePoint admin do not do this exercise.**

> Note: Microsoft 365 Group won't be created.


1. Go to SharePoint admin center
    - `https://[domain]-admin.sharepoint.com/`

1. On the left pane select **Sites** then **Active sites**.

1. Select **+ Create** to create a new site.

1. Select **Other options**

    ![SharePoint Admin Center Create Site Other Option](https://www.rramoscabral.com/training/assets/MSSharePoint/SharePointAdminCenterCreateSiteOtherOptions.png)


1. Select **More Templates**

    ![MoreTemplates](https://www.rramoscabral.com/training/assets/MSSharePoint/SharePointAdminCenterCreateSiteMoreTemplates.png)


1. Fill the requirements.

1. On Collaboration select **Team site (classic expirence)**


### Exercise 3: Find your site

On the SharePoint Start Page, locate the site you just created.

    1. Go to On the SharePoint Start Page.
    1. On the left pane select **My Sites**
    1. Locate the site you just created.

>> **Note:** If the SharePoint Start Page does not show any information, close it and try again. Sometimes this situation can happen.


If you cannot find you site use the following trick.

    1. Go to SharePoint Start Page.
    1. In the search box type in **contentclass:STS_Site**
    1. A list of sites that you have access to will be shown

        - For all site collection + subsites use 




### Exercise 4: Follow public site

1. On the SharePoint Start Page, follow a public site of your choice.
    
    - Locate the SharePoint in Microsoft 365 site you want to follow. 
    
    - You can locate a site by either searching for it in the search box at the top of the SharePoint in Microsoft 365 start page or by finding it in one of the sections on the SharePoint in Microsoft 365 start page.





**END OF LAB**
