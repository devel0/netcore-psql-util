# netcore-psql-util

[![NuGet Badge](https://buildstats.info/nuget/netcore-util)](https://www.nuget.org/packages/netcore-psql-util/)

.NET core postgresql util

## install

- [nuget package](https://www.nuget.org/packages/netcore-psql-util/)

## API

- [API](https://devel0.github.io/netcore-psql-util/api/SearchAThing.PsqlUtil.Util.html)

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
