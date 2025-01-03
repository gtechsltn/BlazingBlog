# BlazingBlog - A fullstack Blog Web App using Blazor Server 
> BlazingBlog - A fullstack blog web app using Blazor Server, EF Core and SQL Server- .Net 7

https://github.com/gtechsltn/BlazingBlog

https://github.com/gtechsltn/BlazingChat

## Screenshots

#### Home Page
![Blazing-Blog-Home-Page-Abhay-Prince](https://raw.githubusercontent.com/Abhayprince/BlazingBlog/master/screenshots/1.png)

--------------------------------------------
#### Blog Post Detail Page
![Blazing-Blog-Detail-Page-Abhay-Prince](https://raw.githubusercontent.com/Abhayprince/BlazingBlog/master/screenshots/2.png)

--------------------------------------------
#### Manage Categories Page
![Blazing-Blog-Manage-Categories-Page-Abhay-Prince](https://raw.githubusercontent.com/Abhayprince/BlazingBlog/master/screenshots/3.png)

--------------------------------------------
#### Manage Blog Posts Page
![Blazing-Blog-Manage-Blog-Page-Abhay-Prince](https://raw.githubusercontent.com/Abhayprince/BlazingBlog/master/screenshots/4.png)

--------------------------------------------
#### Create/Edit Blog Post Page
![Blazing-Blog-Save-Blog-Page-Abhay-Prince](https://raw.githubusercontent.com/Abhayprince/BlazingBlog/master/screenshots/5.png)

## To Run Locally
- Clone the Repo
    `git clone https://github.com/Abhayprince/BlazingChat `
    
- Restore the packages (Rebuild the solution)
    
- Change the Database connection string in `appsettings.Development.json` file in the Project
    ```
    "ConnectionStrings": {
        "Blog": "Data Source=.;Initial Catalog=BlazingBlog;Integrated Security=True; Trusted_Connection=True;Encrypt=False"
     }
     ``` 
     
- Run the migrations - to update the database using following Package Manager Console Command
    
    `Update-Database`

- Run the solution

- Congratulations, BlazingBlog  app is running
---------------------------------------
## Live Coding Video Series of Blazing Chat
> If you want to see this project build with live coding, checkout the detailed video series on my youtube channel
> 
> [Building Blog App with Blazor Server - YouTube](https://www.youtube.com/playlist?list=PLlgYGDJXMjDZa3WCMX31rkyKo6wXUL8qf)

-------------------------------
## Support Me
> If you like my content and want to support me, 
> 
> Star this Repository
> 
> <a href="https://www.buymeacoffee.com/abhayprince" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-violet.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
