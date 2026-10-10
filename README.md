# PR5 – Academic Calendar & Leave Management System

.NET Technologies (01CE1523) – Experiment 5
Aim: Develop Academic Calendar & Leave Management System using Rich Controls, Session & Cookies.

## Pages
- **Default.aspx** – Calendar (rich control). Select a date and click *Apply Leave*; the date is passed to Leave.aspx via query string.
- **Leave.aspx** – Leave application form. On submit, details are stored in **Session** and the employee name in a **Cookie** (`EmployeeInfo`, 7 days). On revisit, the name is pre-filled from the cookie and the previous application is shown from Session. *Logout* clears the Session and expires both cookies.

## How to run
1. Extract the zip and open `PR5.sln` in Visual Studio 2022 (ASP.NET and web development workload, .NET Framework 4.8.1 targeting pack).
2. Right-click the solution → **Restore NuGet Packages** (VS usually does this automatically on build).
3. Set `Default.aspx` as the start page and press **F5** to run on IIS Express.
