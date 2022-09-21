# Dottie's Apothecary
_By Arthur Edward Ortiz, Sean Keane, Brad Buchholz_

## Description

_This project was created for our Epicodus C# Team Week project._ 

## Technologies Used 
* CSS
* HTML 
* dotnet
* .Net 5.0
* Boostrap
* MYSQL
* Markdown       

## Setup / Installation 

1. Download and install **`dotnet 5.0`**
2. Clone the GitHub [repository](https://github.com/ArthurEOrtiz/DottiesApothecarry.Solution.git) onto your computer.
3. Make sure to have MySql Workbench installed on your computer.
4. Make sure to have dotnet-ef installed - this project uses **`version 5.0.1`**. We have it globally installed, but you can also install it just in this directory. 
5. Open the project in VScode or your terminal of choice. 
6. Create an `appsettings.json` file in the `DottiesApothecarry.Solution/DottiesApothecarry/` directory and add the following code, replacing anything in `square brackets` with the information it represents specific to the project database:

```
{
  "Logging": {
    "LogLevel": {
      "Default": "Debug",
      "System": "Information",
      "Microsoft": "Information"
    }
  },
  "AllowedHosts": "*",
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[Database-Name-Here];uid=[User-ID-Here];pwd=[Your-Password-Here];"
  }
}


```
#### Example of complete appsettings.json
```
{
  "Logging": {
    "LogLevel": {
      "Default": "Debug",
      "System": "Information",
      "Microsoft": "Information"
    }
  },
  "AllowedHosts": "*",
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=dotties_apothecary;uid=root;pwd=superawesomestrongpassword;"
  }
}
```
7. Open MySql Workbench and login to your server.
8. From your terminal navigate to the `DottiesApothecarry` folder and run the command **`dotnet ef database update`** to create the database from migrations.
9. Next use the command **`dotnet run`** in your terminal to launch the program.
10. The site should be avaialbe at the local host listed in your terminal. 

[![Dotties-Screen-Shot.png](https://i.postimg.cc/dV6677FB/Dotties-Screen-Shot.png)](https://postimg.cc/4YKVqxm7)
![Setup](Dotties-Gif.gif)

## Known Bugs 
* Custom buttons not working with links.
* Header images not working on views outside of main home. 
## License
_Copyright (c) September 20th, 2022 Arthur Edward Ortiz, Sean Keane, Brad Buchholz MIT_