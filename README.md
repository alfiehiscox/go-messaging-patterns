# Go Messaging Patterns

This repo is to track and explore [Messaging Patterns](http://tmrts.com/go-patterns/#messaging-patterns) in Go. 

With the mass exodus of software from Monolithic to Micro-service systems, 
messaging or [event driven architecture](https://en.wikipedia.org/wiki/Event-driven_architecture) is a huge space at the moment. How does
one deal with the complexity of such a change? Well a good start is to study the
patterns and pitfalls that have come from implementing such systems in the past,
learning from these patterns enables us to build more resilient software from 
day 1.

Inside this repo you will find implementations of such patterns written in Go.
A list of patterns (to be updated as we go along) can be found below. Each pattern 
is it's own go package, and all packages live in a Go Module that you can interact
with as you choose. 

Many, if not all, of the modules will contain a HOWTO.md file that will walk 
you through the process of the implementation. It will also include the advantages 
and disadvantages of using said pattern in your workflow.

## Patterns
- Publish/Subscriber
- Fan Out
- Fan In
