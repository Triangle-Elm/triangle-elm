# Resources For Learning Elm

This is a collection of assorted resources for learning about the Elm programming language.



# Getting Started

Elm is an unfamiliar language for many folks coming to it. Functional
languages in the ML family aren't very common in industry. That means
you may need to spend a bit more time on the basics than you would
picking up a new framework in your favorite language. Don't worry,
you'll get there! 

Here are some resources to help get you started.


## Text

### [An Introduction To Elm](https://guide.elm-lang.org/)

The official getting started guide at elm-lang.org

### [Elm Package Repository](http://package.elm-lang.org/)

Once you're familiar with the language syntax, Elm's 
searchable package repository is a great resource if you learn well
from reading technical documentation. Start with the 
[core language docs](http://package.elm-lang.org/packages/elm-lang/core/latest)
and branch out from there.


## Code

### [Elm Starter Projects](https://github.com/Triangle-Elm/elm-starter-projects)

Our (Triangle Elm) starter projects are intended to provide some basic, but
incomplete applications for beginners who just want to start hacking on existing
code. Each project comes with a recommended first set of changes to try, but
feel free to experiment!



# Tooling

Beyond language basics, some of the first questions that comes up when learning Elm
are things like: "What editor should I use?"  "How do I incorporate my code into an existing page?"
"How do I build larger projects?"

The resources in this section should help you set up your development environment
and understand how to get your Elm project out into the world.


## Code

### [elm-format](https://github.com/avh4/elm-format)

*The* code formatter for Elm. Having your editor set to format code automatically
when you save a file is an amazing improvement over linters that just make suggestions.
No configuration options means no more bikeshedding about style, and a consistent
approach for the whole community.

### [Ellie](https://ellie-app.com) 

Ellie is an online Elm editor & compiler. It's great for sharing example code and
collaborating with other Elm developers online.

### Editor Plug-Ins

  * [Emacs](https://github.com/jcollard/elm-mode)
  * [Vim](https://github.com/ElmCast/elm-vim)
  * [VSCode](https://marketplace.visualstudio.com/items?itemName=sbrink.elm)
  * [IntelliJ/Webstorm](https://plugins.jetbrains.com/plugin/8192-elm-language-plugin)
  * [SublimeText](https://packagecontrol.io/packages/Elm%20Language%20Support)

### Build Tool Integration

  * [Webpack](https://github.com/elm-community/elm-webpack-loader)
  * [Brunch](https://github.com/MattCheely/elm-fancy-brunch)

### Project Templates

  * [create-elm-app](https://github.com/halfzebra/create-elm-app)
  * [elm-brunch-skeleton](https://github.com/MattCheely/elm-brunch-skeleton)



# Leveraging the Type System

The first thing most developers notice about Elm's type system
is how it prevents mistakes, and helps guide development. It's
also a powerful tool that lets you better represent the constraints
and intent behind your data.

These resources should help show how you can leverage the type system
for clearer and more reliable code.


## Text

### [Booleans and Enums](https://robots.thoughtbot.com/booleans-and-enums)

Joël Quenneville discusses how data that's commonly represented with booleans
in other languages can often be better handled with Union types. This is a
nice example of how a common pattern you might be used to can be
completely upended by what Elm's type system has to offer.

### Advanced Types in Elm

In this series of articles, Charlie Koster gets into some of the less common (but still helpful!) 
uses of the type system. He does a good job of explaining when, where and why these techniques are used.

  * [Opaque Types](https://medium.com/@ckoster22/advanced-types-in-elm-opaque-types-ec5ec3b84ed2)
  * [Extensible Records](https://medium.com/@ckoster22/advanced-types-in-elm-extensible-records-67e9d804030d)
  * [The Never Type](https://medium.com/@ckoster22/advanced-types-in-elm-the-never-type-ca9b3297bbd4)
  * [Phantom Types](https://medium.com/@ckoster22/advanced-types-in-elm-phantom-types-808044c5946d)


## Video

### [Making Impossible States Impossible](https://www.youtu.be/IcgmSRJHu_8)

Richard Feldman talks about how to use the type system to make invalid application
states impossible.



# Program Structure & Organization

The Elm Architecture and the type system mean that all
Elm apps share the same data flow, but there's still more
to building a program, and lots of folks get tripped up when
they start building bigger projects and their old habits 
don't necessarily translate well to Elm.

These resources should provide insight into how to structure, organize, and
grow your programs. 


## Video

### [The Life of a File](https://youtu.be/XpDsk374LDE)

Elm's creator, Evan Czaplicki talks about how & when he decides 
a file in Elm is ready to be broken into separate modules. There 
are also some good insights about choosing data structures, and 
how habits from other languages might not transfer to Elm.

### [Scaling Elm Apps](https://youtu.be/DoA4Txr4GUs)

Richard Feldman discusses refactoring and organizing large applications.
He provides some key insights about how narrowing type signatures makes
larger projects easier to reason about. Be sure to watch the whole thing,
as there's a good section at the end about a common pitfall folks
encounter when moving to Elm from Javascript.


## Code

### [Elm SPA Example](https://github.com/rtfeldman/elm-spa-example)

An example single-page-app created by Richard Feldman.



# Perspective

Resources that explain the design principles behind Elm or provide
insight into how the Elm community typically sees things.


## Video

### [If Coco Chanel Reviewed Elm](https://youtu.be/Wiw3YcwGwrU)

Tereza Sokol gives a wonderful talk about the design of languages and
APIs, using fashion as a parallel example. In doing so, she clarifies
the trade-offs involved in different style of design which helps shed
some light on why Elm is the way it is, and how some of the things that
people may not like about it at first are an essential part of the
aspects of the language that they do like. 


### [Code is the Easy Part](https://youtu.be/DSjbTC-hvqQ)

Evan Czaplicki talks about how building a programming language takes
a lot more than just generating technical artifacts. He discusses how
the pace and style of development matters, and the importance of building
a community as part of the process.


## Audio

### [How Do I Write JS in Elm?](https://elmtown.audio/99e18f41)

In this episode of the Elmtown podcast, Evan Czaplicki and host
Murphy Randle nominally talk about JS interop in Elm. However, in 
the course of the discussion, Evan also explains a lot about his
design philosophy for Elm and his goals for the language.


