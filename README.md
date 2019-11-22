# Javascript-Interview-Questions
A list of tricky javascript questions for reference

1) What is the return type of logical operators (||, &&)? If the candidate answers 'Boolean', I ask them to explain, how does "var a = a || {};" work. 

2) How is the length of an array determined? What will be the output of this code?
var a = []; 
a[10] = 5; 
console.log(a.length);
a[-1] = 5; 
console.log(a.length);

3) Do we get keys from the prototypes of an object in the for..in loop? Why don't we get the properties of Object, like 'toString'?

4) Explain the behavior of the keyword 'this'? 

5) What happens if you invoke a constructor, but forget to add keyword 'new' before it? 

6) How many times can we call 'then' on the same promise? What will happen in this code:
   var a = callServer();
   a.then(...);
   a.then(...);
   What happens if we call 'then' on a promise that was already resolved before? 

7) What is a clojure? Most people know the practical aspects, but have a probelm explaining it, so here it is best just to ask for code sample. 

8) ES5 and ES6 basics, prototypes , OOP, web architecture, JS Asynchrony and so on.

9) What happens to the XHR Request which is made and before receiving the response browser is closed.

10) Explain Closures

11) How do you will implement garbage collection for JS in browser?

12) What is dependency injecton?, What for its used?

23) Also you can get some questions about how frameworks works under hood. For example, "What is AngularJS digest?"
