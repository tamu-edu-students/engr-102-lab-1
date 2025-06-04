# ENGR 102 LAB Topic 1

## Activities
**This is an individual assignment**, but you may consult your classmates and others as you work. You must submit your own code. Please complete the following activities. It is suggested that you test your code in an IDE on your own computer first to get the hang of things, then submit your working files to Gradescope. If you have trouble completing any of the activities, please ask a member of the Teaching Team for assistance, or check out the [Frequently Asked Questions](#frequently-asked-questions) below. **Please include the individual header in your ~.py files**. 

1. [Howdy World](#howdy-world)
2. [Print Math](#print-math)
3. [Follow Directions](#follow-directions)

## Howdy World
Write a program named `howdy_world.py` that outputs:
1. `Howdy, World!`
2. One sentence giving some interesting fact about yourself

Example output:
```
Howdy, World!
I code in python for fun.
```

## Print Math
The purpose of this activity is to familiarize you with [some basic engineering equations](https://zachry.tamu.edu/zachry-engineering-quad-equations/) and provide practice writing a simple Python program that performs calculations and displays results. For the equations below, write code that will display the numerical result of using the equation with the specified inputs. Remember to include comments in your code to describe what your code is doing.

Example: Let’s say we want to compute the area of a rectangle of length 5 inches and height 3 inches. The line of code below will print the numerical result.

Code:
```python
print(5 * 3)
```
Output:
```
15
```

If that is all we include in the code and in the output, it will be extremely difficult for someone to understand what the code does or to properly interpret the result. That someone may be the person grading your work, or may be you if you look back at this code in a few weeks!

Note: The code includes the line `print(5 * 3)` and not `print(15)`. We want to use a mathematical expression to compute the answer inside the parentheses. You’ll understand why when we reuse this code in a future lab assignment.

It’s good practice to use comments to document what your code is doing. You can also print out extra information to make the output more meaningful and easier to read.

New code:	
```python
# Calculate and print the area of a rectangle of
# length 5 in and height 3 in
print("Area of rectangle is", 5 * 3, "in^2")
```
New output:
```
Area of rectangle is 15 in^2
```

In the new version of the code, the first comment simply describes what the line of code below it does. It is not printed to the screen. Next, three separate items of information are printed to the screen using one `print()` statement:
1.	`"Area of rectangle is"` – a description of the output value
2.	`5 * 3` – the result of the mathematical operation
3.	`"in^2"` – another string that indicates the units

Notice that these three items are separated by commas in the `print()` statement and that the “strings” consist of text enclosed inside double quotation marks. By default, when print items are separated by a comma, a space is inserted between the items when printed. If someone looks at this code and the output, they should be able to tell what you are doing without having to ask too many questions.

Write a program named `print_math.py` to produce output for the following calculations:
1.	The **Reynolds Number (Re)** is an important dimensionless quantity in fluid mechanics that is used to predict flow patterns in different fluid flow situations. It is the ratio of inertial forces to viscous forces given by the equation<br/>
$$\text{Re}=\frac{uL}{ν}$$<br/>
Calculate the Reynolds number for a fluid with velocity ($$u$$) 9 m/s, kinematic viscosity ($$ν$$) 0.0015 m^2/s, and a characteristic linear dimension ($$L$$) of 0.875 m.
2.	Calculate the wavelength of x-rays scattering from a crystal lattice with a distance between crystal layers of 0.029 nm, scattering angle of 35 degrees, and first order diffraction. **Bragg’s Law** describes the scattering of waves from a crystal using the equation<br/>
$$nλ=2d\sin⁡θ$$<br/>
The standard unit of wavelength in the SI system is nanometers (nm).
3.	The **Arps equation** is a mathematical model to forecast future production rates of oil and gas wells. Use the equation below to calculate the production rate of a well after 10 days, if it had an initial production rate ($$q_i$$) of 100 barrels/day, an initial decline rate ($$D_i$$) of 2/day, and a hyperbolic constant ($$b$$) of 0.8.<br/>
$$q(t)=\frac{q_i}{(1+bD_i t)^{(1⁄b)}}$$
4.	The **Tsiolkovsky rocket equation** describes the motion of a device that can apply acceleration to itself by expelling part of its mass with high velocity. The equation relates the change of vehicle velocity to the exhaust velocity ($$v_e$$) and initial ($$m_0$$) and final ($$m_f$$) masses of the vehicle as<br/>
$$Δv=v_e\ln⁡\left( \frac{m_0}{m_f} \right)$$<br/>
Calculate the change of velocity of a fighter jet for an initial mass of 11000 kg, final mass of 8300 kg, and exhaust velocity of 2029 m/s.

Example output:
```
Reynolds number is 5250.0
Wavelength is 0.03326743330836067 nm
Production rate is 2.8969356500320727 barrels/day
Change of velocity is 571.4470689735155 m/s
```


## Follow Directions
The purpose of this activity is to get you used to Gradescope, and to learn to follow directions. You will encounter limits of functions in calculus and learn to work with them analytically. Writing this program will introduce how limits can be calculated numerically and provide additional practice creating computational Python programs.

Certain functions are difficult to evaluate at particular values, where infinity or division by zero are involved, but can be understood by evaluating them at a number of values that approach zero or infinity. You are to write a program that produces several evaluations for one function. You should perform these evaluations by creating a sequence of print statements that output the desired numbers.

Write a program named `follow_directions.py` that performs the following tasks for the function $$f(x)=(1-\cos⁡x)⁄x^2$$ evaluated close to $$x=0$$. Use values of $$x$$ ranging from 1.0 to 0.00000001 by moving the digit 1 over by one place from the previous value ($$x=1.0$$, $$x=0.1$$, $$x=0.01$$...).
1. First, print a line of text stating the purpose of the program
2. Next, print a line of text stating your guess for the final calculated value
	- There are no wrong answers, just make a guess
	- Think about the answer then see if your guess was close
3. Next, print out a sequence of 8 numbers, representing evaluating the function at 8 different values of $$x$$
4. Finally, print one blank line, followed by a statement of how good your guess is

As an example, for the equation $$f(x)=\tan⁡(x)/x$$ evaluated close to $$x=0$$, your output would look like what’s shown below. **Make sure your code evaluates $$f(x)=(1-\cos⁡x)⁄x^2$$**.

Example output (using $$f(x)=\tan⁡(x)/x$$):
```
This shows the evaluation of tan(x)/x evaluated close to x=0
My guess is 2
1.5574077246549023
1.0033467208545055
1.0000333346667207
1.0000003333334668
1.0000000033333334
1.0000000000333333
1.0000000000003333
1.0000000000000033

My guess was a little off
```

## Frequently Asked Questions
1. **Do I have to use the header in all of my ~.py files?** YES! This is to identify your files if we need to download them.

2. **Where do I submit my files?** Please submit your files to Gradescope. DO NOT submit files to Canvas; no one will see them and therefore will not be graded. If you're having trouble figuring out how to use Gradescope, please ask your instructor or a PT during class for help.

3. **Can I submit my labs more than once?** YES! In fact, [I highly encourage you to submit your files many times](https://www.youtube.com/watch?v=GQtcWPjgwGc). Each time you submit, check the test cases to see what you missed, fix your code, and submit again. There is no penalty for multiple submissions. I have had several students in the past submit ~100 times for one assignment!

4. **I tested my code on my computer and it works, but when I submit to Gradescope it's wrong. What gives?** Make sure your output matches EXACTLY with the example output. Not just the numbers, but also the text. Check your spelling, capitalization, punctuation, and spacing.

5. **Print math part 2 I keep getting the wrong answer.** Remember, trig functions use angles in radians, not degrees. 180 degrees is equal to pi radians.

6. **Follow directions does my guess have to be good?** No! As long as you guess something the autograder will accept it. If you're struggling to pass this test, go back and read the instructions again. Make sure to follow every step, especially the last one!

7. **Can I use `import math` instead of `from math import *`?** We're going to talk about different ways to import math functions later in the semester. It's fine to use `import math`, but remember that all of your function calls need to start with `math.<function>`. Example: `math.cos(math.pi)`

8. **I'm stuck!** Don't worry, you're not alone! First, follow the lab instructions. Don't skip a step! This is a good time to review the example problems in the lecture and practice what we talked about. And if you're still stuck, ask a question in class or visit your instructor or the PTs during office hours.

Have a question you don't see here? Email your instructor!


Based upon Dr. Keyser’s Original<br/>
Revised Summer 2025 SNR
