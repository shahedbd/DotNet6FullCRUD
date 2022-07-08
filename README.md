# Dot Net 6 Full CRUD
Learn ASP.NET Core MVC | .NET 6 | Full Course for Beginner | EF Core | MSSQL | Beginner Tutorials

💻 
Learn the basics of .NET Core (.NET 6) and then build a simple CRUD application with MVC and Entity Framework core code first in these complete tutorials.

Full Video:
https://www.youtube.com/watch?v=5vpA2Hg8hp4&


<b>Summary</b>
- Dot NET Core 6.0 Project
- MSSQL Database connection
- Entity Framework Core
- Code First 
- CRUD Operation


So, Let's create the project step by step:
- Create Project: VS 2022
- Add NuGet dependency
1. Install-Package Microsoft.EntityFrameworkCore -Version 6.0.6
2. Install-Package Microsoft.EntityFrameworkCore.SqlServer -Version 6.0.6
3. Install-Package Microsoft.EntityFrameworkCore.Tools -Version 6.0.6

<hr />

- DB connection
```
"ConnectionStrings": {
        "DefaultConnectionMSSQLNoCred": "Server=DEVSTATION\\MSSQLSERVER2017;Database=BusinessERP;Trusted_Connection=True;MultipleActiveResultSets=true"
    },
```

- Run migration
add-migration InitialCreate
update-database

Categories: CRUD
1. Create Model: Database Table
add int DB Context:
 public DbSet Categories Categories { get; set; }
2. Create View Model: For Display data in UI
Plus: Mapping
3. Create a Controller
4. Create a View
5. Create JS for View


Ref:
https://github.com/shahedbd/DBConnectionDotNet6
