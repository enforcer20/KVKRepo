## Constructor

### What is a Constructor
Constructors are generally used for [instantiating an object](https://amir.rachum.com/blog/2016/10/03/understanding-python-class-instantiation/).The task of constructors is to initialize(assign values) to the data members of the class when an object of class is created.In Python the __init__() method is called the constructor and is always called when an object is created.



### Syntax:

```
def __init__(self):
    # body of the constructor
```

### Types of constructors:

**Default constructor:** The default constructor is simple constructor which doesn’t accept any arguments.It’s definition has only one argument which is a reference to the instance being constructed.

**Parameterized constructor:** constructor with parameters is known as parameterized constructor.The parameterized constructor take its first argument as a reference to the instance being constructed known as self and the rest of the arguments are provided by the programmer.

### Sources

1. [Source #1](https://www.geeksforgeeks.org/constructors-in-python/)

<img src ="https://github.com/vishwa742/KVKRepo/blob/master/python_image/instantiate.png">
