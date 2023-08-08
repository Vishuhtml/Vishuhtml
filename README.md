from sympy import *
var('x,y')
p = x+2*y
q= x-2*y
f = diff(q,x)-diff(p,y)
soln = integrate(f,[x,0,1],[y,0,1])
print("I=",soln)

Output :-
I = -1
