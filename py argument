HOw many argument in python language?
Types of arguments
• Required arguments
• Keyword arguments
• Default arguments
• Variable-length arguments
Required Argument : As far as the required arguments 
are concerned, these are the arguments which are 
required to be passed at the time of function calling with 
the exact match of their positions in the function call and 
function definition. If either of the arguments is not 
provided in the function call, or the position of the 
arguments is changed, then the python interpreter will 
show the error

examples:-
#the function simple_interest accepts three arguments and returns the simple inte
rest accordingly 
def simple_interest(p,t,r): 
 return (p*t*r)/100 
p = float(input("Enter the principle amount? ")) 
r = float(input("Enter the rate of interest? ")) 
t = float(input("Enter the time in years? ")) 
print("Simple Interest: ",simple_interest(p,r,t))

Other example
#the function calculate returns the sum of two arguments a and b 
def calculate(a,b): 
 return a+b 
calculate(10) # this causes an error as we are missing a required arguments b

Keyword Argument 
The name of the arguments is treated as the keywords and 
matched in the function calling and definition. If the same match 
is found, the values of the arguments are copied in the function 
definition.

example:-
def func(name,message): 
 print("printing the message with",name,"and ",message) 
func(name = "John",message="hello")
def simple_interest(p,t,r): 
 return (p*t*r)/100 
print("Simple Interest: ",simple_interest(t=10,r=10,p=1900)) 
**here its match the keyword name mean name of arguments.
def simple_interest(p,t,r): 
 return (p*t*r)/100 
 
print("Simple Interest: ",simple_interest(time=10,rate=10,principle=1900)) # doesn't 
find the exact match

Default Arguments
• Python allows us to initialize the arguments at the 
function definition. If the value of any of the 
argument is not provided at the time of function call, 
then that argument can be initialized with the value 
given in the definition even if the argument is not 
specified at the function call.

example:-
def printme(name,age=22): 
 print("My name is",name,"and age is",age) 
printme(name = "john") #the variable age is not passed into the function
// another example 
def printme(name,age=22): 
 print("My name is",name,"and age is",age) 
printme(name = "john") 
#the variable age is not passed into the function however the default value of age is 
considered in the function 
printme(age = 10,name="David") #the value of age is overwritten here, 10 will be pri
nted as age

example:-
def printme(name,age=22): 
 print("My name is",name,"and age is",age) 
printme(name = "john") #the variable age is not passed into the function
// another example 
def printme(name,age=22): 
 print("My name is",name,"and age is",age) 
printme(name = "john") 
#the variable age is not passed into the function however the default value of age is 
considered in the function 
printme(age = 10,name="David") #the value of age is overwritten here, 10 will be pri
nted as age

