# netcore-psql-util

.NET core postgresql util

## install and usage

browse [myget istructions](https://www.myget.org/feed/devel0/package/nuget/netcore-psql-util)

## how this project was built

```sh
mkdir netcore-psql-util
cd netcore-psql-util

dotnet new sln
dotnet new classlib -n netcore-psql-util

dotnet sln netcore-psql-util.sln add netcore-psql-util/netcore-psql-util.csproj
dotnet restore
dotnet build
```
