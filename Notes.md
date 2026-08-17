# Notes
### items to note

- Stubs * a function that does nothing

def Foo():
    pass

- Ellipsis (...)

def Foo():
    ...
Arguments
code
>>> def calculate_cost(item, quantity, price):
...     print(f"{quantity} {item} cost ${quantity * price:.2f}")
...
code

Position arguments:
The quickest way to call a function with arguments is to rely on the specific position of each argument.
>>> calculate_cost("bananas", 6, 0.74)
6 bananas cost $4.44

Keyword arguments:
When calling a function, you can specify arguments in the form argument=value. This way of passing arguments to a Python function is known as using keyword arguments
>>> calculate_cost(item="bananas", quantity=6, price=0.74)
6 bananas cost $4.44

