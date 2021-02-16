# aspNet-Entity-scaffold-crud
To Create in console
* dotnet restore
* dotnet ef migrations add InitialMigration
* dotnet ef database update
* dotnet aspnet-codegenerator controller -name ContactsController -m Contact -dc ContactsContext --relativeFolderPath Controllers --useDefaultLayout --referenceScriptLibraries
