---
layout: post
title: "WIP: Cassandra Query Language (CQL) IntelliJ Idea Plugin"
date: 2017-02-18 17:01:43 +0000
comments: true
categories: 
---
Working on [Cassandra Query Language](http://cassandra.apache.org/doc/latest/cql/) with [Spring](https://spring.io/) on [IntelliJ Idea](https://www.jetbrains.com/idea/) is simple but I noticed that a plugin for the CQL syntax is missing. So I decided to build one.

I am using an other plugin, [intellij-rust](https://github.com/intellij-rust/intellij-rust), as a guidline. I liked the way it was build. Also I could use the experience and who knows I might be able to contribute back in the future. It is build in Kotlin and sounds like a good excuse to use my polyglot skills again!

As stated from the particular plugin:
See the IDEA platform [documentation][sdk-docs]. Of a particular interest are
the following sections:
  * custom language [tutorial][lang-tutorial]
  * custom language support [reference][lang-reference].

If you find any piece of SDK docs missing or unclear, do open an issue
at [YouTrack][sdk-YouTrack]. You can
also [contribute directly][sdk-contributing] to the plugin development docs.

It's also very inspirational to browse existing plugins. Check out [Erlang] and
[Go] plugins. There is also [plugin repository] and, of course, [Kotlin plugin].

[Kotlin]: https://kotlinlang.org/
[sdk-docs]: http://www.jetbrains.org/intellij/sdk/docs/

[lang-reference]: http://www.jetbrains.org/intellij/sdk/docs/reference_guide/custom_language_support.html
[lang-tutorial]: http://www.jetbrains.org/intellij/sdk/docs/tutorials/custom_language_support_tutorial.html

[sdk-YouTrack]: https://youtrack.jetbrains.com/issues/IJSDK
[sdk-contributing]: https://github.com/JetBrains/intellij-sdk-docs/blob/master/CONTRIBUTING.md

[Erlang]: https://github.com/ignatov/intellij-erlang
[Go]: https://github.com/go-lang-plugin-org/go-lang-idea-plugin
[plugin repository]: https://github.com/JetBrains/intellij-plugins
[Kotlin plugin]: https://github.com/JetBrains/kotlin
