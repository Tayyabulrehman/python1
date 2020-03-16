# python1
row=int(input("Enter row "))
column=int(input("Enter column"))
temp=column-1
front=int(temp/2)
back=front
slash=1
welcom_front=int((column-7)/2)
welcom_back=int((column-7)/2)
for i in range(0,int(row/2)):
    for j in range(0,front):
        print("-",end=" ")
    for k in range(0,slash):
        print(". | .",end=" ")
    for l in range(0,back):
        print("-",end=" ")
    print("\n")
    front=front-3
    back=back-3
    slash=slash+2
for y in range(0,welcom_front):
        print("-",end=" ")
print(" W E L C O M E ",end=" ") 
for x in range(0,welcom_back):
    print("-",end=" ")
print("\n")
for i in range(0,int(row/2)):
    front=front+3
    back=back+3
    slash=slash-2
    for j in range(0,front):
        print("-",end=" ")
    for k in range(0,slash):
        print(". | .",end=" ")
    for l in range(0,back):
        print("-",end=" ")
    print("\n")
               
