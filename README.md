Sample ASP.NET Core API that generates random data, has swagger UI too. This supports Docker container, hosts 
1)	 mailhog smtp server 
2)	Aspnet core web api that generates random data

Steps to host Docker container 
1)	Download source code 
2)	Open PowerShell and change directory to #sourcecode\api
3)	Run command “dotnet build”
4)	Once compiled successfully, 
     run "dotnet publish" 
     then “docker-compose up”
5)	Access 
a.	http://localhost:8090 to access web api
![Web Api](https://github.com/rajeshmuraleedharan/aspnetcoregeneratorapi/blob/master/webapi.PNG)
b.	http://localhost:8025/# to access mailhog client
![mailhog](https://github.com/rajeshmuraleedharan/aspnetcoregeneratorapi/blob/master/mailhogclient.PNG)


