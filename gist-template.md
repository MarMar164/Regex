# Title Regex

Introductory paragraph These are expressions that are patterns used to match character combinations within strings

## Summary

This is a summary on the components of a regular expression used to match hex values. The Hexadecimal code system can be described correctly to a computer with any color, making sure it has consistences and accuracy when it comes to an electronic display. A hex color value is a 6 digit code that is proceeded by a # sign. It defines a color that is used in a computer program or website.

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
do not match any character at all. They match a position before, after, or between characters. They are used to “anchor” the regex match at a certain position. The "^" matches the position before the first character in the string. Applying ^a to abc matches a. ^b does not match abc at all, because the b cannot be matched right after the start of the string, matched by ^. See below for the inside view of the regex engine. Similarly, $ matches right after the last character in the string. c$ matches c in abc, while a$ does not match at all.

### Quantifiers
Quantifiers set the limits of the string that your regex matches (or an individual section of the string). They frequently include the minimum and maximum number of characters that your regex is looking for.
### OR Operator
The or operator indicates that it could either of the components that we are separating with the |. For our hex value regular expression we have ([a-f0-9]{6}``|``[a-f0-9]{3}). Note the or operator separating these 2 components.
### Character Classes
a character class is a set of characters enclosed within square brackets. It specifies the characters that will successfully match a single character from a given input string.
### Flags
 In any regular expression, we can use the following flags: g : matches the pattern multiple times. i : makes the regex case insensitive. m : enables multi-line mode.
### Grouping and Capturing
Groups group multiple patterns as a whole, and capturing groups provide extra submatch information when using a regular expression pattern to match against a string. Backreferences refer to a previously captured group in the same regular expression.
### Bracket Expressions
A bracket expression (an expression enclosed in square brackets, "[]" ) is an RE that shall match a specific set of single characters, and may match a specific set of multi-character collating elements, based on the non-empty set of list expressions contained in the bracket expression.
### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Mid level full stack developer looking to help https://github.com/MarMar164
