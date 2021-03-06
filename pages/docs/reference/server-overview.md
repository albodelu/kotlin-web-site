---
type: doc
layout: reference
category: "Introduction"
title: "Kotlin for Server Side"
---

# Using Kotlin for Server-side Development

Kotlin is a great fit for developing server-side applications, allowing to write concise and expressive code while
maintaining full compatibility with existing Java-based technology stacks and a smooth learning curve:

 * **Expressiveness**: Kotlin's innovative language features, such as its support for [type-safe builders](/docs/reference/type-safe-builders.html)
   and [delegated properties](/docs/reference/delegated-properties.html), help build powerful and easy-to-use abstractions.
 * **Scalability**: Kotlin's support for [coroutines](/docs/reference/coroutines.html) helps build server-side applications
   that scale to massive numbers of clients with modest hardware requirements.
 * **Interoperability**: Kotlin is fully compatible with all Java-based frameworks, which lets you stay on your
   familiar technology stack while reaping the benefits of a more modern language.
 * **Migration**: Kotlin supports gradual, step by step migration of large codebases from Java to Kotlin. You can start
   writing new code in Kotlin while keeping older parts of your system in Java.
 * **Tooling**: In addition to great IDE support in general, Kotlin offers framework-specific tooling (for example,
   for Spring) in the plugin for IntelliJ IDEA Ultimate.
 * **Learning Curve**: For a Java developer, getting started with Kotlin is very easy. The automated Java to Kotlin converter included in the Kotlin plugin
   helps with the first steps. [Kotlin Koans](/docs/tutorials/koans.html) offer a guide though the key features of the language with a series of interactive exercises.

## Frameworks for Server-side Development with Kotlin

 * [Spring](https://spring.io) makes use of Kotlin's language features to offer [more concise APIs](https://spring.io/blog/2017/01/04/introducing-kotlin-support-in-spring-framework-5-0),
starting with version 5.0. The [online project generator](https://start.spring.io/#!language=kotlin) allows to quickly generate a new project in Kotlin.

 * [Vert.x](http://vertx.io), a framework for building reactive Web applications on the JVM, offers [dedicated support](https://github.com/vert-x3/vertx-lang-kotlin)
for Kotlin, including [full documentation](http://vertx.io/docs/vertx-core/kotlin/).

 * [Ktor](https://github.com/kotlin/ktor) is a Kotlin-native Web framework built by JetBrains, making use of coroutines
for high scalability and offering an easy-to-use and idiomatic API.

 * [kotlinx.html](https://github.com/kotlin/kotlinx.html) is a DSL that can be used to build HTML in a Web application.
It serves as an alternative to traditional templating systems such as JSP and FreeMarker.

 * The available options for persistence include direct JDBC access, JPA, as well as using NoSQL databases through their Java drivers.
For JPA, the [kotlin-jpa compiler plugin](/docs/reference/compiler-plugins.html#kotlin-jpa-compiler-plugin) adapts
Kotlin-compiled classes to the requirements of the framework.

## Deploying Kotlin Server-side Applications

Kotlin applications can be deployed into any host that supports Java Web applications, including Amazon Web Services,
Google Cloud Platform and more.

[This blog post](https://jkutner.github.io/2017/04/10/kotlin-heroku-ktor.html) offers a guide for deploying a Kotlin
application on [Heroku](https://www.heroku.com).

AWS Labs provides a [sample project](https://github.com/awslabs/serverless-photo-recognition) showing the use of Kotlin
for writing [AWS Lambda](https://aws.amazon.com/lambda/) functions.

## Users of Kotlin on the Server Side

[Corda](https://www.corda.net/2017/01/10/kotlin/) is an open-source distributed ledger platform, supported by major
banks, and built entirely in Kotlin.

[JetBrains Account](https://account.jetbrains.com/), the system responsible for the entire license sales and validation
process at JetBrains, is written in 100% Kotlin and has been running in production since 2015 with no major issues.


## Next Steps

* The [Creating Web Applications with Http Servlets](/docs/tutorials/httpservlets.html) and
[Creating a RESTful Web Service with Spring Boot](/docs/tutorials/spring-boot-restful.html) tutorials
show you how you can build and run very small Web applications in Kotlin.
* For a more in-depth introduction to the language, check out the [reference documentation](/docs/reference/index.html) on this site and
[Kotlin Koans](/docs/tutorials/koans.html).
