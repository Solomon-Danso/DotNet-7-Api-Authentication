# DotNet-7-Api-Authentication

The database i am using is a local sql database so you need to set your own database and connect it in the DataContext.cs file, located in the Data folder of the root folder 

update this line of code with your own database settings 
optionsBuilder.UseSqlServer("Server=localhost,1433;Database=FlexiApiDb;User=sa;Password=HydotTech;TrustServerCertificate=true;");

Start your database before trying to use the application 

Thank You
