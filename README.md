# basic-arithematic-game
This is a simple input game which works on basic arithematics
#Arithmetic: Input some numbers, do some simple arithmetic, output results
#Arrange these thre integers (2,3 & 4) such that, the resultant number is the highest of all the combinations
#(X) x (Y) / (Z) - No need to follow bodmas, perform diresctly from left to right

X=float(input("Enter value for X: "))
Y=float(input("Enter value for Y: "))

A=mul=X*Y;
#Performing multiplication

Z=float(input("Enter value for Z: "))

P=A/Z
#Dividing A with value of Z

print(P)

if P < 6:
 print("try again, this is not the correct order")

else :
 print("there are two correct combinations, and this is one them! good job!")
