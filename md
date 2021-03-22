# **Functional**

  

# **Specifications**

  

  

# **Client &amp; Applicant platform**

  
  
Written by: Léo SOK

  

Date: 08/12/2020

  

# Table of contents

  

_**[1. Introduction ](#_Toc6507129)**_

  

_**[2. Context for the recruitment products ](#_Toc65071294)**_

  

**[2.1. Vocabularies ](#_Toc65071295)**

  

_**[3. The functional guide of the candidate platform ](#_Toc65071296)**_

  

**[3.1. Expected features ](#_Toc65071297)**

  

**[3.2. The client website screen routes ](#_Toc65071298)**

  

**[3.3. The login page ](#_Toc65071299)**

  

[3.3.1. Fill the fields and click on Login (Link 1) ](#_Toc65071300)

  

[3.3.2. &quot;Password forgotten&quot; button (Link 6) ](#_Toc65071301)

  

**[3.4. Password recovering ](#_Toc65071302)**

  

[3.4.1. Request for a password-reset (Link 7) ](#_Toc65071303)

  

**[3.5. Create a new password ](#_Toc65071304)**

  

[3.5.1. The &quot;Create&quot; button (Link 8) ](#_Toc65071305)

  

**[3.6. The client Dashboard (Link 1, 2 &amp; 4) ](#_Toc65071306)**

  

[3.6.1. Logout from the dashboard 15](#_Toc65071307)

  

[3.6.2. The resume check status ](#_Toc65071308)

  

[3.6.3. Find an applicant study ](#_Toc65071309)

  

[3.6.4. View on the background check ](#_Toc65071310)

  

[3.6.5. Navigating from the status to the audit trail ](#_Toc65071312)

  

[3.6.6. The pagination ](#_Toc65071313)

  

**[3.7. Background check (Link 2 &amp; 3) ](#_Toc65071314)**

  

[3.7.1. Download documents (Link 5) ](#_Toc65071315)

  

[3.7.2. Audit trail (Link 3 &amp; 4) ](#_Toc65071316)

  

[3.7.3. Dashboard (Link 1,2 &amp; 4) ](#_Toc65071317)

  

[3.7.4. Background check (Link 2 &amp; 3) ](#_Toc65071318)

  

_**[4. The functional guide of the candidate platform ](#_Toc65071319)**_

  

**[4.1. Expected features ](#_Toc65071320)**

  

**[4.2. The screen mapping diagram ](#_Toc65071321)**

  

**[4.3. Page without connection restriction ](#_Toc65071322)**

  

[4.3.1. The login pages](#_Toc65071323)

  

[4.3.2. Login request (Link 14) &amp; Invalid link request ](#_Toc65071324)

  

[4.3.3. Annex pages ](#_Toc65071325)

  

**[4.4. Pages with a login required ](#_Toc65071326)**

  

[4.4.1. The authorization page structure (link 1) ](#_Toc65071327)

  

[4.4.2. The breadcrumb ](#_Toc65071328)

  

[4.4.3. The authorization acceptance or refusal process ](#_Toc65071329)

  

[4.4.4. The refusal notification ](#_Toc65071330)

  

[4.4.5. The authorization previews ](#_Toc65071331)

  

[4.4.6. Verification authorization certificate (Link 11) ](#_Toc65071332)

  

[**4.4.7. The form presentation** ](#_Toc65071333)

  

[4.4.7.1. The form guides ](#_Toc65071334)

  

[4.4.7.2. Similarity between each form page ](#_Toc65071335)

  

[4.4.7.2.1. The auto-save forms ](#_Toc65071336)

  

[4.4.7.2.2. How to skip a form ](#_Toc65071337)

  

[4.4.7.2.3. An auto completion with google map ](#_Toc65071338)

  

[4.4.7.2.4. Fill the address manually ](#_Toc65071339)

  

[**4.4.7.3. The specific features of each form** ](#_Toc65071340)

  

[4.4.7.3.1. The ID form (Link4) 46](#_Toc65071341)

  

[4.4.7.3.2. The school career form (Link 5) 48](#_Toc65071342)

  

[4.4.7.3.3. The job form (Link 6) 50](#_Toc65071343)

  

[4.4.7.3.4. The validation steps (Link 7 &amp; 9) 53](#_Toc65071344)

  

[4.4.7.3.5. The final validation (Link 8) 55](#_Toc65071345)

  

###

  

# 1. Introduction

  

EveryCheck was created in 2015 and inspired by Anglo-Saxon countries. It aims to bring background checks for recruitment and real estate in France.

  

This document will describe the functionals specifications for the recruitment web application

  

![Figure 1](https://github.com/everycheck/docs/blob/master/img/HomePage_F1.png)

  

##

  

_Figure 1: Home page_

  

_[https://www.everycheck.com/](https://www.everycheck.com/)_

  

# 2. Context for the recruitment products

  

In the UK or US, most of the compagnies check the applicant&#39;s resume before hiring them. In France, recruiters tend more to trust the applicant and rarely do a background check. But based on statistics from 2016 to 2019, among 10 000 resumes checked, 60% of them had falsified information.

  

Most of the HR reveal they do not have enough time to do a real background check.

  

Applicants who faked their resume do it to hide gaps between experiences or &quot;improve&quot; some part to make it more attractive for recruiters. They can:

  

- Add a diploma

- Change their position in a job

- Extend Began or ended date of employment

- …

  

When discovered some of them reveal the truth, others can deny the fact and leave, and sometimes they may add layers of lies to prove EveryCheck is mistaken.

  

EveryCheck mission is to help recruiters with their future hiring. Providing more information about the applicant will allow the recruiter to base its decision on fact only. This will avoid negative consequences of hiring someone they did not expect.

  

To help them acquire more information, EveryCheck gives them access to a web application focused on applicant background check.

  

EveryCheck can check:

  

- Ids (driver license, passport, ID card)

- Diploma (obtained or not, when, which degree, where ….)

- Employment (where, which position, with which contract, from when to when, ...)

- Or any other information that can be put on a resume.

  

EveryCheck is not meant to judge people. Its mission is only to gather information.  EveryCheck will never be able to help a recruiter to know if an applicant can fit in a job description or not.

  

Each applicant check is called a study and follow this process:

  

![Figure2](https://github.com/everycheck/docs/blob/master/img/Process_f2.png)

  

_Figure 2: Study process_

  

1. The recruiter sends the resume to start the check.

  

1. The second step is really important due to GDPR. Then the applicant provides us some information about his career which does not appear on his resume. (Often the dates on resumes are vague 2012-2013 but is it January 2012 to December 2013 or December 2012 to January 2013? Sometimes the name of the company is not sufficient to know where the applicant has worked, …). This step is divided into five main parts:

  

- The signature accompanied by the applicant&#39;s refusal or acceptance

- The form filling related to identity

- The form filling related to the school career

- The form filling related to the work experiences

- The validation step is the final one accompanied by a summary

  

In general, 20% of applicants do not accept to be checked. It shows to the recruiter that the applicant was not really motivated.

  

1. EveryCheck team members proceed to check all the data given by the applicant. Those checks can take from 1 to 3 open days. After two days if the background check is not finished yet, a temporary report is sent to the recruiter. The duration of the background check may vary depending on the kind of company checked:  big, small, still in activities, closed for vacation or end of activities, ...

  

1. Once EveryCheck members finish checking all the data, a final report will be sent. It shows the results with status icons, when and who did EveryCheck contact to bring information. This report helps recruiters to choose their final employees.

  

This is an example of the final report:

  

![Figure 3](https://github.com/everycheck/docs/blob/master/img/report_f3.png)

  

_Figure 3: Example of a final report_

  

_https://monespace-lite.everycheck.com/studies/abcdef/delivery_

  

## 2.1. Vocabularies

  

First of all, some words are important to understand properly the contents of this document:

  

- **Resume:** Awritten description of the education, qualifications, previous jobs, and also about the personal interests.

  

- **Applicant:** It is the resume owner which must be checked.

  

- **Client:** It is a recruiter/employer who will submit to EveryCheck the applicant&#39;s resume.

  

- **Study:** A study deals with the applicant&#39;s resume, our staff will work on the resume&#39;s information which is composed by the diploma, professional experiences and even about the identity.

  

- **Online agreement:** It is an online checkbox where the applicant will check to allow us to start our investigation.

  

- **Background check:** it is a check of what a person has done in the past, usually as part of the process of deciding whether or not to employ applicants.

  

- **Status:** The status will indicate you the result of each information from the background check if we finished to check or not yet an element.

  

- **Documents:** A document can be seen or downloaded from the study, like the resume or pieces from the ID (card, passport, driver license or the diploma).

  

- **Audit trail:** It will show you the process of our check and how we brought and certified information, the audit trail will justify the status of an element after our check.

  

- **Final report:** It is the final product that you will get after we finished our check. It will summary every information that the client will need to know about the candidate, if the information from the study is true or not.

  

- **Magic link:** A link is sent directly to the mailbox of the applicant. It will allow him to log in again to the platform without password and username.

  

- **Contact:** It could be a former or current applicant&#39;s employer or a school where the applicant studied. A registered contact will help EveryCheck to confirm the information on the resume.

  

# 3. The functional guide of the candidate platform

  



We will explain the client platform into 3 main parts:

  

- Define the features expected by the client

- The screen mapping details

- The presentation of the platform

  


  

## 3.1. Expected features

  

1. As a client I would like to log into my account/dashboard

2. As a client I would like to logout from my account

3. As a client I would like to reset/recover my password

4. As a client I would like to change the language from French to English or the reverse

5. As a client I would like to send by email the studies that I want them to be checked

6. As a client I would like to take a look on a study that I submitted by email and to get the information about the applicant

7. As a client I would like to search by the applicant&#39;s name a study

8. As a client I would like to navigate to a study via the paging

9. As a user I would like to download different documents from the candidate&#39;s background check

10. As a client I would like to know the status of each studies

11. As a client I want to see the audit trail process

12. As a client I would like the get the partial or the final report

  

## 3.2. The client website screen routes

  

![Figure 4](https://github.com/everycheck/docs/blob/master/img/screenmapping_f4.png)

  

_Figure 4: Screen mapping_

  

This is the representation of the website mapping; it shows us every results and interfaces that you can get after an action on the website.

  

## 3.3. The login page

  

The customer will get an account on the &quot;client website &quot;where he can login in order to get the access to its &quot; **Dashboard**&quot;.

  

Below, this is the interface where the customer will have to login:

  

![Figure 5](https://github.com/everycheck/docs/blob/master/img/loginpage_F5.png)

  

_Figure 5: Login page_

  

_[https://monespace-lite.everycheck.com/login](https://monespace-lite.everycheck.com/login)_

  

### 3.3.1. Fill the fields and click on Login (Link 1)

  

In order to get an access to the personal dashboard we will ask to fill the fields with a username and a password.

  

### 3.3.2. &quot;Password forgotten&quot; button (Link 6)

  

If the client doesn&#39;t remember about the password, a new one can be set up, he just needs to click on the button to do the process and follow our instructions.

  

## 3.4. Password recovering

  

If the user doesn&#39;t remember about the password, he can always get it back, click on &quot;Password forgotten&quot; from the Login page and he will be automatically redirected to the Password recovering page as below:



  

![Figure 6](https://github.com/everycheck/docs/blob/master/img/passwordreset_F6.png)

  

_Figure 6: Password recovering page_

  

_[https://monespace-lite.everycheck.com/reset-password](https://monespace-lite.everycheck.com/reset-password)_

 
The user needs to fill the field with its username and to click on Recover.


### 3.4.1. Request for a password-reset (Link 7)
  

Once the client clicked on &quot;Recover&quot;, an email has been sent with a secret code and he will be redirected to a new page where he can use that code and choose its new password.

  

## 3.5. Create a new password

  

![Figure 7](https://github.com/everycheck/docs/blob/master/img/createnewpwd_F7.png)

  

_Figure 7: New password page_

  

_[https://monespace-lite.everycheck.com/set-password](https://monespace-lite.everycheck.com/set-password)_

  

The code will be sent only if the username is correct, otherwise the user will not be able to change its password.

  

Once the code received by email and the new password chosen, the user will be redirected to the login page (Figure 5).

  

### 3.5.1. The &quot;Create&quot; button (Link 8)



  

Click on &quot;Create&quot; to define a new password and the previous password will automatically be replaced.

  

After this step, the user can go back to the login page, and try again with the new password.

  

The Dashboard page will appear after the connection.

  

## 3.6. The client Dashboard (Link 1, 2 &amp; 4)

  

This is the main interface after the log in, first of all if our client wants to use our services, the client must have available credits.

  

Indeed, each resume require one credit, and those credits are only available for 18 months, otherwise they will be expired (the date of purchase is mentioned).

  

  

![Figure 8](https://github.com/everycheck/docs/blob/master/img/Dashboard_F8.png)

  

_Figure 8: Personal Dashboard page_

  

_[https://monespace-lite.everycheck.com/](https://monespace-lite.everycheck.com/)_

  

There are three different dates:

  

- The first column from the left, show the time when the client has submitted the resume.

- The middle one, is the date when the applicant has accepted to allow EveryCheck to check his resume.

- The right one is when EveryCheck replied back to the client after the background check

  

### 3.6.1. Logout from the dashboard
 
  

The client can go back to the login page (Figure 5) once he finished to check information that he needed; he must click on the button Logout.

  

### 3.6.2. The resume check status

  

Once the resume has been checked, the dashboard will be updated, and the client will be able to check the progress of each resume.

  

The status will show us for each background check a different colour:

  

![Figure 9](https://github.com/everycheck/docs/blob/master/img/colourstatus_F9.png)

  

_Figure 9: Status colours_

  

- Green = the check is done and congruent

- Orange = more or less correct

- Red = false information

- Grey = impossible to check

- Blue = on process

  

There is minimum 2 checks and maximum 6 checks, they could be the identity check, a diploma or a professional experience check.

  

### 3.6.3. Find an applicant study

  

![Figure 10](https://github.com/everycheck/docs/blob/master/img/researchbar_F10.png)

  

_Figure 10: Research bar_

  

The applicant can be searched by the client from the research bar with the applicant&#39;s last name.

  

### 3.6.4. View on the background check

  

![Loupe](https://github.com/everycheck/docs/blob/master/img/magnifying-glass.png)

  

The magnifying glass next to the status will allow the client to have more details about the background check of the applicant.

  

### 3.6.5. Navigating from the status to the audit trail

  

![Figure 11](https://github.com/everycheck/docs/blob/master/img/hoover_f11.png)


_Figure 11: status title_


  

It is possible to get a direct access to the audit trail. Hover over on one status, will let appear the title. The client can check the audit trail from the status figure, he must click on it.

  

The user will be redirected to the concerned audit trail.

  

### 3.6.6. The pagination

  

![Figure 12](https://github.com/everycheck/docs/blob/master/img/pagination_f12.png)

  

_Figure 12: The pagination_

  

The pagination will show the number of pages where the background checks are. It is possible to have a look from any page.

  

## 3.7. Background check (Link 2 &amp; 3)

  

On this page every information can be found about the applicant from his identity to his diploma or professional experiences.

  

![Figure 13](https://github.com/everycheck/docs/blob/master/img/backgroundcheck_f13.png)

  

_Figure 13: Background check page_

  

_[https://monespace-lite.everycheck.com/study/](https://monespace-lite.everycheck.com/study/)_

  

### 3.7.1. Download documents (Link 5)

  

  

The client can download the applicant&#39;s documents if they are available such as the ID documents, the short/full report or the resume.

  

A new website window will be opened for each document selected.

  

![Figure 14](https://github.com/everycheck/docs/blob/master/img/CV_f14.png)

  

_Figure 14: The resume_

  

_[https://monespace-lite.everycheck.com/studies/abcdefghij/resume](https://monespace-lite.everycheck.com/studies/abcdefghij/resume)_

  

![Figure 15](https://github.com/everycheck/docs/blob/master/img/ID_f15.png)

  

_Figure 15: The ID card_

  

_[https://monespacelite.everycheck.com/experiences/abc/file](https://monespacelite.everycheck.com/experiences/abc/file)_

  

Click here to have a look for the: [Figure 3: Final report](#_Figure_3:_Example)

  

#

  

### 3.7.2. Audit trail (Link 3 &amp; 4)

  

Besides, the client can check how EveryCheck found that information. He just needs to click on the status to get the audit trail like below:

  

##

  

![F16](https://github.com/everycheck/docs/blob/master/img/audit-trail_f16.png)

  

_Figure 16: Audit trail page_

  

_[https://monespace-lite.everycheck.com/audit/](https://monespace-lite.everycheck.com/audit/)_

  

### 3.7.3. Dashboard (Link 1,2 &amp; 4)

  

It is possible to go back to the main page, which is the dashboard, click on the button &quot; **dashboard**&quot;.

  

### 3.7.4. Background check (Link 2 &amp; 3)

  

It is possible to go back to the background check page, click on the button &quot; **background check**&quot;.

  

#

  

# 4. The functional guide of the candidate platform

  

We will explain the client platform into 3 main parts:

  

- Define the features expected by the applicant

- The screen mapping details

- This part will explain the applicant platform pages with the desktop version and below the mobile version.

  

The mobile version of the platform similar to the desktop version. But the platform will be arranged differently to fit every element in the screen.

  

Besides, the URL between the desktop and mobile version are the same.

  

## 4.1. Expected features

  

1. As an applicant I would like to login to the platform

2. As an applicant I would like to logout from the platform

3. As an applicant I would like to receive the magic link

4. As an applicant I would like to choose my signature style

5. As an applicant I would like to be able to accept or decline the condition of the terms

6. As an applicant I would like to be able to download the signed authorization

7. As an applicant I would like to get a guide/help for the process

8. As an applicant I would like to follow my progress on the breadcrumb trail

9. As an applicant I would like to fill my identity, school and job information in the form

10. As an applicant I would like to upload an attachment

11. As an applicant I would like to skip or continue with missing information

12. As an applicant I would like to add a contact for EveryCheck

13. As an applicant I would like to modify my information

14. As an applicant I would like to have a summary before the validation

15. As an applicant I would like to validate definitely the form

16. As an applicant I want to receive the completion notification

  

## 4.2. The screen mapping diagram

  

![f17](https://github.com/everycheck/docs/blob/master/img/Screenmap_f17.png)

  

_Figure 17: Screen mapping_

  

This is the representation of the website mapping; it shows us every result and interfaces the applicant can get after an action on the website.

  

## 4.3. Page without connection restriction

  

###

  

### 4.3.1. The login pages

  

**Desktop version:**

  

First of all, EveryCheck will send by email a link where the applicant will be able to get a first access to sign the authorization.

  

A link is available only once, after the first login used, the applicant will need to ask another access. He needs to write its email in the field and to click on login to get a new link by email.

  

![F18](https://github.com/everycheck/docs/blob/master/img/Firstloginf18.png)

  

_Figure 18: &quot;First Login&quot; page 


![F19](https://github.com/everycheck/docs/blob/master/img/Login_f19.png)

Figure 19: Login page_

  

_[https://candidat.everycheck.com/first-login](https://candidat.everycheck.com/first-login)_[https://candidat.everycheck.com/login](https://candidat.everycheck.com/login)

  

A chat box can be opened in order to contact directly one of EveryCheck staff members.

  

The chat box has a static position when the applicant is scrolling the page.

  

![f19.1](https://github.com/everycheck/docs/blob/master/img/Chatbox_f19.1.png)

  

_Figure 19.1: The chat box_

  

![f19.2](https://github.com/everycheck/docs/blob/master/img/Chatbox_f19.2.png)

  

_Figure 19.2: The chat box_

  

**Mobile version:**

  

![f20](https://github.com/everycheck/docs/blob/master/img/f20.png)

  

_Figure 20: Applicant platform home page (1) 

![f21](https://github.com/everycheck/docs/blob/master/img/f21.png)

Figure 21: Home page (2) 

![f22](https://github.com/everycheck/docs/blob/master/img/f22.png)

Figure 22: The bottom page_

  

![f22.1](https://github.com/everycheck/docs/blob/master/img/f22.1.png)

_Figure 22.1: The chat box_

  

### 4.3.2. Login request (Link 14) &amp; Invalid link request

  

**Desktop**  **version:**

  

If the mail is correct, the applicant will receive a mail from EveryCheck with a new link, which is available once.

  

The applicant will be able to login again as the first time, without a username and a password.

  

![f23](https://github.com/everycheck/docs/blob/master/img/magiclink_f23.png)

  

_Figure 23: The new access request_

  

[_https://candidat.everycheck.com/magic/request__/abc@abc.fr_](https://candidat.everycheck.com/magic/request/abc@abc.fr)

  

If the link is already used or if it doesn&#39;t work, a new link can be sent by clicking on **&quot;send me a new link&quot;.**

  

![f24](https://github.com/everycheck/docs/blob/master/img/invalidmagiclink_f24.png)

  

_Figure 24: Invalid link_

  

[https://candidat.everycheck.com/magic/QAhGMKWb](https://candidat.everycheck.com/magic/QAhGMKWb)

  

**Mobile version:**

  

![f25](https://github.com/everycheck/docs/blob/master/img/f25.png) 
 

_Figure 25: The link request 

![f26](https://github.com/everycheck/docs/blob/master/img/f26.png)

Figure 26: The invalid link_

  

### 4.3.3. Annex pages

  

**Desktop**  **version:**

  

Below, there are every page, where the applicant can go without being connected. These pages can be reached from the bottom of each page:


![f27](https://github.com/everycheck/docs/blob/master/img/terms_f27.png)

  
Figure 27: Terms of use

![f28](https://github.com/everycheck/docs/blob/master/img/Confidentiality_f28.png)

 Figure 28: Confidentiality and cookies

![f29](https://github.com/everycheck/docs/blob/master/img/Q%26A_f29.png) 
  
https://candidat.everycheck.com/information/cookie_

Figure 29: Q&amp;A



https://candidat.everycheck.com/information/faq 



![f30](https://github.com/everycheck/docs/blob/master/img/legal-mentions_f30.png)

Figure 30: Legal mention

  

https://candidat.everycheck.com/information/legal_

  

![f31](https://github.com/everycheck/docs/blob/master/img/IT_f31.png)

  

_Figure 31: IT and liberty_

  

[_https://candidat.everycheck.com/information/data_](https://candidat.everycheck.com/information/data)

  

**Mobile version:**

  

![terms](https://github.com/everycheck/docs/blob/master/img/terms.png)
 ![confidentiality](https://github.com/everycheck/docs/blob/master/img/confidentiality.png)
  ![mention](https://github.com/everycheck/docs/blob/master/img/legalmentions.png)


![q&a](https://github.com/everycheck/docs/blob/master/img/Q%26A.png)
 ![IT](https://github.com/everycheck/docs/blob/master/img/informatique.png)

  

## 4.4. Pages with a login required

  

### 4.4.1. The authorization page structure (link 1)

  

Once the applicant has finished to log in. He will be redirected to the authorization page.

  

This page is divided into 2 parts:
 

- The menu

- The main content
-   

![f32](https://github.com/everycheck/docs/blob/master/img/Signingpage_f32.png) 
  
_Figure 32: The structure of the logged in page_

  [_https://candidat.everycheck.com/authorization-legal_](https://candidat.everycheck.com/authorization-legal) 
  
  

**The menu (blue part)** on the left, is composed by several elements:

  

- The logo of the company

- The name of the applicant

- The button logout

- The breadcrumb

  

The button ![?button](https://github.com/everycheck/docs/blob/master/img/%22%3F%22%20button.png) is available on each step after the authorization preview, it allows the applicant to come back on the guide page, we will see it on the next page.

  

**The main content (white part)** will be explained at **the page 32.**

  

### 4.4.2. The breadcrumb

  

**Desktop**  **version:**

  

The breadcrumb is a common element, it will appear on every page.

  

Before the authorization preview, the breadcrumb (Figure 33) is different from the breadcrumb after the authorization preview (Figure 34), like below:

  

![f33](https://github.com/everycheck/docs/blob/master/img/breadcrumb_F33.png) 

  
Figure 33: The breadcrumb trail before (1) 

![f34](https://github.com/everycheck/docs/blob/master/img/breadcrumb_f34.png)
Figure 34: The breadcrumb trail after (2)

  

The applicant can know the status of each step through several icons:

  

- The icon ![icone1](https://github.com/everycheck/docs/blob/master/img/icone1.png) means that a step is not reachable yet.

  
- The icon ![icone2]([icone2.png](https://github.com/everycheck/docs/blob/master/img/icone2.png) shows where the applicant is on the breadcrumb trail.

  

- This icon ![icone3](https://github.com/everycheck/docs/blob/master/img/icone3.png) means that a form has not been filled or partially filled.

  

- This icon ![icone4](https://github.com/everycheck/docs/blob/master/img/icone4.png) means that a form has been completed.

  

- The icon ![icone5](https://github.com/everycheck/docs/blob/master/img/icone5.png) shows the final step which is the validation step.

  

He is able to return to a previous step to modify the information at any moment before the validation.

  

**Mobile version:**

  

The breadcrumb closing cross must not be overlapped on the EveryCheck logo.

  

It can be opened in full screen with the hamburger menu. Click on the cross to close the breadcrumb.

  

![figure35](https://github.com/everycheck/docs/blob/master/img/f35.png)
 ![figure 36](https://github.com/everycheck/docs/blob/master/img/f35.1.png)

  

_Figure 35: The breadcrumb_

  

### 4.4.3. The authorization acceptance or refusal process

  

**Desktop**  **version:**

  

To accept or refuse the authorization and to continue to the next step, the applicant must:

  

- Select his signature style among of **3 kinds of signature**

- To **check** the condition of the terms

- To click on **&quot;Accept the conditions&quot;** or **&quot;Decline the terms&quot;**

  

![f36](https://github.com/everycheck/docs/blob/master/img/Fullsigningpage_f36.png)

  

_Figure 36: The authorization request_

  

[_https://candidat.everycheck.com/authorization-legal_](https://candidat.everycheck.com/authorization-legal)

  

Once the applicant clicked on decline, a box will appear. To be sure about the refusal, EveryCheck oblige the applicant to write in the field **&quot;REFUSER&quot;** in order to avoid him to refuse accidently.

  

Click on &quot;close&quot; to come back on the authorization.

  

![f37](https://github.com/everycheck/docs/blob/master/img/refusal_f37.png)

  

_Figure 37: The decline request_

  

[_https://candidat.everycheck.com/authorization-legal_](https://candidat.everycheck.com/authorization-legal)

  

### 4.4.4. The refusal notification

  

Once the refusal is done, a notification will inform the applicant that his refusal has been successfully transmitted to EveryCheck

  

![f38](https://github.com/everycheck/docs/blob/master/img/RefusalNotification_f38.png)

  

_Figure 38: The authorization refusal_

  

[_https://candidat.everycheck.com/authorization-refused_](https://candidat.everycheck.com/authorization-refused)

  

**Mobile version:**

  

In the top left-hand corner, the hamburger button must not be overlapped on the &quot;EveryCheck&quot; logo nor being behind the decline box.

  

![f39](https://github.com/everycheck/docs/blob/master/img/f39.png) 
Figure 39: Authorization page (1) 

![f40](https://github.com/everycheck/docs/blob/master/img/f40.png) 
Figure 40: Authorization page (2) 

![f41](https://github.com/everycheck/docs/blob/master/img/f41.png) 
Figure 41: refusal validation

  

- On this picture, those elements in the red circle are not fitting well the screen.

  

![f42](https://github.com/everycheck/docs/blob/master/img/f42.png)

  

_Figure 42: The refusal notification_

  

### 4.4.5. The authorization previews

  

**Desktop**  **version:**

  

If the applicant accepts the conditions from the authorization, he will move to this page where he can download the official document of the authorization check.

  

He needs to click on **&quot;Start to fill your profile&quot;** to continue.

  

![f43](https://github.com/everycheck/docs/blob/master/img/authorization_F43.jpg)

  

_Figure 43: Your authorization page_

  

[_https://candidat.everycheck.com/show-authorization_](https://candidat.everycheck.com/show-authorization)

  

### 4.4.6. Verification authorization certificate (Link 11)

  

**Desktop**  **version:**

  

From the previous page, the applicant can see his certificate in a bigger size and to download it.

  

![f44](https://github.com/everycheck/docs/blob/master/img/Authorization2_f44.png)

  

_Figure 44: The official check authorization_

  

**Mobile version:**

  

A preview of the authorization must be seen in the middle instead of the blank area.

  

![f45](https://github.com/everycheck/docs/blob/master/img/f45.png)

Figure 45: The document preview 


![f46](https://github.com/everycheck/docs/blob/master/img/f46.png) 
Figure 46: The full-size document

  

### **4.4.7. The form presentation**

  

#### 4.4.7.1. The form guides

  

**Desktop**  **version:**

  

Before the forms, a guide for the applicant is presented.

  

In addition, a **&quot;Q&amp;A&quot;** website is available for any other additional information about EveryCheck or the process.

  

When the applicant is ready to start the first form, he needs to click on **&quot;fill the form&quot;**. The identity form will be the first one to appear.

  

![f47](https://github.com/everycheck/docs/blob/master/img/ApplicantGuide_F47.png)

  

_Figure 47: The guide for the form filling_

  

[_https://candidat.everycheck.com/_](https://candidat.everycheck.com/)

  

**Mobile version:**

  

![f48](https://github.com/everycheck/docs/blob/master/img/f48.png)

  

_Figure 48: The form guide_

  

#### 4.4.7.2. Similarity between each form page

  

Those forms have common points between them, we will present it below.
 

##### 4.4.7.2.1. The auto-save forms

  

**Desktop**  **version:**

  

Every form page is automatically saved by themselves, when the applicant is idle for 1 second while he is writing in the field or when he moves to another field.

  

![f49](https://github.com/everycheck/docs/blob/master/img/IdentityForm_f49.png)  

  

_Figure 49: The autosave_

  

[_https://candidat.everycheck.com/job/39ad295e-a4de_](https://candidat.everycheck.com/job/39ad295e-a4de)

  

  

- When the applicant finished to fill a field, a save will start for the field, it is shown by a spinner

![spinner](https://github.com/everycheck/docs/blob/master/img/spinner.png)

  

- Once the save is finished the applicant will see:

  ![saved](https://github.com/everycheck/docs/blob/master/img/saved.png)

- If the field is empty or not properly fill, no save will be made

  

The applicant **cannot continue** to the next step as long as the save is not finished.

  

The button **&quot;Continue&quot;** will appear just after the save, then he will be able to click on &quot;continue&quot;.

  

**Mobile version:**

  

![f50](https://github.com/everycheck/docs/blob/master/img/f50.png) ![f50.1](https://github.com/everycheck/docs/blob/master/img/f50.1.png)

  

_Figure 50: The autosave_

  

##### 4.4.7.2.2. How to skip a form

  

**Desktop**  **version:**

  

A form can be skipped even if one or several fields are empties. The applicant needs to click on **&quot;Next step&quot;,** or he can decide to stay on the same page. If the applicant has skipped a form, he will be able to return on the form to fill missing fields later.

  

![f51](https://github.com/everycheck/docs/blob/master/img/FormSkip_f51.png)

  

Figure 51: Skipping form box

  

_[https://candidat.everycheck.com/job/c1460499-4a91](https://candidat.everycheck.com/job/c1460499-4a91)_

  

**Mobile version:**

  

![f52](https://github.com/everycheck/docs/blob/master/img/f52.png)

  

_Figure 52: The skip_

  

##### 4.4.7.2.3. An auto completion with google map

  

**Desktop**  **version:**

  

Once the applicant will start to write in the field for **a work or school place** , several results will appear. They are proposed by google map.

  

![f53](https://github.com/everycheck/docs/blob/master/img/SchoolCareerForm_f53.png)

  

_Figure 53: An automatic address filling_

  

[_https://candidat.everycheck.com/job/c1460499-4a91_](https://candidat.everycheck.com/job/c1460499-4a91)

  

**Mobile version:**

  

![f54](https://github.com/everycheck/docs/blob/master/img/f54.png)

  

_Figure 54: The autofill_

  

##### 4.4.7.2.4. Fill the address manually

  

**Desktop**  **version:**

  

An address will be automatically proposed when the applicant will start the fill the field as we can see. He can also decide to fill the information manually by clicking on &quot; **Fill the address manually**&quot;.

  

![f55](https://github.com/everycheck/docs/blob/master/img/SchoolForm-Manual_f55.png)

  

_Figure 55: The manual fill_

  

[_https://candidat.everycheck.com/job/c1460499-4a91_](https://candidat.everycheck.com/job/c1460499-4a91)

  

As we can see below, 4 fields had been added for the applicant to allow him to fill his school address.

  

![f56](https://github.com/everycheck/docs/blob/master/img/ManualField_f56.png)

  

_Figure 56: The manual fill (2)_

  

[_https://candidat.everycheck.com/job/c1460499-4a91_](https://candidat.everycheck.com/job/c1460499-4a91)

  

**Mobile version:**

  

![f57](https://github.com/everycheck/docs/blob/master/img/f57.png)
Figure 57: The manual fill

![f57.1](https://github.com/everycheck/docs/blob/master/img/f57.1.png)

 
  

#### **4.4.7.3. The specific features of each form**

  

The applicant needs to give to EveryCheck several information about him, through a form before to continue to another form.

  

Each form has its own features which are not present on other forms.

  

##### 4.4.7.3.1. The ID form (Link4)

  

**Desktop**  **version:**

  

The applicant must select by a click his civility and to fill every field. The **ID card attachment is mandatory** for the school form, otherwise it will be a missing element.

  

![f58](https://github.com/everycheck/docs/blob/master/img/IDForm2_f58.png)

  

_Figure 58: The school form_

  

[_https://candidat.everycheck.com/job/c1460499-4a91_](https://candidat.everycheck.com/job/c1460499-4a91)

  

An attachment can be shown or be deleted after, with these buttons bellow:

  

![f59](https://github.com/everycheck/docs/blob/master/img/Attachment_f59.png)

  

_Figure 59: Button to remove an attachment_

  

**Mobile version:**

  

![f60](https://github.com/everycheck/docs/blob/master/img/f60.png)

  

_Figure 60: The Identity form_

  

##### 4.4.7.3.2. The school career form (Link 5)

  

**Desktop**  **version:**

  

As we saw previously, the applicant only needs to complete fields. The grade and the status must be selected precisely by the applicant. A comment can be added on the bottom page.

  

![f61](https://github.com/everycheck/docs/blob/master/img/Schoolform2_f61.png)

  

_Figure 61: The school form_

  

[_https://candidat.everycheck.com/job/c1460499-4a91_](https://candidat.everycheck.com/job/c1460499-4a91)

  

There are several choices for the &quot;Grade&quot;:

  

![grade](https://github.com/everycheck/docs/blob/master/img/grade.png)

  

There are several choices for the &quot;Status&quot;:

  

![status](https://github.com/everycheck/docs/blob/master/img/status.png)

  

**Mobile version:**

  

![f62](https://github.com/everycheck/docs/blob/master/img/f62.png) ![f62.1](https://github.com/everycheck/docs/blob/master/img/f62.1.png)

  

_Figure 62: The school career form_

  

##### 4.4.7.3.3. The job form (Link 6)

  

**Desktop**  **version:**

  

Different kind of contract end can be chosen by the applicant. The contract end **&quot;Actual job&quot;** (page 38) is different from another contract ends.

  

An optional attachment can be added by clicking on **&quot;Browse&quot;.** A **specific contact** can be registered.

  

![f63](https://github.com/everycheck/docs/blob/master/img/Jobcareer_f63.png)

  

_Figure 63: The job form_

  

[_https://candidat.everycheck.com/job/103ef594-714b_](https://candidat.everycheck.com/job/103ef594-714b)

  

There are several choices for the applicant for the **&quot;Contract&quot;:**

  

![contract](https://github.com/everycheck/docs/blob/master/img/contract.png)

  

There are several choices for the applicant for the **&quot;Kind of contract end&quot;:**

  

![Contractend](https://github.com/everycheck/docs/blob/master/img/contract-end.png)

  

- If the applicant wishes EveryCheck to **contact a specific person** , he can give us the contact information with a new form like below.

  

![f64](https://github.com/everycheck/docs/blob/master/img/AddContact_f64.png)

  

_Figure 64: The full screen of the work form page_

  

[_https://candidat.everycheck.com/job/103ef594-714b_](https://candidat.everycheck.com/job/103ef594-714b)

  

- If the applicant is still working in the same company, choosing **&quot;actual job&quot;** as the kind of contract end will hide the contract end date. The specific contact will not be asked either.

  

![f65](https://github.com/everycheck/docs/blob/master/img/ContractEnd_f65.png)

  

_Figure 65: Actual job_

  

[_https://candidat.everycheck.com/job/103ef594-714b_](https://candidat.everycheck.com/job/103ef594-714b)

 

**Mobile version:**

  

![f66](https://github.com/everycheck/docs/blob/master/img/f66.png)
 ![f66](https://github.com/everycheck/docs/blob/master/img/f67.png)_Figure 66: The job form_

  

![f67](https://github.com/everycheck/docs/blob/master/img/f67.1.png)_Figure 67: Actual job_ 

![f68](https://github.com/everycheck/docs/blob/master/img/f68.png) _Figure 68: Add a contact_

  

##### 4.4.7.3.4. The validation steps (Link 7 &amp; 9)

  

**Desktop**  **version:**

  

Once the applicant finished to fill every fields from every form without missing elements, a summary will be showed. And two different ways are possible to modify information, with the pencil icon or from the breadcrumb trail.

  

If there is nothing to change the applicant needs to click on &quot;confirm the data&quot; to finish the process.

  

Clicking on the &quot;pencil&quot; icon next to the title box is the second way.

  

![f69](https://github.com/everycheck/docs/blob/master/img/CompletedForm_f69.png)

  

_Figure 69: The validation page (1)_

  

[_https://candidat.everycheck.com/job/validation_](https://candidat.everycheck.com/job/validation)

  

If an element has been forgotten, the applicant won&#39;t be able to validate the final step. The applicant must go back to the step where an element is missing. An indicator will show the missing information in orange.

  

![f70](https://github.com/everycheck/docs/blob/master/img/UncompletedForm_f70.png)

  

_Figure 70: Missing elements_

  

[https://candidat.everycheck.com/job/validation](https://candidat.everycheck.com/job/validation)

  

**Mobile version:**

  

![f71](https://github.com/everycheck/docs/blob/master/img/f71.png)

Figure 71: the invalid validation page 
 ![f72](https://github.com/everycheck/docs/blob/master/img/f72.png)

  
Figure 72: the valid validation page

  

##### 4.4.7.3.5. The final validation (Link 8)

  

**Desktop**  **version:**

  

A message will appear when the validation is done, then the applicant can logout from this page and go back to the login page (Figure 6).

  

![f73](https://github.com/everycheck/docs/blob/master/img/SuccessfulNotification_f73.png)

  

_Figure 73: The final message after the successful form filling_

  

[_https://candidat.everycheck.com/congratulation_](https://candidat.everycheck.com/congratulation)

  

**Mobile version:**

  

![f74](https://github.com/everycheck/docs/blob/master/img/f74.png)

  

_Figure 74: The validation notification_
