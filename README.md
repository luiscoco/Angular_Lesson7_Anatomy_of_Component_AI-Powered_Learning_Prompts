# Angular - Lesson7 - Anatomy of Component AI-Powered Learning Prompts

Role: Your AI assistant acts as a Framework Reasoning Coach
Goal: Understand why Angular components are shaped the way they are, not just how to write them
________________________________________
Practice Set 1 — Conceptual Foundations (Component Mental Model)
Practice Prompt 1 — What Is a Component, Really?
Ask your AI assistant:
“Why does Angular insist that every component must have a class, a template, and a selector?”
Reflect on:
•	Separation of behavior vs presentation
•	Why Angular does not allow a component to be “just HTML”
•	How this model supports tooling, testing, and scalability
Outcome:
You should be able to explain a component as a unit of behavior + structure + identity, not as a UI fragment.
________________________________________
Practice Prompt 2 — The Selector as a Design Decision
Ask:
“Why is the component selector part of the component itself instead of being defined externally?”
Consider:
•	Components as reusable HTML primitives
•	How selectors define where a component belongs in the DOM
•	Why Angular prefers declarative composition over imperative rendering
Outcome:
You should see the selector as the component’s public API in the DOM.
________________________________________
Practice Set 2 — The @Component Decorator as Metadata
Practice Prompt 3 — Metadata vs Code
Ask:
“Why does Angular place configuration (template, styles, selector) inside a decorator instead of inside the class body?”
Explore:
•	Metadata vs runtime logic
•	How the Angular compiler uses decorators
•	Why this separation enables static analysis and optimization
Outcome:
You should recognize @Component as instructions for the framework, not business logic.
________________________________________
Practice Prompt 4 — Inline vs External Templates
Ask:
“What trade-offs exist between inline templates/styles and external files?”
Weigh:
•	Local readability vs file separation
•	Refactoring and code navigation
•	Team scale and ownership (designers vs developers)
Outcome:
You should be able to justify when to choose each approach intentionally.
________________________________________
Practice Set 3 — Styling and Encapsulation
Practice Prompt 5 — Why Styles Are Scoped by Default
Ask:
“Why does Angular scope component styles by default instead of letting CSS cascade freely?”
Reflect on:
•	CSS leakage problems in large applications
•	Predictability vs flexibility
•	How this aligns with component-based architecture
Outcome:
You should understand style scoping as a defensive design choice, not a limitation.
________________________________________
Practice Prompt 6 — Component as a Visual Boundary
Ask:
“How does Angular’s styling model reinforce the idea of components as independent UI units?”
Outcome:
You should connect styling encapsulation to maintainability and long-term stability.
________________________________________
Practice Set 4 — Using Components (Composition & Imports)
Practice Prompt 7 — Why Imports Are Explicit
Ask:
“Why must a component explicitly import other components it uses?”
Think about:
•	Dependency visibility
•	Tree-shaking and build optimization
•	Making component dependencies auditable
Outcome:
You should view the imports array as a dependency contract, not boilerplate.
________________________________________
Practice Prompt 8 — Standalone Components vs NgModules
Ask:
“What problem do standalone components solve compared to NgModules?”
Analyze:
•	Cognitive load
•	Local reasoning vs global configuration
•	How this change reflects Angular’s evolution
Outcome:
You should understand standalone components as a move toward simpler mental models.
________________________________________
Practice Set 5 — Rendering & the DOM
Practice Prompt 9 — Host Element vs View
Ask:
“Why does Angular distinguish between a component’s host element and its view?”
Explore:
•	DOM ownership
•	Lifecycle boundaries
•	Why this distinction matters for styling, queries, and DI
Outcome:
You should be able to clearly explain what Angular creates vs what you write.
________________________________________
Practice Prompt 10 — Components as Instances
Ask:
“Why does Angular create a new component instance for each matching selector in the DOM?”
Consider:
•	Encapsulation of state
•	Reusability without shared mutation
•	How this mirrors object-oriented principles
Outcome:
You should see Angular components as stateful objects mapped onto the DOM.
________________________________________
Practice Set 6 — Application as a Component Tree
Practice Prompt 11 — Thinking in Trees
Ask:
“Why is Angular best understood as a tree of components rather than a collection of pages?”
Reflect on:
•	Parent-child relationships
•	Data flow and dependency injection
•	Why this mental model scales better than page-based thinking
Outcome:
You should naturally describe an Angular app as a hierarchical composition, not flat screens.
________________________________________
Practice Prompt 12 — Why the Tree Matters Later
Ask:
“Which Angular features become easier to understand once you think in terms of a component tree?”
Hint:
Dependency injection, queries, lifecycle hooks, change detection.
Outcome:
You should recognize the component tree as a foundational abstraction for the entire framework.
________________________________________
Final Reflection — Framework Literacy
Practice Prompt 13 — Beyond Syntax
Ask:
“How does Angular’s component model balance structure, flexibility, and long-term maintainability?”
Goal:
Articulate why Angular components look the way they do — even if another framework chooses differently.
Outcome:
You move from Angular user → Angular reasoner.


