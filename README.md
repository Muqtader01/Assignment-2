Program 1

Total_percentage=int(input("Enter the percentage"))
if Total_percentage>90:
    print("The grade as A")
elif Total_percentage>80 and Total_percentage<=90:
    print("The grade is B")
elif Total_percentage>=60 and Total_percentage<=80:
    print("The grade is C")
else:
    print("The grade is D")
Enter the percentage 99
The grade as A

Program 2

cost_price=int(input("Enter the cost price of the bike"))
if cost_price>100000:
    road_tax=cost_price-cost_price*15/100
    print(f"The road tax to be paid is {road_tax}")
elif cost_price>50000 and cost_price<=100000:
    road_tax=cost_price-cost_price*10/100
    print(f"The road tax to be paid is {road_tax}")
elif cost_price<=50000:
    road_tax=cost_price-cost_price*5/100
    print(f"The road tax to be paid is {road_tax}")
cost_price=int(input("Enter the cost price of the bike"))
if cost_price>100000:
    road_tax=cost_price-cost_price*15/100
    print(f"The road tax to be paid is {road_tax}")
elif cost_price>50000 and cost_price<=100000:
    road_tax=cost_price-cost_price*10/100
    print(f"The road tax to be paid is {road_tax}")
elif cost_price<=50000:
    road_tax=cost_price-cost_price*5/100
    print(f"The road tax to be paid is {road_tax}")
Enter the cost price of the bike 50000
THe road tax to be paid is 47500.0

Program 3

city=input("Enter the city name: ")
if city=='Delhi':
    print("Famous monument in Delhi is Red Fort")
elif city=='Agra':
    print("Famous monument in Agra is Taj Mahal")
elif city=='Jaipur':
    print("Famous monument in Jaipur is Jal Mahal")
    
Program 4

number=int(input("Enter the number to be divided by 3: "))
if number<=10:
    print("The given number can be divided {} times".format(number/3))
elif number>10:
    print("The number is greater than 10")
    
Answer 5

A while loop will run a piece of code while a condition is True. It will keep executing the desired set of code statements until that condition is no longer True. A while loop will always first check the condition before running. If the condition evaluates to True then the loop will run the code within the loop's body.

#Example
i = 1
while i < 6:
    print(i)
    i+=1
1
2
3
4
5

Answer 6

#1
n = 6
for i in range(0, n):
    for j in range(0, i+1):
        print("*", end="  ")
    print('')
*  
*  *  
*  *  *  
*  *  *  *  
*  *  *  *  *  
*  *  *  *  *  *  
def pypart2(n):
    k = 2*n-2
    for i in range(0, n):
        for j in range(0, k):
            print(end = " ")
        k = k-2
        
        for j in range(0, i+1):
            print("* ", end ="  ")
        print("\r")
n = 6
pypart2(n)
#2
def pypart2(n):
    k = 2*n-2
    for i in range(0, n):
        for j in range(0, k):
            print(end = " ")
        k = k-2
        
        for j in range(0, i+1):
            print("* ", end ="  ")
        print("\r")
n = 6
pypart2(n)
          *   
        *   *   
      *   *   *   
    *   *   *   *   
  *   *   *   *   *   
*   *   *   *   *   *   
#3
def pypart2(n):
    k = 2*n-2
    for i in range(0, n):
        for j in range(0, k):
            print(end = " ")
        k = k-2
        
        for j in range(0, i+1):
            print("* ", end ="")
        print("\r")
n = 6
pypart2(n)
          * 
        * * 
      * * * 
    * * * * 
  * * * * * 
* * * * * * 

Answer 7

i=10
while i>0:
    i-=1
    print(i)
9
8
7
6
5
4
3
2
1
0
