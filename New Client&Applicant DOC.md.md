<![endif]-->

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image001.jpg)<![endif]>

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image002.jpg)<![endif]>

**Functional**

**Specifications**

**Client platform**

Written by: Léo SOK

Date: 02/08/2021

  

Table of contents

[1. Introduction.. 3](#_Toc81822273)

[2. Context for the recruitment products. 4](#_Toc81822274)

[2.1. Vocabularies. 7](#_Toc81822275)

[3. The functional guide of the client platform.. 8](#_Toc81822276)

[3.1. Expected features. 8](#_Toc81822277)

[3.2. The client website screen routes. 9](#_Toc81822278)

[3.3. The login pages  10](#_Toc81822279)

[3.3.1. Fill the fields and click on Login (Link 1)  10](#_Toc81822280)

[3.3.2. “Password forgotten” button (Link 8)  10](#_Toc81822281)

[3.4. Password recovering. 11](#_Toc81822282)

[3.4.1. Request for a password-reset (Link 9)  11](#_Toc81822283)

[3.5. Create a new password. 12](#_Toc81822284)

[3.5.1. The “Create” button (Link 8)  12](#_Toc81822285)

[3.6. The client Dashboard. 13](#_Toc81822286)

[3.6.1. Logout from the dashboard. 14](#_Toc81822287)

[3.6.2. Find an applicant study. 14](#_Toc81822288)

[3.6.3. Navigating from the status to the audit trail  14](#_Toc81822289)

[3.6.4. View on the applicant’s details. 15](#_Toc81822290)

[3.6.5. Download the background check report  15](#_Toc81822291)

[3.6.6. The full table lists. 15](#_Toc81822292)

[3.7. The applicant’s background checks list (Link 5)  16](#_Toc81822293)

[3.7.1. Waiting for the applicant  17](#_Toc81822294)

[3.7.2. On-going background checks board. 18](#_Toc81822295)

[3.7.3. Background check refusals. 19](#_Toc81822296)

[3.7.1. Completed background checks. 20](#_Toc81822297)

[3.8. The applicant’s details (Link 3). 21](#_Toc81822298)

[3.8.1. Download documents (Link 5)  22](#_Toc81822299)

[3.9. The audit trail (Link 4). 23](#_Toc81822300)

[3.9.1. Dashboard (Link 1)  23](#_Toc81822301)

[3.9.2. Applicant’s details (Link 3)  23](#_Toc81822302)

[3.10. The client statistics (Link 6)  24](#_Toc81822303)

[3.11. Members allowed to connect to the account (Link 12)  25](#_Toc81822304)

[3.11.1 Add a new member to the team (Link 13)  26](#_Toc81822305)

[3.11.2 Edit the member’s information (Active account). 27](#_Toc81822306)

[3.11.3 Edit the member’s information (Unactive account)  28](#_Toc81822307)

[3.12. Check a new applicant (Link 7)  29](#_Toc81822308)

[4. The footer pages (Link 11)  30](#_Toc81822309)

  

# 1. Introduction

EveryCheck was created in 2015 and inspired by Anglo-Saxon countries. It aims to bring background checks for recruitment and real estate in France.

This document will describe the functionals specifications for the recruitment web application.

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image003.png)<![endif]>

Figure 1: Home page

[https://www.everycheck.com/](https://www.everycheck.com/)

  

# 2. Context for the recruitment products

In the UK or US, most of the compagnies check the applicant's resume before hiring them. In France, recruiters tend more to trust the applicant and rarely do a background check. But based on statistics from 2016 to 2019, among 10 000 resumes checked, 60% of them had falsified information.

Most of the HR reveal they do not have enough time to do a real background check.

Applicants who faked their resume do it to hide gaps between experiences or “improve” some part to make it more attractive for recruiters. They can:

-   Add a diploma
-   Change their position in a job
-   extend start or end dates of a job experience
-   …

When discovered some of them reveal the truth, others can deny the fact and leave, and sometimes they may add layers of lies to prove EveryCheck is mistaken.

EveryCheck mission is to help recruiters with their future hiring. Providing more information about the applicant will allow the recruiter to base its decision on fact only. This will avoid negative consequences of hiring someone they did not expect.

To help them acquire more information, EveryCheck gives them access to a web application focused on applicant background check.

EveryCheck can check:

-   Ids (driver license, passport, ID card)
-   Diploma (obtained or not, when, which degree, where ….)
-   Employment (where, which position, with which contract, from when to when, ...)
-   Or any other information that can be put on a resume.

EveryCheck is not meant to judge people. Its mission is only to gather information. EveryCheck will never be able to help a recruiter to know if an applicant can fit in a job description or not.

  

Each applicant check is called a study and follow this process:

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image004.png)<![endif]>

Figure 2: Study process

1.  The recruiter sends the resume to start the check.

2.  The second step is really important due to GDPR. Then the applicant provides us some information about his career which does not appear on his resume. (Often the dates on resumes are vague 2012-2013 but is it January 2012 to December 2013 or December 2012 to January 2013? Sometimes the name of the company is not sufficient to know where the applicant has worked, …). This step is divided into five main parts:

- The signature accompanied by the applicant’s refusal or acceptance

- The form filling related to identity

- The form filling related to the school career

- The form filling related to the work experiences

- The validation step is the final one accompanied by a summary

In general, 20% of applicants do not accept to be checked. It shows to the recruiter that the applicant was not really motivated.

3.  EveryCheck team members proceed to check all the data given by the applicant. Those checks can take from 1 to 3 open days. After two days if the background check is not finished yet, a temporary report is sent to the recruiter. The duration of the background check may vary depending on the kind of company checked: big, small, still in activities, closed for vacation or end of activities, ...

4. Once EveryCheck members finish checking all the data, a final report will be sent. It shows the results with status icons, when and who did EveryCheck contact to bring information. This report helps recruiters to choose their final employees.
  
This is an example of the final report:

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image005.jpg)<![endif]>

Figure 3: An example of the final report

## 2.1. Vocabularies

First of all, some words are important to understand properly the contents of this document:

- **Resume:** A written  description  of the education,  qualifications,  previous  jobs, and also  about the  personal  interests.

-   **Applicant:** It is the resume owner which must be checked.

- **Client:** It is a recruiter/employer who will submit to EveryCheck the applicant’s resume.

-   **Study:** A study deals with the applicant’s resume, our staff will work on the resume’s information which is composed by the diploma, professional experiences and even about the identity.

-   **Background check:** it is a check of what a person has done in the past, usually as part of the process of deciding whether or not to hire applicants.

-   **Status:** The status will indicate you the result of each information from the background check if we finished to check or not yet an element (pending, in progress, completed, cancelled)

-   **Documents:** A document can be seen or downloaded from the study, like the resume or pieces from the ID (card, passport, driver license or the diploma).

-   **Audit trail:** It will show you the process of our check and how we brought and certified information, the audit trail will justify the status of an element after our check.

-   **Final report:** It is the final product that you will get after we finished our check. It will summary every information that the client will need to know about the candidate, if the information from the study is true or not.

  

# 3. The functional guide of the client platform

We will explain the client platform into 3 main parts:

- Define the features expected by the client

- The screen mapping details

- The presentation of the platform

## 3.1. Expected features

1.  As a client I would like to log into my account/dashboard
2.  As a client I would like to logout from my account
3.  As a client I would like to reset/recover my password
4.  As a client I would like to change the language from French to English or the reverse
5.  As a client I would like to upload a resume and check a new applicant
6.  As a client I would like to see an applicant from the pending authorizations board
7.  As a client I would like to see an applicant from the board with CVs being checked
8.  As a client I would like to see an applicant from the board with checked CVs
9.  As a client I would like to search by the applicant’s last name a study
10.  As a client I would like to get the applicant’s details
11.  As a client I would like to navigate to a study via the paging
12.  As a client I would like to download different documents from the candidate’s background check
13.  As a client I would like to know the status of each studies
14.  As a client I want to see the audit trail process
15. As a client I would like the get the partial or the final report
16. As a client I would like to see and download the statistics over the last 90 days/last year
17. As a team leader I would like to add, remove or edit a member

## 3.2. The client website screen routes

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image006.jpg)<![endif]>

Figure 4: The screen mapping

This is the representation of the website mapping; it shows us every results and interfaces that you can get after an action on the website.

## 3.3. The login  pages

The customer will get an account on the “client website “where he can login in order to get the access to its “**Dashboard** “.

Below, this is the interface where the customer will have to login:

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image007.png)<![endif]>

Figure 5: The login page

[https://monespace-lite.everycheck/login](https://monespace-lite.everycheck/login)

### 3.3.1. Fill the fields and click on Login (Link 1)

In order to get an access to the personal dashboard we will ask to fill the fields with a username and a password.

### 3.3.2. “Password forgotten” button (Link 8)

If the client doesn’t remember about the password, a new one can be set up, he just needs to click on the button to do the process and follow our instructions.

  

## 3.4. Password recovering

If the user doesn’t remember about the password, he can always get it back, click on “Password forgotten” from the Login page and he will be automatically redirected to the Password recovering page as below:

<![if !vml]>![Une image contenant texte

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image008.png)<![endif]>

Figure 6: Password recovering

[https://monespace-lite.everycheck/reset-password](https://monespace-lite.everycheck/reset-password)

The user needs to fill the field with its username and to click on Recover.

### 3.4.1. Request for a password-reset (Link 9)

Once the client clicked on “Recover”, an email has been sent with a secret code and he will be redirected to a new page where he can use that code and choose its new password.

  

## 3.5. Create a new password

<![if !vml]>![Une image contenant texte

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image009.png)<![endif]>

Figure 7: Set a new password

[https://monespace-lite.everycheck/set-password](https://monespace-lite.everycheck/set-password)

The code will be sent only if the username is correct, otherwise the user will not be able to change its password.

Once the code received by email and the new password chosen, the user will be redirected to the login page (Figure 5).

### 3.5.1. The “Create” button (Link 8)

Click on “Create” to define a new password and the previous password will automatically be replaced.

After this step, the user can go back to the login page, and try again with the new password.

The Dashboard page will appear after the connection.

  

## 3.6. The client Dashboard

This is the main interface after the log in, first of all if our client wants to use our services, the client must have available credits.

Indeed, each resume require one credit, and those credits are only available for 18 months, otherwise they will be expired.

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image010.png)<![endif]>

Figure 8: Client dashboard

[https://monespace-lite.everycheck.com/](https://monespace-lite.everycheck.com/)

  

There are three different boards which can show the study status:

<![if !supportLists]>· <![endif]>The board “**Pending**” is about applicants who didn’t start to complete the authorization form, they are temporarily in this board until they refused or finished to complete the form.

<![if !supportLists]>· <![endif]>The board “**In progress**” is about study verifications which are being processed.

<![if !supportLists]>· <![endif]>The board “**Completed**” is about every study which are successfully done

For the “**pending**” and “**in progress**” table list, it can show until 5 result lines and for the “**completed**” table list until 10 result lines.

### 3.6.1. Logout from the dashboard

The client can go back to the login page (Figure 5) once he finished to check information that he needed; he must click on the button Logout.

### 3.6.2. Find an applicant study

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image011.png)<![endif]>

Figure 9: The research bar

The client can find an applicant’s study from the research bar by writing the applicant’s last name.

### 3.6.3. Navigating from the status to the audit trail

<![if !vml]>![Une image contenant texte

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image013.png)<![endif]>

Figure 10: Status title

Hover over on one status, will let appear the title of the verification. The client can check a specific audit trail by clicking on the status figure, then he will be redirected to the concerned audit trail.

### 3.6.4. View on the applicant’s details

The “**eye**” button <![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image015.png)<![endif]>  allows the client to get more details about the applicant and its background check.

### 3.6.5. Download the background check report

This button <![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image017.png)<![endif]>  allows the client to download the report of completed background check

### 3.6.6. The full table lists

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image018.png)<![endif]>

Figure 11: The button “shows more”

The button “**show more**” allows the client to have a full view on the concerned table list (pending, in progress, completed).

The client will be redirected to the board which will show every study with the “pending” status.

  

## 3.7. The applicant’s background checks list (Link 5)

From the **dashboard**, the client can be redirected to the overall background checks list like below:

<![if !vml]>![Une image contenant table

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image019.png)<![endif]>

Figure 12: The background checks list sorted by filter

[https://monespace-lite.everycheck.com/studies](https://monespace-lite.everycheck.com/studies)

As we can see here, the client will be redirected in the “all” section by default. The report can be only downloaded when the background check is completed.

In addition, the client can select the kind of background check list that he wants to see (In progress, pending, cancelled or completed).

  

### 3.7.1. Waiting for the applicant

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image020.png)<![endif]>

Figure 13: Pending table list

[https://monespace-lite.everycheck.com/studies?category=2](https://monespace-lite.everycheck.com/studies?category=2)

In order to allow our checker to start the verification process, the applicant must accept and finish the authorization form.

As long as the form is not completed, the background check will be located in the “pending” table list.

  

### 3.7.2. On-going background checks board

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image021.png)<![endif]>

Figure 14: In progress table list

[https://monespace-lite.everycheck.com/studies?category=3](https://monespace-lite.everycheck.com/studies?category=3)

Once the applicant has accepted to sign the authorization and finished to complete the form, the background check status will move from “**pending**” to “**in progress”.**

As long as a checker is still working on the background check, the study will be located in the board “**in progress** “. This table list regroups every background check which are not fully finished.

  

### 3.7.3. Background check refusals

[<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image022.png)<![endif]>](https://monespace-lite.everycheck.com/studies?category=5)

Figure 15: Background checks filtered by cancelled status

[https://monespace-lite.everycheck.com/studies?category=5](https://monespace-lite.everycheck.com/studies?category=5)

If the applicant has refused to sign the authorization, the background check will be located in the “**cancelled**” table list. A background check which has a “cancelled” status cannot progress anymore.

  

### 3.7.1. Completed background checks

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image023.png)<![endif]>

Figure 16: Completed studies list

[https://monespace-lite.everycheck.com/studies?category=4](https://monespace-lite.everycheck.com/studies?category=4)

Once a background check is finished (job experience, diploma…), the study will be removed from the « in progress » table to the « completed » table.

  

## 3.8. The applicant’s details (Link 3)

The applicant’s information and its resume preview must be shown on this page.

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image024.png)<![endif]>

Figure 17: Applicant's information

[https://monespace-lite.everycheck.com/study/045fca0f-511a-4444-9980-ff03b56bf40b  
](https://monespace-lite.everycheck.com/study/045fca0f-511a-4444-9980-ff03b56bf40b)

### 3.8.1. Download documents (Link 5)

On the applicant’s details page, the client can download the partial or full report.

Several other documents can be also downloaded from this page such as the identity card, the applicant’s resume or the filled authorization.

A new website window will be opened for each document selected.

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image025.png)<![endif]>

Figure 18: The resume visualization

[https://monespace-lite.everycheck.com/experiences/35106672-0bf7-4dde-96b4-3d04543ca67d/file](https://monespace-lite.everycheck.com/experiences/35106672-0bf7-4dde-96b4-3d04543ca67d/file)

<![if !vml]>![Une image contenant texte

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image027.png)<![endif]>

Figure 19: The identity card visualization

[https://monespace-lite.everycheck.com/experiences/35106672-0bf7-4dde-96b4-3d04543ca67d/file](https://monespace-lite.everycheck.com/experiences/35106672-0bf7-4dde-96b4-3d04543ca67d/file)

  

## 3.9. The audit trail (Link 4)

Besides, the client can check how EveryCheck found that information. He needs to click on the **experience status icon** from the completed table (figure 10) or on the button “**view the audit trail**” (figure 12) to get the audit trail like below:

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image028.png)<![endif]>

Figure 20: Audit trail details

[https://monespace-lite.everycheck.com/audit/35106672-0bf7-4dde-96b4-3d04543ca67d](https://monespace-lite.everycheck.com/audit/35106672-0bf7-4dde-96b4-3d04543ca67d)

### 3.9.1. Dashboard (Link 1)

It is possible to go back to the main page, which is the dashboard, by clicking on the button “**dashboard**”.

### 3.9.2. Applicant’s details (Link 3)

It is possible to go back to the applicant’s details (background check page), by clicking on the button “**go back to the profile**”.

  

## 3.10. The client statistics (Link 6)

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image029.png)<![endif]>

Figure 21: The client statistics overview

[https://monespace-lite.everycheck.com/stats](https://monespace-lite.everycheck.com/stats)

The client will be able to download his statistics about the number of completed background checks, from the last year and the current year.

The statistics also show how long the applicant takes to submit the completed authorization form and the average time by week for EveryCheck for a background check.

A threshold can be set and save by the client only to determine the maximum of percentage for the red and orange status (Red = major gap, orange = minor gap).

## 3.11. Members allowed to connect with its own account (Link 12)

The client can see who and how many members are linked to his account. They are sharing the same right to see applicant’s details, audit trail, dashboard …

The team leader can add a new member, remove a member or modify a current information for a member.

A member can not add a new member or to edit a member information, he can’t edit the threshold for the statistics or download the statistical data.

<![if !vml]>![Une image contenant texte

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image030.png)<![endif]>

Figure 22: Team members

[https://monespace-lite.everycheck.com/users  
](https://monespace-lite.everycheck.com/users)

### 3.11.1 Add a new member to the team (Link 13)

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image031.png)<![endif]>

Figure 23: Adding a new member

[https://monespace-lite.everycheck.com/users/new](https://monespace-lite.everycheck.com/users/new)

The team leader can add a new member to his list. He needs to feel the fields with the member’s information. Click on “**save**” to apply the modification and to go back to the member list.  

### 3.11.2 Edit the member’s information (Active account)

<![if !vml]>![Une image contenant texte

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image032.png)<![endif]>

Figure 24: Editing an existing member information (1)

[https://monespace-lite.everycheck.com/users/3](https://monespace-lite.everycheck.com/users/3)

The team leader can edit its member information such as the email address, the first and last name.

It is also possible to remove the access for the member by clicking on the button “**Deactivate**”. Click on the button save to apply the modification and to go back to the member list. Once the member account is disabled, the member cannot be logged again until the team leader enables is account.

  

### 3.11.3 Edit the member’s information (Unactive account)

<![if !vml]>![Une image contenant texte

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image033.png)<![endif]>

Figure 25: Editing an existing member information (2)

[https://monespace-lite.everycheck.com/users/3](https://monespace-lite.everycheck.com/users/3)

It is also possible to give a new access for the member who has been removed by clicking on the button “**Activate**”. Click on the button save to apply the modification and to go back to the member list. Once the member account is activated, the member will receive a new password and be able to log again.

  

## 3.12. Check a new applicant (Link 7)

The feature to submit a resume on the website is still on progress.

<![if !vml]>![Une image contenant texte

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image034.png)<![endif]>

Figure 26: Check a new resume from the website

[https://monespace-lite.everycheck.com/new](https://monespace-lite.everycheck.com/new)

  

## 4. The footer pages (Link 11)

Below, there are every page, where the applicant can go without being connected. These pages can be reached from the bottom of each page:

<![if !vml]>![](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image035.png)<![endif]>

Figure 27: Available footer pages

Below, is an example of the footer page:

<![if !vml]>![Une image contenant texte

Description générée automatiquement](file:////Users/leo/Library/Group%20Containers/UBF8T346G9.Office/TemporaryItems/msohtmlclip/clip_image036.png)<![endif]>

Figure 28: Legal notice

[https://monespace-lite.everycheck.com/information/mentions-legales](https://monespace-lite.everycheck.com/information/mentions-legales)
