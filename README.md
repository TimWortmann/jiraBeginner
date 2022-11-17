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


## 0. Introduction
In the following i will introduce the project planing tool jira. The structure is very similar to the youtrack beginners guide so you compare both tools better.  


## 1. Create a Project
To create a project click on "Projects" and then on "Creat project"
![Jira1](https://user-images.githubusercontent.com/86354671/202115422-79784e38-9e37-497b-a0b3-8bbbb500f32d.jpg)

We will use the scrum template for our example project to explain how sprints are working in jira.
![Jira2](https://user-images.githubusercontent.com/86354671/202115424-1e915c86-2b3c-469f-adfc-c61eeb1590c9.jpg)
![Jira3](https://user-images.githubusercontent.com/86354671/202115429-51736b0c-6c23-4985-a47b-56f547fa822d.jpg)

The project type will be a team-managed project, because it represents the work in small teams.
![Jira4](https://user-images.githubusercontent.com/86354671/202115432-e47802dc-a518-4cbf-9927-a6fc58dbfaab.jpg)

On the following site you can choose the name and the key of the created project. In addition to that you can check if some repositories should be connected with this project.
![Jira5](https://user-images.githubusercontent.com/86354671/202115434-84817b6a-a106-496d-8def-762e84962a8d.jpg)

Here you can connect new or already created repositories to the jira project. The standard for that is bitbucket, because its a atlassian product, too. In addition to that you can also connect repositories of github or gitlab. If you press connect the project will be finally created.  
![Jira6](https://user-images.githubusercontent.com/86354671/202115420-74f4352d-9904-4458-aa15-d1adaace8ad1.jpg)

For extern repositories a free jira addon is needed. 
![Jira6 1](https://user-images.githubusercontent.com/86354671/202115411-b31aed17-1092-43a3-a9ae-b878ead065f7.jpg)


## 2. Settings
There are a lot of opportunities to individualize your project with the settings according to the needs of your team. In the following there is a explanation of the most used and important settings for your project. 

### 2.1 Details
In this view you can edit the base informations of your project and determine your project lead.
![JiraSettingsDetails](https://user-images.githubusercontent.com/86354671/202116047-822810e5-83d0-4368-988d-d6d4584cdda1.jpg)

### 2.2 Access
If there are people on your team rolemanagement is very important. BEcause of this there is a rolemanagement tool where roles can be created, edited and assigned to team members. 
![JiraSettingsAccess](https://user-images.githubusercontent.com/86354671/202116069-f8446083-7d76-4316-9487-93012a5692a4.jpg)

### 2.3 Notifications
Here you can edit which notifications should be send to which e-mail adress.
![JiraSettingsNotifications](https://user-images.githubusercontent.com/86354671/202388342-2aaca75e-b27a-4afd-9521-8862172a144a.jpg)


### 2.4 Automation
The automation is seperated in three segments to control each automation process precisely.

The rules determine the scope of the automations.
![JiraSettingsAutomation1](https://user-images.githubusercontent.com/86354671/202116690-4bd61f4f-cd14-4aa1-8ede-199100ed23d6.jpg)

In the audit log tab the status of actived automations can be checked. There are a view statuses the verify the state of the processes.
![JiraSettingsAutomation2](https://user-images.githubusercontent.com/86354671/202116693-5735e28e-d0fe-4509-9c8a-88d4702d4ea2.jpg)

In the libary are all activated automations listed. Additional to that there are a view suggestions for useful processes, but of course individual automations can be created with the create-rule-button, too.   
![JiraSettingsAutomation3](https://user-images.githubusercontent.com/86354671/202116695-7bf12d63-bc59-4c56-af0c-2280c29c2e59.jpg)

Each created rule needs one or more trigger. A trigger is condition which have to be fullfilled to start the automation process. 
![JiraSettingsAutomation4](https://user-images.githubusercontent.com/86354671/202116697-a6ef4edb-03ee-4106-baf2-81b8a88ae89a.jpg)

Now other components can be added to the rule. More conditions can be added to determine if a action should be called or not. 
![JiraSettingsAutomation5](https://user-images.githubusercontent.com/86354671/202116687-ae02bfc7-d5a0-4de1-9d5e-da1abab0e707.jpg)

### 2.5 Issue Types
In the settings to issue types issues can be created and its properties can be edited. 

To create a issue type there is a name and a icon needed. A discription is optional.
![JiraSettingsIssueTypes3](https://user-images.githubusercontent.com/86354671/202117031-932d9d8a-0db7-4cb2-a466-4ba1b3f70d49.jpg)

In the following we will use the subtask issue type to show the different possibilites to edit a issue type.
![JiraSettingsIssueTypes1](https://user-images.githubusercontent.com/86354671/202117038-5512ef33-5f9c-468a-9e7a-62f466aa97da.jpg)

You add and remove all sorts of context fields to your ticket templates. In this example time tracking is added to the subtask type to show the functunality of a later discusses addon. You can also edit the workflow of a issue type.
![JiraSettingsIssueTypes2](https://user-images.githubusercontent.com/86354671/202117026-9d7570b2-8ebe-4548-ad95-bb33e71d8261.jpg)

In the workflow view issue statuses and the transitions between can be addited. To save all changes press the update-workflow-button. 
![JiraSettingsIssueTypes4](https://user-images.githubusercontent.com/86354671/202117035-c66be767-3e84-4d9a-a1d7-6b4d6fa8d7bc.jpg)

### 2.6 Features
![JiraSettingsFeatures](https://user-images.githubusercontent.com/86354671/202117140-12ee0480-183e-43a7-baf7-9ad7cff5f753.jpg)

### 2.7 Board
![JiraSettingsBoard1](https://user-images.githubusercontent.com/86354671/202117238-787bf484-fe45-4a40-b272-63ce7f572b3d.jpg)

### 2.8 Toolchain

### 2.9 Apps
![JiraSettingsApps1](https://user-images.githubusercontent.com/86354671/202117325-e4664bc3-ece4-470f-a858-722d76733532.jpg)
![JiraSettingsApps2](https://user-images.githubusercontent.com/86354671/202117327-ac845414-467d-473a-b4c2-1778a7ed594a.jpg)
![JiraSettingsApps3](https://user-images.githubusercontent.com/86354671/202117329-97c7001c-0f20-4f99-b8b0-873de4e78140.jpg)
![JiraSettingsApps4](https://user-images.githubusercontent.com/86354671/202117310-e4ace116-5631-4b94-ae2a-ad5a5213f151.jpg)
![JiraSettingsApps5](https://user-images.githubusercontent.com/86354671/202117319-9a906569-3694-4923-89f8-ef657e817cca.jpg)


## 3. Backlog
![JiraBacklog1](https://user-images.githubusercontent.com/86354671/202122119-e52bb493-f02c-44bd-abd0-b53d54e5561e.jpg)
![JiraBacklog2](https://user-images.githubusercontent.com/86354671/202122121-d5b3fedb-6509-46d7-a584-d1559e780514.jpg)
![JiraBacklog3](https://user-images.githubusercontent.com/86354671/202122123-1fe43751-60e3-4325-830d-46209429e1ae.jpg)
![JiraBacklog4](https://user-images.githubusercontent.com/86354671/202122126-7858d76f-28fa-4c5d-bb28-e6de76963bc8.jpg)
![JiraBacklog5](https://user-images.githubusercontent.com/86354671/202122099-498311d1-c75c-475d-a8e7-9f81e18fcce1.jpg)
![JiraBacklog6](https://user-images.githubusercontent.com/86354671/202122109-ba2e67cc-0dc3-4773-b188-95b44880516d.jpg)
![JiraBacklog7](https://user-images.githubusercontent.com/86354671/202122115-c2534a64-fbc1-46e0-81fc-58d031077b14.jpg)


## 4. Ticket
![JiraCreateEpic1](https://user-images.githubusercontent.com/86354671/202123925-1b82cd75-33e8-462a-ac08-0dec047e3043.jpg)
![JiraTicket1](https://user-images.githubusercontent.com/86354671/202122522-06d7c475-de20-4a5c-9340-d3b288e53dd9.jpg)
![JiraTicket2](https://user-images.githubusercontent.com/86354671/202122526-771b8ac9-ef6a-4211-86cc-883953fc980e.jpg)


## 5. SCRUM Board
![JiraBoard1](https://user-images.githubusercontent.com/86354671/202123009-af1604f0-120f-4898-9c07-24cbf6cfd1b0.jpg)
![JiraBoard2](https://user-images.githubusercontent.com/86354671/202123011-901b66ac-cb90-46f6-a3c0-5f40aa64c75b.jpg)
![JiraBoard3](https://user-images.githubusercontent.com/86354671/202123014-00feffae-806c-4ccd-8823-f9837c5b2cce.jpg)
![JiraBoard4](https://user-images.githubusercontent.com/86354671/202123074-ef13b050-be8a-401f-a9c6-5c44d3f86187.jpg)
![JiraBoard5](https://user-images.githubusercontent.com/86354671/202123004-d3219f8a-d717-4983-a86d-98a902ddb320.jpg)


## 6. Timetracking Addon
![JiraTimesheet0](https://user-images.githubusercontent.com/86354671/202123557-ad77c15a-8029-41ba-b69a-7d1f8813feca.jpg)
![JiraTimesheet2](https://user-images.githubusercontent.com/86354671/202123560-ccd4ef7b-0df5-4bec-add5-49add09cd664.jpg)
![JiraTimesheet1](https://user-images.githubusercontent.com/86354671/202123559-136ba2df-f391-4110-866a-a6d96ac7daca.jpg)
![JiraTimesheet3](https://user-images.githubusercontent.com/86354671/202123539-477fd997-44df-46da-b60f-d4eea266e76b.jpg)
![JiraTimesheet4](https://user-images.githubusercontent.com/86354671/202123544-93941001-0bda-44d2-a5d8-774c03107159.jpg)
![JiraTimesheet5](https://user-images.githubusercontent.com/86354671/202123548-faa6ab89-afb1-492d-b2a8-064f3d9475b3.jpg)
![JiraTimesheet6](https://user-images.githubusercontent.com/86354671/202123552-27ace893-fca6-40f6-b0d7-9a3733ee3140.jpg)


## 7. Others
![JiraAddPeople1](https://user-images.githubusercontent.com/86354671/202123801-ebbf72a6-d004-4db3-af11-dba12d52c115.jpg)
![JiraQuickstart1](https://user-images.githubusercontent.com/86354671/202123913-f0f1f4c8-7d2b-4d1a-b7f9-f3d76915550a.jpg)
![JiraRoadmap1](https://user-images.githubusercontent.com/86354671/202123920-28d6ef05-c682-4780-b379-542b55104606.jpg)
![JiraReports1](https://user-images.githubusercontent.com/86354671/202123915-6905c2f8-1af1-4b11-acbb-32c69ecebc36.jpg)
![JiraIssues](https://user-images.githubusercontent.com/86354671/202123927-7a0015b2-580c-429e-a5f4-4cfb7d78069f.jpg)
![JiraCode1](https://user-images.githubusercontent.com/86354671/202123922-2be85a72-8c79-4c53-9f36-bd1485f36d5d.jpg)
