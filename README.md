MSBuild Tasks (Sample project)
==============================

Blog post: 
[Shipping a cross-platform MSBuild task in a NuGet package](http://www.natemcmaster.com/blog/2017/07/05/msbuild-task-in-nuget/)

This repo contains examples of how to build MSBuild tasks that run on both "msbuild.exe" (inside Visual Studio 2017) and
with "dotnet.exe" (.NET Core CLI on Windows, Linux, and macOS).

To run this sample,

1. Install .NET Core CLI 1.0.0 or greater. See <https://dot.net/core> for download links.
2. Run `./build.ps1` in PowerShell or `./build.sh` from Bash.
