# Jira - Beginner Guideline

## Table of contents
- [Table of contents](#table-of-contents)
- [Introduction](#0-introduction)
- [Create a Project](#1-create-a-project)
- [Settings](#2-settings)
  - [Details](#21-details)
  - [Access](#22-access)
  - [Notifications](#23-notifications)
  - [Automation](#24-automation)
  - [Issue Types](#25-issue-types)
  - [Features](#26-features)
  - [Board](#27-board)
  - [Toolchain](#28-toolchain)
  - [Apps](#29-apps)
- [Backlog](#3-backlog)
- [Ticket](#4-ticket)
- [SCRUM Board](#5-scrum-board)
- [Timetracking Addon](#6-timetracking-addon)
- [Others](#7-others)
  - [Adding People](#71-adding-people)
  - [Quickstart Tool](#72-quickstart-tool)
  - [Roadmap](#73-roadmap)
  - [Overview](#74-overview)
  - [Issues](#75-issues)
  - [Code](#76-code)


## 0. Introduction
In the following you will be introduced to the project planing tool JIRA. To better compare the different tools this guide is structured in a similiar way to the [YouTrack guide](https://github.com/KadrioL/youtrackBeginner/blob/main/README.md) provided by Adrian.


## 1. Create a Project
To create a project click on "Projects" and then on "Create project"
![Jira1](https://user-images.githubusercontent.com/86354671/202115422-79784e38-9e37-497b-a0b3-8bbbb500f32d.jpg)

We will use the SCRUM template for our example project to best explain how to work with sprints and other agile principles.
![Jira2](https://user-images.githubusercontent.com/86354671/202115424-1e915c86-2b3c-469f-adfc-c61eeb1590c9.jpg)
![Jira3](https://user-images.githubusercontent.com/86354671/202115429-51736b0c-6c23-4985-a47b-56f547fa822d.jpg)

The project type will be a team-managed project, because it encapsulates our current needs in the best way. Providing small teams with a fast and efficient and most of all free way to plan and build their products.
![Jira4](https://user-images.githubusercontent.com/86354671/202115432-e47802dc-a518-4cbf-9927-a6fc58dbfaab.jpg)

In the following site you can choose the projects name and key as well as select the possibility to add some repositories or documents(of course that can also be done at a later point).
![Jira5](https://user-images.githubusercontent.com/86354671/202115434-84817b6a-a106-496d-8def-762e84962a8d.jpg)

Here you can connect newly or already created repositories to the JIRA project. This defaults to Bitbucket Cloud because its an atlassian product also. In addition GitHub and GitLab are avaliable options to select as well. If you press connect the project will be finally created.  
![Jira6](https://user-images.githubusercontent.com/86354671/202115420-74f4352d-9904-4458-aa15-d1adaace8ad1.jpg)

For remote repositories other than the BitBucket inhouse solution, free JIRA Add-Ons are available which have to be installed.
![Jira6 1](https://user-images.githubusercontent.com/86354671/202115411-b31aed17-1092-43a3-a9ae-b878ead065f7.jpg)


## 2. Settings
There are a lot of opportunities to personalize your project to adhere to your teams needs. In the following the most commonly used and important settings will be discussed.

### 2.1 Details
In this view you can edit the projects base information and determine your project lead.
![JiraSettingsDetails](https://user-images.githubusercontent.com/86354671/202116047-822810e5-83d0-4368-988d-d6d4584cdda1.jpg)

### 2.2 Access
Even in a small team role management is a important topic. Because of this there is a role management tool where roles can be created, edited and assigned to team members and yourself. This functionality cannot be used with the free plan though!
![JiraSettingsAccess](https://user-images.githubusercontent.com/86354671/202116069-f8446083-7d76-4316-9487-93012a5692a4.jpg)

### 2.3 Notifications
Here you can edit which notifications should be send automatically to a personally defined E-Mail address and which should not.
![JiraSettingsNotifications](https://user-images.githubusercontent.com/86354671/202388342-2aaca75e-b27a-4afd-9521-8862172a144a.jpg)


### 2.4 Automation
The automation rules are seperated into two areas of magnitude as well as one containing all the active rules.
![JiraSettingsAutomation1](https://user-images.githubusercontent.com/86354671/202116690-4bd61f4f-cd14-4aa1-8ede-199100ed23d6.jpg)

In the audit log tab the status of actived automations can be checked. The different ones are defined here as well.
![JiraSettingsAutomation2](https://user-images.githubusercontent.com/86354671/202116693-5735e28e-d0fe-4509-9c8a-88d4702d4ea2.jpg)

In the libary all out of the box as well as the custom rules are listed, which easily can be created by using the "Create rule" button. In a new project there are a few recomendations as well which can be added quickly. 
![JiraSettingsAutomation3](https://user-images.githubusercontent.com/86354671/202116695-7bf12d63-bc59-4c56-af0c-2280c29c2e59.jpg)

Each created rule needs one or more triggers. A trigger is condition which has to be fullfilled before a automation is started. 
![JiraSettingsAutomation4](https://user-images.githubusercontent.com/86354671/202116697-a6ef4edb-03ee-4106-baf2-81b8a88ae89a.jpg)

Now components can be added to define what a triggered rule changes in the system or further restrict its activation.
![JiraSettingsAutomation5](https://user-images.githubusercontent.com/86354671/202116687-ae02bfc7-d5a0-4de1-9d5e-da1abab0e707.jpg)

### 2.5 Issue Types
In the settings for issue types, issue types can be created and edited. 

To create a issue type a name and an icon is needed. A discription is optional.
![JiraSettingsIssueTypes3](https://user-images.githubusercontent.com/86354671/202117031-932d9d8a-0db7-4cb2-a466-4ba1b3f70d49.jpg)

In the following we will use the subtask issue type to show the different possibilites to configure an issue type.
![JiraSettingsIssueTypes1](https://user-images.githubusercontent.com/86354671/202117038-5512ef33-5f9c-468a-9e7a-62f466aa97da.jpg)

You can add all sorts of context fields to your ticket templates as well as remove unneeded ones. In this example "time tracking" is added to the subtask type to show the functunality of an Add-On which will be discussed at a later point. You can also edit the workflow of any issue type.
![JiraSettingsIssueTypes2](https://user-images.githubusercontent.com/86354671/202117026-9d7570b2-8ebe-4548-ad95-bb33e71d8261.jpg)

In the workflow view issue statuses and the transitions between them can be edited. This represents the flow the configured ticket can take on the board and which columns it can move into. To save all changes press the update-workflow-button. 
![JiraSettingsIssueTypes4](https://user-images.githubusercontent.com/86354671/202117035-c66be767-3e84-4d9a-a1d7-6b4d6fa8d7bc.jpg)

### 2.6 Features
In features you can determine which sections should be shown in your projects sidebar. Just activate the features that you need and want to use and deactivate the ones you do not. In this example we activate reports and the issue navigator which will get explained later.   
![JiraSettingsFeatures](https://user-images.githubusercontent.com/86354671/202117140-12ee0480-183e-43a7-baf7-9ad7cff5f753.jpg)

### 2.7 Board
In the bord settings you can edit nearly every aspect of your SCRUM board. Because of the vast configuration possibilities, this topic will only be touched on briefly. 

In the following image you can see how columns and statuses can be assigned to each other.
![JiraSettingsBoard1](https://user-images.githubusercontent.com/86354671/202117238-787bf484-fe45-4a40-b272-63ce7f572b3d.jpg)

### 2.8 Toolchain
Because of the missing relevance for our current software projects the toolchain section won't be discussed.

### 2.9 Apps
Apps can be a great way to add missing functionalities to your JIRA projects. 
![JiraSettingsApps1](https://user-images.githubusercontent.com/86354671/202117325-e4664bc3-ece4-470f-a858-722d76733532.jpg)

In this example we will add a timesheet addon to analyse the projects booked time. 
![JiraSettingsApps2](https://user-images.githubusercontent.com/86354671/202117327-ac845414-467d-473a-b4c2-1778a7ed594a.jpg)

Before you add any addon to your project you should check how it is priced for your teams size. This timetracking addon is free for our size and can be added without any worries.
![JiraSettingsApps3](https://user-images.githubusercontent.com/86354671/202117329-97c7001c-0f20-4f99-b8b0-873de4e78140.jpg)

When an Add-On is selected a JIRA atlassian instance can be specified to which it should be installed. Be mindfull though, the instance is not equal to a project! Your account generates one instance of JIRA in the cloud when you create a new JIRA connection. This instance can hold many projects, all of which have access to the Add-Ons installed.
![JiraSettingsApps4](https://user-images.githubusercontent.com/86354671/202117310-e4ace116-5631-4b94-ae2a-ad5a5213f151.jpg)

Once you click on "get" and specify the JIRA instance, you once more get an overview of the software you're about to install which has to be accepted one last time.
![JiraSettingsApps5](https://user-images.githubusercontent.com/86354671/202117319-9a906569-3694-4923-89f8-ef657e817cca.jpg)


## 3. Backlog
The product backlog is in accordance to the agile principles the place all new features and tickets are saved and generated to. The backlog view does not only contain the product backlog but also the current or next sprint backlog. This gives a overall overview of the product and the sprint as well as the possibility to interact between the two.
![JiraBacklog1](https://user-images.githubusercontent.com/86354671/202122119-e52bb493-f02c-44bd-abd0-b53d54e5561e.jpg)

You can create tickets directly in the backlog or the current sprint in a quick access way, if you do not want to use the already discussed "Create"-Button. If no sprint is present yet, one can be created.
![JiraBacklog2](https://user-images.githubusercontent.com/86354671/202122121-d5b3fedb-6509-46d7-a584-d1559e780514.jpg)

If you want to add a ticket from the product backlog to the current sprint backlog you can just drag and drop it into the sprint column.
![JiraBacklog3](https://user-images.githubusercontent.com/86354671/202122123-1fe43751-60e3-4325-830d-46209429e1ae.jpg)
![JiraBacklog4](https://user-images.githubusercontent.com/86354671/202122126-7858d76f-28fa-4c5d-bb28-e6de76963bc8.jpg)

To individualize you can add a personalized name if the automatically generated one does not satisfy your needs, as well as a duration. Optionally you can define Sprint Goals in a text field, which determine for your team when the sprint is successfull and when it is not.
![JiraBacklog5](https://user-images.githubusercontent.com/86354671/202122099-498311d1-c75c-475d-a8e7-9f81e18fcce1.jpg)

The start and end dates as well as the goals will then be shown after the sprint name. You can reconfigure this information until the sprint is started.
![JiraBacklog6](https://user-images.githubusercontent.com/86354671/202122109-ba2e67cc-0dc3-4773-b188-95b44880516d.jpg)

When the start button is pressed the information is once again displayed and reconfigurable because after starting they are not changable.
![JiraBacklog7](https://user-images.githubusercontent.com/86354671/202122115-c2534a64-fbc1-46e0-81fc-58d031077b14.jpg)


## 4. Ticket
The ability to create tickets is an important feature to JIRA in gernal, as not only the SCRUM type projects need this functionality. This tickets can represent multiple different types of tasks.

To create a ticket/issue you can use the "Create"-button in the upper task bar or the quick access ways in the backlog view. The tickets summary is always needed (/it represents the name of the ticket) and if no more mandatory fields are specified the ticket could already be created.
![JiraCreateEpic1](https://user-images.githubusercontent.com/86354671/202123925-1b82cd75-33e8-462a-ac08-0dec047e3043.jpg)

There are two ticket views. The "minimal" one you get when selecting the ticket on the board or in the backlog, and the "complete" one which will get opened in a new tab, once you click on the ticket ID (here "DOC-1").
![JiraTicket1](https://user-images.githubusercontent.com/86354671/202122522-06d7c475-de20-4a5c-9340-d3b288e53dd9.jpg)

The second possiblity to edit a ticket is in the complete view.

Below the tickets summary are the three main quick access options 
1. You can attach images that are relevant to the ticket.
2. You can add child issues to represent subtasks which need to be finished to complete the parent issue.
3. You can link other issues, which are in some way connected to your ticket. The different relationships are:
    - Blocks a ticket or is blocked by it
    - Clones a ticket or is cloned by it
    - Duplicates a ticket or is duplicated by it
    - Relates to a ticket (in general)

The tickets parameters can be edited too. In this example we can assign a ticket to a team member, add labels or give a story point estimation (expense estimation). Other parameters  can be activated in the settings (like time tracking).
![JiraTicket2](https://user-images.githubusercontent.com/86354671/202122526-771b8ac9-ef6a-4211-86cc-883953fc980e.jpg)


## 5. SCRUM Board
The board is one of the the most important views in our software engineering based project. Here you can manage all of your current sprint's tickets and see their progress.

The board is only populated if a sprint has been created and started beforehand.
![JiraBoard1](https://user-images.githubusercontent.com/86354671/202123009-af1604f0-120f-4898-9c07-24cbf6cfd1b0.jpg)

If a sprint is started all of your added tickets can be seen in the "To Do"-Column by default. 
![JiraBoard2](https://user-images.githubusercontent.com/86354671/202123011-901b66ac-cb90-46f6-a3c0-5f40aa64c75b.jpg)

To adapt the view to your individual needs you can group it by assignee, epic, or subtask. In this example we will use the subtask view.
![JiraBoard3](https://user-images.githubusercontent.com/86354671/202123014-00feffae-806c-4ccd-8823-f9837c5b2cce.jpg)

All the tickets can be moved between the stages in accordance to the defined workflow for that ticket type. Once the sprint is done in your definition of done it can be completed, even if not all tickets are in the done stage yet.
![JiraBoard4](https://user-images.githubusercontent.com/86354671/202123074-ef13b050-be8a-401f-a9c6-5c44d3f86187.jpg)

Before you can complete the sprint though, you need to decide whether the still open tickets are moved to the next sprint or the product backlog.
![JiraBoard5](https://user-images.githubusercontent.com/86354671/202123004-d3219f8a-d717-4983-a86d-98a902ddb320.jpg)


## 6. Timetracking Addon
To use the installed time tracking Add-On we need to add the "time tracking" field to the tickets we want to use it on. In this field you can book your times once it is done. 
![JiraTimesheet0](https://user-images.githubusercontent.com/86354671/202123557-ad77c15a-8029-41ba-b69a-7d1f8813feca.jpg)

There is a timesheet overview. It analyzes the data and calculates some ready-made statistics.
![JiraTimesheet2](https://user-images.githubusercontent.com/86354671/202123560-ccd4ef7b-0df5-4bec-add5-49add09cd664.jpg)

But the main reason why the addon was installed was not the overview function. To use the main feature you have to go up to "Apps" and select timesheet
![JiraTimesheet1](https://user-images.githubusercontent.com/86354671/202123559-136ba2df-f391-4110-866a-a6d96ac7daca.jpg)

Now you can calculate specific times and generate matching diagrams. There are a few filters to individualize the results.
![JiraTimesheet3](https://user-images.githubusercontent.com/86354671/202123539-477fd997-44df-46da-b60f-d4eea266e76b.jpg)

If the basic filters are not enough you can use the JQL language to even further specify what times you want to use for the calculation. In addition to that this querries can be saved and loaded again later.
![JiraTimesheet4](https://user-images.githubusercontent.com/86354671/202123544-93941001-0bda-44d2-a5d8-774c03107159.jpg)

To select a matching diagram you have to press the three dashes and got to settings.
![JiraTimesheet5](https://user-images.githubusercontent.com/86354671/202123548-faa6ab89-afb1-492d-b2a8-064f3d9475b3.jpg)
![JiraTimesheet6](https://user-images.githubusercontent.com/86354671/202123552-27ace893-fca6-40f6-b0d7-9a3733ee3140.jpg)


## 7. Others
### 7.1 Adding People 
Add people by clicking on the "Add" button situated in the backlog or scrum board. The E-Mail address of the wanted member as well as their appropriate role has to be specified. This person will receive an invitation via mail later.
![JiraAddPeople1](https://user-images.githubusercontent.com/86354671/202123801-ebbf72a6-d004-4db3-af11-dba12d52c115.jpg)

### 7.2 Quickstart Tool
The quickstart tool is a useful assistant for new JIRA users to understand the creation process of a new project. Just follow the instructions if you need its help. 
![JiraQuickstart1](https://user-images.githubusercontent.com/86354671/202123913-f0f1f4c8-7d2b-4d1a-b7f9-f3d76915550a.jpg)

### 7.3 Roadmap
The roadmap provides an overview over the duration of sprints and epics. It is used to plan the them and define which epics have to be done by when. 
![JiraRoadmap1](https://user-images.githubusercontent.com/86354671/202123920-28d6ef05-c682-4780-b379-542b55104606.jpg)

### 7.4 Overview
With the overview tab you can choose between multiple different report types. 
![JiraReports1](https://user-images.githubusercontent.com/86354671/202123915-6905c2f8-1af1-4b11-acbb-32c69ecebc36.jpg)

### 7.5 Issues
The issues tab is especially useful if you want to search for a specific ticket or tickets that are already done and not inside any of the backlogs anymore.
![JiraIssues](https://user-images.githubusercontent.com/86354671/202123927-7a0015b2-580c-429e-a5f4-4cfb7d78069f.jpg)

### 7.6 Code
Inside the code tab you can see your linked repositories. It is very helpful when you want to have a fast comparision between the JIRA project and the git commits.
![JiraCode1](https://user-images.githubusercontent.com/86354671/202123922-2be85a72-8c79-4c53-9f36-bd1485f36d5d.jpg)
