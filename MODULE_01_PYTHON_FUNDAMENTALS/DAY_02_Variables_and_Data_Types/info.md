# Day 02 — Variables and Data Types

## 1. What is a Variable?

A **variable** is a name used to store a value in memory.

```python
name = "Gaurav"
age = 22
salary = 25000.50


2. Variable Naming Rules
- Must start with a letter or underscore (_).
- Cannot start with a number.
- Cannot contain spaces.
- Cannot use Python keywords.
- Variable names are case-sensitive.
student_name = "Gaurav"_age = 22



3. Python Data Types
Data types define the type of value stored in a variable.
Data Type	Description	Example
int	Whole numbers	10
float	Decimal numbers	10.5
str	Text	"Python"
bool	True or False	True
list	Ordered, mutable collection	[1, 2, 3]
tuple	Ordered, immutable collection	(1, 2, 3)
set	Collection of unique elements	{1, 2, 3}
dict	Key-value pairs	{"name": "Gaurav"}

4. Checking Data Types
The type() function checks the data type of a variable.
age = 22name = "Gaurav"print(type(age))print(type(name))



Output:
<class 'int'>
<class 'str'>


5. Type Conversion
Type conversion means changing one data type into another.
x = "100"y = int(x)print(y)print(type(y))



Output:
100
<class 'int'>


Important conversion functions:
- int() — Converts to integer.
- float() — Converts to float.
- str() — Converts to string.
- bool() — Converts to Boolean.
- list() — Converts to list.
- tuple() — Converts to tuple.
- set() — Converts to set.
6. Multiple Variable Assignment
Assign multiple values to multiple variables in one statement.
a, b, c = 10, 20, 30print(a, b, c)



Output:
10 20 30


7. Variable Reassignment
A variable's value can be changed after creation.
x = 10x = 20print(x)



Output:
20


Important Points
- Python is dynamically typed.
- Variables do not require explicit type declarations.
- type() checks the data type.
- Python supports multiple built-in data types.
- Type conversion can be implicit or explicit.
- None represents the absence of a value.
- Variable names are case-sensitive.
Interview Questions
Q1. What is a variable?
A variable is a name used to store a value.

Q2. What is dynamic typing?
Python determines the variable's data type at runtime.

Q3. How do you check a variable's data type?
Using the type() function.

Q4. What is type casting?
Converting one data type into another.

Q5. What are the basic Python data types?
int, float, str, bool, list, tuple, set and dict.

Q6. Is Python case-sensitive?
Yes. For example, name and Name are different variables.

Q7. What is the difference between int and float?
int stores whole numbers; float stores decimal numbers.

Q8. What is None in Python?
None represents the absence of a value.

Q9. What is the difference between mutable and immutable data types?
Mutable objects can be changed; immutable objects cannot be changed after creation.

Q10. What is type conversion?
Changing a value from one data type to another.