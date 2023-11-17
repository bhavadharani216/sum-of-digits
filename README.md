# sum-of-digits

num = int(input("Enter the number"))
sum = 0
if num!=0:
   while(num!=0):
   digit=num%10
   num=num//10
   sum=sum+digit
print(sum)
