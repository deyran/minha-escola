# [[sharpcorner]](https://www.c-sharpcorner.com/article/simple-login-application-using-Asp-Net-mvc/)

## CREATE DATABASE
1. Open *Microsoft SQL server Managment Studio* and create Database called *sharpcornerDB* [[1]](https://support.mailessentials.gfi.com/hc/en-us/articles/360015116400-How-to-create-a-new-database-in-Microsoft-SQL-Server)
2. Click on *New Query* and insert the code below:
```js
    Create Table UserProfile  
    (  
        UserId int primary key identity(1, 1),  
        UserName varchar(50),  
        Password varchar(50),  
        IsActive bit  
    );

    Insert into UserProfile  
    Select 'jaipal', 'jai1234', 1 Union All  
    Select 'praveen', 'praveen1234', 1 Union All  
    Select 'pruthvi', 'pruthvi1234', 1 
```  
3. Run de code  

## CREATE A MVC PROJECT
1. These steps can be used to create a Web Application  -> [[2]](https://github.com/deyran/pro-asp-net-mvc/blob/main/CHAPTER%207%20-%20SPORTSSTORE%20-%20A%20REAL%20APPLICATION/AA%20GETTING%20STARTED.md)
2. Call the project *sharpcornerWeb*  

## PREPARING A DATABASE
1. In the top menu, open the Server Explorer window (View > Server Explorer)
2. In *Data Connections* right-click and choose *Add Connection*  
3. Set the fields to match the pictures below  <br />
    ![Add Connection](/REQUISITOS%20FUNCIONAIS/03%20-%20LOGIN/0301%20-%20sharpcorner/Pictures/sharpcornerPIC00.png)  

## ADD A CONTROLLER
## CREATE A VIEW

minhaescola
    Requisitos Funcionais
        3. Login
            sharpcorner
                PREPARING A DATABASE