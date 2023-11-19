import numpy as fm
def costSlab1():
     slab1=10*matrix[0]
     print("Bill for slab 1: \n",slab1)
def costSlab2() :
    slab2=10*matrix[1]
    print("Bill for slab 2: \n",slab2)
def costSlab3() :
    slab3=10*matrix[2]
    print("Bill for slab 3: \n",slab3)

matrix=fm.array([[2,3,4],[5,6,7],[8,9,1]]) 
ID=input("enter you ID :")
print("student’s ID : ",ID)
print(""""     Menu
            1. Display Bill of Slap 1 and Slap 2
            2. Display Bill of Slap 3
            3. Exit """)
choice=int(input("Enter your choice (1_3)::"))     
if choice == 1 :
    costSlab1()
    costSlab2()
elif choice == 2 :
    costSlab3()
else:
   print()
