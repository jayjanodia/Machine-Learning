## Cost Function
- Will help us figure out how to fit the best possible straight line to our data.

> Hypothesis h(x) = theta_0 + theta_1*x
>
>theta_0 and theta_1 are the parameters of the model.
>
>We choose theta_0 and theta_1 so that the hypothesis h(x) is close to y for our training examples(x,y)
>To do this we would need to minimize theta_0 and theta_1, so that h(x) - y is small. To get more accurate results, we need ![(h(x) - y)^2](https://latex.codecogs.com/gif.latex?%28h%28x%29%20-%20y%29%5E2) to be small. You will need to use this equation for each training example in the data set. So we get: ![sum(h(x) - y)^2](https://latex.codecogs.com/gif.latex?%5Csum_%7B1%7D%5E%7Bm%7D%28h%28x%29%20-%20y%29%5E2)
>Andrew Ng in his video has decided to reduce the sum of differences even further by dividing the above equation by 2m. So we have the equation as:
> ![1/2m(sum(h(x) - y)^2)](https://latex.codecogs.com/gif.latex?%5Cfrac%7B1%7D%7B2m%7D%5Csum_%7B1%7D%5E%7Bm%7D%28h%28x%29%20-%20y%29%5E2)
>
>So finally, the cost function is: ![Cost Function](https://latex.codecogs.com/gif.latex?J%28%5CO%20_%7B0%7D%2C%20%5CO_%7B1%7D%29%3D%5Cfrac%7B1%7D%7B2m%7D%5Csum_%7Bi%3D1%7D%5E%7Bm%7D%28h%28x%5Ei%29%20-%20y%5Ei%29%5E2)
>
> We need to minimize this cost function
> This cost function is also called as the squared error function.
> This cost function is the most commonly used function used for regression problems 