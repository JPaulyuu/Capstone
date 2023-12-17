# Model Card

See the [example Google model cards](https://modelcards.withgoogle.com/model-reports) for inspiration. 

## Model Description

**Input:** Describe the inputs of your model 
Input
The inputs of the model are parameter sets for the function being optimized. These parameters are numerical values within a defined range, dynamically adjusted based on the optimization process.


**Output:** Describe the output(s) of your model

Output
The output is the evaluation result of the function for the given set of parameters. It's a numerical value representing the function's performance at those specific parameters, with the objective typically being to minimize this value.

**Model Architecture:** Describe the model architecture you’ve used
Model Architecture
The model architecture is based on Bayesian Optimization. It utilizes Gaussian Process Regression (GPR) as its primary method, with various kernels (e.g., Matern, RBF, RationalQuadratic) to model the function landscape. The optimization process involves iteratively selecting new parameters to evaluate based on prior results, aiming to efficiently find the function's minimum.


## Performance

Give a summary graph or metrics of how the model performs. Remember to include how you are measuring the performance and what data you analysed it on. 

Performance
Metric Used: The primary metric for evaluating the model's performance is the minimum value of the function achieved during optimization.
Performance Summary: The model generally showed improvement in finding lower minimum values with each successive run, indicating effective learning and adaptation. The performance was assessed by comparing the minimum values obtained in each optimization run.
Data Analyzed: The data analyzed consists of sets of parameters and their corresponding function evaluations across multiple runs.
Performance Graph


## Limitations

Outline the limitations of your model.

Limitations
Model Specificity: My model is tailored for numerical optimization and might not generalize well to other types of data or problems.
Computational Resources: My model can be computationally intensive, especially with complex functions and large parameter spaces.
Local Minima: There's a risk of converging to local minima, especially in highly irregular or multimodal function landscapes, which lead to a few problems such as the long duration of runtime.

## Trade-offs

Outline any trade-offs of your model, such as any circumstances where the model exhibits performance issues. 

Trade-offs
Exploration vs. Exploitation: The model needs to balance exploring new areas of the parameter space and exploiting known promising areas. Too much exploration can lead to inefficiency, while too much exploitation can miss better solutions.
Complexity vs. Comprehension: As the model evolved, it became more complex, which improved performance but also made it harder to intuitively understand the function landscape and the model's decision-making process.
Performance vs. Time: Increasing the number of function calls and the complexity of the model generally improved performance but also increased the time required for each optimization run.




