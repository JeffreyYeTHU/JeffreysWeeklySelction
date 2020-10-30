# Selection #5
October 29, 2020

## Database Stuff

[EF Core Tips - Don't call Update when you don't need to!](https://blog.oneunicorn.com/2020/01/17/dontcallupdate/)

I am not a fan of heavy orm such as ef core, but I do need to maintain code base that use it. This is a blog on context tracking and the usage of context.Update.

[Project RoundhousE - Database Change Management done right](https://github.com/chucknorris/roundhouse)

When I get used to use dapper to do database access stuff, I find data migration is a real headache, until i find RoundHousE. This is a awesome CLI tool that make migration painless using SQL scripts. It's lightweight and powerful, highly recommend it.

[Continuous Integration and Delivery for Databases - Jimmy Bogard](https://www.youtube.com/watch?v=HdXDSjWe2Q8)

This video take migration to the next level - integrate migration into CI/CD pipeline. 

## C#

[Task cancellation in C# and things you should know about it](https://binary-studio.com/2015/10/23/task-cancellation-in-c-and-things-you-should-know-about-it/)

This blog is nicely put, and to summary, to get cancellation, you need do:

* Write methods that support cancellation.
* Pass cancellation token to the cancelable method.
* Issue cancel request.

In the blog, the author will instruct you how to do that in detail.

[Eliding Async and Await](https://blog.stephencleary.com/2016/12/eliding-async-await.html)

This is a blog by [Stephen Cleary](https://blog.stephencleary.com/), who is an awesome blogger. At first look, eliding async and await is great, yet underneath pitfalls lie and wait.

After fully analysis, the guideline from Stephen is:
* Keep async and await by default.
* Consider eliding when the method is just a passthrough or overload.