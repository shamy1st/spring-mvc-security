# Spring MVC Security

* https://docs.spring.io/spring-security/site/docs/4.2.3.RELEASE/reference/htmlsingle/

## Spring Security Model

* Spring Security defines a framework for security
* Implemented using Servlet filters in the background
* Two methods of securing a web app: declarative and programmatic

## Spring Security with Servlet Filters

* Servlet Filters are used to pre-process / post-process web requests
* Servlet Filters can route web requests based on security logic

## Spring Security Overview

![](https://github.com/shamy1st/spring-mvc-security/blob/main/images/spring-security-overview.png)
![](https://github.com/shamy1st/spring-mvc-security/blob/main/images/spring-security-in-action.png)

## 1. Declarative Security

* Define application's security constraints in configuration
    * All Java config (@Configuration, no xml)
    * Or Spring XML config
* Provides separation of concerns between application code and security

## 2. Programmatic Security

* Spring Security provides an API for custom application coding
* Provides greater customization for specific app requirements




## Ref
* https://docs.spring.io/spring-security/site/docs/4.2.3.RELEASE/reference/htmlsingle/
