<!-- $theme: default -->

Building Microservices in ASP.NET Core
===
This is just a placeholder strawman for collaboration. None of this should be taken seriously yet.

---
![](images/sw.jpg)
# About Us
TBD

---

# Agenda

* Create a new ASP.NET Core project
* Add middleware
* Add controller and Repository
* Use Spring Cloud Config Server
* Use Service Discovery
* All on a Mac! ðŸ˜±

---

# What is ASP.NET Core?
foo
bar
baz

---
# Why do we care?
tbd
* a
* b
* c

---
# Hello World
tbd

```text
dotnet new
dotnet restore
dotnet run
```

---
# Adding Middleware
tbd code to respond to all requests

```c#
public void Configure(IApplicationBuilder app, 
                      IHostingEnvironment env, 
                      ILoggerFactory loggerFactory)
{
  app.Run(async (context) =>
  {
    await context.Response.WriteAsync("Hello, world!");
  });
}
```
---
# RESTful Routes
tbd
* Attributes for Route Mapping
* Automatic JSON conversion
* c
* etc

---
# Controllers
TBD
* Handling HTTP Methods (GET, PUT, etc.)
* Async request handling
* Returning meaningful HTTP results (201, 401, etc)
* c
* etc



---
# Dependency Injection
TBD
* Services
	* Request-Scoped, Global
* Configuration
* Middleware
* ?

---
# Delivering Continuously
TBD
* Wercker
* Dockerhub
* etc
* ?

--- 
# Running in the Cloud
TBD
* Push/deploy
* Run
* Elastic scalability
* Buildpacks vs. Docker

---
# External Configuration
TBD

* ASP.NET Core Configuration
* Adding Config Server as Config Source
* ?


![](images/boots.jpg)

---
# Service Discovery with Eureka
TBD
* jf
* ?

![](images/boots.jpg)

---
# Q and A

Q - ??
A - 42.




