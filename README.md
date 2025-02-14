employeepay.py
hourly_wage = float(input("Enter the hourly wage: "))
total_regular_hours = float(input("Enter the total regular hours worked: "))
total_overtime_hours = float(input("Enter the total overtime hours worked: "))
regular_pay = hourly_wage * total_regular_hours
overtime_pay = 1.5 * hourly_wage * total_overtime_hours
total_weekly_pay = regular_pay + overtime_pay
print("The total weekly pay is:", total_weekly_pay)

minutes.py
years = float(input("Enter the number of years: "))
minutes = years * 365.25 * 24 * 60
print("The minutes in years is:", minutes)

taxform
income = float(input("Enter your annual income: "))
tax_rate = float(input("Enter the tax rate (as a decimal): "))
tax = income * tax_rate
tax = round(tax, 2)
print("The tax is:", tax)
