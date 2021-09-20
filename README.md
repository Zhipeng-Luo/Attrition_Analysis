# Attrition Analysis and Prediction

## Background

This is a team project we do for the course MADS591/592for the Master of Applied Data Science program in University of Michigan - Ann Arbor. 

**Team Member**
- Zhipeng Luo (brianluo@umich.edu)
- Chihshen Hsu (cshsu@umich.edu)
- Qi Zhang (qizhan@umich.edu)

Our team select the topic Attrition Analysis as the project of the course MADS591/592 - MileStone1. The reason we choose this topic is that attrition rate control and talent retention are always important parts of a company’s development strategy and one of the biggest challenges for the Human Resources (HR) department, especially under the “new normal” condition with COVID-19 impacting world widely. From the newest research from [McKinsey]( https://genesishrsolutions.com/peo-blog/types-of-employee-turnover/) published on September 8, 2021, the “Great Attrition” is happening and will probably continue.

In this project, we target to explore that employees voluntarily choose to leave which could be caused by poor work environment, unsatisfied pay, lack of advancement opportunities, long overtime, or even just the employee wanting to make some changes. 

In addition to exploring the correlations, we would like to design a model with the function to predict whether an employee would leave based on diverse independent variables and identify the key features. 


## Data Source

- The primary dataset is from Shared publicly in [Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset), which is a fictional data set created by IBM data scientists 4 years ago. Assuming the data was randomly extracted from IBM annual human resources data with desensitization treatment. 
- The secondary dataset is [Stack Overflow 2018 Developer Survey](https://www.kaggle.com/stackoverflow/stack-overflow-2018-developer-survey) data published on Kaggle 3 years ago. It provides extra features to support our exploration and analysis. 
 
## Conclusion

**Monthly income** and **overtime** can be regarded as the factors with top-level importance that relate to attrition. However, even being promoted in recently, someone may still choose to leave for better opportunities outside or other factors.  This is important from a learning perspective as it could be used by HR department to guide future talent retention strategy and policy.
- Monthly Income: people on higher wages are less likely to leave the company. Hence, efforts should be made to gather information on industry benchmarks in the current local market to determine if the company is providing competitive wages.
- Over Time: We don’t find clear evidence that over-time work triggers people to leave. From my point of view, there are two possibilities. If the employee takes serious about the free time and work-life balance, overtime is high likely resulting in attrition. In reverse, some employees may be possibly very interested in his job or has strong career ambitions, then overtime is not a problem. 
- Promotion: Without doubt, promotion opportunity and policy are vital for talent retention in general. But the whole talent retention strategy should be designed from multiple perspectives and dimensions, including talents’ career path, salary, working environment, management style, company culture, etc.

## Ethical Statement

The primary dataset for this analysis is fictional from IBM. Before referring to the findings to design any talent retention policy or strategy, we highly recommend to verify the results with real datasets. In addition, taking care of the applicable range and area of the conclusion to avoid biases, such as the limitation of country, industry, etc. Finally, the conclusion or prediction may relate to sensitive features, such as age and gender, which could possibly lead to discrimination. Before any algorithm applied for this task, the risks and possible damages should be systematically evaluated.




