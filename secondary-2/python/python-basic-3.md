# Python Basic 3

## [Slides](https://docs.google.com/presentation/d/1iHfU3v4NG95bCHlSMrXJ5jEzkzmupcCqN0EbHmbOWcU/present)

{% embed url="https://docs.google.com/presentation/d/1iHfU3v4NG95bCHlSMrXJ5jEzkzmupcCqN0EbHmbOWcU/present" %}

## 2 types of loops

* for loop, in which the number of repetitions is specified explicitly in advance
* while loop, in which the code block executes until some condition is met

## range()

{% tabs %}
{% tab title="range(stop)" %}
```python
for x in range(10):
    print(x)
```
{% endtab %}

{% tab title="range(start, stop)" %}
```python
for x in range(5, 15):
    print(x)
```
{% endtab %}

{% tab title="range(start, stop, step)" %}
```python
for x in range(1, 30, 2):
    print(x)
```
{% endtab %}
{% endtabs %}

```python
#Skip multiples of 4, end at 30

for i in range(1, 100):
    if i % 4 == 0:
        continue
    if i > 30:
        break
    
    print(i, end = ", ")
```

The `break` statement terminates the loop containing it.

The `continue` statement is used to skip the rest of the code inside a loop for the current iteration only.
