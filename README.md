# cu-mvc1-net7
### Dykstra Contoso Tutorial w/MVC using dotnet7 - Part 1
- This repos is being created for students registered in TINFO-431 Server Side Web Applications at UW Tacoma Winter 2023
- This MVC version of the code has been updated so that EF scaffolding works correctly with dotnet7
- It will work correctly with the Tom Dykstra/Rick Anderson tutorial published at:

(https://learn.microsoft.com/en-us/aspnet/core/data/ef-mvc/intro?view=aspnetcore-7.0)

- dotnet7 version of the tutorial requires the following nuget packages:
  - Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design
  - Install-Package Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore
  - Install-Package Microsoft.EntityFrameworkCore.SqlServer

- Program.cs file has been updated to work without a Startup.cs file.
  - The Program class is working correctly for the part 1 tutorial, but code added or modified in future parts could break the order of some statements. We'll have to wait and see. I will test each part before posting and notate the changes.
  - The EF issues dealing with nullable types have been addressed as noted in the Razor Pages part 1, changing the .csproj file and Grade in the Enrollment class, but there could be more - I'm not completely clear on this issue - still reading about it.
#### The remaining parts of the Dykstra/MVC version of the tutorial will be coming soon...
