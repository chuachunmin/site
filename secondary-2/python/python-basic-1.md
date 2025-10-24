# Python Basic 1

## [Slides](https://docs.google.com/presentation/d/1gAMT8FzUI5530H2uhIybXwpMoFwusT-hrvzhc8o3hPs/present)

{% embed url="https://docs.google.com/presentation/d/1gAMT8FzUI5530H2uhIybXwpMoFwusT-hrvzhc8o3hPs/present" %}

## Setup

Download [Python](https://www.python.org/downloads/)\
Refer to [Documentation](https://docs.python.org/)

## Data Types

```python
anInt = 10               #integer: whole number
aFloat = 3.14            #float: decimal point
aString = "Hello World"  #string of characters: text
aBool = True             #Boolean: True/False
```

## Python Reserved Words

```python
from keyword import kwlist
kwlist
```

## Output: print( )

The print() function prints the specified message to the screen. The message can be a string or any other object.

```python
print(object(s), sep=separator, end=end)
```

| Parameter         | Description                                                                              |
| ----------------- | ---------------------------------------------------------------------------------------- |
| object(s)         | Any object, and as many as you like. Will be converted to string before printed          |
| sep='_Separator'_ | Optional. Specify how to separate the objects, if there is more than one. Default is ' ' |
| end='_end'_       | Optional. Specify what to print at the end. Default is '\n' (newline)                    |

{% tabs %}
{% tab title="Code" %}
```python
print("Hello World")
```
{% endtab %}

{% tab title="Result" %}
```python
Hello World
```
{% endtab %}
{% endtabs %}

### Various ways to print

```python
a = "Hello"
b = "World"

print(a, b)  #print a then b
print(a + b) #concatenate a & b, then print

print("Hello \nWorld") #\n is to have a new line using escape character \
```

### Escape Sequence

```python
\n #new line
\t #horizontal tab
\v #vertical tab
\x #hexadecimal
```

## Input

{% tabs %}
{% tab title="Code" %}
```python
name = input("Enter Your Name: ") #input("prompt")
print("Hello", name, "! \nGood Job!")
```
{% endtab %}

{% tab title="Result" %}
```python
Enter Your Name: John
Hello John!
Good Job!
```
{% endtab %}
{% endtabs %}

> input() returns result in string.

## Type Casting

There may be times when you want to specify a type on to a variable. This can be done with casting.

* **int()** - constructs an integer number from
  * a float by rounding down to the previous whole number
  * a string, provided the string represents a whole number
* **float()** - constructs a float number from
  * an integer
  * a float
  * a string, provided the string represents a float or an integer
* **str()** - constructs a string from a wide variety of data types, including strings, integer literals and float literals

