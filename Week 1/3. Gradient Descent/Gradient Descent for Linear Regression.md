## Linear Regression Model
> Hypothesis(line/slope to fit the data): ![hypothesis function](https://latex.codecogs.com/gif.latex?h_%7B%5Ctheta%7D%28x%29%20%3D%20%5Ctheta_%7B0%7D%20&plus;%20%5Ctheta_%7B1%7Dx)
>
> Cost Function(which is to be minimized to get the local optimum so as to get the highest accuracy): ![cost function for Linear Regression](https://latex.codecogs.com/gif.latex?J%28%5Ctheta_%7B0%7D%2C%20%5Ctheta_%7B1%7D%29%20%3D%20%5Cfrac%7B1%7D%7B2m%7D%5Csum_%7Bi%3D1%7D%5E%7Bm%7D%28h_%7B%5Ctheta%7D%28x%5E%7B%28i%29%7D-y%5E%7B%28i%29%7D%29%29%5E%7B2%7D)

## Gradient Descent Algorithm

>repeat_until_convergence {
    ![gradient descent algorithm](https://latex.codecogs.com/gif.latex?%5Ctheta_%7Bj%7D%20%3A%3D%20%5Ctheta_%7Bj%7D%20-%20%5Calpha%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%5Ctheta_%7Bj%7D%7DJ%28%5Ctheta_%7B0%7D%2C%20%5Ctheta_%7B1%7D%29) (for j = 0 and j = 1)

> Substitute the cost function into the gradient descent algorithm.
>
> The reason we can use this gradient descent on the linear regression model is, the gradient descent gives you the local optimum of the cost function 3D graph. ![cost function 3D graph](https://miro.medium.com/max/1406/1*t4aYsxpCqz2eymJ4zkUS9Q.png) However, the cost function of Linear Regression has only one optimum. That is, the local optimum and the global optimum are the same. ![cost function 3D graph](https://miro.medium.com/max/1460/1*JNOVaxLlNZk-4KyEKQsrQA.png))

## Batch Gradient Descent

> We are training our algorithm on all examples (represented by m) in the training set. Hence we are using Batch Gradient Set.