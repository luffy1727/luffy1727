<!-- Zero width character is used to put extra blank lines before and after code -->

<h2>Hey! This is @luffy1727!</h2>

<p><em>Software Enginner at <a href="https://www.booztgroup.com">Boozt Fashion AB</a></br>
Currently located in Malmö, Sweden.
</em></p>

> I'm a curious question asker who likes to build useful stuff.

Connect me on Linkedin: 

[![Linkedin Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintushig-ochirsukh-4a00a275/)

Or even better send me an email:

[![Gmail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tushig.tushig@gmail.com)

<img align='right' src='https://luffy1727.github.io/tushig-rants/assets/whatever.gif' width='200"'>

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
