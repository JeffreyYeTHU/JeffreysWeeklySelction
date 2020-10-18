# Section #4
October 18, 2020

## .NET Assembly Versioning

[Understanding How Assemblies Load in C# .NET](https://michaelscodingspot.com/assemblies-load-in-dotnet/)

This blog explain the process of assembly loading process, including assembly binding and binding redirect. Which is a good start point for the next post.

[Assembly Versioning and DLL Hell in C# .NET Framework: Problems and Solutions](https://michaelscodingspot.com/dotnet-dll-hell/)

When your project reference different version of a same library, you may have the issue of version hell. This post illustrate three possible solution for this:
1. Easiest and safest one: make the version fit, that is use the same version.
2. When you reference different package and they intern reference to different version of a same package, the first solution may not so easy, in this situation, you may use binding redirect.
3. Loading different-version assemblies side by side. Be sure to invest your option before you decide to do this because it can be troublesome.

## Python Development Env Setup on Win10

[Get started using Python for web development on Windows](https://docs.microsoft.com/en-us/windows/python/web-frameworks#set-up-visual-studio-code)

With VS CODE remote, combine with WSL, this is a nice setup for python env on win10.

## .NET 5

[Top 10 .NET 5.0 new APIs](https://blog.ndepend.com/top-10-net-5-0-new-apis/)

If you want to know the api change bring by .NET 5, read this article.