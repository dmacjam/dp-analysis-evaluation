# Recommendation of New Questions in Online Student Communities
## Master's thesis
- Author:     Jakub Mačina
- University: Slovak University of Technology in Bratislava
- Degree Course:    Information Systems
- Supervisor:    Ivan Srba, PhD. 

## Data
Data are from [Askalot CQA system](https://github.com/AskalotCQA/askalot) used in [QuCryptox Quantum cryptography](https://courses.edx.org/courses/course-v1:CaltechDelftX+QuCryptox+3T2016) 
MOOC course offered by *California Institute of Technology* and *Delft University of Technology*.

## Source code
Available in branch [question-routing-mooc-feature in Askalot CQA system](https://github.com/AskalotCQA/askalot/compare/question-routing-mooc-feature).

## Files
- [Online Evaluation.ipynb](Online%20Evaluation.ipynb) - Evaluation of online A/B experiment.
- [question-routing-evaluation.ipynb](question-routing-evaluation.ipynb) - Feature selection, evaluation of recommendation and classifier performance

## Setup
1. Checkout [Askalot branch MOOC question routing](https://github.com/AskalotCQA/askalot/tree/question-routing-mooc-feature)
2. Install python requirements. 
`pip install -r requirements.txt`
3. Import data (please, contact me for an access to anonymized backup of the database.) 
`pg_restore -d askalot_edx_development < askalot_anonymized.backup` 

## Abstract
Student’s performance in Massive Open Online Courses (MOOCs) is enhanced by participation in discussion forums or recently emerging Community Question Answering (CQA) systems. Nevertheless, the problem is low engagement of students in question answering which leads to many unanswered questions in discussion tools.

The goal of the master’s thesis is to propose a new approach for a routing of new questions for CQA systems employed in educational settings. Existing approaches for question routing recommends new questions only to a few experts, which is not suitable in MOOCs because participation in discussions positively influences student’s learning outcomes. We proposed a novel approach for question routing which models along user’s expertise for a given question also user’s willingness to answer a question. The predictions based on these two models are combined and the list of recommended users is optimized by a workload constraint. Furthermore, we incorporated non-QA data from the course for user modelling, such as student’s grades and activity in the course, which help in routing new questions to greater part of the student community.

The proposed question routing approach was fine-tuned and evaluated by the offline experiment and the online experiment which measured total impact on the student community. Online experiment was conducted using A/B test in CQA system used by a course at the EdX platform. The proposed question routing method outperformed a baseline question routing method commonly used on the open Web by 4.96% in click-through rate and by 5.30% in S@10.
