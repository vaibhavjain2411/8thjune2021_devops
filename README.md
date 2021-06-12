# 8thjune2021_devops

# TASK -1 how to find the value of the variable whose address is given ?

#EXAMPLE- 
x= ?
id(x)
12345

what is the value of x ?

solution - 

>>>import ctypes
>>>a = 5
>>>address = id(a)
>>>address
493382800
>>>ctypes.cast(address, ctypes.py_object).value
5
