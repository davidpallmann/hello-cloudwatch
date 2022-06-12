# Hello, CloudWatch!

This is the code project for the [Hello, CloudWatch!](https://davidpallmann.hashnode.dev/hello-cloudwatch) blog post. 

This episode: Amazon CloudWatch and observability. In this Hello, Cloud blog series, we're covering the basics of AWS cloud services for newcomers who are .NET developers. If you love C# but are new to AWS, or to this particular service, this should give you a jumpstart.

In this post we'll introduce CloudWatch and use it to monitor a "Hello, Cloud" .NET application. We'll do this step-by-step, making no assumptions other than familiarity with C# and Visual Studio. We're using Visual Studio 2022 and .NET 6.

## Our Hello, CloudWatch Project

We will create a simple .NET website and instrument it for logging with the AWS Logging .NET plug-in for ASP .NET Core Logging. We'll host our website in AWS App Runner. As we use the website, we'll view the logs and metrics in CloudWatch.

See the blog post for the tutorial to create this project and run it on AWS.

