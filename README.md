# Ridge Regression in Python
### Constrained Optimization Project

The aim of the project is to implement and solve in Python the constrained ridge regression model.

The data set we are going to use as an example is the death rate data set with 60 observations, where the death rate is represented as a function of 15 features as the nitric oxide pollution index, the hydrocarbon pollution index and so on.

In order to implement the constrained ridge regression model, we first need to find the formulae that define the objective function 𝑓(𝒘, 𝛾), the gradient of the objective function ∇𝑓(𝒘, 𝛾), the hessian of the objective function ∇ 3 𝑓(𝒘, 𝛾), the inequality constraint ℎ(𝒘), its gradient (the Jacobian) ∇ℎ(𝒘) and the hessian of the constraint ∇ 3 ℎ(𝒘). So, we are going to work step by step upon these functions.

