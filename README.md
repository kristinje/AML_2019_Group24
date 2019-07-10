# AML_2019_Group24
-----------

## Introduction
The coursework is about gradient descent, where we chose a loss function and experimented to find the global minima. The goal of this task was to find the deepest point in the valley in the chosen function. We used plain vanilla gradient descent which is the simplest form of gradient descent. The vanilla gradient descent takes small steps in the direction of the gradient. 

Gradient descent is an optimization algorithm used to minimize some function by iteratively moving in the direction of the steepest descent as defined by the negative of the gradient. (ML Cheats cite)
It is used specifically in machine learning as it helps to identify the most suited parameters which would give the minimal cost in that specific model.


## Part 1
Chose the Matya function that works with two variables.  

Matya Function looks like this:
f(x, y)=0.26(x^2+y^2) -0.48xy

With a global minimum at:
f(x*) = 0 at x*(0,0)

## Part 2

Vanilla gradient descent is the simplest form of gradient descent. Its main feature is that we take small steps in the direction of the gradient. It basically calculates the error for each sample in the data and updates the model only after the training example has been calculated. Advantage of vanilla gradient descent is that it is computationally efficient.

When using vanilla gradient descent we found that bigger step sizes did not hit the local minima, the steps were too big. When experimenting with smaller step sizes, too small steps did not hit the global minima either.

<img width="471" alt="Screen Shot 2019-07-10 at 15 33 20" src="https://user-images.githubusercontent.com/52716291/60977887-1baf3f80-a328-11e9-9844-fd85bcfef615.png">

Results of plain vanilla gradient descent.

## Part 3
Experimented with two variants of gradient descent: Nag and Momentum. From the results, the two variants are not hitting the local minima. On the other hand, the vanilla gradient descent is hitting the local minima, showing that this one works better. 

<img width="432" alt="Screen Shot 2019-07-10 at 15 30 02" src="https://user-images.githubusercontent.com/52716291/60977760-edc9fb00-a327-11e9-919e-4b16b7d8d10c.png">

Results of two variants of gradiant descent: Blue line is plain vanilla, while red line is Nag and Momentum.


