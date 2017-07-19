
# Philly.NET 15 minutes of Fame
EF Core Framework example

This is a simple project that has dbcontext and migrations in it.

Dotnet ef migrations add {name of migration}

Dotnet ef database update

## Reverse Engineer a database

Add these pacakges:

Install-package Microsoft.EntityFrameworkCore.SqlServer
install-package Microsoft.EntityFrameworkCore.Tools
Install-Package Microsoft.EntityFrameworkCore.SqlServer.Design

Scaffold-DbContext "{your server connection}" Microsoft.entityFrameworkCore.SqlServer -OutputDIr Models
