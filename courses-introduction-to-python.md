## courses-introduction-to-python/

### ch1

1.The Python Interface

@instructions

Experiment in the IPython Shell; type 5 / 8, for example.

Add another line of code to the Python script on the top-right (not in the Shell): print(7 + 10).

Hit Submit Answer to execute the Python script and receive feedback.

#### hint Simply add print(7 + 10) in the script on the top-right (not in the Shell) and hit 'Submit Answer'.

## soulation! :
~~~

# Example, do not modify!
print(5 / 8)

# Put code below here
print(7 + 10)

~~~
## 

2.When to use Python?

@instructions

Experiment in the IPython Shell; type 5 / 8, for example.

Add another line of code to the Python script on the top-right (not in the Shell): print(7 + 10).

Hit Submit Answer to execute the Python script and receive feedback.

#### hint Simply add print(7 + 10) in the script on the top-right (not in the Shell) and hit 'Submit Answer'.
## soulation! :
~~~

# Example, do not modify!
print(5 / 8)

# Put code below here
print(7 + 10)

~~~
## 
3.Python as a calculator

## soulation! :
~~~
# Addition, subtraction
print(5 + 5)
print(5 - 5)

# Multiplication, division, modulo, and exponentiation
print(3 * 5)
print(10 / 2)
print(18 % 7)
print(4 ** 2)

# How much is your $100 worth after 7 years?
print(100 * 1.1 ** 7)

~~~
## 

4.Variable Assignment

@instructions

Create a variable savings with the value 100.

Check out this variable by typing print(savings) in the script.

@hint

Type savings = 100 to create the variable savings.

After creating the variable savings, you can type print(savings)
## soulation! :
~~~
# Create a variable savings
savings = 100

# Print out savings
print(savings)

~~~
## 
5.Calculations with variables

Create a variable growth_multiplier, equal to 1.1.

Create a variable, result, equal to the amount of money you saved after 7 years.

Print out the value of result.

@hint

To create the variable growth_multiplier, use growth_multiplier = 1.1.

In the example code block of the assignment, replace 100 with savings and 1.1 with growth_multiplier: savings * growth_multiplier ** 7.

Use the print() function to print the value of a variable.

## soulation! :
~~~

# Create a variable savings
savings = 100

# Create a variable growth_multiplier
growth_multiplier = 1.1

# Calculate result
result = savings * growth_multiplier ** 7

# Print out result
print(result))

~~~
## 

5.Other variable types

@instructions

Create a new string, desc, with the value "compound interest".

Create a new boolean, profitable, with the value True.

@hint

To create a variable in Python, use =. Make sure to wrap your string in single or double quotes.

Only two boolean values exist in Python: True and False. TRUE, true, FALSE, false and other versions will not be accepted.

## soulation! :
~~~

# Create a variable desc
desc = "compound interest"

# Create a variable profitable
profitable = True

~~~
## 

6.Operations with other types

@instructions

Calculate the product of savings and growth_multiplier. Store the result in year1.

What do you think the resulting type will be? Find out by printing out the type of year1.

Calculate the sum of desc and desc and store the result in a new variable doubledesc.

Print out doubledesc. Did you expect this?

@hint

Assign growth_multiplier * savings to a new variable, year1.

To print the type of a variable x, use print(type(x)).

Assign desc + desc to a new variable, doubledesc.

To print a variable x, write print(x) in the script.

## soulation! :
~~~


savings = 100
growth_multiplier = 1.1
desc = "compound interest"

# Assign product of savings and growth_multiplier to year1
year1 = savings * growth_multiplier

# Print the type of year1
print(type(year1))

# Assign sum of desc and desc to doubledesc
doubledesc = desc + desc

# Print out doubledesc
print(doubledesc)
~~~
## 

7.Type conversion

@instructions

Hit Run Code to run the code. Try to understand the error message.

Fix the code such that the printout runs without errors; use the function str() to convert the variables to strings.

Convert the variable pi_string to a float and store this float as a new variable, pi_float.

@hint

You should use str() twice!

Use float() on pi_string and store the result in pi_float.

## soulation! :
~~~

# Definition of savings and result
savings = 100
result = 100 * 1.10 ** 7

# Fix the printout
print("I started with $" + str(savings) +
      " and now have $" + str(result) + ". Awesome!")

# Definition of pi_string
pi_string = "3.1415926"

# Convert pi_string into float: pi_float
pi_float = float(pi_string)

~~~
## 

### ch2
## Python Lists

#### 1.Create a list

Create a list, areas, that contains the area of the hallway (hall), kitchen (kit), living room (liv), bedroom (bed) and bathroom (bath), in this order.

Use the predefined variables.

Print areas with the print() function.

## soulation! :
~~~

# Area variables (in square meters)
hall = 11.25
kit = 18.0
liv = 20.0
bed = 10.75
bath = 9.50

# Create list areas
areas = [hall, kit, liv, bed, bath]

# Print areas
print(areas)

~~~
## 

### 2.Create list with different types

Finish the code that creates the areas list.

Build the list so that the list first contains the name of each room as a string and then its area. 

In other words, add the strings "hallway", "kitchen" and "bedroom" at the appropriate locations.

Print areas again; is the printout more informative this time?

## soulation! :
~~~

# area variables (in square meters)
hall = 11.25
kit = 18.0
liv = 20.0
bed = 10.75
bath = 9.50

# Adapt list areas
areas = ["hallway", hall, "kitchen", kit, "living room", liv, "bedroom", bed, "bathroom", bath]

# Print areas
print(areas)

~~~
## 

### 3.List of lists

Finish the list of lists so that it also contains the bedroom and bathroom data. 

Make sure you enter these in order!

Print out house; does this way of structuring your data make more sense?

Print out the type of house. Are you still dealing with a list?

## soulation! :
~~~

## area variables (in square meters)
hall = 11.25
kit = 18.0
liv = 20.0
bed = 10.75
bath = 9.50

# house information as list of lists
house = [["hallway", hall],
         ["kitchen", kit],
         ["living room", liv],
         ["bedroom",bed],
         ["bathroom",bath]
         ]

# Print out house
print(house)

# Print out the type of house
print(type(house))

~~~
## 



