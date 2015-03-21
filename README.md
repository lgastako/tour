# A Brief Tour of the Clojure/ClojureScript Landscape

[Clojure](http://clojure.org/) is a modern
[Lisp implementation](http://en.wikipedia.org/wiki/Lisp_%28programming_language%29)
on the JVM creatd by
[Rich Hickey](http://thechangelog.com/rich-hickeys-greatest-hits/).

[ClojureScript](https://github.com/clojure/clojurescript) is an implementation
of Clojure which compiles to javascript via the
[Google Closure Compiler](https://developers.google.com/closure/compiler/). [There are some differences](https://github.com/clojure/clojurescript/wiki/Differences-from-Clojure).

[Leiningen](http://leiningen.org/) Clojure's most popular and battle tested
build tool,
[Boot](http://boot-clj.com/)/[Boot](https://github.com/boot-clj/boot) is the
primary contender, new to the scene and on the rise.

There are plugins for leiningen for:
- Writing Chrome Extensions
  * [lein-chrome-extension](https://github.com/clumsyjedi/lein-chrome-extension)
  * [lein-chromebuild](https://github.com/clumsyjedi/lein-chromebuild).
- NodeJS
  * https://github.com/RyanMcG/lein-npm
  * https://github.com/bodil/cljs-noderepl

[Chestnut](https://github.com/plexus/chestnut) is a leiningen template which
creates a project which already has
[Figwheel](https://github.com/bhauman/lein-figwheel),
[Weasel](https://github.com/tomjakubowski/weasel),
[om](https://github.com/omcljs/om),
[om-tools](https://github.com/Prismatic/om-tools),
[ring](https://github.com/ring-clojure/ring),
[http-kit](http://www.http-kit.org/) and others to provide a full-stack
environment for building single page web apps using
[Facebook's React](http://facebook.github.io/react/) with
[full support for WebSockets](http://www.http-kit.org/server.html).

[om](https://github.com/omcljs/om) is the work of
[David Nolen](http://swannodette.github.io/) who also does a ton of great work
in many other areas of the Clojure and ClojureScript ecosystem.

[prismatic](http://getprismatic.com/home) is a company that has created many
interesting open source Clojure tools such as
[schema](https://github.com/Prismatic/schema),
[plumbing and Graph](https://github.com/Prismatic/plumbing),
[om-tools](https://github.com/Prismatic/om-tools),
[dommy](https://github.com/Prismatic/dommy)
and [others](https://github.com/Prismatic).

[LightTable](http://lighttable.com/) is a IDE
[created by Chris Granger](http://www.chris-granger.com/lighttable/) which was
inspired by [Brett Victor](http://worrydream.com/)'s
[Inventing on Principle](https://vimeo.com/36579366) talk and related work.

To be elaborated on:
* SQL/Databases
  - https://github.com/krisajenkins/yesql
  - https://github.com/korma/Korma
  -
* [Cljx](https://github.com/lynaghk/cljx)
* [core.async](https://github.com/clojure/core.async).
* [ClojureScript REPL for Chrome](https://chrome.google.com/webstore/detail/clojurescript-repl/lmjjlapjpjeodaadkljnmdfbjpfddchm?hl=en).
* [transducers](http://clojure.org/transducers).
* http://www.datomic.com/
* https://github.com/ibdknox/jayq (jquery)
* https://github.com/lynaghk/c2 (d3)
* https://github.com/clojure/core.logic (prolog)
* https://github.com/weavejester/hiccup (edn->html :clj)
* https://github.com/davidsantiago/hickory (html->edn)
* https://github.com/teropa/hiccups (edn->html :cljs)
* https://github.com/r0man/sablono (edn->html :cljs :om)

* Other React alternatives like[Reagent](http://holmsand.github.io/reagent/).

## Resources

Misc
- http://www.reddit.com/r/clojure
- http://www.reddit.com/r/clojurescript

Talks
- [Stuart Sierra: Clojure/ClojureScript - One Language to Rule the Web](https://www.youtube.com/watch?v=EpcNDd8nuYY)
- [David Nolen: Lisp's Revenge](https://www.youtube.com/watch?v=MTawgp3SKy8)
- [Kevin Lynagh](https://keminglabs.com/talks/)
- [Kevin Lynagh: Extending JavaScript Libraries from ClojureScript](https://www.youtube.com/watch?v=XfzXFWTT-z0)
- [Kevin Lynagh: Visual Interfaces in ClojureScript (StrangeLoop 2012)](http://www.infoq.com/presentations/Visual-Interfaces)

Haven't watched these, probably good, some might be the same.
- [David Nolen: Immutability, interactivity & JavaScript (FutureJS 2014)](https://www.youtube.com/watch?v=mS264h8KGwk)
- [David Nolen: Immutability: Putting The Dream Machine To Work - JSConf2014](https://www.youtube.com/watch?v=SiFwRtCnxv4)
- [David Nolen: The Functional Final Frontier 5/2014](https://www.youtube.com/watch?v=xeEojV8K7Lk)
