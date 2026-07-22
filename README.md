print("===================================")
print("      Student Registration")
print("===================================")

name = input("Enter your name: ")
age = input("Enter your age: ")
grade = input("Enter your grade/class: ")
percentage = float(input("Enter your percentage: "))
ai_interest = input("Are you interested in AI? (Yes/No): ")

print("\n===================================")
print("Student Information")
print("===================================")
print("Name:", name)
print("Age:", age)
print("Grade/Class:", grade)
print("Percentage:", percentage)
print("Interested in AI:", ai_interest)
print("===================================")

if percentage >= 90:
    print("🏆 Full Scholarship")
elif percentage >= 75:
    print("🥇 Merit Scholarship")
elif percentage >= 50:
    print("🥈 Participation Scholarship")
else:
    print("📚 Better Luck Next Time")

if ai_interest.lower() == "yes":
    print("Welcome to the AI Builder Club!")
else:
    print("We hope you'll join us in the future!")
