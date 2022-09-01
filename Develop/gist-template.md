# Liv's Regex Tutorial - Matching an Email

This regex (Regular Expression) tutorial contains detailed information to help a reader understand what a regex is and how it functions. This tutorial breaks down the expressions into simple parts.

## Summary

This tutorial breaks down the components of a regex used to validate whether or not an input is an email address. The regex makes sure that a given string matches the template for an email address.

Here is the expression:
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
This regex contains two anchors -- ^ and $

^ refers to code that must appear at the beginning of a string

$ refers to code that must appear at the end of a string

Since this regex contains both of these anchors, strings must match every specification exactly or it won't be a validated as an email address.

### Quantifiers

Quantifiers specify how many times a character is expected to appear.

This regex contains two quanitifers -- + and {2,6}

+ connects a users email name + email service + .com. 

[a-z0-9_.-]+ specifies that a character matching the characters inside the brackets is expected to appear at least once with no limit

{2,6} specifies a match range of 2-6 characters for the character set of [a-z\.]

### OR Operator

This regex contains two OR operators -- | and []





### Character Classes

This regex contains one character class -- \d 

This used to match any digit character; it matches a single character that is a digit from 0-9 and will only match a single digit such as 1 but not 11. A backslash is necessary to differentiate the digit class from the letter d.

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
