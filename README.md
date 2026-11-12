# EsteticaMVC

Aplicación ASP.NET Core MVC (.NET 8) + Entity Framework Core + SQL Server para el inventario de una estética.

## Cómo ejecutarla
1. Abre `Database/EsteticaDB.sql` en SSMS y ejecútalo (crea la BD y datos de ejemplo).
2. Ajusta `ConnectionStrings:EsteticaConnection` en `appsettings.json` según tu servidor.
3. En la terminal: `dotnet restore` y luego `dotnet run`.
