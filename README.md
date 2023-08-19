## Useful dotnet cli COMMANDS

 - Creatinig a Solution file to make it easier to manage multiple
   projects

```powershell
C:\> dotnet new sln -n <SolutionName>
```

 - Adding a Project or Multiple projects to a Solution
```powershell
C:\> dotnet sln <SolutionName> add <ProjectName> <ProjectName>...
```
 - Adding a Project Reference

```powershell
C:\> dotnet add refence ..\path\to\<ProjectFolder>\Project.csproj
```