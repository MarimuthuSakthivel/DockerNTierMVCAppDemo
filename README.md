# Containerizing N-Tier MVC .Net Framework Application with Docker

Microservice Architecture and Containerization using docker are the latest buzzwords in the software industry. But, many people, including me, in the software industry who are developing big monolithic enterprise applications using .NET Framework for many years have a very limited scope of applying these concepts into existing applications. Well, it's not easy to break the enterprise monolithic application into a microservice architecture without redesigning the application. Also, the .NET Core framework would be the de-facto choice for microservice architecture because it supports cross-platform and can be hosted in Linux containers or Windows containers easily. As of today, Windows Docker container does not support GUI applications, such as WinForms, WPF etc. However, we can still consider modernizing .NET Framework monolithic applications by packaging into docker images for automated end-to-end testing or security testing.
 
In this article, I will explain how to containerize a simple N-Tier CRUD MVC application using docker. We will create a separate app server and database server container images and deploy and run the simple N-Tier MVC application. If you are new to docker, I would recommend you first read this article about docker for developers and watch the awesome pluralsight course of Modernizing .NET Apps with Docker by Elton Stoneman.

https://www.c-sharpcorner.com/article/containerizing-n-tier-mvc-net-framework-application-with-docker/