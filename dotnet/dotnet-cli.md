## create new project

`dotnet new` list installed templates

## working with solutions

https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-sln

````
dotnet new sln
dotnet new console --output folder1/folder2/myapp
dotnet sln add folder1/folder2/myapp
````

## new api project

 ````
  dotnet new sln
  dotnet new webapi --output api
  dotnet sln add api
  
 ````

## api with aad auth

https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-new-sdk-templates#webapi

````
dotnet new webapi --auth SingleOrg --client-id xxx --domain foo.onmicrosoft.com --tenant-id <guid> 
````
