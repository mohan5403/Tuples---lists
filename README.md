# Tuples---lists
'''Write a program which accepts a sequence of comma-separated numbers from console and generate a list and a tuple which contains every number. Suppose the following input is supplied to the program'''
values = input('enter the values with seperated by "," :')
l = values.split(',')
t=tuple(l)
lis=list(l)
print(t)
print(lis)
