# Imperial-ML-AI-Capstone-BBO

## :gear: Imperial's professional certificate in machine learning and artificial intelligence black box optimisation capstone project. :gear: ##

This project consists of eight black box functions of growing dimensionality that mirror real-world style ML challenges. This project requires the optimisation of unkown functions using limited information reflecting a Bayesian optimisation style challenge. 

The gaol is to find the maximum of eight unknown functions by:

- Submitting a query each week using Bayesian optimisation strategies to determine which point to explore next
- Review the resulting output each week and make informed decisions around exploration, exploitation and strategy to select the next point to update the function
- Continue to employ new techniques and consider week on week how to improve optimisation with the limited data available.

##  :rocket: Data :rocket:

There are eight functions to explore, representing real-world scenarios such as drug discovery, radiation detection or manufacturing requirements which are expensive to explore or have limited data to work with. 

Each function is described below:

### :oil_drum: Function 1:
Detect likely contamination sources in a two-dimensional area, such as a radiation field, where only proximity yields a non-zero reading. The system uses Bayesian optimisation to tune detection parameters and reliably identify both strong and weak sources.

### :dart: Function 2: 
Imagine a black box, or a mystery ML model, that takes two numbers as input and returns a log-likelihood score. Your goal is to maximise that score, but each output is noisy, and depending on where you start, you might get stuck in a local optimum. 

### :pill: Function 3: 
You’re working on a drug discovery project, testing combinations of three compounds to create a new medicine. Your goal is to minimise side effects.

### :robot: Function 4: 
Address the challenge of optimally placing products across warehouses for a business with high online sales, where accurate calculations are costly and only feasible biweekly. To speed up decision-making, an ML model approximates these results within hours. The model has four hyperparameters to tune, and its output reflects the difference from the expensive baseline. 

### :test_tube: Function 5: 
You’re tasked with optimising a four-variable black-box function that represents the yield of a chemical process in a factory. The function is typically unimodal, with a single peak where yield is maximised. Your goal is to find the optimal combination of chemical inputs that delivers the highest possible yield, using systematic exploration and optimisation methods.

### :cake: Function 6: 
You’re optimising a cake recipe using a black-box function with five ingredient inputs, for example flour, sugar, eggs, butter and milk. Each recipe is evaluated with a combined score based on flavour, consistency, calories, waste and cost, where each factor contributes negative points as judged by an expert taster. This means the total score is negative by design. 

### :white_circle: Function 7: 
You’re tasked with optimising an ML model by tuning six hyperparameters, for example learning rate, regularisation strength or number of hidden layers. The function you’re maximising is the model’s performance score (such as accuracy or F1), but since the relationship between inputs and output isn’t known, it’s treated as a black-box function. 

### :signal_strength: Function 8: 
You’re optimising an eight-dimensional black-box function, where each of the eight input parameters affects the output, but the internal mechanics are unknown. Your objective is to find the parameter combination that maximises the function’s output, such as performance, efficiency or validation accuracy. Because the function is high-dimensional and likely complex, global optimisation is hard, so identifying strong local maxima is often a practical strategy.


## Model

## Hyperparameter optimisation

## Results
![Screenshot](image.png)


## Contact details
