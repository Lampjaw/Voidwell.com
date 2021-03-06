# Voidwell.com

Voidwell.com leverages a few technology stacks to operate. The main being docker microservices that communicate with each other via HTTP/REST. They also depend on an OIDC implementation (Voidwell Auth) for token authentication and authorization.

#### Technologies used:

* .NET Core 2.x (C#)
  * ASP.NET Core Identity
  * IdentityServer4
  * Entity Framework Core
* AngularJS 7.x (TypeScript/JavaScript)
* PostgreSQL (SQL)
* Docker
* Redis
* Nginx

#### Services

* [Voidwell.API](https://github.com/voidwell/Voidwell.API)
  * REST API gateway responsible for user authorization and internal route propagation.
* [Voidwell.Auth](https://github.com/voidwell/Voidwell.Auth)
  * OpenID Connect provider.
* [Voidwell.ClientUI](https://github.com/voidwell/Voidwell.ClientUI)
  * Front end interface for [Voidwell.com](https://voidwell.com).
* [Voidwell.DaybreakGames](https://github.com/voidwell/Voidwell.DaybreakGames)
  * Manages data and interactions regarding Daybreak Games Company properties (e.g. Planetside 2).
* [Voidwell](https://github.com/lampjaw/Voidwell)
  * Manages data specifically belonging to Voidwell (e.g. the blog, event configurations, etc).
* [Voidwell.ReverseProxy](https://github.com/voidwell/Voidwell.ReverseProxy)
  * A simple reverse proxy implemenation for handling routing to the necessary public services.
* [Voidwell.UserManagement](https://github.com/voidwell/Voidwell.UserManagement)
  * Manages user data and authentication.
  
#### Setup
To get the application up and running you may want to use the docker-compose.yml file in this repository. Just make sure to fill in the required fields.
