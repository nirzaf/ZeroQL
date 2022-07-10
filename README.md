# ZeroQL | ![GitHub](https://img.shields.io/github/license/byme8/zeroql?style=flat-square) ![Nuget](https://img.shields.io/nuget/v/zeroql?style=flat-square)

The ZeroQL is a high-performance C#-friendly GraphQL client. It supports Linq-like syntax and provides performance close to a simple HTTP call.

# How to use


``` bash
dotnet new classlib -o QLClient # create class library
cd QLClient 
curl http:/localhost:10000/graphql?sdl > schema.graphql # fetch graphql schema from server(this step can vary depending on your web server)
dotnet new tool-manifest
dotnet tool install ZeroQL.CLI
dotnet add package ZeroQL --prerelease
```