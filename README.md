# iSmart_Blogger

iSmart_Blogger is a powerful MVC web application built using ASP.NET Core that enables bloggers to create, manage and publish their blog posts effortlessly. The application follows the Model-View-Controller (MVC) architectural pattern, separating the application's concerns into three distinct components, improving modularity and scalability.

The Model component defines the data structure and how the data is accessed, managed and manipulated, using technologies like Entity Framework Core, SQL Server, and LINQ. The View component defines the presentation and user interface of the application, using Razor syntax to generate HTML markup. The Controller component defines the application's logic, handling user input, coordinating the interactions between the Model and View components, and rendering responses back to the user.

iSmart_Blogger offers a user-friendly interface for bloggers to create, edit, and publish their blog posts, with support for rich-text formatting, images, and media. The application supports user authentication and authorization, allowing bloggers to manage their own posts and granting admin privileges to site administrators. The application also includes features like search, categories, tags, and comments to enhance the user experience and encourage user engagement.

Overall, iSmart_Blogger is a reliable and robust solution for bloggers who want to share their ideas, stories, and expertise with the world, without worrying about the technical complexities of building and maintaining a blogging platform.

#To run this project run these commmand below and install mentioned tools and sdk :

Install VS 2022 Install .net core 7 sdk Install SSMS & SQL Server

#open appsetting.json file and make sure your server name in connection string

#After clone this project into vs 2022

open nuget package manager console from tools option in navbar

#Run these two command for data migration

update-database -context BloggieDbContext <br>
update-database -context AuthDbContext
