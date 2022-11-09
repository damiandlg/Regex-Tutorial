# Regex Email Tutorial

Regular expressions (regex or regexp) are extremely useful in extracting information from any text by searching for one or more matches of a specific search pattern.ields of application range from validation to parsing/replacing strings, passing through translating data to other formats and web scraping.

## Summary

The purpose of this is to explain Regex through an Email example. I will be using the following code snipet to explain Regex: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Escaped Expressions](#escaped-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
Lets start simple +@ means "plus @ sign". turotial(+@)aol.com
### Anchors
>  ^ and $ - represent the start (^) and the end ($) of the expression.
### Quantifiers

### OR Operator
> {2,6} matches a . followed by two or three word characters, e.g., ".com", ".edu", ".us", ".uk", ".co".
### Character Classes
> The sub-expression [a-z0-9_\.-]+) is used to match the username in the email, before the @ sign. It begins with at least one word character [a-zA-Z0-9_], followed by more word characters or . or -. 
### Flags

### Grouping and Capturing

### Escaped Expressions

The backslash (\)in a regular expression precedes a literal character. You also escape certain letters that represent common character classes, such as \w for a word character or \s for a space.
### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

My name is Damian De La Garza and I hope this tutorial was as benifical as it was for me. Dont hesitate to reach out +@ :) github.com/damindlg, if youd like to comment or add functionaloity please feel free at https://gist.github.com/damiandlg/0cfa70a6947e6cd3e1ab3b12ed301179
