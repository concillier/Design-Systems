# Design-Systems

# Where's the data from and what's it about? 
Exploratory analysis of dummy data extracted from an ATS for a role that has been closed.
As the Hiring cordinator for this role, I wanted to have an understanding of what data points are most important in tracking any useful data that can improve the hiring process. 

# How to access the data analysis summary. 
You do not need to install anything on your computer to access a summary of the analysed data. 
All you need to do is to click on the file 'Labour' <highlighted in blue> and my labour of love will automatically load with plenty of graphics 😙 . 

# Data source
Data was collected from ATS - Lever in csv format, added on google sheets with minor data cleaning such as removing duplicates and unnecessary rows. 


# Data definition
| Column          | Definition of the data                                  |
| ----------------|-------------------------------------------------------- |
|Location	| The location of the candidate that is automatically read from their CV |
|Origin	| Inbound applications are referred to as 'applied' and candidates we sourced are referred to as 'sourced'|
|Sources | Inbound applications come to us via our Glassdoor, Angel List, Linkedin, directly on our website i.e Job site (Pleo careers) or Main website (Pleo.io). For candidates who show more than 1 source, I pick the first source as that is the first point of contact for candidates and will allow us to see what channels are most effective in attracting inbound applications.| 
|Applied At (GMT)|The time of application. This information can be important in helping us understand what are the pick days and times applicants sent applications and this could help the team understand the best times to promote job ads. |
|Profile Archive Status	| If the profile archive status is 'TRUE', the candidate was not succesful in getting the job and was rejected.|
|Posting Archive Reason	|This shows the reason why the candidate was archieved. Could be because of inexperience, or lack in skills for the role. This field allows us to evaluate the quality of applicants we attract for the role |
|Posting Archived At (GMT)|The time the application was archived. We can use this information to track the average candidate life cycle in the hiring process|
|Current Stage | This shows the stage the candidate reached in the process. I can use this information to track what point of the hiring process we get most drop offs. This information can be potentially used to improve different stages of the hiring process. To note: the hiring process for this role was a bit different as there was no challenge phase. Candidates went through Recruiter Screens > Hiring Manager interviews > Team interviews > Hiring Manager interviews > Values interviews > Debriefs > Offers > Hired |
|Start Date	| When the hired candidate started to work at Pleo |
|Stage - New lead	| Date and time when a candidate was sourced |
|Stage - Reached out |	Date and time when a sourced candidate was reached out to |
|Stage - Responded | Date and time when a sourced candidate responded to our reachout |
|Stage - New applicant	| Date and time when an applicant sent us an application |
|Stage - quality review	| Date and time when applicant moved to quality review |
|Stage - Contacted	| Date and time when applicant was contacted |

# Burning questions that need answers 
1. What is the percentage of sourced candidates vs. those that applied? 
2. What is the most popular source of applications for these candidates? Is it the main website, careers page, Linkedin, Glassdoor or Angelist? 
3. What are some of the most popular days and times when candidates send us applications? (We could come up with a hypothesis why)
4. What are some of the main reasons why these candidates were not hired? (This will allow me to look into the quality of applications that we attract for this role)
5. How was the funnel looking and what were the major stages that applicants dropped off? 

