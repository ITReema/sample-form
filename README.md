# Sample Form
semple form in jupiter

## Installation
JupyterLab can be installed using ```conda``` or ```pip```. For more detailed instructions, consult the [installation guide](http://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)

## Code 

```
from ipywidgets import *
from IPython.display import display

name = input("Enter your name:")
print("Hello ", name )

print("Please answer this questions!"),

age = widgets.DatePicker(
        description = 'Age:',
        disabled = False 
)

gender = widgets.RadioButtons(
        options=['Male','Female'],
        value = 'Male',
        description = 'Gender: ',
        disabled = False 
)

color= widgets.ColorPicker(
    concise = False,
    description = 'Color:',
    value = 'Red',
    disabled = False 
)

food= widgets.SelectMultiple(
    options=['Pizza','Pasta','Rice', 'Burger'],
    value = ['Pizza'],
    description = 'Fevorite Eat: ',
    disabled = False 
)
display(age)
display(gender)
display(color)
display(food)

```

<p align="center">
  <img width="500" height="200" src="https://user-images.githubusercontent.com/27751735/61357438-fb7c0500-a880-11e9-9798-5027b6e27711.png">
</p>

