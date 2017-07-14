# `async`/`await`, Generators, TypeScript, and jQuery

A brief exploration for [SeattleJS](https://github.com/seattlejs/seattlejs) into async/await, generators, and hacking TypeScript to like jQuery's Promises.

We'll look into how generators work to let functions stop and start again, and see how `async` functions combine generators with `Promise`s to make asynchronous coding smoother.
We'll then see how TypeScript processes code using those ideas and how we can hack that to use `jQueryPromise`s instead of the built-in ones.

### About

This is the source code for a talk given by [Josh Goldberg](http://joshuakgoldberg.com), Software Development Engineer at Microsoft in Office Sway, for SeattleJS on 7/13/2017.
That's me!

Since it's a :zap: _lightning_ :zap: talk, we'll try to keep it surface level.
Stop me if you're lost.

### Table of Contents

1. [Generators](./1.%20Generators.md)
2. [`async`/`await`](./2.%20async-await.md)
3. [TypeScript](./3.%20TypeScript.md)
4. [Hacking the `__awaiter`](./4.%20Hacking%20the%20awaiter.md)
5. [Takeaways](./5.%20Takeaways.md)
