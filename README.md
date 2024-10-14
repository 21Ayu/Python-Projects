# Python-Projects

## This Repository will contain all the Python programs in a user friendly format from Basic  to Advance in well Structured way .



## 1. Python Programs to print  simple Pyramid.

n = int(input("Enter the number "))


for i in range(0,n):

    for j in range(0,i+1):
        print("*",end=" ")

    print()        


    ## Result

![Screenshot (1879)](https://github.com/user-attachments/assets/bed518f3-e6f8-4872-9185-5122797a6982)




# 2.Simple Python program to print the square of stars 

num = int (input("Enter the size of the square"))

for i in range (0,num):
    for j in range (0,num):
        print("*",end=" ")
    print()





    

![Screenshot (1882)](https://github.com/user-attachments/assets/e42a7fbc-ffdf-40a6-a995-090b4c8c9957)




# 3. Simple Python program to print the  hollow square of stars 

num = int (input("Enter the size of the square"))

for i in range (num):
    for j in range (num):
        if ((i ==0) or (i== num-1) or (j == 0) or (j == num-1)):
           print("*",end=" ")

        else :
           print(" ",end=" ")
    print() 

![Screenshot (1884)](https://github.com/user-attachments/assets/62f7e679-4649-45aa-963e-d2d823bf0594)




