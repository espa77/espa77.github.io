---
layout: post
title: "Dear Binding Pry Creator...Thank You!"
date: 2015-12-07 13:20:08 -0500
comments: true
categories: Flatiron School
---
I've been at the Flatiron School for 6 days and I've put in about 100 hours since the course started. On 'Day 2' I figured out how to use binding pry in a way which will save me countless hours as I move through this course.

Binding pry is a great tool that allows in-process/line debugging which has already allowed me to fix errors that I would have otherwise not been able to.  Here is the feature list from the Pry website:

Source code browsing (including core C source with the pry-doc gem)
Navigation around state (cd, ls and friends)
Rubinius core source browsing
Documentation browsing
Live help system
Open methods in editors (edit-method Class#method)
Syntax highlighting
Command shell integration (start editors, run git, and rake from within Pry)
Gist integration
Runtime invocation (use Pry as a developer console or debugger)
Exotic object support (BasicObject instances, IClasses, ...)
A powerful and flexible command system
Ability to view and replay history
Many convenience commands inspired by IPython, Smalltalk and other advanced REPLs
Pry also aims to be more than an IRB replacement; it is an attempt to bring REPL driven programming to the Ruby language. It is currently not as powerful as tools like SLIME for lisp, but that is the general direction Pry is heading.

Pry is also fairly flexible and allows significant user customization making it a good choice for implementing custom shells.

Here are some examples where I have used pry within our labs to get the tests to pass:

  Blackjack CLI
  Hashketball
  Object Oriented Cash Register
  Advanced Class methods


The Pry Project was founded by John Mair, Conrad Irwin, Ryan Fitzgerald, and a healthy number of other contributors. I checked out their individual blogs and learned a few exciting new things.  

1. 'Pry-nav' This 2012 plugin for Pry adds the `next`, `step`, and `continue` commands to Pry. After requiring this gem, you can use Pry as normal, placing `binding.pry` wherever you want to start your session. The `next` command will advance execution by one line. I can only imagine how helpful this will be as my code becomes longer and more complex.

2. 'Pry-remote' This allows remote debugging using pry. It sounds incredibly useful, especially with teams that sometimes span the globe. However, I'm not sure if I will use this at The Flatiron School.

I've installed pry-nav and I can't wait to work with it today and in the future labs that we do here at the Flatiron School.

-Ethan
