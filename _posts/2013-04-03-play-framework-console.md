---
layout: post
title: "Play Framework console"
description: "Two simple tips to start the Play Framework console with a running application."
category: "Tips"
tags: ["Play Framework"]
---
{% include JB/setup %}

I am learning [Play Framework][Play] and I use `play console` a lot
to scribble code and test my applications. But when an application
uses a database, the bare console is not always enough. Here are two
simple tips to start a Play application in a console session.

First, apply evolutions automatically by adding the
`-DapplyEvolutions.default=true` flag when launching the Play
console (where `default` is actually the name of the datasource
defined in `application.conf`).

    play -DapplyEvolutions.default=true console

Then, in the console, start the Play application by creating an
instance of it.

    new StaticApplication(new File("."))

[Play]: http://www.playframework.com/
