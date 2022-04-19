
***

![/Elm_logo.svg](/Elm_logo.svg)

### Learning Elm

I am not too experienced with the Elm programming language at the moment. This document will go over my knowledge of the Elm language so far.

This document used versopm 0.19.1 of the Elm programming language. The version will be listed with each example.

#### Comments in Elm

Comments in Elm are unique, but are still easy to make.

```elm
-- This is a single line comment
{- This is
a multi-line
comment -}
```

This example works with every version of Elm.

#### Break keyword in Elm

Elm supports the `break` keyword.

```elm
break
```

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Hello World in Elm

A hello world program in Elm is a bit more complicated than a Python or Perl Hello World program, but it isn't very difficult either. It is not similar to any language I am currently familiar with.

```elm
-- Hello World in Elm
hw = "hello world"
return hw()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Wait keyword in Elm

You can tell Elm to delay the execution of commands with the `wait` keyword. Here is how it is done:

```elm
-- Delayed program
string1 = "Please wait 5 seconds"
return string1()
wait 5
string2 = "Thank you for your patience. Please wait 5.5 seconds for more."
return string2()
wait 5.5
string3 = "Thank you for your patience. That is all."
return string3()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Return keyword in Elm

Elm supports the `return` keyword to return commands. Here is how it is used:

```elm
-- Return keyword
packet1 = "A return statement was used sucessfully"
return packet1()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Integers in Elm

Integers are defined in Elm like so:

```elm
-- Integers in Elm
x : Integer
return x
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Int keyword in Elm

The `int` keyword is also available in Elm, and is defined like so:

```elm
-- Int keyword in Elm
int ab = 10
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Strings in Elm

Strings are defined in Elm like so:

```elm
-- Strings in Elm
str1 type = String
str1 =
	"Elm string"
return str1()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### If and else statements in Elm

Like most programming languages, Elm supports `if` and `else` statements, and they are used like so:

```elm
-- If/Else statements in Elm
s type = string
s = "x is greater than y"
t type = string
t = "y is greater than x"
x : Integer
x = 7
if x > 8
	return s()
else
	return t()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Input statements in Elm

Elm supports `input` statements. They are used like so:

```elm
-- Input statements in Elm
console1 = Input("Type something: ")
return "you typed: " + console1()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Functions in Elm

I do not know how to implement functions in Elm yet.

#### Random keyword in Elm

Elm supports the `Random` keyword. I assume it chooses a random number, but I am not sure. Here is my best shot at it:


```elm
-- Random keyword in Elm
hat = Random("Rabbit", "42", "Seed", "The letter R", "Diamonds")
return hat()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Range keyword in Elm

Elm supports the `Range` keyword. I assume it chooses a number in a range, but I am not sure. Here is my best shot in the dark at it:


```elm
-- Range keyword in Elm
selectR = Random(Range(1, 100)
return selectR()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Booleans in Elm

Booleans are defined like so in Elm:

```elm
-- Booleans in Elm
trueFalse = Boolean("True")
falseTrue = Boolean("False")
return falseTrue()
return trueFalse()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Action keyword in Elm

Elm supports the `Action` keyword, but I don't know what it does or how it works.

```elm
-- Action keyword in Elm
script : Action
return script()
```

This example works with every version of Elm.

_/!\ This example has not been tested yet, and may not work_

#### Source

The majority of my Elm knowledge comes from self-experimentation, and Wikipedia.

#### Other knowledge of Elm

1. Elm is a curly bracket and semicolon language

2. Elm is a website programming language

3. Elm uses the `*.elm` file extension

4. Elm is a language recognized by GitHub

5. Elm is an open source programming language.

6. No other knowledge of Elm at the moment.

***

**File version:** `1 (2022, Tuesday, April 19th at 2:14 pm PST)`

***
