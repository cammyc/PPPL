Cameron Connor
Partner: Brandon Zink
PPPL
Lab 1 Write up

2a)
i)Line 4 is bound on line 3
	As a result of pi being redeclared using val inside of the brackets. It will be mapped to 3.14159 until the closing bracket on line 5.
ii)Line 7 is bound on line 1
	As a result of pi being redelcared within the the area function. Therefor it uses the original declaration.

2b)

i)x,line 3
	Bound by the function parameter on line 2.
ii)x,line 6
	Bound by the function parameter on line 2, but line 6 will only excectue if x does not equal 0.
iii)x,line 10
	Bound by the function parameter on line 2 since the x on line 8 is a part of a different scope.
iv)x,line 13
	Bound on line 1 since line 13 is outside of the f functions scope.

3)
	It is well typed if a valid return type is in the code because this makes the code consistant. This is a result of there being both an if and else clause resulting in all possibilities being accounted for.
	
	(a,b): (int, (int, int))
		a: int becuase
			1: int
		b: (int, int) because
			x: int
			3: int
