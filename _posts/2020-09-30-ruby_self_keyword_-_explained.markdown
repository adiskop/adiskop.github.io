---
layout: post
title:      "Ruby Self Keyword - Explained "
date:       2020-09-30 11:26:41 -0400
permalink:  ruby_self_keyword_-_explained
---


The "self" keyword, which can be confusing at times is simply created to give access to the current object. 
Which is going to depend on where we use it. 

#### Three important instances we use and confuse Self:

Lets say we are inside an instance method (of a class), **Self** is going to refer to the *instance of that class*. 

When using **Self** inside of a class - self is going to refer to the *class itself*. 

When we call the initialize method, the interpreter is already executing it, and instantiate an instance, and so **Self** is going to refer to this instance, which is the object itself in this case. 


Using self is also very useful when we would like to change a class or method name - self would not be affected of this change, when compared to if we simply use the specific class/method name. 

It also makes the code shorter and easier to understand. 
And so it is safe to say that the Self keyword is often used in programming and it is important to understand and distinguish between its different uses. 
