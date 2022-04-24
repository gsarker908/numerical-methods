# NumericalMethods
This repository contains naive implementation of different numerical methods applied in linear algebraic equations, integration, ordinary differential equations etc. The following methods are implemented.

**For the Numerical Solution of Algebraic Aquations**
1. The Bisection Method
2. The False Position Method
3. The Newton Raphson Method
4. The Secant Method

**For the Numeric Solution of Linear System of Equations**
1. Matrix Inversion Method
2. Gauss Elimination Method
3. Gauss Jordan Method
4. Gauss Seidal Method

**For Numerical Integration**
1. Trapezoidal Rule
2. Simpson 1/3 formula
3. Simpson 3/8 formula

**To Find the Solution of Ordinary Differential Equations**
1. Euler's Method
2. Picard's Method
3. Runge-Kutta Method of Order 2
4. Runge-Kutta Method of Order 4

## Installation Step
1. Step-1: Download or clone this repository.
2. Step-2: Open MATLAB and change working directory to the downloaded directory
3. Step-3: Run NumericalMethods.m

## Usage Examples
Run the **NumericalMethods.m** file and when prompted write the method name to use in small letter.
**For the solution of algebraic equations**


| Method        | write           |
| ------------- |:-------------:  |
| Bisection     | 'bisection'     |
| False Position| 'false position'|
| Newton Raphson| 'newton raphson'|
| Secant        | 'secant'        |

for example, to find the real root of x^4-11x+8 = 0 near 2.0  using the Newton Raphson method, write newton raphson first to select it.
![alt text]("https://github.com/gcsarker/NumericalMethods/utility/images/newton_raphson_select.png" "Selecting Newton Raphson Method")
Next choose the value of necessary parameters prompted to find the solution as shown.
![alt text]("https://github.com/gcsarker/NumericalMethods/utility/images/newton_raphson_method.png" "Choosing parameters for Newton Raphson Method")
The final output consists of an iteration table and the solution value. 
![alt text]("https://github.com/gcsarker/NumericalMethods/utility/images/newton_raphson_output.png" "Solution")


