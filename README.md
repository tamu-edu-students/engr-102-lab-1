# ENGR 102 LAB Topic 1

## Activities
This is an individual assignment, but you may consult your classmates and others as you work. You must submit your own code. Please complete the following activities. It is suggested that you test your code in VS Code first to get the hang of things, then submit your working files to Gradescope. If you have trouble completing any of the activities, please ask a member of the Teaching Team for assistance.

* [Howdy World](#howdy-world)
* [Print Math](#print-math)
* [Follow Directions](#follow-directions)

## Howdy World - individual
Write a program named howdy_world.py that outputs:
A)	Howdy, World!
B)	One sentence giving some interesting fact about yourself

Example output:
Howdy, World!
I code in python for fun.

## Print Math - individual
The purpose of this activity is to familiarize you with [some basic engineering equations](https://zachry.tamu.edu/zachry-engineering-quad-equations/) and provide practice writing a simple Python program that performs calculations and displays results. For the equations below, write code that will display the numerical result of using the equation with the specified inputs. Remember to include comments in your code to describe what your code is doing.

Example: Let’s say we want to compute the area of a rectangle of length 5 inches and height 3 inches. The line of code below will print the numerical result.

Code: 		print(5 * 3)
Output: 	15

If that is all we include in the code and in the output, it will be extremely difficult for someone to understand what the code does or to properly interpret the result. That someone may be the person grading your work, or may be you if you look back at this code in a few weeks!

Note: The code includes the line print(5 * 3) and not print(15). We want to use a mathematical expression to compute the answer inside the parentheses. You’ll understand why when we reuse this code in a future lab assignment.

It’s good practice to use comments to document what your code is doing. You can also print out extra information to make the output more meaningful and easier to read.

New code:	# Calculate and print the area of a rectangle of 
# length 5 in and height 3 in
print("Area of rectangle is", 5 * 3, "in^2")
New output:	Area of rectangle is 15 in^2

In the new version of the code, the first comment simply describes what the line of code below it does. It is not printed to the screen. Next, three separate items of information are printed to the screen using one print() statement:
1.	"Area of rectangle is" – a description of the output value
2.	5 * 3 – the result of the mathematical operation
3.	"in^2" – another string that indicates the units

Notice that these three items are separated by commas in the print() statement and that the “strings” consist of text enclosed inside double quotation marks. By default, when print items are separated by a comma, a space is inserted between the items when printed. If someone looks at this code and the output, they should be able to tell what you are doing without having to ask too many questions.

Write a program named print_math.py to produce output for the following calculations:
*	The Reynolds Number (Re) is an important dimensionless quantity in fluid mechanics that is used to predict flow patterns in different fluid flow situations. It is the ratio of inertial forces to viscous forces given by the equation
Re=uL/ν
Calculate the Reynolds number for a fluid with velocity (u) 9 m/s, kinematic viscosity (ν) 0.0015 m^2/s, and a characteristic linear dimension (L) of 0.875 m.
*	Calculate the wavelength of x-rays scattering from a crystal lattice with a distance between crystal layers of 0.028 nm, scattering angle of 35 degrees, and first order diffraction. Bragg’s Law describes the scattering of waves from a crystal using the equation
nλ=2d sin⁡θ
The standard unit of wavelength in the SI system is nanometers (nm).
*	The Arps equation is a mathematical model to forecast future production rates of oil and gas wells. Use the equation below to calculate the production rate of a well after 10 days, if it had an initial production rate (q_i) of 100 barrels/day, an initial decline rate (D_i) of 2/day, and a hyperbolic constant (b) of 0.8.
q(t)=q_i/(1+bD_i t)^(1⁄b) 
*	The Tsiolkovsky rocket equation describes the motion of a device that can apply acceleration to itself by expelling part of its mass with high velocity. The equation relates the change of vehicle velocity to the exhaust velocity (v_e) and initial (m_0) and final (m_f) masses of the vehicle as
Δv=v_e  ln⁡(m_0/m_f )
Calculate the change of velocity of a fighter jet for an initial mass of 11000 kg, final mass of 8300 kg, and exhaust velocity of 2028 m/s.

Example output:
Reynolds number is 5250.0
Wavelength is 0.03212028043565858 nm
Production rate is 2.8969356500320727 barrels/day
Change of velocity is 571.1654292155197 m/s


## Follow Directions
*describe follow directions*

Based upon Dr. Keyser’s Original
Revised Summer 2025 SNR
