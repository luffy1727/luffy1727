<!-- Zero width character is used to put extra blank lines before and after code -->

<h3>
    
```python
​
import json
from dataclasses import asdict, dataclass


@dataclass
class Stack:
    languages   : tuple = ("Python", "PHP", "Javascript")
    databases   : tuple = ("MySQL", "Mongo", "Redis")
    misc        : tuple = ("Docker", "Netflix Conductor", "AWS")
    frameworks  : tuple = ("Django", "Symfony")

    def serialize(self):
        return json.dumps(asdict(self), indent=4)


stack = Stack()
print(stack.serialize())
​
```
</h3>
