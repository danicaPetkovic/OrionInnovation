# OrionInnovation
In OrionApp -> appsettings.json file there is a connection string to the db - change it if neccessery.

In OrionApp -> appsettings.json file there is a api base path for API app - change it if neccessery.

EF code First approach is used. The migration is already created.

In Package Manager Console set Default Project to "Data".

Execute -> update-database.

Multiple Startup Projects are set, if there is an error, just set the "ClientApp" to be the only Start up project and execute update-database again.
