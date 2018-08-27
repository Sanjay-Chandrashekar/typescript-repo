[Recently, we moved our Browser RUM agent from JavaScript to TypeScript](https://blog.appdynamics.com/devops/8-steps-migrating-javascript-typescript/). In my last post, I focused on walking through the steps of migrating from JavaScript, the challenges, and best practices we uncovered along the way.

This one will focus on more details of the benefits and one missing feature in TypeScript compiler we suggest to implement.

TypeScript’s main benefits:

1. Class and Module Support
2. Static Type-checking
3. ES6 Feature Support
4. Clear Library API Definition
5. Build-in Support for JavaScript Packaging
6. Syntax Similarity to Our Backend Languages (Java, [Scala](http://www.slideshare.net/razvanc/quick-typescript-vs-scala-sample))
7. Superset of JavaScript

### Class and Module Support

Keywords like class, interface, extends and module are available in TypeScript.

You can define a class as

[*// class define in TypeScript*](https://placehold.it/15/1589F0/000000?text=+)
