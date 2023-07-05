# Euler's Method on Pyhton for TI-Nspire CAS

## Preface

Euler's Method is not envolving into Specialist Mathematics and plus it is not the very consice method to use to determine the unknown shape of the actual equation and the value of $y$, but it is essential to understand the concept as on [VCAA](https://www.vcaa.vic.edu.au/curriculum/vce/vce-study-designs/specialistmathematics/Pages/Index.aspx) Exam 1 and/or Exam 2 they can ask quetions relating to that method.

TI-Nspire CX II has an ultimate but, unfortunately, limited feature - Programming in Python. It is **the best** solution that they can put because it makes easier to do many tasks, especially those that in Mathematical Methods and Specialist Mathematics. In addition to that, it is a good way to practice your skills in Python and get maximum from provided [modules](https://education.ti.com/en/activities/ti-codes/python/ti-nspire-cx-ii/python-modules). 

## Features

Along side that this will do the basic and the only method - determining $$y_{n+1} = y_{n} + h * f'(x_{n})$$ where:
* $y_{n+1}$ is your next value with $n +1$. For example, if $n = 1$, you will determine the value of $y_{2}$ based on the information of $x_{1}$ and $y_{1}$. It is also a "future $y$ value".
* $y_{n}$ is your value of $y$. It is "previous $y$ value".
* $h$ is your step size. Basically, you will be asked to find this value or you will be told what is the step size of determination.
* $f'(x_{n})$ is your differential equation with the value of $f'(x)$ from $x_{n}$. Hence, you sub $x_{n}$ into differential equation to determine the value of $f'(x)$ based on $x_{n}$ value.

  
There are also features, such as:
* _User Friendly Interface_ (unfortunately, not GUI as TI-Nspire does not support external libs)
* _Math Module Support_ for more advanced expressions (such as exponentioal: $e^x$, trignometric: $cos(x)$ and logarithmics: $log_{e} x$)
* _Very simple to run_
* _Tablau form of output_ with also gaps between each value ($step$, $x$, $y$ and Equation Value)

## How to install - Three Easy Steps:
1. Download `.tns` file to your computer
2. Go to [Connect](https://nspireconnect.ti.com/nsc/). Follow the instructions to connect calculator to the website
3. Click on `Transfer Files` and select the file from the computer to the device. Once it is done, the pop-up message will be displayed on your calculator. __Enjoy!__

## How to use the Python code:

