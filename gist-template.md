# HTML TAG MATCHING



## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Matching an html tag:  /^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

### Anchors
^   Starts the string
<   Matches the character with the index             

### Quantifiers
a*  greedy quantifier
a*? lazy quantifier

### OR Operator
a|b a or b operator

### Character Classes
[a-z]   Matches any characters between a and z, including a and z.

### Flags
A   anchor

### Grouping and Capturing
([a-z]+) first capturing group

### Bracket Expressions
This section is not used by this regex.

### Greedy and Lazy Match
a*  greedy quantifier
a*? lazy quantifier
U   Ungreedy

### Boundaries
\b  word boundary
\B  non-word boundary

### Back-references
This section is not used by this regex.

### Look-ahead and Look-behind
(?(?=...)yes|no)    look ahead
(?(?<=...)yes|no)   look behind

## Author
Daniel Warren II
Dev in training
GitHub: Callmeicanhelp@github.com