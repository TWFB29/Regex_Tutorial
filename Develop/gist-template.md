# Regex Tutorial

In this tutorial I will explain what anchors are and how they are used. Then we will preceed with an explanation of what a quantifiers are and how they are used. Next will be the OR operator we will go over what it is and how it is used. Character classes will be next on the list of things that we will go over. This will be followed by an explanation of what flags are and how they are used. Next on the list of explanations is how grouping and capturing is used and what it is. We will also be going over what bracket expressions are and how it is used. Following after that will be what greedy and lazy match is and how it is used. There will be an explanation of how boundaries are used and what they are. I will go over back-references and explain what they are and how to use them. Lastly we will explain look-ahead and look-behind and why it is important.

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

### Anchors
Anchors are html code that is used to create a link to a specific place on a webpage or even a completly different webpage all together. This is very usefull in making a webpage user friendly. This will allow you to skip straight to the section of the page that you are looking for. It will allow you to link to other webpages that may be related to the current one you are on. For example <a href="https://www.nfl.com">NFL</a> now to break this down, the a is the start of the anchor, followed by the href which is the refrence which is equal to the webpage you which to link to. Then we close the opening and put the string that we want to appear on the page NFL and we close our anchor </a>.
### Quantifiers
Quantifiers are used to specify a number of occurences that a character, group or character class to find a match.

Here are some examples:
* match zero or more times.
+ match one or more times.
? match zero times.
{n} match exactly n times.
{n,} match at least n times.
{n, m} match from n to m times.
### OR Operator
An OR operator is a logic based operator used to give multiple options to make a statement true. This allows us to make our code shorter and more efficent.
An example of this would be IF (a < 7 || a > 10). This allows us to return false if a has a value of 8 or 9. 
### Character Classes
A character class is used to define a type of character that is used to find a match. These characters can be a digit or a alphabetic letter depending on which determines the class.

an example would be: 
[a-z] any character between a-z
[0-9] any digit between 0-9
[\w] alphanumeric characters plus the underscore
### Flags
Flags are used to add rules for your search. The i is used to ignore casing and global g flags.
### Grouping and Capturing
Parenthese group the regex between them. Then they are captured by the regex inside of them into a numbered group that can then be reused by a backreference.
### Bracket Expressions
Characters that are inside of square brackets that are used to match a specific sequence of characters. Then is followed by a number inside a squiggly bracket this is used to tell you the number of times the sequence needs to repeat. [abc]{5} = abcabcabcabcabc
### Greedy and Lazy Match
A greedy match is used to match the whole string. A lazy match is used to match just the first abc. By nature most regex is greedy by default in order to make it lazy you simply add a question mark.

{+} Match the preceding character or subexpression 1 or more times (as many as possible). (greedy match)
{+?} Match the preceding character or subexpression 1 or more times (as few as possible). (lazy match) 
### Boundaries
A word boundary is used to match whole alphabetic words. 

an example would be:
\band\b  landing  that is not a match because and is preceeded and followed by a alphabetic character.
\band\b  and,  that would be a match because the comma is not an alphabetic character. 
### Back-references
Back-references are use to find previous matches and search for them again.
### Look-ahead and Look-behind

## Author

My name is Taylor Black and I am currently taking the fullstack web devevlopment course through Case Western Reserve. After this course I plan to pursue a career in web development.
