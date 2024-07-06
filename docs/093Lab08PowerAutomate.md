---
layout: default
title: "Exercício: Guarde uma resposta do Microsoft Forms no SharePoint List."
nav_order: 9.3
has_children: true
---

#  Exercício: Guarde uma resposta do Microsoft Forms no SharePoint List.
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

## Lab 08: Save a Microsoft Forms response to SharePoint List.

**Atenção:** Os exercícios não estão escritos em português por norma todo o conteúdo criado pelo formador [Ricardo Cabral](https://www.rramoscabral.com/) é escrito em inglês utilizando a terminologia original.

<br/>

## Microsoft 365 user interface

Given the dynamic nature of Microsoft cloud tools, you might experience UI (User Interface) changes that occur after the development of this training content. As a result, the lab instructions and lab steps might not align correctly.

Cloud updates occur frequently, so you might encounter UI changes before this training content updates. **If this occurs, adapt to the changes, and then work through them in the labs as needed.**


## Lab Scenario 

In the previous lab you created a form in Microsoft Forms. Now you need to create a SharePoint List to store the form responses through an automated Power Automate flow.


## Objectives

- Create a new SharePoint library to store form responses.
- Create an automated Power Automate flow to obtain responses from Microsoft Forms and save in the SharePoint library.


## Instructions

### Before you start

- You have to complete the previous exercise.
- You must have access to a Microsoft 365 account with SharePoint Online, Microsoft Forms and Power Automate.

#### Sign in to the lab environment

Use the credentials provider by the instructor.

<br/>

### Exercise 1: Create SharePoint document library

1. On the SharePoint site that you created in the first exercise, create a new SharePoint list to store the responses to the form created in the previous exercise.

1. The data type of the columns must be identical to the data type of the form questions.


### Exercise 2: Create SharePoint document library


1. In Power Automate, search for **Record form responses in SharePoint** and select the template **Record form responses in SharePoint**.

    ![Image Broken](https://www.rramoscabral.com/training/assets/MSPowerAutomate/MSPowerAutomateTemplateLab1.png)

1. Enable the necessary connectors and click the **Continue** button.

    ![Image Broken](https://www.rramoscabral.com/training/assets/MSPowerAutomate/MSPowerAutomateTemplateLab2.png)

1. The template used does not have enough ability to automatically define which form and SharePoint to use. So the flow was to present that it has invalid paraments.

    ![Image Broken](https://www.rramoscabral.com/training/assets/MSPowerAutomate/MSPowerAutomateTemplateLab3.png)

1. Change the flow trigger parameters with data from the form created in Microsoft Forms.

1. In the **Get response details** action, in the **Form Id** parameter, choose the name of the form. This action will process all the details of a received response.

1. A ação **Create item** vai guardar os dados da resposta processado na ação anteiror **Get response details**. Prencha os parametros 

| Properties | Action to be carried out |
| --- | --- |
| Website address | Choose SharePoint from the first exercise |
| List Name | Choose the SharePoint list created to store the responses |
| Other fields | Fill in according to the questions and answers you defined. |

1. Change the flow name.

1. Save the flow.

1. Submit a new response in the form and check if it is stored in SharePoint.

1. Check the flow's action history in Power Automate.

**END OF LAB**