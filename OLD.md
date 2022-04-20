### Learning Elm (programming language)

As of 2021 December, I am in the process of learning the Elm programming language. I currently have no way to test what I am writing, so none of the following examples work.

#### Wikipedia reference

This is the source code from Wikipedia I am using as a reference to learn the language. I have expanded from this:

```elm
-- This is a single line comment.

{-
This is a multi-line comment.
It is {- nestable. -}
-}

-- Here we define a value named `greeting`. The type is inferred as a `String`.
greeting =
    "Hello World!"

 -- It is best to add type annotations to top-level declarations.
hello : String
hello =
    "Hi there."

-- Functions are declared the same way, with arguments following the function name.
add x y =
    x + y

-- Again, it is best to add type annotations.
hypotenuse : Float -> Float -> Float
hypotenuse a b =
    sqrt (a^2 + b^2)

-- We can create lambda functions with the `\[arg] -> [expression]` syntax.
hello : String -> String
hello = \s -> "Hi, " ++ s

-- Function declarations may have the anonymous parameter names denoted by `_`, which are matched but not used in the body. 
const : a -> b -> a
const k _ = k


-- Functions are also curried; here we've curried the multiplication 
-- infix operator with a `2`
multiplyBy2 : number -> number
multiplyBy2 =
    (*) 2

-- If-expressions are used to branch on `Bool` values
absoluteValue : number -> number
absoluteValue number =
    if number < 0 then negate number else number

 -- Records are used to hold values with named fields
book : { title : String, author : String, pages : Int }
book =
    { title = "Steppenwolf"
    , author = "Hesse"
    , pages = 237 
    }

-- Record access is done with `.`
title : String
title =
    book.title

-- Record access `.` can also be used as a function
author : String
author =
    .author book

-- We can create tagged unions with the `type` keyword.
-- The following value represents a binary tree.
type Tree a
    = Empty
    | Node a (Tree a) (Tree a)

-- It is possible to inspect these types with case-expressions.
depth : Tree a -> Int
depth tree =
    case tree of
        Empty ->  0
        Node _ left right ->
            1 + max (depth left) (depth right)
```

#### Hello World in Elm

This is how you make a Hello World program in the Elm programming language:

```elm
helloWorld : String
helloWorld = "Hello World"
```

#### Comments in Elm

Comments in Elm are unique and uncommon compared to most programming languages.

```elm
-- This is a single line comment
{- This is a multi-
line comment -}
{- Multi-line comments can
{- Nest -} comments within
themselves -{
```

#### Booleans in Elm

I think this is how to do Booleans in Elm, but I am not entirely sure:

```elm
yesNo : Boolean
yesNo == "true"
```

_/!\ This example has not been tested yet, and may not work_

#### Strings in Elm

I think this is how to define strings in Elm:

```elm
myMsg : String
myMsg =
"Stringy string"
```

_/!\ This example has not been tested yet, and may not work_

#### Return keyword in Elm

Elm supports the `return` keyword.

```elm
functionB : String
functionB = "A functional functioning function in the form of a string"
return functionB()
```

_/!\ This example has not been tested yet, and may not work_


#### Break keyword in Elm

```elm
break
```

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Other knowledge of Elm

1. Elm is named after the Elm tree species.

2. Elm is NOT a curly bracket and semicolon language

3. Elms main file format is `.elm` and I am unsure if it uses other file formats.

4. Elm is an open source language, and it can be found on [GitHub](https://github.com/elm/compiler/)

5. Elm can be used as a web programming language

6. No other knowledge of the Elm programming language at the moment.

***
