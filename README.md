# Age-Calculator-with-Tkinter
Explanation:

Import Libraries:

tkinter is imported for creating the GUI.
datetime is imported to get the current year.
Define calculate_age() Function:

Retrieves the birth year from the entry field.
Calculates the age using the current year.
Updates the age label with the calculated age.
Create Main Window:

The tk.Tk() constructor creates the main window.
The title() method sets the window's title.
Create Widgets:

A label for the birth year prompt is created.
An entry field for the user to input their birth year is created.
A button to trigger the age calculation is created.
A label to display the calculated age is created.
Pack Widgets:

The pack() method organizes the widgets in the window.
Run Main Loop:

The mainloop() method starts the event loop, keeping the GUI running and responsive to user interactions.
To use the program:

Save the code as a Python file (e.g., age_calculator.py).
Run the file from your terminal using python age_calculator.py.
Enter your birth year in the entry field.
Click the "Calculate Age" button to see your age displayed in the label.
