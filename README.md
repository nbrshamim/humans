# Humans Library
a Python collection of biblical humans and their family relations.
<br>
Please note, this is the source code of version 0.0.1, which is the starter file for my "Create Python Package" tutorial on YouTube:
<br>
[https://youtu.be/9Ii34WheBOA](https://www.youtube.com/playlist?list=PLeH3as6pzIpjBSsBf_EAj73OztEPOC5qX)

## Quickstart
the library provides different scopes of information

### Father Objects
a set of classes that represent biblical fathers, such as Abraham, Isaac and Jacob.

```
import humans

abraham = humans.Abraham()
print(abraham.__dict__)
```
### List of Humans
on a broader scope, the library traces different categories of humans, such as fathers, mothers and children.
```
import humans

all_mothers = humans.mothers
print(all_mothers)
```
