# ccscTasks

# Task 1

### Q1 : Correct Code :
K=[3,1,2,'a','b']
for i in K:
    if i=='a':
        break
    else:
        print("A")

### Errors :
Line 1 : there should be ‘]’ at the end.
Line 3 : a should be in single inverted commas and : at the end.
Line 4 : there should be no : after break present


### Q2 : Correct Code :

K = int(input("Enter any number:"))
L=0
for j in range(1,K,2):
    L+=1
    if j%2==0:       
        print("Codechef"*2)
    else:
        print("Codechef"*3)
    print(L)

### Errors :

Line 3 : there should be : in the end 
Line 4 : it should be capital L
Line 5 : it should be double equals to (==) as we are checking condition not assigning
Line 9 : it should be parentheses() not brackets[] .

### Q3 : Correct Code :

def extendList(val,list=[]):
    list.append(val)
    return list

list1 = extendList(10)
list2 = extendList(123,[])
list3 = extendList(3)

print("list1=",list1)
print("list2=",list2)
print("list3=",list3)

### Errors :

Line 1 : there should be singe equals as we are assigning list and : present at the end and ,     instead  of ;
Line 6 : it should be only = as list3 is not predefined and it will not be add two list
Line 7 : it should be parentheses() not brackets[]
Line 9 : it should be parentheses() not braces{} at the end 

### Q4 : Correct Code :

def compound_interest(principle,rate,time):
    principle,rate,time=0,0,0          //(its a logical error as it will tend to give answer 0 everytime)
    Amount=principle*((1+rate/100)*time)
    CI=Amount-principle
    print("Compound interest is",CI)
    
p=float(input("Enter the principle "))
r=float(input("Enter the principle "))
t=float(input("Enter the principle "))

compound_interest(p,r,t)

### Errors :

Line 1 : there should be : present  the end
Line 4 : its principle not principal
Line 5 : its CI not Ci
Line 8 : there should be “ not ‘
Line 9 : the parameters are p,r,t in the function 

# Task 2

1) - a - 10
2) - d - 5
3) - c - assignment
4) - a - 123450
5) - d - all of these
6) - there are no options given
7) - b - 0.000000
8) - c - same address is printed
9) - c - 19
10) - a - 1 time

