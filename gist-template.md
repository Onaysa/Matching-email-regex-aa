# Matching an email - Regex Tutorial

This tutorial is going to explain the use of regex to match an email address.

## Summary

Regular Expressions or Regex (in short) in Java is an API for defining String patterns that can be used for searching, manipulating, and editing a string in Java. Email validation and passwords are a few areas of strings where Regex is widely used to define the constraints. 

In this tutorial we will be breaking down a Regex that helps matching an email address. Here is the following code :
 `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

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

The anchors used in this regex expression are the following:
"^" The anchor asserts that we are at the beginning of the string.
"$" The anchor asserts that we are at the end of the string.
We use two anchors. One at the beginning, and one at the end; to 
match the email we are looking for.


### Quantifiers

Quantifiers match a number of instances of a character, group, or character class in a string.
Quantifiers in our regex include:
"+" = takes its preceding pattern and quantifies it for one or more number of times.
"2,6" = forces the input of characters between two & six characters long.


### Grouping Constructs

Grouping constructs seperate specific expressions into different sections. 
Capturing group in this expression is :
"()" Captures everything enclosed within the parenthesis.

### Bracket Expressions

A bracket expression enclosed in square brackets is a regular expression that matches a single character. It represents a single character. The character can be anything specified within the brackets.
We have three bracket expressions in our example:

`[a-z0-9_\.-]`
`[\da-z\.-]`
`[a-z\.]`

### Character Classes

Character classes are one of the most commonly used features of regular expressions.The character classes in this expression are:
"." which represents any character except characters on a new line.
"\d" represents digits.
`[a-z]` represents character between a and z. In the expression /^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/ character classes a-z and "\d" are used. This means that a letter a to z and a digit from 0 to 9 can be in the string.


### The OR Operator

The logical OR ( || ) operator is typically used with boolean (logical)values. It eturns the boolean value true if either or both operands is true and returns false otherwise. We don't have any OR operator in our example.

### Flags

A flag is an optional parameter to a regex that modifies its behavior of searching. In JavaScript regex, we have a total of 6 flags, each serving a different purpose. In our code  `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` We don't have flags.


### Character Escapes


 The main character escape in regex and the only one in this example is :
 The  "\"  single backlash. The backslash in a regular expression precedes a literal character. You also escape certain letters that represent common character classes, such as \w for a word character or \s for a space.

## Author

You can view my previous work and projects at (https://github.com/Onaysa)
