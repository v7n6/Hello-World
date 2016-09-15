Python readings
----------------

All commands will have parenthesis
multi line comments have 3 parantheses

To tell Python when to use bases other than base 10, you add a 0 and a special
letter to the number. For example, 0b100 is the value one-zero-zero in
base 2. Here are the letters you normally use:
? b: Base 2
? o: Base 8
? x: Base 16

type() - to get the type of the variable
str - string 
bool - boolean
convert any single letter to its numeric eqv using the ord() command
datetime.datetime.now()
datetime.datetime.now().date()
str(datetime.datetime.now().date())) - converts to readable format 

ternary operator - TrueValue if Expression else FalseValue
eg: "hello" if (1>0) else "bye"

another flavor: (FalseValue, TrueValue) [Expression]
("Goodbye", "Hello")[1>0]

unary operator
~ - all the 0 bits become 1 bits and vice versa. ~4 results in a value of -5
it calculates to -x - 1

arithmetic operator
** - for calculating power ( 5**2 = 25)
// - division to give whole number as result 5//2 = 2

logical operator - and, or, not

membership - in, not in “Hello” in “Hello Goodbye” is True

identity - identity operators determine whether a value or expression is of a certain class or type
type(2) is int is True

function:
def Hello():
	print("Test")
	
function can accept variable num of args
def Hello4(*VarArgs):

input() helps to get input from user
	
no switch statements

colon after condition is required
if/elif
