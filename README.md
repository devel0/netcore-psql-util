# netcore-psql-util

[![NuGet Badge](https://buildstats.info/nuget/netcore-util)](https://www.nuget.org/packages/netcore-psql-util/)

.NET core postgresql util

## install

- [nuget package](https://www.nuget.org/packages/netcore-psql-util/)

## API

- [Util](doc/api/PsqlUtil/Util.md)

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
