Welcome to the aspnetcore-generatorapi wiki!

Sample ASP.NET Core API that generates random data, has swagger UI too. This supports Docker container, hosts

mailhog smtp server
Aspnet core web api that generates random data
Steps to host Docker container

Download source code
Open PowerShell and change directory to #sourcecode\api
Run command “dotnet build”
Once compiled successfully, 
run "dotnet publish" 
then “docker-compose up”
Access 
a.	http://localhost:8090 to access web api Web Api 
![https://github.com/rajeshmuraleedharan/aspnetcore-generatorapi/blob/master/webapi.PNG](https://github.com/rajeshmuraleedharan/aspnetcore-generatorapi/blob/master/webapi.PNG)
b.	http://localhost:8025/# to access mailhog client mailhog
![https://github.com/rajeshmuraleedharan/aspnetcore-generatorapi/blob/master/mailhogclient.PNG](https://github.com/rajeshmuraleedharan/aspnetcore-generatorapi/blob/master/mailhogclient.PNG)
