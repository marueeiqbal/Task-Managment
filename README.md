Task Management Solution (Minimal working example)
Contents:
- backend/TaskManagement.API : ASP.NET Core Web API (Program.cs, controllers, EF Core)
- frontend : Minimal React app
- tests : xUnit sample
- db_init.sql : SQL Server script to create DB and tables

Notes:
- This is a minimal but functional starter. You should replace the Jwt key in backend appsettings.json.
- To run backend on port 5000, use: `dotnet run` (it will pick Kestrel defaults; use launchSettings or env vars as needed).
