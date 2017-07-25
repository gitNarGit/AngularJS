![ng-post-1-pic-2](https://user-images.githubusercontent.com/27890805/28572953-fc51d4ba-7159-11e7-80b6-18e65f91b471.png)

# What Is AngularJS?
AngularJS is a structural framework for dynamic web apps. It lets you use HTML as your template language and lets you extend HTML's syntax to express your application's components clearly and succinctly.
AngularJS is what HTML would have been, had it been designed for applications. HTML is a great declarative language for static documents.

AngularJS takes another approach. It attempts to minimize the impedance mismatch between document centric HTML and what an application needs by creating new HTML constructs. AngularJS teaches the browser new syntax through a construct we call directives. Examples include:

- Data binding, as in {{}}.
- DOM control structures for repeating, showing and hiding DOM fragments.
- Support for forms and form validation.
- Attaching new behavior to DOM elements, such as DOM event handling.
- Grouping of HTML into reusable components.

## AngularJS's sweet spot

AngularJS simplifies application development by presenting a higher level of abstraction to the developer. AngularJS was built with the CRUD application in mind. Luckily CRUD applications represent the majority of web applications. To understand what AngularJS is good at, though, it helps to understand when an app is not a good fit for AngularJS.

# The Zen of AngularJS
AngularJS is built around the belief that declarative code is better than imperative when it comes to building UIs and wiring software components together, while imperative code is excellent for expressing business logic.

- It is a very good idea to decouple DOM manipulation from app logic. This dramatically improves the testability of the code.
- It is a really, really good idea to regard app testing as equal in importance to app writing. Testing difficulty is dramatically affected by the way the code is structured.
- It is an excellent idea to decouple the client side of an app from the server side. This allows development work to progress in parallel, and allows for reuse of both sides.
- It is very helpful indeed if the framework guides developers through the entire journey of building an app: From designing the UI, through writing the business logic, to testing.
- It is always good to make common tasks trivial and difficult tasks possible.

AngularJS frees you from the following pains:
- Registering callbacks
- Manipulating HTML DOM programmatically
- Marshaling data to and from the UI
- Writing tons of initialization code just to get started