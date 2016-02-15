
#Variables and Assignment
Much like in math, variables are words or characters that hold values. In algebra, however, variables are only placeholders for numbers. In programming languages like Javascript, a variable can point to almost any type of value including numbers, strings, arrays and objects - which you'll learn more about in later lessons.

You can code-along in the console as you explore this lesson in varaiables.

In Javascript, variables are explicitly declared with the `var` keyword like this:
```
>var students = 30
```


Return the value of the variable by calling its name
```
>students
30
```

Variables store data, and that data can be reassigned with the = sign. Variables will always hold the most recent value that was assigned to it.
```
>var instructors = 4
>instructors
4
>instructors = 6
>instructors
6
```

An "undefined" message is the  the interpreter telling you that variable assignment itself doesn't evaluate to anything.

We can put strings into variables:

```
> var city = "Mountain View"
> var state = "California"
```

Those variables can then be used in expressions - they act as if the value stored inside them is in the expression instead:
```
> students + instructors
36
> city + ", " + state
"Mountain View, California"
```
Variables can also be assigned to to the results of expressions:
```
>var totalCount= students + instructors
>var location = city + ", " + state
>totalCount
36
>location
"Mountain View, California"
```

Note that variable names are case-sensitive.
```
>Location
ERROR!!
```
'location' has been defined, but "Location" has not, which is why the console returns an error.

Variable names should be specific and relevant to so that it is easy for other developers to understand what goes inside.
```
var x = 30; // pretty unintelligible
var number = 30; // what does the number mean?
var studentCount = 30; // this one is pretty clear!
```
Each programming language has a set of best practices - called coding conventions - on how multiple words are handled: camelCase or snake_case. JavaScript developers use camelCase.

Consistency in coding style is very important to maintain code readability in large projects. You can read Google's own style guidelines for Javascript and other languages here: http://google.github.io/styleguide/ .