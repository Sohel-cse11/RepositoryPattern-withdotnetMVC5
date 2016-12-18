This project is developed by using 
1. ASP.NET MVC 5
2. Entity Framework 6.1.3
3. Design Pattern : Repository Pattern 

# Installation instructions

    Build solution to restore packages
    Rebuild solution
    Change the connection strings inside the Web.config accoarding to your development environment
    Open Package Manager Console
    run the following commands
        add-migration "initial"
        update-database -verbose
    Run the application
    
# OR
   by using SQl Server Management Studio 
   import database from Databas file/Person.bacpac
   Run the  application
