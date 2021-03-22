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
![Figure 1](https://github.com/Leoppa/docs/blob/master/img/HomePage_F1.png)
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
![Figure2](https://github.com/Leoppa/docs/blob/master/img/Process_f2.png)
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
![Figure 3](https://github.com/Leoppa/docs/blob/master/img/report_f3.png)
_Figure 3: Example of a final report_
_https://monespace-lite.everycheck.com/studies/abcdef/delivery_
