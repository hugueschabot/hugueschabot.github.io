---
layout: post
title: "Play Framework Console"
description: "Two simple tips to start the Play Framework console with a running application."
category: "Tips"
tags: ["Play Framework"]
---
{% include JB/setup %}

As a new [Play Framework][Play] developer I use `play console` a
lot to scribble code and test my applications. But as an application
evolves (when it uses a database for instance) the bare console is
not enough. Here are two simple tips to start a Play application in
a console session.

First, apply evolutions automatically by adding the
`-DapplyEvolutions.default=true` flag when launching the Play
console.

    play -DapplyEvolutions.default=true console

Then, in the console, start the Play application by creating an
instance of it.

    new StaticApplication(new File("."))

[Play]: http://www.playframework.com/
