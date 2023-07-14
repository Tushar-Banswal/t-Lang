# t-Lang
An interpreted programming language build upon JavaScrit
# Run the project
Run the project with command 
```
npm start
```
# Use the project
Try writing 
```
tlang> take var = 3
```
This will create a variable  _var_
```
{ var : 3 }
> 3
```
Now you can use this variable
```
tlang> take newVar = var + 1
{ var : 3, newVar : 4 }
> 4
```
Try writing a branch statement
```
tlang> if newVar ?= 4 do var = (var + newVar) else  do var = (var - newVar)
{ var : 7, newVar : 4 }
> undefined
```
Loop statement, for now it only supports while loops
```
tlang> take a = 1
{ var : 7, newVar : 4, a : 1 }
> 1
tlang> while a < 10 do a = (a+1)
{ var : 7, newVar : 4, a : 2 }
{ var : 7, newVar : 4, a : 3 }
{ var : 7, newVar : 4, a : 4 }
{ var : 7, newVar : 4, a : 5 }
{ var : 7, newVar : 4, a : 6 }
{ var : 7, newVar : 4, a : 7 }
{ var : 7, newVar : 4, a : 8 }
{ var : 7, newVar : 4, a : 9 }
{ var : 7, newVar : 4, a : 10 }
> undefined
```

# Operations language supports
Arithematic Operations
```
+
-
*
/
%
```

Logical Operations

```
and
or
not
```

Unary Operations
```
-
not
```

Comparision Operations
```
?= (is Equals)
!= (not Equals)
>
<
>=
<=
```
