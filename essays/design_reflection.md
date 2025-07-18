---
layout: essay
type: essay
title: "Design Patterns: City Building!"
# All dates must be YYYY-MM-DD format!
date: 2025-07-18
published: true
labels:
  - Design Patterns
  - Reflection
  - ICS314
---

<img class="img-fluid" src="../img/design_pattern.jpeg">

## Design Patterns

Think of software development as a culinary art. As developers, we're chefs, whipping up digital dishes from raw ingredients like code, functions, and classes. 

And just like a great chef doesn't just toss things in a pot, but follows techniques and recipes, skilled developers use principles that really elevate their craft.

That's exactly what design patterns are all about: they're culinary principes, the go-to recipies, and the core techniques of software engineering. They capture the best ideas from countless projects where common challenges kept popping up, and brilliant solutions naturally formed.

Wonder how to make a dish that needs to be slightly different each time without redoing the whole thing? Or make sure one ingredient is used consistenly by everyone?

Design patterns answer these questions. They're not strict rules; they're flexible, proven blueprints. Plus, they give us a shared language, so developers can chat about complex ideas using simple, widely understood terms.

## My Culinary Design Toolkit

First up, think about a unique, super important ingredient in the kitchen - maybe a rare spice blend, or that one specialized oven that everyone shares. You wouldn't want multiple chefs preparing their own version. That's where the Singleton pattern comes in. 
 
It makes sures there's only one instance of a specific "ingredient" or "tool" available throughout the whole "kitchen." This is critical for managing shared resources like a central configuration file or a single logger, preventing conflicts and keeping things consistent across your entire system.


Or, consider a resturant that needs  to dish out different types of pasta - spaghetti, fettuccine, ravioli - but the main order system wouldn't have to know every little detail about how to make each one.

I've seen the Factory Method pattern work perfectly here. It's like having a dedicated pasta station: you can just ask for "pasta," and the station knows exactly how to make the right kind, abstracting away all those intricate preperation steps. 


There is also a scenario where a coffee needs few extras - milk, sugar, or a flavored syrup - without creating a seperate recipe for every single combination. 

The Decorator pattern handles this beautifully. It lets you add "ingredients" dynamically to a core "dish" without changing its orignial structure. Instead of endless variations, you can simply "wrap" that basic coffee object with different decorators, each addinga  new layer of funtionality. 


Lastly, there is a scenario where you need to decide how to cook something - should that chickn be baked, grilled, or fried? The Strategy pattern helps by putting each "cooking method" into its own "recipe." The main "chef" can then pick and apply the right "cooking method" to the "ingredient" on the fly.

This makes the system super flexible; you can easily swap behaviors, like choosing different sorting algorithms for data based on its size.

## Conclusion

Bottom line: design patterns are essential for software excellence. They turn raw code into really cool and awesome digital dishes. By start making robust, easy-to-maintain, and adaptable software solutions just like a master chef who consistently creates well-structured and truly memorable meals.
