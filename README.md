# Intro to Spring Boot MVC
  
**Definition/Overview:** Spring Boot MVC is an open-source *model-view-controller* framework built into the Spring Boot libraries, which are utilized for streamlining the setup, programming, configuration, and deployment of Java microservice applications.
  
Examples of Spring Boot features include diagnostic checks, production-ready metrics, customizable startup configurations, and embedded app servers (e.g., Jetty, Tomcat, Undertow). No code or XML generation is necessary to create Spring Boot projects, and best configurations for projects are automatically determined (and manually adjustable, as desired or needed).
  
*Note: Spring differs from Spring Boot in that it is a configuration framework that empowers enterprise Java app developers with flexible, ready-to-use controls and boilerplate code that make apps quicker and simpler to setup, allowing developers to focus more on the other aspects of development. The Spring Boot framework is assembled 'on top of' it, with extra features (such as additional configuration tools) that make generating stand-alone/autonomous apps even more convenient to setup and configure.*

#### Table of Contents:

1. Dispatcher Servlets
2. Spring Servlet XML Configuration
3. Controllers
4. Models
5. Autowiring
6. RESTful Service URLs 
    
<hr />
  
## 1. Dispatcher Servlets
  
Dispatcher servlets are utilized when handling incoming requests and routing them via Spring.
  
<hr />

## 2. Spring Servlet XML Configuration
  
Spring is configured to search for a *servletname-servlet.xml* file in a folder called */WEB-INF*.
  
<hr />

## 3. Controllers
  
Controllers can be utilized to retrieve classes and the objects associated within a class.
  
<hr />
  
## 4. Models
  
Models allow for objects to be passed from controllers into views.
  
<hr />

## 5. Autowiring  
  
Autowiring enables Spring to instantiate a class. The class's methods become accessible at runtime via *dependency injection*.
  
<hr />

## 6. RESTful Service URLs

These allow for CRUD database operations (creating, reading, updating, deleting) to be accomplished through HTTP methods (such as GET, POST, PUT, and DELETE).

<hr />
  
TODO: Details for each section, including code examples as relevant.
