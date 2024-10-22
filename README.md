# Python BMI Calculator

## Project Description
This Python program calculates a user's Body Mass Index (BMI) based on their height and weight inputs. After calculating the BMI, the program categorizes the result as underweight, normal weight, overweight, or obesity based on standard BMI ranges.

## Features
- Collects height (in meters) and weight (in kilograms) from the user.
- Calculates the BMI using the formula:
\[
  \text{BMI} = \frac{\text{weight (kg)}}{\text{height (m)}^2}
\]
- Categorizes the BMI into:
  - Underweight (BMI < 18.5)
  - Normal weight (BMI 18.5 - 24.9)
  - Overweight (BMI 25 - 29.9)
  - Obesity (BMI ≥ 30)
- Displays the BMI value and its corresponding category.

## How It Works
1. The user inputs their height in meters and weight in kilograms.
2. The program calculates BMI using the formula: `BMI = weight / (height ** 2)`.
3. It then uses conditional statements to categorize the BMI result into one of the four categories (underweight, normal weight, overweight, obesity).
4. The program outputs the calculated BMI along with its category.

## Requirements
- Python 3.x

## How to Run the Script
1. Clone or download the project.
2. Open a terminal or command prompt in the project directory.
3. Run the following command:
   ```bash
   python bmi_calculator.py
