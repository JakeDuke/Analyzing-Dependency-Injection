# Analyzing Modular Applications

In this project I read and analyzed several applications.  They each had a slightly different structure but all of them were built from small, reusable pieces of code.  

I learned how to read applications like the runtime environment by finding the entry point and back-tracking through "require" statements to build up a complete specification of the application at run-time.

Using this technique I was able to understand how "Dependency Injection" (or _developing to an interface_) is a great way to make maintainable, flexible applications that can be modified for different run-time environments or UI's.

---

## Projects I Analyzed

[dom-console-node](https://github.com/elewa-academy/Modular-Design/tree/master/03-dependency-injection/1-app-components-architecture/1-dom-console-node)
[mix-match-operation](https://github.com/elewa-academy/Modular-Design/tree/master/03-dependency-injection/1-app-components-architecture/2-mix-match-operations)
---

## Notes


Things I learned:
* How to infer the runtime application from sourcecode
* Navigating repositories
* Thinking of applications as pieces of functionality instead of code
* More about sourcecode vs runtime
* Using diagrams to understand the architecture of applications

New Vocabulary:
* Dependency Injection
* Developing to an Interface

Things I struggled with:
* Holding the runtime application in my working memory
* Navigating file structures: on GitHub, terminal, and text editor
* Diagramming Build-time behavior
* Mapping build-time diagrams into run-time specs

Next study plans:
* Read & diagram more code!
* Diagram my projects before I build them