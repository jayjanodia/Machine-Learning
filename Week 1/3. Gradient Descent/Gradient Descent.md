>Used for minimizing the cost function J or other functions
1. Start of with some value for theta_0 and theta_1. Can be anything, for example you can initialize both of them to 0.
2. Manually keep changing the values of theta_0 and theta_1 till you reach the minimum cost function.
3. If you draw the 3D graph for the cost function as illustrated ![gradient descent contour plot for cost function](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/bn9SyaDIEeav5QpTGIv-Pg_0d06dca3d225f3de8b5a4a7e92254153_Screenshot-2016-11-01-23.48.26.png?expiry=1608768000000&hmac=PQG7jEgjXst2J8o6fnEmazlZd-MgH3W6LxQmNxnoVCg) you will finally reach the local optimum, by changing the value of theta_0 and theta_1 at every step.

## Equation
>repeat_until_convergence {
    ![gradient descent algorithm](https://latex.codecogs.com/gif.latex?%5Ctheta_%7Bj%7D%20%3A%3D%20%5Ctheta_%7Bj%7D%20-%20%5Calpha%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%5Ctheta_%7Bj%7D%7DJ%28%5Ctheta_%7B0%7D%2C%20%5Ctheta_%7B1%7D%29) (for j = 0 and j = 1)
}
>
>:= is the assignment operator
>
>alpha is the learning rate. If the learning rate is high, we are taking huge steps while going downhill. If the learning rate is low, we are taking baby steps to go downhill. There's no need to keep changing the learning rate, we can keep it constant, since the derivative becomes smaller each time 
>
>the derivative is of the cost function of theta_0 and theta_1. When we reach the local optimum the derivative should become minimum, that is close to 0, or 0 itself.
