# -Student-Marks-Based-Grade-Calculator-In-Python-Programming-Language
ee = input("Enter Subject:")
em = float(input("Enter Marks:"))
print()

me = input("Enter Subject:")
mm = float(input("Enter Marks:"))
print()

se = input("Enter Subject:")
sm = float(input("Enter Marks:"))
print()

def grade(marks, sub):
    if float(marks) >= 90:
        print(sub + "\nA+")
    elif 80<= float(marks) <90:
        print(sub + "\nB+")
    elif 70<= float(marks) <80:
        print(sub + "\nC+")
    elif 60<= float(marks) <70:
        print(sub + "\nD+")
    elif 60 > float(marks):
        print("Sorry Better Luck Next Time")

grade(em, ee)

grade(mm, me)

grade(sm, se)

Average = ((float(em) + float(mm) + float(sm)) / 3)

print("Your Total Average:",Average)

if float(Average) >= 90:
        print("Average Grade: \nA+")
elif 80 <= float(Average) < 90:
        print("Average Grade: \nB+")
elif 70 <= float(Average) < 80:
        print("Average Grade: \nC+")
elif 60 <= float(Average) < 70:
        print("Average Grade: \nD+")
elif 60 > float(Average):
        print("Sorry You Failed The Semester")


