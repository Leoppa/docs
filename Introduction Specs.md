# **Functional**

  

# **Specifications**

  


# **Client &amp; Applicant platform**

  
  
Written by: Léo SOK

  

Date: 08/12/2020


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
