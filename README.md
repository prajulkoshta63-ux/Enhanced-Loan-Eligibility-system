# Enhanced-Loan-Eligibility-system
# Taking input from user 
age = int(input("Enter your age:"))
salary = int(input("Enter your salary :"))
employment = input("Enter employment type:")

# Checking conditions
if age >= 21 and age <= 60 and salary >= 25000:
    print("Loan approved ")

elif age >= 21 and age <= 30 and salary <30000:
    print("Needs Guarantor")

elif age > 55 and employment == "self-employed":
    print("High Risk - Senior Review Needed")

else:
    print("Loan Rejected")
