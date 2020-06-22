Basic Cookiecutter template for a .NET Core Angular 9 SPA (Single-page App).   
Only one setting to change the project name (equivalent of the -o flag in "dotnet new angular" command)
   
This template is basically the default angular .NET Core template but updated to Angular 9 with added workarounds to fix .NET Core 3.1's issues with V9
   
```bash
pip install cookiecutter
  
cookiecutter gh:RichardHancock/cookiecutter-dotnetcore-angular-spa-template
```
    
Template uses Angular 9.1.11 but can be upgraded with this command run inside ClientApp directory:
```bash
ng update @angular/core@9 @angular/cli@9
```
   
This is the source I used for the fixes:
https://jasontaylor.dev/asp-net-core-angular-9-upgrade/
   
I'll try and support if you have any issues, but this was mostly built for my personal use-cases. 