# Python Basic 2

## [Slides](https://docs.google.com/presentation/d/1apV2NFfF1n6LlOVH9v4L8XkcrXFqApkF7VALVqaqlF8/present)

{% embed url="https://docs.google.com/presentation/d/1apV2NFfF1n6LlOVH9v4L8XkcrXFqApkF7VALVqaqlF8/present" %}

## Conditional Statements

In Python, the if statement is used to perform decision-making. It allows for conditional execution of a statement or group of statements based on the value of an expression.

## Structure

```python
if <condition>:
    statement
```

* `if` is a reserved word for conditions.
* `:` at the end of the if statement. This is needed at the end of a control flow statement.
* Indentation has special significance in Python. Python uses indentation to determine blocks of code. You can contain blocks of code within another block of code, so long as it indents. There is no limit on the indent, but it must be kept constant or you'll get an error.

## Relational Operators

| Symbol | Meaning                  |
| :----: | ------------------------ |
|    >   | Greater than             |
|    <   | Smaller than             |
|   >=   | Greater than or equal to |
|   <=   | Smaller than or equal to |
|   ==   | Equivalent to            |
|   !=   | Not equal to             |

## if ... else

### Example 1

In this example, the script will print "'a' is equivalent to 3" if `a` is equivalent to 3.

```python
a = 3 #'a' can be 1, 2 or 3

if a == 3:
    print("'a' is equivalent to 3")
```

### Example 2

In this example, the script will print "'a' is equivalent to 1" if `a` is equivalent to 1. Else, it will print "'a' is not equivalent to 1".

```python
a = 3 #'a' can be 1, 2 or 3

if a == 1:
    print("'a' is equivalent to 1")
else:
    print("'a' is not equivalent to 1")
```

### Example 3

Example 3.1, 3.2, 3.3 does the same thing.

#### Example 3.1

introduce the idea that an _if...else_ statement can be written within an _if...else_ statement.

```python
a = 3 #'a' can be 1, 2 or 3

if a == 1:
    print("'a' is equivalent to 1")
else:
    if a == 2:
        print("'a' is equivalent to 2")
    else:
        print("'a' is equivalent to 3")
```

#### Example 3.2

introduce _elif_ (else if) to simplify the script.

```python
a = 3 #'a' can be 1, 2 or 3

if a == 1:
    print("'a' is equivalent to 1")
elif a == 2:
    print("'a' is equivalent to 2")
else:
    print("'a' is equivalent to 3")
```

#### Example 3.3

Introduce Nested if as an alternative way of writing the script. Note that the short hand for _else_ can also be used on _if_.

```python
a = 3 #'a' can be 1, 2 or 3

if a != 1:
    if a != 2:
        print("'a' is equivalent to 3")
    else: print("'a' is equivalent to 2") #short hand. can be used on if too.
else: print("'a' is equivalent to 1") #short hand. can be used on if too.
```

## Logical Operators

If there are more than 1 conditions, it is then called an expression. An expression is made up as least two conditions connected together by a logical operator.

**Basic logical operators are:**\
`or`	The expression is true as long as one of the conditions is true.

```python
age = int(input("Enter age : "))
isStudent = input("Do you have a student pass [Y/N] : ")

if age >= 65 or isStudent == "Y" :
	print("You are eligible for LNY discount!")
else:
	print("Not eligible for discount.")
```

`and`	The expression is true only both conditions are true.

```python
tscore = int(input("Enter your tscore : "))
gender = input("Enter gender [M/F] : ")

if tscore >= 264 and gender == "F":
    print("You are eligible for NYGH, RGS, MGS")
elif tscore >= 262:
    print("You are eligible for …")
```
