Technology - Dot Net Core
3.1, EF Core, HTML and Database Sql Server

We have used EF Core ode first approach here. Below steps would be used to create the database and tables.
1) Go to SqlServer Management Studio.Connect to local DB ( using . or localhost)
2) Create a database with name "test_ECommerceDB"
3) Go to Visual Studio Menu >> Tools >> NuGet Package Manager >> Package Manager Console and run below commands:
 Update-Database -Context ECommerceDbContext