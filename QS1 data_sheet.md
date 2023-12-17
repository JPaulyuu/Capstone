# Datasheet Template

As far as you can, complete the model datasheet. If you have got the data from the internet, you may not have all the information you need, but make sure you include all the information you do have. 

*

## Motivation

- For what purpose was the dataset created? 
- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?


*Motivation
Purpose: The dataset was created for the purpose of optimizing mathematical functions using Bayesian optimization techniques. This involves finding the minimum values of complex, often non-linear functions—a common task in machine learning and data science for hyperparameter tuning.
Creators and Funding: IMPERIAL BUSINESS SCHOOL



 
## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 
- How many instances of each type are there? 
- Is there any missing data?
- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by    doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?


*
Instance Representation: Each instance in the dataset represents a set of input variables (parameters) and their corresponding output from the mathematical function being optimized.
Instance Count: The number of instances varies based on the number of function evaluations conducted during each optimization run. It's dynamically generated and can change with each experiment.
Missing Data: There is no missing data in the traditional sense since each instance is a complete set of input-output pairs.

Data Sensitivity:Data Does contain Private or confidential information





## Collection process

- How was the data acquired? 
- If the data is a sample of a larger subset, what was the sampling strategy? 
- Over what time frame was the data collected?

*
Collection Process
Data Acquisition: The data was acquired through function evaluations during the optimization process. Each input set (parameters) was fed into the function, and the corresponding output was recorded.
Sampling Strategy: The sampling was not random but based on the Bayesian optimization algorithm's strategy, which chooses points based on 
prior evaluations to efficiently explore the function space.
Time Frame: The data was collected over the duration of the optimization process, which varies depending on the various experiment's settings.



## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 
- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 

*Preprocessing/Cleaning/Labelling
Preprocessing: No traditional preprocessing, cleaning, or labeling was required since the data is generated and used in numerical form.

Other Uses: Apart from optimization, the dataset can be useful for studying and testing other mathematical or computational models, especially those related to numerical analysis and machine learning algorithms.


 
## Uses

- What other tasks could the dataset be used for? 
- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 
- Are there tasks for which the dataset should not be used? If so, please provide a description.

*
Alternate Uses: Apart from optimization, the dataset can be useful for studying and testing other mathematical or computational models, especially those related to numerical analysis and machine learning algorithms.

Inappropriate Uses: The dataset is not suitable for social, economic, or human-centered analyses since it lacks training on various real-world data.

## Distribution

- How has the dataset already been distributed? 
- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?  

*Distribution
The dataset has not been formally distributed as it is generated uniquely for each experiment.
IP and ToU: The dataset is not subject to copyright or IP license due to its being a mix of various and widely used codebases algorithmic and experimental in  nature. It's also generated independently by the optimization software on the respective computing platform (juputer notebook/lab).

## Maintenance

- Who maintains the dataset?


*
Maintenance Responsibility:The responsibility would lie with the individual or team conducting the optimization if retention is needed (ME IN THIS CASE).

