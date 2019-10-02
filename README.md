# Python Regular Expression Cheatsheet
Python 3 cheatsheet for regular expressions using the `re` module.

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
| **a{3,}** | Match at least 3 consecutive "a" characters |
| **a{3,6}** | Match between 3 and 6 (inclusive) consecutive "a" characters |
| **^** | Match the start of a string without consuming any characters. If multiline mode is used, this will also match immediately after a newline character. |
| **$** | Match the end of a string without consuming any characters. If multiline mode is used, this will also match immediately before a newline character. |
| **\b** | Match, without consuming any characters, immediately between a character matched by \w and a character not matched by \w (in either order). It cannot be used to separate non words from words. |
| **\B** | Match, without consuming any characters, at the position between two characters matched by \w. |

## General Tokens

## Anchors

## Meta Sequences

## Quantifiers

## Group Constructs

## Character Classes

## Flags/Modifiers

## Substitution
