# Book_List

This is a VanillaJs based project that i used to differentiate between E55 &amp; Es6

In this project ill also be using event delegation(, if something is gonna show up more than once with the same class or something that is not there when the page loads, but is dynamically added then we use event delegation)

Q- Is there any other reason besides not cluttering up the function constructor to use the prototype to add methods ? Seems from the examples , the outcome is the same , didn't know if there were any other distinct advantages.

Ans- The whole point of adding methods to the prototype chain is to achieve prototypal inheritance.
We add the methods once to the constructors prototype and all instances of that constructor inherit the methods via the prototype chain.
So you could have hundreds of thousands of objects each and every one with their own functions/methods (expensive).
Or you can have hundreds of thousands of instances (objects) each with access to one function via the prototype chain (efficient).

-> On doing the comparison between the Es5 & Es6 when we do console.log(ui) we see that both have the same proto pseudoselector
