BMI Calculator in Python

A simple terminal-based Python program that calculates the Body Mass Index (BMI) using a user's height and weight.

 Features
Runs in the terminal / command prompt
Takes user input for height and weight
Calculates BMI using the BMI formula
Displays BMI rounded to 2 decimal places
Shows BMI category automatically
🧮 BMI Formula

BMI=
height
2
weight
	​


Where:

Weight is in kilograms (kg)
Height is in meters (m)
💻 Python Code
# BMI Calculator in Python

# Take user input
height = float(input("Enter your height in meters: "))
weight = float(input("Enter your weight in kilograms: "))

# Calculate BMI
bmi = weight / (height ** 2)

# Display result
print("\nYour BMI is:", round(bmi, 2))

# Interpret BMI
if bmi < 18.5:
    print("Category: Underweight")
elif bmi < 24.9:
    print("Category: Normal weight")
elif bmi < 29.9:
    print("Category: Overweight")
else:
    print("Category: Obese")
▶️ How to Run the Program
Step 1: Save the File

Save the code in a file named:

bmi_calculator.py
Step 2: Open Terminal

Open:

Command Prompt (Windows)
Terminal (Linux/Mac)
Step 3: Run the Program
python bmi_calculator.py

If Python 3 is required:

python3 bmi_calculator.py
📷 Example Output
Enter your height in meters: 1.75
Enter your weight in kilograms: 68

Your BMI is: 22.2
Category: Normal weight
📊 BMI Categories
BMI Range	Category
Less than 18.5	Underweight
18.5 to 24.9	Normal weight
25 to 29.9	Overweight
30 and above	Obese
🚀 Future Improvements

Two practical improvements:

Input Validation
Prevent invalid inputs like negative values
Handle text input errors
GUI Version
Create a graphical interface using Tkinter

Example:

Add buttons for calculation
Display BMI in a popup window
🛠 Requirements
Python 3 installed on your system
