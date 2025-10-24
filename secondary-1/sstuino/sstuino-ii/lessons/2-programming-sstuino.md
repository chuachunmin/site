# 2: Programming SSTuino

{% embed url="https://youtu.be/SayB2bVJBd4" %}

{% embed url="https://docs.google.com/presentation/d/122nG-qa5RRY2aRfMTnJcOhGtD0A-q4fiRgX45cBhGZY/edit?usp=sharing" %}

{% embed url="https://www.tinkercad.com/embed/fsJUC7TzCq6" %}

{% tabs %}
{% tab title="Blocks" %}
![](<../../../../.gitbook/assets/2 Programming SSTuino II.png>)
{% endtab %}

{% tab title="Code" %}
```cpp
void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(500); // Wait for 500 millisecond(s)
  digitalWrite(13, LOW);
  delay(500); // Wait for 500 millisecond(s)
}
```
{% endtab %}
{% endtabs %}
