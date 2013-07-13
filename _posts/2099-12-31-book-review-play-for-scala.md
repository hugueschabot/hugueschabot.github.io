---
layout: post
title: "Book Review: Play for Scala"
description: "Play for Scala is a hands-on guide to Scala-based web applications development using Play 2 framework."
category: "reviews"
tags: ["Play Framework", "Scala"]
---
{% include JB/setup %}

> Play for Scala is a hands-on guide to Scala-based web applications development using Play 2 framework. It provides complete code samples and detailed explanations about many aspects of the framework. It is a very valuable book for developers wanting to learn Play 2.

[Play][play] is an open source web framework for Java and Scala heavily inspired by Ruby on Rails and Django. It takes advantage of Scala to provide statically type-checked APIs and web application specific DSLs instead of relying on dynamic features or general purpose technologies like XML. Play applications are stateless, event-based and can easily use non-blocking I/O.

[Play for Scala][playforscala], by Peter Hilton and Erik Bakker, is a book about building Scala-based web applications using Play 2 framework. It is currently available through [MEAP][meap] (Manning Early Access Program) and is scheduled for September 2013.

The book starts with a short introduction which presents Play framework's key features and overview its usage via a classic "Hello World" example. Then, chapter 2 kicks in with a multilingual "Paper Clips Store" application based on [Twitter Bootstrap][twitterbootstrap] which presents, among other things, the model-view-controller architecture, the form API and how to integrate external libraries; an overall dense, but very captivating introduction to Play framework.

The second part of the book digs through every aspect of the framework encountered so far. Chapter 3 overviews Play's architecture and configuration. Chapter 4 focus on HTTP related aspects of the framework like URL routing and static resources serving. Chapter 5 covers data persistence with Anorm and [Squeryl][squeryl]. Chapter 6 deals with views rendering and the template engine. Finally, chapter 7 shows form validation and rendering.

The book ends with a third part that mostly covers advanced topics and Play's signature features. Chapter 8 starts with a complete single-page application using Ajax and shows many techniques to parse and render JSON documents. Chapter 9 covers plugins development and application deployement. Chapter 10 covers the asynchronous programming model with WebServices, WebSockets, iteratees and [Akka][akka] actors.

Play for Scala provides everything a developer should know to build a Scala-based application using Play framework by providing detailed explanations, complete examples and by covering a wide range of technologies.

Even though Play’s online documentation is ???

## The trial and error approach

The authors ...

## No secret

The authors explains how it works (compilation)...

In my opinion, the book lacks a section on testing.

[play]: http://www.playframework.org/
[playforscala]: http://www.manning.com/hilton/
[meap]: http://www.manning.com/about/meap.html
[twitterbootstrap]: http://twitter.github.com/bootstrap/
[squeryl]: http://squeryl.org/
[akka]: http://akka.io/
