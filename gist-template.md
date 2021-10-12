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

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
