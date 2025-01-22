# codtech-task2
name : Karunya R I

company : CODTECH IT SOLUTIONS

domain : python programming

duration : jul to aug 2024

Id : CT08DS5219

mentor : Harish Neelam

Here is an overview of the task:

Task: Create a Python program to generate a student mark list with input marks and respective grades.

Program Requirements:

- Take user input for:
    - Marks for each subject
- Calculate the average marks
- Assign grades based on the percentage (e.g., A, B, C, D, F)
- Display Grades

Grade Criteria:

- A: 90-100%
- B: 80-89%
- C: 70-79%
- D: 60-69%
- F: Below 60%

Program Code:

#student grade system

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

output

![student_grade_op](https://github.com/user-attachments/assets/bb2fb3f1-fd59-4f0a-8480-e0789d4b385d)

