# Building Serverless Applications<a name="serverless-building"></a>

Building your serverless application involves taking your AWS SAM template file, application code, and any applicable language\-specific files and dependencies, and placing all build artifacts in the proper format and location for subsquent steps in your workflow\.

For example, you might want to locally test your application, or you might want to deploy your application using the AWS SAM CLI\. Both of these activities use the build artifacts of your application as inputs\.

This section shows you how to use the `[sam build](sam-cli-command-reference-sam-build.md)` command to build serverless applications using AWS SAM\. You have the option to build all functions and layers of your application, or individual components of your application, like a specific function or layer\.

**Topics**
+ [Building Applications](serverless-sam-cli-using-build.md)
+ [Building Layers](building-layers.md)
+ [Building Custom Runtimes](building-custom-runtimes.md)