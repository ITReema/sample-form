# sample-form
semple form in jupiter
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
