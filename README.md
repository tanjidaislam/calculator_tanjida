#Description of Calculator (Tanjida)

#Library Used: Tkinter
Tkinter is Python's standard GUI (Graphical User Interface) library that provides a fast and easy way to create desktop applications. It's a thin object-oriented layer on top of Tcl/Tk, making it Python's de facto standard GUI package. The library comes pre-installed with most Python distributions, making it readily accessible for developers.

#Application Structure
The calculator application is built using a simple yet effective structure. It consists of a main window created using Tk() that serves as the container for all interface elements. The window includes an entry field for displaying input and results, along with a grid of buttons for numbers and operations.

#User Interface Components
The calculator features a clean interface with a prominent entry field at the top, styled with Arial font and a right-aligned justification for better readability. Below the entry field is a 4x4 grid of buttons including:

Numeric buttons (0-9)
Basic arithmetic operators (+, -, *, /)
Clear button (C)
Equals button (=)
Each button is uniformly sized with adequate padding (20 pixels) and uses Arial font for consistency in appearance.

#Functionality
The calculator implements basic arithmetic operations through a central press() function that handles all button interactions. When numbers or operators are pressed, they are appended to the entry field. The equals button triggers the evaluation of the mathematical expression using Python's eval() function, while the clear button (C) removes all content from the entry field. Error handling is implemented to display "Error" when invalid expressions are evaluated.

#Layout Management
The application uses Tkinter's grid layout manager to organize interface elements. The entry field spans across all four columns at the top (row 0), while the buttons are arranged in a 4x4 grid below it. This creates a traditional calculator layout that is both functional and familiar to users
