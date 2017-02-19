# Recommendation of New Questions in Online Student Communities
## Diploma thesis
- Author:     Jakub Mačina
- University: Slovak University of Technology Bratislava
- Degree Course:    Information Systems
- Supervisor:    Ivan Srba, PhD. 

## Data
Data are extracted from [Askalot CQA system](https://github.com/AskalotCQA/askalot) used in [QuCryptox Quantum cryptography](https://courses.edx.org/courses/course-v1:CaltechDelftX+QuCryptox+3T2016) 
MOOC course offered by California Institute of Technology and Delft University of Technology

## Files
- [course-analysis.ipynb](course-analysis.ipynb) - data about the course
- [question-routing-evaluation.ipynb](question-routing-evaluation.ipynb) - feature selection, evaluation of recommendation and classifier performance

## Abstract
Community  question  answering  (CQA)  systems  are  successfully  used  on  the  open  Web  and  in 
enterprise environments. With an increasing popularity of Massive Open Online Courses (MOOCs) 
there is an opportunity for the CQA systems to help students in the online learning communities as 
well.   

The  goal  is  to  propose  a  new  approach  for  a  recommendation  of  new  questions,  which  will  be 
specifically designed for CQA systems employed in educational settings. The main objective is to 
provide  a  better  educational-specific  online  recommendation  in  comparison  to  the  general 
recommendation approaches. Many of the existing methods tend to overload only few experts by 
recommending most of the questions to them. This work focus more on answerer’s preferences and 
effective  knowledge utilization  of  a  greater  part of  an  online  student  community to  increase the 
accuracy of answerer’s prediction and in total, to increase the number of questions answered in a 
CQA system.  

We built a novel question routing approach which models along user’s expertise for a given question 
also  user’s  willingness  to  answer  the  question.  The  predictions  based  on  these  two  models  are 
combined and the list of recommended users is optimized by a work load constraint in order to involve 
greater part of the community into question answering. The results of experiment in the MOOC 
course deployed in EdX platform showed an increase in accuracy of question routing in comparison 
to the baseline question routing without educational-specific features. Therefore, we can conclude 
that  additional  features  specific  to  learning  environments,  help  in  predictions  of  new  question 
answerers. 
