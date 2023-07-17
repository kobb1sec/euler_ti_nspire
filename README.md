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
The usage of the code is a bit different from what we can do on calculator. For example, to put $\sqrt{x}$ we press `ctrl` + $x^2$. In this code we cannot use it as it does not recognise the expressions from built-in functions from TI-Nspire. Hence, there is a question, how to input complex functions such as $e^x$? 

The asnwer is __we can still do it!__ by using `math` library. `Math` library is very useful but it is a bit difficult to use for the first time but practice is a very good friend! It uses [LaTeX](https://en.wikibooks.org/wiki/LaTeX/Mathematics) notations.

#### Running the code
1. Turn on calculator and press `2` to `Browse` ![image1](https://github.com/kobb1sec/euler_ti_nspire/assets/65459136/cd59cc0b-f570-45d5-afda-7f9d9fd08e1f)
2. Find `Euler's Method_Spesh` by pressing `Enter` ![image2](https://github.com/kobb1sec/euler_ti_nspire/assets/65459136/84a6a421-209d-4ded-8819-5ef928d8be3e)
3. You will the exaxt the same screen as I do. __DO NOT EDIT THE CODE UNLESS YOU ENSURE WHAT YOU ARE DOING!__ ![image3](https://github.com/kobb1sec/euler_ti_nspire/assets/65459136/a797e9aa-6ed6-445c-9901-1f14fca3a8fb)
4. To run the code, press `ctrl + R`. It will open the next page in the same file and you will see that thing: ![image4](https://github.com/kobb1sec/euler_ti_nspire/assets/65459136/01616e62-3777-4723-8cf4-f9f76a87a185)
5. Enter the following:
   * Initial $x$ value
   * Initial $y$ value
   * Step size
   * Number of steps
   * Differential equation in [LaTeX](https://en.wikibooks.org/wiki/LaTeX/Mathematics) notation
6. Then, you will see the magic with something like this: ![image5](https://github.com/kobb1sec/euler_ti_nspire/assets/65459136/0b474bea-e5e6-433f-8d5a-2d1ea2c2918d)




