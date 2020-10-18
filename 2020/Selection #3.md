# Selection #3
October 13, 2020

## Override C# GetHashCode

[Overriding Equals in C#](https://www.loganfranken.com/blog/687/overriding-equals-in-c-part-1/)

In C#, hash code has tight relation with equality override. This blog go into detail and catches of equality and hash code override. Include how to implement Equals, GetHashCode, and operator == properly.

[GetHashCode Made Easy](https://rehansaeed.com/gethashcode-made-easy/)

After reading the above post, you may think GetHashCode is complicated and may try to shun away from it, do not worry, this post is come to rescue. This post present a very nice helper class for hash code override. It also point out for .NET core 2.1 or higher, the System.HashCode will save you a lot of headache.

[Introducing C# 9: Records](https://anthonygiretti.com/2020/06/17/introducing-c-9-records/)

Records will come with C# 9 and it will be a great feature for immutable programming. Records also come with value equality build inside like struct. So with records, you no longer need to override Equals and GetHashCode anymore, which would be in most scenarios.

[Why is string.GetHashCode() different each time I run my program in .NET Core?](https://andrewlock.net/why-is-string-gethashcode-different-each-time-i-run-my-program-in-net-core/)

This is a side note on GetHashCode. To avoid hash flood attacks, .NET core improve string.GetHashCode() to be random for each app domain.

## Get Started with Docker&K8s

__Warning__: Some resources are in Chinese. 

[win10下使用Docker部署mongo](http://www.moguf.com/post/windockerrunmongo)

First, get hands on experience by use docker to run mongo.

[Docker Tutorial for Beginners - A Full DevOps Course on How to Run Applications in Containers](https://www.youtube.com/watch?v=fqMOX6JJhGo&list=LLRpOjpaT3zjf_Qjnmxp27Mg&index=6)

Moving on, learn the basics by follow this video step by step. Be suer to practice every command and make notes all along.

[在Win10上使用minikube体验K8S](https://www.jianshu.com/p/214bcc76b8cf)

After get the basics of docker, moving on to K8s. Just like docker, first get the hands on experience with minikube.

[Kubernetes Tutorial | Kubernetes | Kubernetes tutorial for beginners](https://www.youtube.com/watch?v=gpmerrSpbHg&list=LLRpOjpaT3zjf_Qjnmxp27Mg&index=1)

After hands on experience, follow on this video.