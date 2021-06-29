<br>
<h1 align = "center">
<b> PierreSweets </b>
</h1>

<p align = "center">
This application allows the user to keep track of PierreSweets bakery using a login feature</p>
<p align = "center"> Created May 6/20/21 </p>

<p align = "center">
 By Andrew Mickel
 </p>

--------------------

## 📖  Description

Pierre's Business is booming and he needs the same pizazz that we applied to his bakery to help sell his new sweet and savory treats! He wants to be able to have a list of treats, as well as a list of flavors and to be able to associate them so that he can have multiple flavors for each treat and vice-versa. He also wants his employees to be able to log in so that they can add, update, delete, and associate treats and flavors, while customers will only be able to view what is available for the day.

This project uses C#, MySQL, Entity Framework, Microsoft Identity, and MVC to create a web interface that will allow the greatest video rental franchise of all time to maintain a daily menu of treats, categorize them by flavor, and allow authorized users to employ full CRUD functionality. The interface will achieve this by utilizing a MySQL database along with Identity authorization.

--------------------

## 🛠️ Technologies Used

This project uses the following technologies:

- C# v7.3.0
- .NET Core v2.2.0
- ASP .NET MVC
- ASP .NET Core Razor Pages
- MySQL
- MySQL Workbench
- Entity Framework Core

-------------------

## Specifications

| Behavior | Input | Output |  Completed(Y/N?)  |
| -------- | ----- | ------ | -------- |
| Create an object called Treat with an auto-implementing property for its Name |  |  | Y |
| Create an object called Flavor with an auto-implementing property for its Name | | | Y |
| Allow authorized users to create a new Treat object through a user interface |  |  | Y |
| Allow authorized users to create a new Flavor object through a user interface |  |  | Y |
| Create a database with tables for Treat and Flavor objects using Entity Framework and code first development and database migrations | | | Y |
| Maintain a many-to-many relationship between Treat and Flavor objects via a joing table | | | Y |
| Allow authorized users to create a new join relationship between an Treat and a Flavor from each object's details page | | | Y |
| Allow unauthenticated users to view a list of Treats and Flavors, as well as their details page | | | Y |
| Restrict unauthenticated users from Creating, Editing, Deleting, or Associating Treat or Flavor objects | | | Y |

-------------------

## 🐛 Known Bugs


-------------------

## 🔧 Setup & Requirements

### 📋 Necessary Specifications

#### To run this project locally you will need:

- **ASP .NET Core :** You can check if you have .NET Core by running `dotnet --version` in the command line. If you do not have .NET Core please find more information and download [here](https://dotnet.microsoft.com/download/dotnet-core)
- **MySQL :**  You can download MySQL [here](https://dev.mysql.com/downloads/file/?id=484914) and MySQL Workbench [here](https://dev.mysql.com/downloads/file/?id=484391)
- **Prefered Code Editor**


### ⚙️ Clone or Download

#### To Download:

Go to my GitHub repository here, [https://github.com/AndrewMMickel/PierreSweetsFactory](https://github.com/AndrewMMickel/PierreSweetsFactory), and click on the green 'Code' button to clone the repository, Open with GitHub Desktop OR Download the ZIP file

#### To clone (my prefered method):

1. Push the green 'Clone' button and copy the URL.
2. Open Terminal or GitBash and input the command: `git clone https://github.com/AndrewMMickel/FINISH-URL`
3. To view the code, open the copied directory with Visual Studio Code or your preferred text editor by inputing the command `code .` in your terminal.

### 🧰 Database Setup Options

#### AppSettings (option 1):

- After you have the project on your computer you will need to create a file in the root directory of the project called "appsettings.json". 
- Add the following snippet of code to the appsettings.json file:

```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=andrew_mickel;uid=root;pwd=YOUR-PASSWORD-HERE;"
    }
}
```
*Please note you will need to replace `YOUR-PASSWORD-HERE` with the password you created for your MySQL server.
*You may also need to update `uid`, `port`, or `database` name depending on your configurations.

#### Import Database using Entity Framework Core (option 1 continued):

 - In the command line run ` cd Desktop/PierreSweets.Solution/PierreSweets` to navigate to the "PierreSweets" folder. 
 - Next, run `dotnet ef database update` to generate the database. You can confirm the database was created by checking MySQL workbench.

*to make changed to the database you can run `dotnet ef migrations add <MigrationName>`

#### Running/viewing application:

1. Once you have opened the code in your preferred text editor you will need to navigate to the 'PierreSweets.Solution/PierreSweets' folder (`cd PierreSweets`) in the command line and run `dotnet run` or `dotnet watch run`.
2. At this point you should be able to click on the link to the local server's url path to view the compiled project. 

--------------------------

## 📫 Support and contact details

If you run into any problems or have any questions please contact me via [email](mailto:andrew.m.mickel@gmail.com).

---------------------------

## 📘 License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Copyright (c) 2020 Andrew Mickel