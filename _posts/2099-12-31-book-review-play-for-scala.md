---
layout: post
title: "Book Review: Play for Scala"
description: "Play for Scala is a practical guide to Scala-based web applications development using Play 2 framework."
category: "Reviews"
tags: ["Play Framework", "Scala"]
---
{% include JB/setup %}

> Play for Scala is a practical guide to Scala-based web applications development using Play 2 framework. It provides detailed explanations and realistic examples for many aspects of the framework.

[Play][play] is an open source web framework for Java and Scala heavily inspired by Ruby on Rails and Django. It takes advantage of Scala to provide statically type-checked APIs and web application specific DSLs instead of relying on dynamic features or general purpose technologies like XML. Play applications are stateless, event-based and can easily use non-blocking I/O, which make them good candidates for high-scalability.

[Play for Scala][playforscala], by Peter Hilton and Erik Bakker, is a book about building Scala-based web applications using Play 2 framework. It is currently available through [MEAP][meap] (Manning Early Access Program) and is scheduled for April 2013.

## Summary

The book starts with a short introduction which presents Play framework key features and overview its usage via a classic “Hello World” example. Then, chapter 2 kicks in with a multilingual “Paper Clips Store” application based on [Twitter Bootstrap][twitterbootstrap] which presents, among other things, the model-view-controller architecture, the form API and how to integrate external libraries. An overall dense but very captivating introduction to Play framework.

The second part of the book digs through every aspect of the framework encountered so far. Chapter 3 overviews Play’s architecture and configuration. Chapter 4 focus on HTTP related aspects of the framework like URL routing and static resources serving. Chapter 5 covers data persistence with Anorm and [Squeryl][squeryl]. Chapter 6 deals with views rendering and the template engine. Finally, chapter 7 shows form validation and rendering.

The book ends with a third part that covers most advanced techniques and Play's signature features. Chapter 8 starts with a complete single-page application using Ajax and shows many techniques to parse and render JSON documents.

## In my opinion

Play for Scala provides everything a developer should know to build a Scala-based application using Play framework by providing detailed explanations, realistic examples and by covering a wide range of technologies.

## The trial and error approach

The authors ...

## No secret

The authors explains how it works (compilation)...

#### TODO Play 2.0 (but everything worked on 2.1 except JSON parsing)

One big challenge with this book is that Play evolves rapidly. The book is based on Play 2.0 but Play 2.1 will be released soon and some aspects of the book will then be obsolete (like the need to use the form validation API to validate JSON).

It lacks an example with Slick in my opinion.

#### TODO Java EE

Since Play is a framework for web applications that run on the JVM, it is difficult to avoid any comparison with Java EE.

#### Nothing about testing

[play]: http://www.playframework.org/
[playforscala]: http://www.manning.com/hilton/
[meap]: http://www.manning.com/about/meap.html
[twitterbootstrap]: http://twitter.github.com/bootstrap/
[squeryl]: http://squeryl.org/