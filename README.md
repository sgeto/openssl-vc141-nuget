# openssl-vc141-nuget
OpenSSL library nuget package for Visual Studio 2017 C++ (msvc141) Project.

## Nuget Gallery
- [NuGet Gallery | openssl-vc141 1.1.0](https://www.nuget.org/packages/openssl-vc141)

## Usage
Run the following command in the Package Manager Console on Visual Studio 2017.
```
PM> Install-Package openssl-vc141
```

## How to package (for Package Owner)
Run the commands below on the Developer Command Prompt for VS 2017.
```
build-win32.bat

cd packaging\nuget
package.bat
```
