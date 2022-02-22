Sign In/Out Study in .net 6
=================================

Documents.
-----------

- [Microsoft identity platform documentation](https://docs.microsoft.com/en-us/azure/active-directory/develop/)
- [ASP.NET Core Security の概要](https://docs.microsoft.com/ja-jp/aspnet/core/security/?view=aspnetcore-6.0)

作業手順
-------

[Scaffold Identity in ASP.NET Core projects](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/scaffold-identity?view=aspnetcore-6.0&tabs=visual-studio)

```
Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design
```

```
From Solution Explorer, right-click on the project > Add > New Scaffolded Item.
From the left pane of the Add New Scaffolded Item dialog, select Identity > Add.
In the Add Identity dialog, select the options you want.
Select your existing layout page, or your layout file will be overwritten with incorrect markup:
~/Pages/Shared/_Layout.cshtml for Razor Pages
~/Views/Shared/_Layout.cshtml for MVC projects
Blazor Server apps created from the Blazor Server template (blazorserver) aren't configured for Razor Pages or MVC by default. Leave the layout page entry blank.
Select the + button to create a new Data context class. Accept the default value or specify a class (for example, MyApplication.Data.ApplicationDbContext).
Select Add.
```


