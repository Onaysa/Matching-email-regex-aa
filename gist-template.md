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
Capturing group #1 in this expression is :
"()" Captures everything enclosed within the parenthesis.

### Bracket Expressions


### Character Classes


### The OR Operator


### Flags



### Character Escapes


## Author

You can view my previous work and projects at (https://github.com/Onaysa)
