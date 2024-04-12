# PROG6221POE-
This is the first part of PROG6221
README for Recipe Manager Application
Overview
The Recipe Manager Application is a simple console-based C# program designed to help users manage cooking recipes. It allows users to create recipes, add and adjust ingredients, include preparation steps, and manage these recipes through a simple interface. This program is particularly useful for both beginner and experienced cooks who want to organize and manipulate their recipes digitally.
Features
Create New Recipes: Start a fresh recipe to add ingredients and steps.
Add Ingredients and Steps: Dynamically add ingredients with their quantities and units, as well as detailed cooking steps.
Scale Recipe Quantities: Easily scale the entire recipe's ingredient quantities by a desired factor (e.g., for serving more or fewer people).
Reset Quantities: Revert all ingredient quantities to their original values.
Display Recipe: View the complete list of ingredients and cooking steps formatted neatly.
Clear Recipe: Remove all ingredients and steps from the current recipe, allowing you to start anew without creating a new recipe object.
Exit: Safely exit the program.
How to Use
Starting the Program: Run the program using a C# compatible IDE or a command line tool that supports .NET.
Navigating the Menu: Use the displayed menu options to select what you would like to do:
[N]ew recipe: Clears the current recipe and starts a new one.
[A]dd details: Adds ingredients and steps to the current recipe.
[S]cale: Scales the recipe's ingredients by a specified factor.
[R]eset: Resets all ingredient quantities to their original amounts.
[D]isplay: Displays the current recipe details.
[C]lear: Clears all details from the current recipe.
[E]xit: Exits the application.
Adding Details: When adding ingredients or steps, follow the prompts to enter the appropriate details.
Classes and Methods
Program: Contains the main entry point of the application.
Ingredient: Manages the properties of ingredients including name, quantity, and unit. Allows scaling and resetting of quantities.
Recipe: Holds a list of ingredients and preparation steps, and includes methods to manipulate these lists.
RecipeManager: Contains the logic for the user interface and interaction flow.
Requirements
.NET Framework or .NET Core installed on your system.
An IDE (like Visual Studio) or a simple text editor and command line setup for running C# applications.
Running the Application
Clone/download the source code to your local machine.
Open the project in your IDE or navigate to the directory in your command line interface.
Build and run the program using the .NET CLI commands or through your IDE's run command.
Troubleshooting
Ensure all .NET dependencies are correctly installed.
Check for typing errors in the console inputs which may cause the program to behave unexpectedly.
For numeric inputs, entering non-numeric data will cause errors.
Conclusion
The Recipe Manager Application provides a straightforward tool for managing recipes through a console interface. It is designed for ease of use and modifiability, making it a suitable base for further expansion or customization according to specific culinary needs or preferences
