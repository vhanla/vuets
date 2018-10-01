# SPA Template for ASP.NET Core 2.1 + VueJS + TypeScript + WebPack 4

This is a modified template based upon official Microsoft.AspNetCore.SpaTemplate::*

**IMPORTANT** It's strongly recommended to use Bootstrap 4.1.2 or newer. It's relatively easy to migrate.

As of now, official template uses Webpack 2 and older NPM packages, and it hasn't been migrated to .Net Core 2.1.

![snap](https://cdn-images-1.medium.com/max/800/1*4PCyQ7-L4a3igqxOfsjSDA.png)

## This template has the following changes:

- Migrated to .Net Core 2.1
- Updated NPM packages except BootStrap 3
- Supports WebPack 4

Other than that it has minor changes to VueJS original files.

## How to install:

Just clone or download this repo, and install as follows:

```
dotnet new --install <path to this template directory>
```
You can see it listed `dotnet new -l` with the shortname `vuets` so in order to create new projects using this template just use that shortname.

```
dotnet new vuets -n myspa -o myspa
cd myspa
dotnet restore
npm install
dotnet run
```
To publish, just as usual: `dotnet publish -c release`

## Disclaimer

All rights belongs to the original authors, this is a repository for education purposes as part of this article at https://medium.com/@vhanla/creating-a-vuejs-with-typescript-spa-on-asp-net-core-2-1-5efaee226154
