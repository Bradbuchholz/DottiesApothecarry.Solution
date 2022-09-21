# Dottie's Apothecary
_By Arthur Edward Ortiz, Sean Keane, Ryan Rendon, Brad Buchholz_

## Description

_This project was created for Epicodus bootcamp as our C# Team Week project. ._ 

## Technologies Used 
* C#
* dotnet
* .Net 5.0
* MYSQL
* CSS
* HTML 
* Boostrap
* Markdown
      

## Setup / Installation 

1. Download and install `dotnet 5.0` 
2. Clone the GitHub [repository](https://github.com/ArthurEOrtiz/DottiesApothecarry.Solution.git) onto your computer.
3. Make sure to have MySql Workbench installed on your computer.
4. Make sure to have dotnet-ef installed - this project uses **`version 5.0.1`**. I have it globally installed, but you can also install it just in this directory. 
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
    "DefaultConnection": "Server=localhost;Port=3306;database=doetties_apothecary;uid=root;pwd=superawesomestrongpassword;"
  }
}
```

## Known Bugs 

## License
_Copyright (c) September 18th, 2022 Arthur Edward Ortiz, Sean Keane, Ryan Rendon, Brad Buchholz MIT_