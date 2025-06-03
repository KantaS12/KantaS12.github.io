---
layout: essay
type: essay
title: "TypeScript: My First Types"
# All dates must be YYYY-MM-DD format!
date: 2025-06-01
published: true
labels:
  - TypeScript
  - Reflection
  - ICS314
---

<img class="img-fluid" src="../img/typscript.jpeg">

## TypeScript Easy?

After doing around 150 coding practices on TypeScript, I am happy to say that I am pretty good at it. Not at the language itself but the actual structure of my code too. I took a class that required Java like 2 years ago and never touched it again. Doing TypeScript, it reminded me of what Java's syntax and structure was like. However, something that I noticed that was different was the difference between "let" and "var." I also noticed that we used a lot of "const" variables. It is much different than Python and took a little bit to get used to the syntax. Overall, it wasn't so bad.

```

let hello = "Hello";

compared to

hello = "Hello"

```

## Is TypeScript a Good Programming Language?

TypeScript in my opinion is a good programming language, especially from a software engineering perspective. As a beginner, it was much easier to get into this language than languages like C. There also have types that you can set your objects to which is convenient and also to make sure there are no errors being raised up.  

Two types that were helpful was the "any" and also the "unknown" type. 

```

let flexVar: any = 10;
flexVar = "anything"; // No error

let unknownVar: unknown = 10;
unknownVar = "anything"; //No error

```

A practice WOD that I found useful was finding if a string is unique or not. It was something that we can use in a real life setting. It's like Leetcode style coding which is really helpful in interviews for tech companies. It also helped me understand structure of the code and also new things like Maps.  

```

function isUnique(str: string): boolean{
    const seenstr: Map<string, boolean> = new Map();
    for (let i = 0; i < str.length; i++){
        const letter = str.charAt(i);
        if (seenstr.get(letter)) {
            return false;
        } 
        else {
            seenstr.set(letter, true);
        }
    }
    return true;
}

console.log(isUnique('abcde')); //true
console.log(isUnique('abcdea')); //false

```
 
## Conclusion

Overall, TypeScript is a language that requires not that much time to learn and also it is something that I would want to be good at. It was enjoyable to learn and was stress free. I think doing the WODs will greatly make me a good software engineer since it requires me to use my critical thinking skills. 
