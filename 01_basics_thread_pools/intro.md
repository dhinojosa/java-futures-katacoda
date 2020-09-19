In this Katacoda we will do an in-depth look into Java Futures.  Java Futures are the result or the upcoming result of an asynchronous operation. Every `Future` is parameterized with an answer, for example `Future<Integer>` states that the asynchronous operation will return an `Integer` when it is complete.  A `Future` is either in one of two states, in process or complete.  A `Future` can be cancelled, except when it is complete.

Most new frameworks and libraries use `Future`s.  In Effective Java 3rd Edition, Java luminary Josh Bloch writes to prefer executors, tasks, and streams to threads.  Threads are the "old way". Our new `java.util.concurrent` API which includes `Future`, `CompletableFuture`, `Task`, `Executors`. In this Katacoda we focus on `Future`, `CompletableFuture` and `Executors`, let's get started. 