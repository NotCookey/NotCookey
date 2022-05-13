```py
#!/usr/bin/python
# -*- coding: utf-8 -*-


class System:

    def __init__(self):
        self.name = "Arete"
        self.role = ["Student", "Programmer", "Reverse Engineer"]
        self.skill = ["Python", "JavaScript", "React" , "VueJs", "Java", "Kotlin"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")


me = System()
me.say_hi()
```
