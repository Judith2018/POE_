# POE_
Read ME FILE 

1. Introduction 
The Recipe Management Application is a Windows-based software tool that allows users to manage their recipes effectively. Users can add new recipes, filter existing ones, view recipe details, and see a pie chart distribution of food groups. 

2. Features 
These are the following features: Add, filter, and view recipes. User can input detailed recipe steps, display a pie chart of food group distribution. Clear all recipes with a single click. 

3. System Requirements 
Operating System: Windows 7 or higher 
.NET Framework: 4.7.2 or higher 
Development Environment: Visual Studio 2019 or later 

4. Compilation Instructions 
Prerequisites, Install Visual Studio 2019 or a later version and ensure .NET Framework 4.7.2 or higher is installed. 
Steps to Compile 
Clone the Repository: 

  

bash 

Copy code 

git clone https://github.com/username/recipe-management-app.git 

Replace https://github.com/username/recipe-management-app.git with your repository URL. 

  

Open the Project in Visual Studio: 

  

Navigate to the cloned repository directory and open RecipeApp.sln using Visual Studio. 

Restore NuGet Packages: 

  

Visual Studio will prompt you to restore NuGet packages. Click Restore to download and install the required packages, including OxyPlot. 

Build the Project: 

  

In the Solution Explorer, right-click on the solution and select Build Solution or press Ctrl + Shift + B. 

Verify Build Success: 

  

Ensure there are no errors in the Output window. You should see the message Build succeeded. 

5. Running the Application 

From Visual Studio 

Start Debugging: 

  

Press F5 or click on the Start Debugging button (green arrow) in the toolbar. 

Using the Executable: 

  

Navigate to the bin\Debug\net472 directory (or appropriate output directory based on your build configuration). 

Run RecipeApp.exe. 

From Command Line 

Navigate to the Output Directory: 

  

bash 

Copy code 

cd path\to\repository\bin\Debug\net472 

Run the Application: 

  

bash 

Copy code 

RecipeApp.exe 

6. Changes Based on Feedback 

Based on feedback from the lecturer, the following enhancements were made to the Recipe Management Application: 

  

Added Recipe Steps Field: 

  

A new textbox for recipe steps was added in the Add Recipe window, allowing users to enter detailed instructions for preparing each recipe. 

The Recipe class was updated to include a Steps property to store these instructions. 

Displayed Steps in Recipe Details: 

  

The Recipe Details window was modified to display the recipe steps along with other details like ingredients, food group, and calories. 

Implemented Food Group Pie Chart: 

  

A feature was added to display a pie chart that shows the distribution of different food groups across the recipes, providing users with a visual representation of their diet composition. 

These changes enhance the application's functionality by making it more user-friendly and informative. 
