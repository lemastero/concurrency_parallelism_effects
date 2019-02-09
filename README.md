Practice & theory behind concurrency, parallelism, process calculi and effects systems on JVM and beyond



# Process calculi

## Actor model
* Actor Model of Computation: Scalable Robust Information Systems - Carl Hewitt [(paper)](https://arxiv.org/abs/1008.1459)
* [Erlang User's Guide - Concurrent Programming](http://erlang.org/doc/getting_started/conc_prog.html)
* [Akka](https://akka.io/)

## CSP
* [Go CSP](https://godoc.org/github.com/thomas11/csp)
* [clojure/core.async](https://github.com/clojure/core.async)

## Join Calculus
* [Chymyst/chymyst-core](https://github.com/Chymyst/chymyst-core)
* [Scala 2.8 scala.concurrent.jolib](https://github.com/scala/legacy-svn-scala/blob/2.8.x-opening/src/library/scala/concurrent/jolib.scala)

## π-calculus (pi calculus)
* [Wikipedia](https://en.wikipedia.org/wiki/%CE%A0-calculus) [Hacker News](https://news.ycombinator.com/item?id=6908837)
* PiLib: A Hosted Language for Pi-Calculus Style
Concurrency - Vincent Cremet, Martin Odersky [(pdf)](http://lampwww.epfl.ch/~cremet/publications/pilib.pdf) [Scala 2.9 scala.concurrent.pilib](https://github.com/scala/legacy-svn-scala/blob/2.9.x-opening/src/library/scala/concurrent/pilib.scala)
* [pmatiello/pistache](https://github.com/pmatiello/pistache)
* A π-Calculus Internal Domain-Specific - Language for Scala[(pdf)](https://www.ime.usp.br/~cef/mac499-10/monografias/pedromatiello/pistache-monograph/monograph.pdf), [(slides)](https://www.slideshare.net/pmatiello/pistache-sbmf)

## rho-calculus
* Introduction to Rho Calculus -  Jeremy Beal [(blog post)](https://blog.rchain.coop/blog/2018/07/17/intro-rho-calc/)
* Introduction to the design of computational calculi - RChain [(video playlist)](https://www.youtube.com/watch?v=50z-TP0_HEA&list=PLf2bbiic5ZjD3q67melAFj8UWUFZy4PKP)
* Rho-Calculus Papers (http://rho.loria.fr/papersGuidelines.html)



# Approaches to concurrency

## Messaging Patterns
* [Enterprise Integration Patterns - Messaging Patterns](https://www.enterpriseintegrationpatterns.com/patterns/messaging/index.html)

## Fork Join
* [Java Tutorials - Fork/Join](https://docs.oracle.com/javase/tutorial/essential/concurrency/forkjoin.html)

## STM
* [scala-stm](https://nbronson.github.io/scala-stm/)
* [Haskell STM](http://hackage.haskell.org/package/stm)
* [Clojure Refs - STM](https://clojure.org/reference/refs)

## Fibers / Coroutines
* [Processes, threads, green threads, protothreads, fibers, coroutines: what's the difference? (SO)](https://stackoverflow.com/questions/3324643/processes-threads-green-threads-protothreads-fibers-coroutines-whats-the)
* [Distinguishing coroutines and fibers (pdf)](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2014/n4024.pdf)
* [The Obligatory "Why Elixir?" Personal Take](http://www.akitaonrails.com/2015/12/01/the-obligatory-why-elixir-personal-take#coroutines)
* [Erlang (and Go) in Clojure (and Java)](http://blog.paralleluniverse.co/2013/05/02/quasar-pulsar/)
* [MS Windows - Processes and Threads - Fibers](https://docs.microsoft.com/en-gb/windows/desktop/ProcThread/fibers)
* [Coroutines and Fibers. Why and When - Mark Papadakis](https://medium.com/software-development-2/coroutines-and-fibers-why-and-when-5798f08464fd) [hasker news](https://news.ycombinator.com/item?id=10908147)
* [Hackage coroutines libraries](http://hackage.haskell.org/packages/search?terms=coroutines)
* [C++ Boost Coroutine vs Fiber - SO](https://stackoverflow.com/questions/44521178/what-is-the-difference-between-coroutine-coroutine2-and-fiber)
* [Why I'm Excited About Scalaz 8 - John A De Goes](http://degoes.net/articles/scalaz8-is-the-future)
* [kilim - Lightweight threads for Java](https://github.com/kilim/kilim)
* [puniverse/quasar - Fibers, Channels and Actors for the JVM](https://github.com/puniverse/quasar)
* [Eta Fibers Towards Better Concurrency on the JVM - Rahul Muttineni (video)](https://www.youtube.com/watch?v=ZuJg2cfmSmw) [slides](https://rahulmutt.github.io/slides/fuconf17-eta-fibers/slides.html#1)
* [Coroutines, Fibers and Threads, Oh My (video)](https://www.youtube.com/watch?v=S6JpbmeuzNg)

## Session Types
* State Machines All The Way Down - Edwin Brady [(paper)](https://www.idris-lang.org/drafts/sms.pdf)
* Session Types for Rust [(paper)](http://munksgaard.me/papers/laumann-munksgaard-larsen.pdf)
* Embedding Session Types in Haskell [(video)](https://www.youtube.com/watch?v=rweCcOTfgWs)
* [Publications by Sam Lindley](http://homepages.inf.ed.ac.uk/slindley/) Session types, compare to actors, CPS,
* OPLSS 2018 - Session-Typed Concurrent Programming - Stephanie Balzer [(video lectures)](https://www.cs.uoregon.edu/research/summerschool/summer18/topics.php#Balzer)

# Parallelism/Concurrency in programming languages

## Parallelism/Concurrency in Clojure
* [Clojure docs - Concurrency overview](https://clojure.org/about/concurrent_programming)
* [Clojure docs - Refs](https://clojure.org/reference/refs)
* [Clojure docs - Atoms](https://clojure.org/reference/atoms)
* [Clojure docs - Agents](https://clojure.org/reference/agents)
* [Clojure docs - Vars](https://clojure.org/reference/vars)
* [clojure/core.async](https://github.com/clojure/core.async)

## Parallelism/Concurrency in Scala
* [Futures & Promises](https://docs.scala-lang.org/overviews/core/futures.html)
* [Akka](https://akka.io/)
* [Monix](https://monix.io/)
* [fs2](https://fs2.io/)
* [Scalaz zio](https://github.com/scalaz/scalaz-zio)
* [Iteratees](https://github.com/travisbrown/iteratee)
* [Akka Streams](https://doc.akka.io/docs/akka/current/stream/index.html)

## Parallelism/Concurrency in Rust
* [The Rust Programming Language - Concurrency](https://doc.rust-lang.org/book/ch16-00-concurrency.html)
* Session Types for Rust [(paper)](http://munksgaard.me/papers/laumann-munksgaard-larsen.pdf)
* OPLSS 2018 - Aaron Turon [(video lectures, links)](https://www.cs.uoregon.edu/research/summerschool/summer18/topics.php#Turon)

## Parallelism/Concurrency in Go
* [Go docs - Concurrency](https://golang.org/doc/effective_go.html#concurrency)

## Parallelism/Concurrency in Haskell
* [Haskell Wiki - Parallelism and concurrency](https://wiki.haskell.org/Research_papers/Parallelism_and_concurrency)
* [Parallel and Concurrent Programming in Haskell](https://simonmar.github.io/pages/pcph.html)
* [Coroutine](http://hackage.haskell.org/package/Coroutine)
* [pipes](http://hackage.haskell.org/package/pipes)
* [conduit](http://hackage.haskell.org/package/conduit)
* [machines](http://hackage.haskell.org/package/machines)
* [Haskell STM](http://hackage.haskell.org/package/stm)
* Embedding Session Types in Haskell [(video)](https://www.youtube.com/watch?v=rweCcOTfgWs)
* Revisiting software transactional memory in Haskell 2016 [(paper)](https://dl.acm.org/citation.cfm?id=2976020)
* [ubenpieters/Orthogonal-Pipes](https://github.com/rubenpieters/Orthogonal-Pipes) Faster coroutine pipelines - Michael Spivey[paper](https://dl.acm.org/citation.cfm?doid=3136534.3110249)

## Parallelism/Concurrency in Erlang
* [Erlang User's Guide - Concurrent Programming](http://erlang.org/doc/getting_started/conc_prog.html)
* Modelling Erlang Processes as Petri Nets [(video)](https://www.youtube.com/watch?v=Gzl5dBNxD6Q)


# Computational effects
* [yallop/effects-bibliography](https://github.com/yallop/effects-bibliography)
* Algebraic Effects and Handlers - Andrej Bauer [(video lectures)](https://www.cs.uoregon.edu/research/summerschool/summer18/topics.php#Bauer)
* [effect-handlers/effects-rosetta-stone](https://github.com/effect-handlers/effects-rosetta-stone)
* Algebraic Effect Handlers go Mainstream [links to publications of participants](https://www.dagstuhl.de/program/calendar/partlist/?semnr=18172&SUOG), report with summary of talks [(pdf)](http://drops.dagstuhl.de/opus/volltexte/2018/9762/pdf/dagrep_v008_i004_p104_18172.pdf)
* [purescript/purescript-effect](https://github.com/purescript/purescript-effect)
* [slamdata/purescript-aff](https://github.com/slamdata/purescript-aff)
* [owickstrom/purescript-leffe](https://github.com/owickstrom/purescript-leffe)


# Benchmarks
* https://github.com/travisbrown/iteratee
* http://letitcrash.com/post/14783691760/akka-vs-erlang
* https://alexn.org/blog/2016/08/25/monix-task-performance.html
* http://degoes.net/articles/scalaz8-is-the-future
* https://doc.akka.io/docs/akka/1.3/additional/benchmarks.html
* https://github.com/ThoughtWorksInc/Dsl.scala/wiki/Benchmarks:-Dsl.scala-vs-Monix-vs-Cats-Effect-vs-Scalaz-Concurrent-vs-Scala-Async-vs-Scala-Continuation
* https://github.com/fosskers/scala-benchmarks



# Benchmarks - unrelated but interesting anyhow :)
* http://www.lihaoyi.com/post/BenchmarkingScalaCollections.html
* https://www.techempower.com/benchmarks/
