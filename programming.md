# Programming

- [Designing Even Larger Applications](https://medium.com/@cramforce/designing-even-larger-applications-460ee029012d?source=friends_link&sk=e732423e46e87029473431067fd066fc) 

  > Unnecessary tradeoffs are the root of all evil.
  
  > If uncertainty is high then reduce the degree of abstraction.

- [The Cost of Abstraction](http://sam-koblenski.blogspot.de/2014/07/the-cost-of-abstraction.html)

  > Adding abstractions only when and where they're necessary allows a software system to evolve naturally, becoming the solution it needs to be without adding a lot of extra cruft. If the team accepts this process and allows it to happen instead of fighting against it, development will have a pleasant flow to it. Progress will be faster and require less effort when the system isn't overloaded with unnecessary, costly abstractions.
  
- [The wrong Abstraction](https://www.sandimetz.com/blog/2016/1/20/the-wrong-abstraction)

  > duplication is far cheaper than the wrong abstraction

  > prefer duplication over the wrong abstraction

  > The moral of this story? Don't get trapped by the sunk cost fallacy. If you find yourself passing parameters and adding conditional paths through shared code, the abstraction is incorrect. It may have been right to begin with, but that day has passed. Once an abstraction is proved wrong the best strategy is to re-introduce duplication and let it show you what's right. Although it occasionally makes sense to accumulate a few conditionals to gain insight into what's going on, you'll suffer less pain if you abandon the wrong abstraction sooner rather than later.

  > When the abstraction is wrong, the fastest way forward is back. This is not retreat, it's advance in a better direction. Do it. You'll improve your own life, and the lives of all who follow.

- [Too much Abstraction](http://wiki.c2.com/?TooMuchAbstraction)

  > I think that his point is that when you add abstraction layers, you risk changing the original problem into a more general and possibly more complex one.
  
- [The law of leaky Abstractions](https://www.joelonsoftware.com/2002/11/11/the-law-of-leaky-abstractions/)

  > The law of leaky abstractions means that whenever somebody comes up with a wizzy new code-generation tool that is supposed to make us all ever-so-efficient, you hear a lot of people saying “learn how to do it manually first, then use the wizzy tool to save time.” Code generation tools which pretend to abstract out something, like all abstractions, leak, and the only way to deal with the leaks competently is to learn about how the abstractions work and what they are abstracting. So the abstractions save us time working, but they don’t save us time learning.
  > 
  > And all this means that paradoxically, even as we have higher and higher level programming tools with better and better abstractions, becoming a proficient programmer is getting harder and harder.

- [Write code that is easy to delete, not easy to extend.](http://programmingisterrible.com/post/139222674273/write-code-that-is-easy-to-delete-not-easy-to)

  > You don’t need to throw it all away but you will need to delete some of it. Good code isn’t about getting it right the first time. Good code is just legacy code that doesn’t get in the way.
  >
  > Good code is easy to delete.

- [Oh composable World!](https://www.youtube.com/watch?v=SfWR3dKnFIo)

  > All about dot-chaining and how FP helps/deals with control flow, side effects, ...

- [Call me Maybe](https://glebbahmutov.com/blog/call-me-maybe/)

  > Replacing the built-in OR and TERNARY operators with Maybe monads.

- [The Intuition behind Applicative](https://glebbahmutov.com/blog/applicative-intuition/)

  > If you have a plain value, it can be wrapped and mapped over a function Box(x).map(f)
  > If you have a function, you can wrap it and apply to a wrapped value Box(f).ap(Box(x))
  > You can apply wrapped function that expects multiple arguments if you curry the function

- [The Return of Stream I/O](https://www.youtube.com/watch?v=Tkjg179M-Nc)

  > While the I/O Monad has been established as the standard in Haskell, we are seeing the resurgence of variations of Stream I/O in Frontend, through tools like Cycle.js and Elm. In this talk we will explore the benefits and downsides of Stream I/O, and what it promises for the future.

- [WTF is JSX](https://jasonformat.com/wtf-is-jsx/)

  > JSX is actually quite straightforward: take 1 minute and read this, and you'll understand everything there is to know about this interesting alternative to templates.

- [Functional Principles for Object-Oriented Development](https://www.youtube.com/watch?v=GpXsQ-NIKXY)

- [Goodbye, Object Oriented Programming](https://medium.com/@cscalfani/goodbye-object-oriented-programming-a59cda4c0e53)

  > The problem with object-oriented languages is they’ve got all this implicit environment that they carry around with them.   > You wanted a banana but what you got was a gorilla holding the banana and the entire jungle.