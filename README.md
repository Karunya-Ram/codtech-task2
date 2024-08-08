# codtech-task2
s1=int(input("Enter marks of the first subject: "))
s2=int(input("Enter marks of the second subject: "))
s3=int(input("Enter marks of the third subject: "))
s4=int(input("Enter marks of the fourth subject: "))
s5=int(input("Enter marks of the fifth subject: "))
avg=(s1+s2+s3+s4+s4)/5.0
if(avg>=90):
    print("Your Grade: A")
elif(avg>=80 and avg<90):
    print("Your Grade: B")
elif(avg>=70 and avg<80):
    print("Your Grade: C")
elif(avg>=60 and avg<70):
    print("Your Grade: D")
else:
    print("Your Grade: F")
print('Thank you..')
