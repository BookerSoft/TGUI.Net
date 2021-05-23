TGUI.Net
========

**This binding is no longber being actively developed. There are currently no plans to update it to TGUI 0.9**

[TGUI.Net](https://tgui.net) is a .Net binding for the [TGUI library](https://github.com/texus/TGUI), a cross-platform GUI for SFML.

[![NuGet](https://img.shields.io/badge/win--x64-blue.svg?label=NuGet&longCache=true)](https://www.nuget.org/packages/TGUI.Net.win-x64/)


Build
-----

Note: These steps are only needed when building from source. It is recommended to use a precompiled version.

First make sure that the submodules are initialized (the folders in the `extlibs` folder should not be empty). If these folders are still empty, run the following command:

``` c++
git submodule update --init --recursive
```

Go into the `build` directory and run `build.bat` to build TGUI.Net and all of its dependencies.


Usage
-----

The dotnet dll files can be found in the `lib` folder, they have to be added as references to your project.

The dll files in `extlib\lib` have to be copied next to your binary (several directories deep inside the `bin` directory that is created next to your project).

Make sure to use all dlls, not only the ones from TGUI. You must use the exact SFML.Net, CSFML and SFML files as provided with TGUI.Net.
