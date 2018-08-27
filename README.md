Recently, we moved our Browser RUM agent from JavaScript to TypeScript (https://blog.appdynamics.com/devops/8-steps-migrating-javascript-typescript/). In my last post, I focused on walking through the steps of migrating from JavaScript, the challenges, and best practices we uncovered along the way.
This one will focus on more details of the benefits and one missing feature in TypeScript compiler we suggest to implement.

TypeScript’s main benefits:

Class and Module Support
Static Type-checking
ES6 Feature Support
Clear Library API Definition
Build-in Support for JavaScript Packaging
Syntax Similarity to Our Backend Languages (Java, [Scala] (http://www.slideshare.net/razvanc/quick-typescript-vs-scala-sample))
Superset of JavaScript
Class and Module Support
Keywords like class, interface, extends and module are available in TypeScript.
You can define a class as
