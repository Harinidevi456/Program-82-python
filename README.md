def Fib(n):
if n&lt;0:
print(&quot;The input is incorrect.&quot;)
elif n==1:
return 0
elif n==2:
return 1
else:
return Fib(n-1)+Fib(n-2)
print(Fib(7))
output
8
