# .Net + MySQL + React JS CRUD Application Example
# After completing this tutorial what we will build? 
We will build a full-stack web application that is a basic User Management Application with CRUD features: 

• Create User 

• List User 

• Update User 

• Delete User 

• View User

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhI1-5A8pPKNYkDAiLgCclIbeE_BOcJPw8CZgU5lXaRDyOv9RsRyWhctgn-ouIkWkXGiF6-cyOSXNe7ANxhWmMeNUUk9PFgSKYyhsyLY5ffe2icicf72AfhGOPmwtl2tO_e0HI9YOGkefB8kIOPCMsghI00qSyh_EKAlYjNNGlnJ78CnBJWNeTx-PEY5A/s1308/userlist.png">


# Local Setup and Run the application

<h2>Create database and table</h2>

```CREATE DATABASE testdb;```

```
CREATE TABLE users(
 id INT PRIMARY KEY AUTO_INCREMENT, 
 first_name VARCHAR (20) NOT NULL, 
 last_name VARCHAR (20) NOT NULL, 
 email VARCHAR (20) NOT NULL 
);

```

<h2> Download or clone the source code from GitHub to the local machine</h2>

<h2> Backend</h2>

You can start the api by running ```dotnet run``` from the command line in the project root folder (where the WebApi.csproj file is located)

OR

You can also start the application in debug mode in Visual Studio by opening the project root folder in Visual Studio and pressing F5 or by selecting Debug -> Start Debugging from the top menu, running in debug mode.

<h2>Frontend</h2>

```npm install```

```npm start```

<h2>From the browser call the endpoint http://localhost:3000</h2>
