This task is for to learn how to expose a function written in any language as a Service or a Remote Procedure. A function written in any language and running on any machine can be triggered remotely in several different ways. However, we are only going to focus on two different methods that enables you to learn how to trigger the function over web using two most popular protocols.

1. REST
2. gRPC

This exercise is divided into two parts and both of them can be completed independently. This exercise will only define the expected outcome and you can use pretty much any backend programming language to implement it. Every language has either built in support for creating a REST/gRPC trigger or an external library that be used to creating the same. Here is a list of most popular languages that are commonly used by various companies.

1. Java
2. Python
3. NodeJS
4. Go
5. C#

### PART I: Expose a function as a REST API Service

When a service is exposed as a REST API over HTTP Protocol, the function can be triggerred by using any REST client. The most popular REST clients that are available for free with varied feature set are listed below.

1. All web Browsers
2. curl
3. Postman

Now, a function that has a REST trigger can be invoked by using one of the above mentioned client. The important part of a REST API Service signature are:

1. URL:
  1. Hostname
  2. Context Path
2. HTTP Method
3. Authentication

##### Example:


### PART I: Expose a function as a gRPC API Service

gRPC is a relatively newer protocol which not as widely used as REST Protocol. Unlike REST not many languages offer support for gRPC protocol.
