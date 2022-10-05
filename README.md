<!-- Zero width character is used to put extra blank lines before and after code -->

<h2>Hey! This is @luffy1727!</h2>

<h3>

```python
​
import json
from dataclasses import asdict, dataclass


@dataclass
class Stack:
    languages   : tuple = ("Python", "PHP", "JS")
    databases   : tuple = ("MySQL", "MongoDB", "Redis")
    misc        : tuple = ("Docker", "Netflix Conductor", "AWS")
    frameworks  : tuple = ("Django", "Symfony", "Laravel")

    def serialize(self):
        return json.dumps(asdict(self), indent=4)


stack = Stack()
print(stack.serialize())
​
```
</h3>
