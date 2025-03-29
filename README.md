# ASSIGNMENT -3
## TASK 1-CALCULATE FACTORIAL USING FUNCTION
<b>DESCRIPTION</b>:The following python programme calculates the factorial of a number(using function) ansd then prints the result accordingly.

<b>STEP 1-DEFINING THE FUNCTION:</b><br>
In the first step we define the function name that is <b>def factorial(n)</b> that is it takes <b>'n'</b> as input and would return its factorial.<br>

<b>STEP 2-BASE CASE:</b><br>
If <b>'n'</b> is less than 2(that is either 0 or 1) then it should return us 1 <b>(0!=1!=1)</b><br>

<b>STEP 3-RECURSIVE CASE:</b><br>
If <b></b>n>=2</b>, then it should call the function with <b>(n-1)</b> and the function is calaculated with <b>n*factorial(n-1).</b><br>

<b>STEP 4-CALLING THE FUNCTION:</b><br>
The function is called with <b>num=7</b> which is our sample number which calculate its factorial.

<b>STEP 5-PRINTING THE RESULT:</b><br>
Now the the computed factorial gets printed.<br>

<b>HOW THE RECURSION WORKS:</b><br>
Factorial of 7 is calculated as:<br>
7!=7×6×5×4×3×2×1<br>
Now,<br>
factorial(7) = 7 * factorial(6)<br>
factorial(6) = 6 * factorial(5)<br>
factorial(5) = 5 * factorial(4)<br>
factorial(4) = 4 * factorial(3)<br>
factorial(3) = 3 * factorial(2)<br>
factorial(2) = 2 * factorial(1)<br>
factorial(1) = 1  (Base case)<br>

Now returning values:<br>
factorial(2) = 2 * 1 = 2<br>
factorial(3) = 3 * 2 = 6<br>
factorial(4) = 4 * 6 = 24<br>
factorial(5) = 5 * 24 = 120<br>
factorial(6) = 6 * 120 = 720<br>
factorial(7) = 7 * 720 = 5040<br>


## TASK 2- USING MATH MODULE FOR CALCULATIONS
<b>DESCRIPTION</b>:The following python programme uses math module to calculate 3 things-<br>
1.Square root of the given number <br>
2. Natural logarithm(log base e) of the number<br>
3. Sine of the number(in radians)<br>

<b>STEP 1-IMPORTING THE MATH MODULE:</b><br>
In the first step ,we import the math module which gives the mathematical functions like sqrt(),log() and sin().<br>

<b>STEP 2-GET USER INPUT:</b><br>
In the next step, we ask the user for the input by using the built-in function input().This built-in function gets the input as string and int() converts it into a integer and the stores the value in the variable <b>"num"</b><br>

<b>num=int(input("Enter a number:"))</b><br>

<b>STEP 3-CALCULATING THE NECESSARY THINGS:</b><br>
<b>math.sqrt(num)</b> calculates the square root of the number and the final answer gets stored in the variable <b>"a1"</b><br>
Similarly using the functions <b>math.log(num)</b> and <b>math.sin(num)</b> we calculate Natural logarithm(log base e) of the number and Sine of the number(in radians) and gets stored in the variables <b>"a2"</b> and <b>"a3"</b> respectively.<br>

a1 = math.sqrt(num)<br>
print("The square root of the number is :", a1)<br>

a2 = math.log(num)<br>
print("Natural logarithm (log base e) of the number:", a2)<br>

a3 = math.sin(num)<br>
print("The sine of the number(in radians) is:", a3)<br>

<b>STEP 4-PRINTING THE RESULTS:</b></br>
The required results get printed.










