# Types
## Let's talk types!
Kelp is a *strongly* typed language. What does that mean?

It means that every variable must have a type. For example the `number` type:
```kelp
let i = 32
```
>this method is called implicit typing, if we assign value to `i`, kelp compiler can guess which type we meant and automatically add it.

`i` has now the type of `number`. It means, that if we would try to assign `string` to it, it would simply fail.
```kelp
let i = 32
i = "text" // fails
```
## How do I specify a type?
Types are specified as `: type`, but there are some special cases, that we will discuss later.

So how do you create for example `decadic` variable `d` instead of type `number`?
```kelp
let d = 32.0
//or
let d: dec = 32
```