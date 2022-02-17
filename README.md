# 17-02-2022-assignment-1
n=int(input("Enter the n:"))
sum=0
se=0

for i in range (1,n+1):# odd
    if i%2==1:
        sum=sum+i
    elif i%2==0:#even
        se=se+i    
print("sum of odd numbers",sum)
        
print("sum of even numbers:",se)

output:
Enter the n:9
sum of odd numbers 25
sum of even numbers: 20
>>> 
================== RESTART: C:/Python37/odd and even sum.py ==================
Enter the n:20
sum of odd numbers 100
sum of even numbers: 110
>>> 
================== RESTART: C:/Python37/odd and even sum.py ==================
Enter the n:5
sum of odd numbers 9
sum of even numbers: 6
>>> 
