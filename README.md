# jsreport.Binary.Ph2
[![Build status](https://ci.appveyor.com/api/projects/status/lwfukhlj432twa0c?svg=true)](https://ci.appveyor.com/project/pofider/jsreport-dotnet-binary-ph2)
[![NuGet](https://img.shields.io/nuget/v/jsreport.Binary.Ph2.svg)](https://nuget.org/packages/jsreport.Binary.Ph2)

This package includes the raw [jsreport.exe binary](https://jsreport.net/learn/single-file-executable) embedded in the manifest stream. This allows very easy attaching of jsreport into .net projects. The binary can be used directly but it is recommended to use another package [jsreport-local](https://github.com/jsreport/jsreport-dotnet-local) which adds simple to use wrapper around.

The releases of this package should match the release number of jsreport itself and always include the particular binary. This means you can choose which version of jsreport you want to use, because the sdk it self is agnostic to it.

You can find examples and documentation in the [jsreport sdk for .net home page](https://jsreport.net/learn/dotnet).
The general development and contribution instructions can be find in the [jsreport for .net  root repository](https://github.com/jsreport/jsreport-dotnet).
