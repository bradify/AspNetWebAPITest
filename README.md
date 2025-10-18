# ASP.NET Core 9 - Configuring Swagger for Building Minimal Web API Projects with Visual Studio Code

## What?
An [ASP.NET Core 9](https://learn.microsoft.com/en-us/aspnet/core/release-notes/aspnetcore-9.0?view=aspnetcore-9.0) Minimal Web API sample project that can be easily tested and debugged with [Swagger](https://swagger.io).

## Why?
Building and debugging ASP.NET Core 9 APIs with Visual Studio Code tooling just got a bit more tricky. Prior versions of ASP.NET Core leveraged [Swashbuckle](https://learn.microsoft.com/en-us/aspnet/core/tutorials/getting-started-with-swashbuckle?view=aspnetcore-8.0&tabs=visual-studio) to generate objects from routes, controllers, and models to expose Swagger JSON.

**But [Swashbuckle no longer works starting in ASP.NET Core 9](https://github.com/dotnet/aspnetcore/issues/54599)**

[ASP.NET Core 9 supports the generation of OpenAPI documents](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/openapi/overview?view=aspnetcore-9.0&preserve-view=true) in controller-based and minimal APIs apps. The implentation of the [OpenAPI Specification](https://spec.openapis.org/oas/latest.html) enables humans and software (like Swagger middleware) to easily discover and understand you web service's operations and endpoints.

This project demonstrates the configuration that you can mimic in your own application so that you can quickly build, debug, and test ASP.NET Core 9 minimal web APIs.

## What? (Pre-requisites)
In order to run this project, you'll need to setup you dev environment:
- Download and install Visual Studio Code (Linux, Mac, or Windows) from: https://code.visualstudio.com
- Install Extensions
  - C# Dev Kit (published by Microsoft). This will also install the C# extension becuase C# Dev Kit depends on the C# extension.
  - Connect your Microsoft Account with the C# Dev Kit
  - Install the .NET 9 SDK (using the Install button on the C# Dev Kit welcome back within Visual Studio Code)

## How
- Install the pre-requisites to setup Visual Studio Code
- Load this project, Run and Debug
- See that your web browser launches automatically with Swagger