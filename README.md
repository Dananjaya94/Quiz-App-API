# Quiz-App-API
This ASP.Net Core Web Api is created to work as the backend of the Quiz App created using React.js. Link to Quiz App https://github.com/Dananjaya94/Quiz-App

#Initialize thw database
To initialize the databse, use the following commands in Nuget Pckage Mnager console.
Step 01:
  **Add-Migration "Inirial create" ** 
  if this command is not working 
  **EntityFrameworkCore\Add-Migration "Inirial create" **

Step 02:
  **Update-Database**
  if this command is not working 
  **EntityFrameworkCore\Update-Database **
  
These commands will create the necessary tables to run the application in your localhost.
