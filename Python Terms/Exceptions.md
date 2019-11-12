## Unit Test

### What is an Unit Test
In computer programming, unit testing is a software testing method by which individual units of source code, sets of one or more computer program modules together with associated control data, usage procedures, and operating procedures, are tested to determine whether they are fit for use.

### Raising an Exception

**Syntax**
```
raise [Exception [, args [, traceback]]]
```
Here, Exception is the type of exception (for example, NameError) and argument is a value for the exception argument. The argument is optional; if not supplied, the exception argument is None.

### Example 
```
def functionName( age ):
   if age < 0:
      raise "Invalid age!", age
```
In this example, if the age is less than 0, an exception is raised and the message "Invalid age!" is displayed. 

### Sources

1. [Source #1](https://www.tutorialspoint.com/python/python_exceptions.htm)
