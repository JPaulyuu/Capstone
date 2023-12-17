# Capstone 101 


## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
100 words to explain what your project is about to a general audience. 

My project involves optimizing complex mathematical functions using a sophisticated technique called Bayesian optimization. Imagine trying to find the lowest point in a landscape filled with hills and valleys without seeing the entire terrain. Bayesian optimization helps predict these low points by smartly choosing which areas to explore based on previous findings. It's like a treasure hunt where each clue makes the next step smarter and more focused. This technique is widely used in various fields like machine learning to fine-tune models for better performance.

## DATA
A summary of the data you’re using, remembering to include where you got it and any relevant citations. 

The data for this project comprises input-output pairs from mathematical functions, essentially a set of points where each input (a combination of variables) corresponds to an output (the function's value at that point). This data wasn't pulled from a conventional database but was generated as part of the optimization process. Each function represents a different optimization challenge, with the outputs illustrating the "landscape" the algorithm explores. The goal is to find inputs that lead to the lowest outputs (the valleys in our landscape analogy).

## MODEL 
A summary of the model you’re using and why you chose it. 

The model I used is a Gaussian Process Regression (GPR) within the Bayesian optimization framework. GPR is adept at predicting complex, nonlinear patterns, which is crucial in understanding and navigating the multifaceted landscapes of our functions. I chose this model for its flexibility and ability to incorporate uncertainty in its predictions, making it ideal for optimization tasks where exploration is key. It's like having an intelligent guide that not only suggests the next step but also considers how confident we are about the unseen territory.

## HYPERPARAMETER OPTIMSATION
Description of which hyperparameters you have and how you chose to optimise them. 

HYPER PARAMETER OPTIMIZATION
Hyper parameters in my context include the choice and configuration of kernels for GPR, the bounds of the search space, the number of function calls, and random starts. Kernels like Matern, RBF, and Rational Quadratic were tuned to capture different aspects of the data's complexity. The search space bounds and the number of function calls were adjusted, based on the performance in previous runs. This dynamic optimization helped me in refining the model's focus and efficiency progressively.


## RESULTS
A summary of your results and what you can learn from your model 

The results showed a gradual improvement in identifying the optimal points of the functions. Through iterative adjustments and increasing model sophistication, the predictions became more accurate, guiding the optimization process more effectively. The evolving strategy, from a basic setup to a more complex and adaptive one, demonstrated the importance of understanding both the model and the problem. These results are a testament to the power of Bayesian optimization in navigating complex spaces and the value of iterative learning and adaptation in model tuning.

You can include images of plots using the code below:
![Screenshot](image.png)

## (OPTIONAL: CONTACT DETAILS)
If you are planning on making your github repo public you may wish to include some contact information such as a link to your twitter or an email address. 
