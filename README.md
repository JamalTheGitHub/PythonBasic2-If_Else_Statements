# PythonBasic2 If Else Statements

Prerequisite => From this tutorial onwards, it is expected that you have the following extensions in your Visual Studio Code;

1)Code Runner 2)Python

If you want to know more on how to get Python on Visual Studio Code, google it.

First thing first, create a file called called whatever you want it to be called and save it as ".py". For example like this, "PythonTutorial.py". Navigate to that file and do your coding there.

================================================================================================

<strong>If Else Statements</strong>

Assuming;

    a = 3
    b = 5

Now that we have set the variables to their corresponding values, what is left is to test a simple <strong>print function</strong> that says if "a" is greater than "b" then do this and vice versa. Therefore, we can do something like;

    if a < b:
      print("a is smaller than b")
    else:
      print("a is ACTUALLY greater than b")

In this case, since we defined <strong> a = 3 </strong>, it will definitely give the output of <strong>"a is smaller than b"</strong>. However by changing the value of "a" to be bigger than the value of "b" will give the <strong>else</strong> output. <strong>Something to remember</strong> is that the <strong>colon(:)</strong> is used to determine the start of the function from a statement which in this case is the <strong>if else statement</strong>.

Okay, now that we got that covered, the next question is, how are we going to implement more than <strong>ifs</strong>? You could make multiple if statements but that would be tedious. Instead we will be using </strong>elif</strong> which stands for <strong> else if</strong>. Look at the example below;

    a = 5
    b = 6

    if a < b:
      print("b is greater than a")
    elif a == b:
      print("a is equals to b")
    else 
      print("b is NOT greater than a")

Now if we change the value of "a" to fit the criteria, the corresponding output will be printed. Note that this <strong>=</strong> syntax and this <strong>==</strong> are different. We use <strong>=</strong> to assign value whereas this <strong>==</strong> is used to emphasize on <strong>equals to</strong>. In layman's term, we could say that <strong>the value of a is the same as the value of b</strong> in the example given above.

Another way of writing multiple statements is to write it within the <strong>else</strong> statement. Given the same example above, we could re-write it like this;

    a = 5
    b = 6

    if a < b:
      print("b is greater than a")
    else:
      if a == b:
        print("a is equals to b")
      else
        print("b is NOT greater than a")

The outcome will be the same if you modified the value for "a" or "b" to fit the corresponding statements.

================================================================================================

Okay, now that We know how to use the <strong>If Else Statements</strong>, let's tess your undertanding on how to implement it.

Given what you have <strong>learnt so far</strong>, build a simple BMI calculator using <strong>variables</strong> and <strong>If Else Statements</strong>.

The equation for BMI is <strong>Weight(kg)/Height(m**2)</strong>.
*Hint: syntax for height in meters is "height_m" and weight in kilograms is "weight_kg"*

Be creative and work your solutions out. 