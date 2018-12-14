# Principles

- [The Ten Commandments of Egoless Programming](https://blog.codinghorror.com/the-ten-commandments-of-egoless-programming/) 

- [The Origins of Opera and the Future of Programming](https://the-composition.com/the-origins-of-opera-and-the-future-of-programming-bcdaf8fbe960)

  > Great Teams Make Great People. You don’t hire star developers, put them together, and poof get a great team. It’s the other way around. When developers form a great team, the team makes us into great developers.
  
  > Systems thinking says, we are more than the components; we are also the interrelationships. Agile recognizes that these matter.
  
  > My team includes the people I work with, and also the software itself. And the servers it runs on, the databases it uses, and all the tools that we use to interact with the running software: the code, version control, automated tests, deployment scripts, logging.
  
  > This is dangerous, because the useful ideas are the ones we contribute. The mental models we hoard make us look good; those we share make the whole team powerful.
  
  > Software is not Art. Software is the next thing after art. It is something new, that we’ve never been able to do before.

- [Becoming a 10x Developer](https://kateheddleston.com/blog/becoming-a-10x-developer)

  > A 10x engineer isn’t someone who is 10x better than those around them, but someone who makes those around them 10x better.

# Architecture

- [Removing User Interface Complexity, or Why React is Awesome](http://jlongster.com/Removing-User-Interface-Complexity,-or-Why-React-is-Awesome)

  > I ask that you set aside your framework prejudices and read this post with an open mind. This post is not to evangelize React specifically, but to explain why its technique is profound. I want developers steeped in other technologies to take a hard look at these techniques, particularly those involved in Web Components.

- [Designing very large (JavaScript) applications](https://medium.com/@cramforce/designing-very-large-javascript-applications-6e013a3291a3) [🎬](https://www.youtube.com/watch?v=ZZmUwXEiPm4)

  > avoid central configuration of your application at all cost, because central configuration, like having a central CSS file, makes it very hard to delete code.
  
  > In fact, it is the opposite of import. It is a reverse dependency. If you enhance a module, you make that module have a dependency on you.
  >
  > Looking at the dependency graph, what happens it that there are still the same components, but the arrows point in the opposite direction. So, instead of the router importing the root component, the root components announce themselves using enhance to the router. This means I can get rid of a root component by just deleting the file. Because it is no longer enhancing the router, that is the only operation you have to do to delete the component.

- [From Dependency Injection to Dependency Rejection](http://blog.ploeh.dk/2017/01/27/from-dependency-injection-to-dependency-rejection/)

  > The problem typically solved by dependency injection in object-oriented programming is solved in a completely different way in functional programming.

- [Pure UI](https://rauchg.com/2015/pure-ui)

  > The fundamental idea I want to discuss is the definition of an application’s UI as a pure function of application state.

  > Since I’m not returning the actual DOM elements (no document.createElement) or performing any real rendering, we can think of this function as one that performs mappings between an input (my parameters) and an output (the virtual dom).
  >
  > If throughout the lifetime of the program the parameters change (let’s say there’s a new video to play or the user performs an action), the function is called again with new parameters and the rendered view is updated.
  >
  > With this model in place, the programmer is thus relieved from the burden of specifying the transition between states (or transformation) of the UI over time. No need to specify how to go from A to B: just describe what A looks like and what B looks like, in a discrete way.
  
- [Documenting Architecture Decisions](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)

  > An architecture decision record is a short text file in a format similar to an Alexandrian pattern. (Though the decisions themselves are not necessarily patterns, they share the characteristic balancing of forces.) Each record describes a set of forces and a single decision in response to those forces. Note that the decision is the central piece here, so specific forces may appear in multiple ADRs.
  
- [Von Schichten zu Ringen – Hexagonale Architekturen erklärt](https://www.maibornwolff.de/blog/von-schichten-zu-ringen-hexagonale-architekturen-erklaert) *(German)*

  Short, but easy to comprehend!
  
# Learning

- [Half Life: The Decay of Knowledge and What to Do About It](https://www.fs.blog/2018/03/half-life/)

  > The problem is that we rarely consider the half-life of information. Many people assume that whatever they learned in school remains true years or decades later.
  
  > The faster the pace of knowledge change, the more valuable the skill of learning becomes.

- [How Developers Stop Learning: Rise of the Expert Beginner](http://www.daedtech.com/how-developers-stop-learning-rise-of-the-expert-beginner)

  > On the other hand, the least talented developers are more likely to stay put since they’ll have a hard time convincing other companies to hire them. This serves as important perspective for understanding why it’s common to find people with titles like “super-duper-senior-principal-fellow-architect-awesome-dude,” who make a lot of money and perhaps even wield a lot of authority but aren’t very good at what they do.

  > There’s nothing you can do to improve as long as you keep bowling like that. You’ve maxed out. If you want to get better, you’re going to have to learn to bowl properly. You need a different ball, a different style of throwing it, and you need to put your fingers in it like a big boy. And the worst part is that you’re going to get way worse before you get better, and it will be a good bit of time before you get back to and surpass your current average.

- [The Difference Between Excellent, Good and Bad JavaScript Developers](http://thefullstack.xyz/excellent-javascript-developer/)

  > How we behave when writing horrible code is the ultimate litmus test for developer competency.

- [What I Wish I Knew When Starting Out as a Software Developer: Slow the Fuck Down](http://blog.salsitasoft.com/what-i-wish-i-knew-when-starting-out-as-a-software-developer-slow-the-fuck-down/)

  > [..] it's about creating software that is stable, performant, maintainable and understandable.

- [Why debugging is all about understanding](http://futurice.com/blog/why-debugging-is-all-about-understanding)

  > Programmers often make the bug "the enemy", and it's not rare to swear at the computer. Programming, however, is a lot about understanding correctly, not about typing and building. Most of our programming time is spent understanding how all parts should be connected, and only a small fraction of our time is spent with actual keyboard typing.

# Process

- [Agile Software Development: The Business of Innovation](http://sunset.usc.edu/events/2002/arr/agile.pdf)
  
  > Traditional approaches assumed that if we just tried hard enough, we could anticipate the complete set of requirements early and reduce cost by eliminating change. Today, eliminating change early means being unresponsive to business conditions—in other words, business failure.
  
- [Agile Software Development: The People Factor](https://pdfs.semanticscholar.org/9558/7f603098b5b30253b727cb9e0ddaac6ba164.pdf)

  > The first is the idea that the business and technology worlds have become turbulent, high speed, and uncertain, requiring
a process to both create change and respond rapidly to change. 

  > The first connotation implies the second one: An agile process requires responsive people and organizations.
Agile development focuses on the talents and skills of individuals and molds process to specific people and teams, not the other way around.

- [Why slow thinking wins](https://www.bostonglobe.com/ideas/2015/07/25/the-power-slow-thinking/ToZbzYl7rG0yVMCtsZ7WnJ/story.html)

  > Everyone remembers the story of the tortoise and the hare, but no one seems to have learned the lesson it teaches: Slowness wins.

  *One of the best books ever: [Thinking, Fast and Slow, Daniel Kahneman](https://www.amazon.com/Thinking-Fast-Slow-Daniel-Kahneman/dp/0374533555)*

- [Technical debt 101](https://medium.com/@joaomilho/festina-lente-e29070811b84)

  > A “debt” means that you traded acquiring something now for a long-term financial burden. This burden is not just about repaying what you got: there is an “interest”. It means that, even if you pay your debt timely, you’ll pay more than you took, and if you don’t, your debt will keep increasing even if you don’t do anything. And if you ignore a debt long enough, it will become unpayable and you’ll get “bankrupt”.

  > The problem of big rewrites is that they are a technical solution to a cultural problem.

  > He thought nothing less becoming in a well-trained leader than haste and rashness, and, accordingly, favorite sayings of his were: More haste, less speed.
  >
  > That is done quickly enough which is done well enough.

- [Defining and Dealing with Technical Debt](https://css-tricks.com/defining-and-dealing-with-technical-debt/)

  > The one thing worth taking away from the Wikipedia entry is that not all technical debt is created equal. In fact, there are four types of debt to consider. Let's take a look at each one.

- [Getting Real: Take it slow if you need it fast](https://signalvnoise.com/archives2/getting_real_take_it_slow_if_you_need_it_fast.php)

  > In the moment of pressure, it’s incredibly easy to commit the fallacy of thinking that you “don’t have time to do the right thing”. That’s a big warning sign and should condition your brain to slap you when the thought pops into your head.

- [Bad code isn't Technical Debt, it's an unhedged Call Option](http://higherorderlogic.com/2010/07/bad-code-isnt-technical-debt-its-an-unhedged-call-option/)

  > This is all Chris Matts‘ idea. He realised that the problem with the “Technical Debt” metaphor is that for managers debt can be a good thing. Executives can be required to take on more debt because it makes the finances work better, it might even be encouraged by tax breaks. This is not the same debt as your personal credit card. Chris came up with a better metaphor, the Call Option.

- [Code Review Checklist](https://ana-balica.github.io/2017/02/21/code-review-checklist/)

  > Over the last couple of months, I’ve developed my own internal code review checklist. I use it both for reviewing for own finished code and my teammates code complete tickets. It’s split up into 3 sections: code, automated testing and manual testing.
  
- [Solve it once](http://gedd.ski/post/solve-it-once/)

  > When you set out to solve a problem, the biggest temptation is to do a quick fix. [..] Here’s a better way to work: if it happens twice, solve it once. Like, actually solve it.

# Programming

- [The Cost of Abstraction](http://sam-koblenski.blogspot.de/2014/07/the-cost-of-abstraction.html)

  > Adding abstractions only when and where they're necessary allows a software system to evolve naturally, becoming the solution it needs to be without adding a lot of extra cruft. If the team accepts this process and allows it to happen instead of fighting against it, development will have a pleasant flow to it. Progress will be faster and require less effort when the system isn't overloaded with unnecessary, costly abstractions.
  
- [The wrong Abstraction](https://www.sandimetz.com/blog/2016/1/20/the-wrong-abstraction)

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

# Design

- [Change your focus and design "Content First"](https://www.everydaydesigner.net/design/change-your-focus-and-design-content-first)

- [Aesthetic Sass 3: Typography and Vertical Rhythm](https://scotch.io/tutorials/aesthetic-sass-3-typography-and-vertical-rhythm)

  > [..] using both a modular type scale and a vertical rhythm can provide a systematic way of laying out content in your projects, without having to use magic numbers.
  
- [Intro to The 8-Point Grid System](https://builttoadapt.io/intro-to-the-8-point-grid-system-d2573cde8632)

  > Bootstrap is an opinionated library of components that allows designers/developers to focus on the content and user experience. It has raised the quality of countless websites across the web. But not having a consistent unit of measurement can lead to layout inconsistencies between pages, particularly on projects with two or more designers.
  
- [CSS Baseline: The Good, The Bad And The Ugly](https://www.smashingmagazine.com/2012/12/css-baseline-the-good-the-bad-and-the-ugly/) 

# Quotes

> The primary cost of abstaction is indirection. In my experience, you should only abstract when the added abstraction clarifies things more than the added indirection confuses them. - Bryan Edds
