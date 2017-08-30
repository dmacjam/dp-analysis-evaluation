# Educational Question Routing in Online Student Communities
Evaluation for paper accepted at RecSys 2017 - http://dl.acm.org/citation.cfm?id=3109886

- Author:     Jakub Mačina
- University: Slovak University of Technology in Bratislava
- Advisor:    Ivan Srba, PhD. 

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

