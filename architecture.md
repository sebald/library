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