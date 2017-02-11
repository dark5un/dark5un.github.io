---
layout: post
title:  "Challenge 1 - Java Web API"
date:   2017-02-09 01:31:00 +0000
categories: java web api
---
Challenge? Well yes why not?

So lets start creating a Java API using the [1337](https://en.wikipedia.org/wiki/Leet)est of the [1337](https://en.wikipedia.org/wiki/Leet)est and as hardcore as possible! Always in a main stream fashion. (Don't ask me how I want to achieve this. I have no clue so far)

Tools for the thing? Hmmm lets start with [Gradle](https://gradle.org/)! Who cares about [Ant](http://ant.apache.org/) anymore and lately [Maven](https://maven.apache.org/) seems so 2k (put troll emoticon here).

Ok Mr Gradle I would like a nice clean project for my app to run:

```bash
$ gradle init --type java-application --test-framework spock
``` 

Why [Spock](http://spockframework.org) instead of [TestNG](http://testng.org) (and why not [JUnit](http://junit.org))?

Because Spock had enough love in its site and because it is a cool name. Ok [Groovy](http://www.groovy-lang.org) is stupid easy to play with, that is why. And testing in Java sucks. (Yes I am doing group therapy for what I just said)

Gradle init has finished and there is a basic folder structure. Look ma no hands! How 2017 this feels! But the Gradle people made it even better! They created a basic java app structure. And added [Google Guava](https://github.com/google/guava) as a dependency!

Why java-application type you said? Well I was thinking about [Spring Boot](https://projects.spring.io/spring-boot) and felt so good to just start my app from command line. I can do it with [Node.js and Express](http://expressjs.com) I can certainly do it with [Rails](http://rubyonrails.org) so there you go. Java saw the light finally!

