# Regex Tutorial

In this gist, I will be explaining Regex and the concept of matching an email through a regex.

## Summary

Regular expressions use characters, numbers, and letters to build parameters for input data. In this gist I will explain matching an email with the following code snippet: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

The code snippet above is the template the email would follow.
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
Anchors are expressions that dont match any characters, but are used to denote the beginning or end of a string. The ^ that immdiately follows the / at the start of the code snippet above, denotes the beginning of the string of characters the email format will follow. The $ preceeding the / at the end of the code snippet, is reprersenting the end of that string. 
### Grouping Constructs
In our code snippet, we have (), this is known as a capturing group. This makes it so whatever is inside of this group has to be considered when matching our email.
### Bracket Expressions
inside of the (), is [a-z0-9_\.-]+ , this series of code is the character parameters for everything before our @ in the email. Here it specifically states all letters, numbers, underscores, hyphens, and dots. The letters are specified with a-z, numbers with 0-9, the underscore is given, the dot is expressed with \., and the hyphen is given as well.
### Character Classes
Once were inside our second bracket expression, [\da-z\.], the \d matches any digit 0 through 9.
### Quantifiers
The {} in our code snippet, specify how many characters long and short our second bracket expression can be. In this example the amount of characters can be no less than 2 and can be no greater than 6. 
### The OR Operator
The + is a Match-one-or-more Operator, this means it  tries to match all the given characters inside of the (). 
## Author
Thank you for reading my rexgex tutorial, My name is Christian and I am a Full Stack Web Development Student. My Github is [Colon182](https://github.com/Colon182).