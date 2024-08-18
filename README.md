# Understanding Email Validation Regex

In this tutorial, we'll break down a regular expression (regex) used for validating email addresses. This is a common task in web development, ensuring that user input matches the expected format of an email address.

## Summary

We'll be examining the following regex used for email validation:

`/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z]{2,6})$/`

This regex checks if a string follows the basic pattern of an email address: something@something.something

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

^ : Marks the start of the string
$ : Marks the end of the string

### Quantifiers

+ : Matches one or more of the preceding element
{2,6} : Matches between 2 and 6 of the preceding element

### OR Operator

This regex doesn't use the OR operator.

### Character Classes

\d : Matches any digit (0-9)

### Flags

This regex doesn't use any flags.

### Grouping and Capturing

([a-z0-9_.-]+) : First capturing group for the local part of the email
([\da-z.-]+) : Second capturing group for the domain name
([a-z]{2,6}) : Third capturing group for the top-level domain

### Bracket Expressions

[a-z0-9_.-] : Matches any lowercase letter, digit, underscore, dot, or hyphen
[\da-z.-] : Matches any digit, lowercase letter, dot, or hyphen
[a-z] : Matches any lowercase letter

### Greedy and Lazy Match

This regex uses greedy matching by default.

### Boundaries

This regex doesn't use specific boundary matchers.

### Back-references

This regex doesn't use back-references.

### Look-ahead and Look-behind

This regex doesn't use look-ahead or look-behind assertions.

## Author

This tutorial was created by Ashley D. Von. You can find more of my work on my [GitHub profile](https://github.com/AshleydVon).

## Gist Link

For the full gist of this regex tutorial, please visit: https://gist.github.com/AshleydVon/c5a529302e78a7aca20a25413f42a949

