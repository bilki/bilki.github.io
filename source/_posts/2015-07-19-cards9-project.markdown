---
layout: post
title: "Cards9 project"
date: 2015-07-19 09:42:41 +0200
comments: true
categories: misc
---

At [Wyred](http://wyred.biz), we are creating a nice tool to customize interactions with clients. But there are many things that I don't like about our process. I won't enter into details, but lack of professional experience and time are two powerful reasons.

So I'm starting a new personal project to fill these gaps, at least the one concerning to me. A multiplayer turn-based board game that mimics the [Tetra Master](http://finalfantasy.wikia.com/wiki/Tetra_Master_%28Minigame%29) minigame from Final Fantasy IX. It splits into a server (the fancy part) and a (probably) javascript mobile application. You can see in my github that I already started developing the server part three months ago, but problems always arise and I parked the project. Now I'm on holidays, so chances are that it will get a little boost.

Technologies involved into the server subproject are Scala, Akka, Play and Postgresql. I want to update my knowledge to the new concepts introduced with Scala 2.11, Akka 2.3, Play 2.4, and also get a glimpse of Postgresql with Slick. By the way, testing will be implemented using Scalatest, Scalacheck and Mockito. The UI part isn't very clear to me, so I will wait until the server is ready.

This last year, because of my job, I have been working intensively with Mongodb (mainly 2.6). It's an awesome documental database, but [some articles](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/) have convinced me that my Mongodb knowledge, using the excellent [Reactivemongo](http://reactivemongo.org/) driver, has deepened too much and I'm forgetting about SQL (or other type of) databases and Scala database stuff like Slick. I'm getting biased. Hence the choice for this project is Postgresql.

Future posts will track the development process of this funny project.