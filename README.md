EmployeeMaintenanceASP
A simple ASP.NET web application for managing employee records. This project demonstrates basic CRUD (Create, Read, Update, Delete) operations using ASP.NET MVC.

Features
Employee record management (Add, Edit, Delete, View)
ASP.NET MVC architecture
Database integration with Entity Framework
Responsive UI with basic styling

Project Structure
EmployeeMaintenanceASP/ – Main project folder containing all source code, views, controllers, and configurations.
EmployeeMaintenanceASP.sln – Visual Studio solution file.
Note: .vs and packages folders are intentionally excluded for GitHub. NuGet packages can be restored automatically.

Prerequisites
Visual Studio 2022
 (or later) with ASP.NET and web development workload installed

.NET Framework / .NET SDK
 as required by the project

SQL Server or SQL Express (if using a local database)

Setup Instructions

Clone the repository
git clone https://github.com/<your-username>/EmployeeMaintenanceASP.git
cd EmployeeMaintenanceASP

Open the solution in Visual Studio
Double-click EmployeeMaintenanceASP.sln.

Restore NuGet packages
Right-click the solution in Solution Explorer → Restore NuGet Packages. This will download all required dependencies.

Build the solution
Press Ctrl+Shift+B or go to Build → Build Solution.

Run the project

Press F5 to run the application in debug mode, or Ctrl+F5 to run without debugging.

Notes
If the database connection is required, update the connectionStrings in Web.config to match your local SQL Server instance. Any changes in .vs settings or packages folder are local and do not affect the project functionality.
