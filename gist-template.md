# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

Anchors are used to match postions in a string. Anchors are as follows, "^" this markes the beggining of an anchor. "$" marks the end of an anchor. "\b" is the word boundry, and the "not word boundry" is "\B".

### Quantifiers

 These specify how many times to look for a character/group of charaters.
 examples include: "+"(looks for one or more of the preceeding token), "*"(looks for zero of more of the preceeding token), "?"(looks for as few instances as possible), and {n} (takes and matches to tokens as specified)

### Grouping Constructs

These constructs describe precisely the subexpression of regex and capture the subtrings of the input. This is done using parentheses ()

### Bracket Expressions

A bracket expression will matcha set of individual characters. These are contained in square brackets []

### Character Classes

This will match a character from a set, you can also create your own sets. This can be done as character set, ex: [ABC]. ranges like a through z, ex: [A-Z], words this selects any word character, ex: \w. As well as many more.

### The OR Operator

OR Operators will return several things depending on what is enterd into the operator. "|" will return one or the other of two given inputs, "(...)" will return both on and two of the given inputs. "[...]" will return anything that matches the inputs provided. Finnally "[a-z]" will return all character that are lowercase and between "a" and "z"

### Flags

Flags are used to allow extra functionality like a search that disregards whether something is upper case or lower case, or to see a pattern like Unicode sequences.
examples include but are not limited to: "g" this performs a global search, "i" ignores letter case, and a few more.

### Character Escapes

These can insert unicode characters, reserved characters, and special characters. These start with "\".

## Author

Hello, my name is Chris Dorner. I have written a small document here to help remember the functions of different parts of regex. If you have any questions regarding this document or any of my other works please visit my GitHub at : https://github.com/ChrisDorner1
