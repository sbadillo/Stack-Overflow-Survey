# Stack-Overflow-Survey

A rather quick insight into the results of Stack Overflow's annual surveys for 2019 and 2020. 

We use this exemple to go throught the basic stages of analysis 

* Prepare data:
    * Gather necessary data to answer your questions
    * Handle categorical and missing data
    * Provide insight into the methods you chose and why you chose them

* Analyze, Model, and Visualize
    * Provide a clear connection between your business questions and how the data answers them.

Following the CRISP-DM process, we define and adress three simple questions

1. What's does the distribution of developper jobs looks like ?  
2. How is country of residence related to job satisfaction or salary ?
3. Which job types or fields are better paid ?

Insights are then published in [this article](https://sbadillow.medium.com/what-developers-are-doing-earning-worldwide-e317a4117c1e). 

## The CRISP-DM Process (Cross Industry Process for Data Mining).
* Business Understanding. Understand the problem. The question.
* Data Understanding. What do I need to answer my question. This might be a hard question to answer which is why companies tend to collect all data they can and then try to find the answer.
* Data Preparation. Gathering and Wrangling the data. The Wrangling proces is the most time consuming. Many DS problems can be answered just at this stage by using simple data exploration and inference and does not require any fancy modelling.
* Modelling.
* Evaluation.



## Files :
- datasets/oecd_avgwages2019.csv and oecd_avgwages2019.csv : both average and minimum wages for OECD countries. Collected from reported values, and updated in 2020. 
- datasets/stackoverflow/* : contains Stack Overflow's public data results and schemas for 2017 to 2020. More information can be found [here](https://insights.stackoverflow.com/survey).
- charts*.png : images used in in the communication.
- README.md
- Stack Overflow 2017 Survey 18-20.ipynb : analytical run.