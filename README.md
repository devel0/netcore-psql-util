# netcore-psql-util

[![devel0 MyGet Build Status](https://www.myget.org/BuildSource/Badge/devel0?identifier=4f3ad9fa-f5b8-4b0d-a9e1-3f19cd58e76a)](https://www.myget.org/)

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
