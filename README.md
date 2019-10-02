# Python Regular Expression Cheatsheet
Reference guide for regular expressions in Python.

## Common Tokens
| Regex | Description |
|:------|:------------|
| **[abc]** | Match any character present in the list |
| **[^abc]** | Match any character not present in the list |
| **[a-z]** | Match any character between a and z, including a and z |
| **[^a-z]** | Match any character except those in the range a-z |
| **[a-zA-Z]** | Match any character between a-z or A-Z |
| **.** | Match any character other than newline (or including newline with the /s flag) |
| **\s** | Match any space, tab, newline character (any whitespace character) |
| **\S** | Match anything other than a space, tab or newline (any non-whitespace character) |
| **\d** | Match any decimal digit. Equivalent to [0-9] |
| **\D** | Match anything other than a digit |
| **\w** | Match any letter, digit or underscore. Equivalent to [a-zA-Z0-9_] |
| **\W** | Match anything other than a letter, digit or underscore |
| **(...)** | Capture part of the regex enclosed in parentheses from the results of a successful match |
| **(a\|b)** | Match the a or the b part of the subexpression |
| **a?** | Match an "a" character or nothing ("a" character may or may not be present) |
| **a\***| Match zero or more consecutive "a" characters |
| **a+** | Match one or more consecutive "a" characters |
| **a{3}** | Match exactly 3 consecutive "a" characters |


## General Tokens

## Anchors

## Meta Sequences

## Quantifiers

## Group Constructs

## Character Classes

## Flags/Modifiers

## Substitution
