height = input("Enter your height in inches ")
weight = input ("Enter your weigh in pounds ")
BMI = 703 * (int(weight))/(int(height)**2)
print("Your BMI is " + str(BMI))
if (int(BMI) <= 18):
	print("You are underweight")
elif (BMI >=18) and (BMI <= 26):
	print("You are normal weight")
else:
	print("You are overweight")