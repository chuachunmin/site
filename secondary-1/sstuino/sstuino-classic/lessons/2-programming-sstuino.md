# 2: Programming SSTuino

{% embed url="https://docs.google.com/presentation/d/1olBx26U6ZHRGsTPL7K89ELBPmHdGGDwFufgXZ01vg6M/present" %}

{% embed url="https://www.tinkercad.com/embed/fsJUC7TzCq6" %}

{% tabs %}
{% tab title="Blocks" %}
![](<../../../../.gitbook/assets/2 Programming SSTuino.png>)
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
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```
{% endtab %}
{% endtabs %}

{% embed url="https://youtu.be/9hKp_XC0FVo" %}
