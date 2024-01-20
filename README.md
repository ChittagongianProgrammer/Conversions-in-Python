# Conversions-in-Python
 Here is an explanation of the code in the two Jupyter notebook files that could be used for a README file on GitHub:

## Temperature Conversion.ipynb

This notebook implements a temperature converter that can convert between Celsius and Fahrenheit. 

It contains the following functions:

- `celsius_to_fahrenheit(c_temp)` - Converts a temperature from Celsius to Fahrenheit by using the formula F = C x 9/5 + 32
- `fahrenheit_to_celsius(f_temp)` - Converts a temperature from Fahrenheit to Celsius by using the formula C = (F - 32) x 5/9

The main code:

- Asks the user to input 'C' to convert Celsius to Fahrenheit, or 'F' to convert Fahrenheit to Celsius
- Gets a temperature input from the user based on their choice
- Calls the appropriate conversion function to convert the input temperature
- Prints out the converted temperature rounded to 2 decimal places

It handles invalid inputs by printing an error message if the user enters anything other than 'C' or 'F'.

## Weight Conversion.ipynb 

This notebook converts a weight between kilograms and pounds.

The code:

- Asks the user to input whether they want to measure in 'Kilograms' or 'Pounds'
- Gets a weight input from the user 
- Uses conditional logic to check the unit of measurement 
  - If Pounds: Converts to kg by dividing by 2.205
  - If Kilos: Converts to lbs by multiplying by 2.205
- Prints out the converted weight rounded to 2 decimal places and the new unit

The notebook shows how to chain together input, conditional logic, math operations, print formatting to implement a simple weight conversion application.

Let me know if any part needs more explanation!
