# Java Futures

## Scenario 1: Java Concurrent Programming: Basics and Thread Pools

Futures have been around since JDK 5, let’s make sure we understand the old classic java.util.concurrent.Future first.  First we start off with Thread Pools: Fixed, Cached, Single Threaded, Single Thread, and Work-stealing Thread Pool.  We take a look at them in turn and discuss when to choose one over the other.

## Scenario 2:  Java Concurrent Programming: Creating a Completable Future

We  approach the modern era of concurrent development using a Completable Future. In this short scenario, we do a simple completable future creation and accept the value.  In the following scenarios, we compose the complete futures. Then we discuss how to create a Completable Future so we can, for example, look up the current temperature for a city anywhere in the world.  Future by themselves don’t accept parameters, how do we program it?

## Scenario 3: Java Concurrent Programming: Functional Programming a Completable Future

We take our computation, but now we want to do something with the results; manipulate it, enhance it, combine it, and compose with another Completable Future object. In this scenario, we display how to handle the difficult situations when Completable Futures fail and we can recover from a disaster.

## Scenario 4: Java Concurrent Programming: Making Promises

All the futures we covered are a computation, what if we don’t want a computation? Maybe I want to provide the answer based on a manual decision, this is where a promise can come in.

## Scenario 5: Java Concurrent Programming: Learning new Advancements in `CompletableFuture`s

With each new JDK, new methods that are introduced to the CompletableFuture, so we go through all the latest CompletableFuture features available now up to JDK 14 and describe their use-case.

