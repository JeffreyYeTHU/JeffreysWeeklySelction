
# Selection #7
February 10, 2021

## Hash Algorithms

[漫谈非加密哈希算法](https://segmentfault.com/a/1190000010990136)

Roughly speaking, hash algorithm can be categorize as crypto and non-crypto ones. In non security related situation, the main focus of hash would be speed. This post outline the non-crypto hash in practice.

FYI, this post is in Chinese.

[smhasher](https://github.com/aappleby/smhasher)

This is a repo that test hash algorithms. The nice about the post is that, it is a connection of theses hash algorithms, as well as show their performance, so awesome!

## .NET

[Enabling prerendering for Blazor WebAssembly apps](https://andrewlock.net/enabling-prerendering-for-blazor-webassembly-apps/)

[Prerendering a Blazor WebAssembly app to static files, without an ASP.NET Core host app](https://andrewlock.net/prerending-a-blazor-webassembly-app-without-an-asp-net-core-host-app/)

These two posts of [Andrew Lock](https://andrewlock.net/) focus on prerendering of blazor.

[Fun with IConfiguration](https://bakedbean.org.uk/posts/2021-01-fun-with-iconfiguration/)

StackOverflow talk about the way they use the IConfiguration.

[My preferred .NET console stack](https://www.devlead.se/posts/2021/2021-01-15-my-preferred-console-stack?utm_source=csharpdigest&utm_medium=web&utm_campaign=346)

As a programmer, we all love good CLI tools. If you want to build one, you can build from scratch, yet build on top of framework would be faster, since you can focus on the real peace of your app. This post highlight the author's choice on console frameworks.

## C#

[C# development with Visual Studio Code](https://medium.com/edgefund/c-development-with-visual-studio-code-b860cc71a5ec)

If you want to set up vs code for c# development, checkout this post.

[Fluent Generics in C#](https://tyrrrz.me/blog/fluent-generics?utm_source=csharpdigest&utm_medium=web&utm_campaign=339)

[How to Design and Implement the Fluent Interface Pattern in C#](https://assist-software.net/blog/how-design-and-implement-fluent-interface-pattern-c)

We all love fluent interface provided by LINQ. If you want to fluent you lib api, the above two post provide technique to make generics and interface fluent.

[When C# 9.0 patterns go wrong: mechanism over intent](https://endjin.com/blog/2020/12/dotnet-csharp-9-patterns-mechanism-over-intent.html)

Pattern matching is great, but do not use it just because you want to use it. Take a look at the suggestion form the above post.

[Asynchronously wait for Task<T> to complete with timeout](https://stackoverflow.com/questions/4238345/asynchronously-wait-for-taskt-to-complete-with-timeout)

[Crafting a Task.TimeoutAfter Method](https://devblogs.microsoft.com/pfxteam/crafting-a-task-timeoutafter-method/)

How would you implement a timeout logic? The about two posts may give you some idea.