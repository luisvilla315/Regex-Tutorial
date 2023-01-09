# Regex-Tutorial

## Summary
Regular expressions are a way to identify patterns in a string. They are used in programming languages such as Javascript, Perl, Python, PHP, and Java. In Javascript, regular expressions can be created using the RegExp constructor or by enclosing the pattern in forward slashes ( / ). A character class is a group of characters that can match any one character within the group. Ranges of characters can be specified using a hyphen, but if the hyphen appears at the beginning or end of the group, it is treated as a literal character rather than a range indicator. Regular expressions are useful for matching and extracting values from patterns, such as URLs, input/output data, email addresses, passwords, and usernames. For example, the regular expression ( /^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/ ) can be used to match an email address.

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
Anchors are special characters that match a position rather than a character. For example, the caret symbol (^) matches the start of a line, and the dollar symbol ($) matches the end of a line
### Quantifiers
Quantifiers specify how many times a preceding character, group, or character class should be matched. For example, the plus symbol (+) specifies that the preceding character or group should be matched one or more times, while the asterisk (*) specifies that the preceding character or group should be matched zero or more times.
### OR Operator
OR Operator: The OR operator in regular expressions is denoted by the vertical bar |. It allows you to specify multiple options for a pattern, and will match if any of the options are present.
### Character Classes
Character classes are a set of characters that are grouped together and treated as a single unit. There are several predefined character classes, such as \d for digits and \s for whitespace characters.
### Flags
Flags are used to perform case-insensitive matching, multi-line matching, and other modifications.
### Grouping and Capturing
Grouping and capturing is used to group characters together and capture the matched text for later use. Captured groups can be referred to by a number, with the first left parenthesis being group 1, the second being group 2, and so on.
### Bracket Expressions
Bracket expressions are used to match any one of a set of characters. For example, the pattern [0123456789] matches any digit.
### Greedy and Lazy Match
Greedy and Lazy Match: In a regular expression, the "greediness" of a quantifier (a character or group that specifies how many times a pattern should match) refers to how many characters it will try to match. A greedy quantifier will try to match as many characters as possible, while a lazy quantifier will try to match as few characters as possible.
### Boundaries
Boundaries: In a regular expression, boundaries are characters that anchor the pattern to a specific position in the string. For example, the boundary ^ matches the beginning of a string, while the boundary $ matches the end of a string.
### Back-references
Back-references refer to a previously captured group and can be used to match repeating patterns.
### Look-ahead and Look-behind
Look-ahead and look-behind are zero-length assertions that match a position rather than a character. Look-ahead asserts that the characters following the current position match a given pattern, while look-behind asserts that the characters preceding the current position match a given pattern.
## Author
Hi, my name is Luis Villa and I am currently enrolled in the UW coding Bootcamp. I am a student who is passionate about learning and improving my skills in software development. You can check out some of my work on my Github profile at https://github.com/luisvilla315.
