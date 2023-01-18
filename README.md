# Univariate-Linear-Regression

## Problem statement
Linear Regression is implemented to identify the relationship between profit of a bike sharing company and population of different cities. The main objective is to find the next city in which a new outlet should be opened which results in optimal profitability.

## Data visualization
![data_plot](https://user-images.githubusercontent.com/94393300/213113588-0b01415b-ccae-4afe-9d04-ba27e34da0ad.png)

## Implementation
- Application of the cost function as shown below: <br>
![cost_function_formula](https://user-images.githubusercontent.com/94393300/213114352-73d176d7-c226-4a97-b8b1-0743f3a13225.png) <br>

- Visualization of the cost function by plotting the cost over a 2-dimensional grid of 𝜃_0 and 𝜃_1 values. The cost function J(𝜃) is bowl-shaped and has a global minimum <br>
![cost_function_3D](https://user-images.githubusercontent.com/94393300/213116669-b1053fb3-ca36-4951-a106-f6b79b4493d2.png) <br>

- Implementation of gradient descent algorithm from scratch in Python without the use of machine learning frameworks such as scikit-learn and statsmodels. Ran the algorithm over 2000 iterations to minimize the cost J(θ). With each step of batch gradient descent, the parameters 𝜃_j come closer to the optimal values that will achieve the lowest cost J(𝜃). The plot of convergence is shown below.<br>
![gradient_descent](https://user-images.githubusercontent.com/94393300/213116054-f6077d65-cbef-4c46-8184-51a1f258056a.png) <br>

## Results
### Univariate Linear Regression Fit
![line_of_bestfit](https://user-images.githubusercontent.com/94393300/213117552-be12983c-e0aa-4e90-ba08-a169f361f016.png)

## Libraries used

## References
