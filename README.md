<!-- Zero width character is used to put extra blank lines before and after code -->

<h2>Hey! This is @luffy1727!</h2>

<p><em>Software Enginner at <a href="https://www.booztgroup.com">Boozt Fashion AB</a></br>
Currently located in Malmö, Sweden.
</em></p>

> I'm a curious question asker who likes to build useful stuff.

Connect me on Linkedin or even better send me an email:

[![Linkedin Badge](https://img.shields.io/badge/chintushig-ochirsukh-4a00a275?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chintushig-ochirsukh-4a00a275/)

[![Gmail Badge](https://img.shields.io/badge/-tushig.tushig@gmail.com?style=flat-square&logo=Gmail&logoColor=white&link=mailto:tushig.tushig@gmail.com)](mailto:tushig.tushig@gmail.com)

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
