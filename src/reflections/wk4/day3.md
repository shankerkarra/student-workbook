# Week 4( Day 3)

## What is the purpose of Async/Await?
Promises are introduced to reduce the issues related to the chaining of callback, but promises has complexity issues. Async/awaitis bbuild on top of promises, but to  reduce the complexity.  Async/await doesn't hold the application and looks like the code is synchronous, executes the code behind.

## What must you do in order to await a promise inside of a function?

In order to await a promise, the function needs to be prefixed with async and the call should have await.

## What are some of the primary benefits of Async/Await?

Using sync/await, th chained callback promises can be broken down into multiple individual conditions. It helps in readablility and the code will look like  synchronous.

lab url: https://shankerkarra.github.io/Pokemon/