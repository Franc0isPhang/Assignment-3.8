## Assignment

### Brief

In this assignment, we will perform group research on:

1. The difference between Asynchronous Programming and Multithreaded Programming
1. The various approach to run `CompletableFuture` that is used for asynchronous programming

> Note: No coding assignment

### Async vs Multithreaded Programming

In your group, research and discuss the difference between Asynchronous Programming and Multithreaded Programming.

Q1: What is asynchronous programming?

```
Asynchronous programming is a technique that enables your program to start a potentially long-running task and still be able to be responsive to other events while that task runs, rather than having to wait until that task has finished. Once that task has finished, your program is presented with the result.
```

Q2: What is multithreaded programming?
```
Multithreading is the ability of a program or an operating system to enable more than one user at a time without requiring multiple copies of the program running on the computer. Multithreading can also handle multiple requests from the same user.
```

Q3: What are the similaries and differences between them?
```
From the definitions we just provided, we can see that multithreading programming is all about concurrent execution of different functions. Async programming is about non-blocking execution between functions, and we can apply async with single-threaded or multithreaded programming.

Multithreading is about workers, Asynchronous is about tasks.
```

### Understanding `CompletableFuture`

Q1: What is the difference between `supplyAsync` and `runAsync` in `CompletableFuture`?

```
 runAsync() is used when you want to run a task asynchronously and do not need to produce any result, while supplyAsync() is used when you want to run a task asynchronously and produce a result which can be used to complete the returned CompletableFuture instance.
```

Q2: What is the difference between `thenAccept`, `thenRun`, and `thenApply` in `CompletableFuture`?
```
The method thenApply is similar to thenAccept, except that instead of a Consumer, the callback that gets invoked when the asynchronous task completes is a `Function.

There are other variations:

thenRun, which takes a Runnable,
```

### Submission

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL.

### References

_Example of Referencing Classmate_

Referenced the code block below from Terence.

```js
function printMe() {
  console.log('I am a reference example');
}
```

_Example of Referencing Online Resources_

- https://developer.mozilla.org/en-US/
- https://www.w3schools.com/html/
- https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github
