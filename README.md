# Portfolio1
print("=== STUDENT EVALUATION SYSTEM ===\n")

name = input("enter student name: ") #string
quiz = float(input("enter quiz score: ")) #float
exam = float(input("enter exam score: ")) #float
attendance = float(input("enter attendance score: "))

final_grade = (quiz * 0.30) + (exam * 0.50) + (attendance * 0.20)
passed = final_grade >= 75
scholar = final_grade >= 90 and attendance >= 90

print("\n========== STUDENT REPORT ==========")
print("Student Name :", name)
print("Final Grade  :", round(final_grade, 2))
print("Passed       :", passed)
print("Scholar      :", scholar)
print("====================================")

bonus = final_grade + 5
print("Grade with Bonus:", round(bonus, 2))

print("\nProgram Finished Successfully!")
     
