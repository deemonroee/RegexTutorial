# Understanding Regex

Learning how to use regex can shorten your code, it has distinguished kinds of characters for letters and digits 

## Summary
Learning how to use regex can shorten your code, it has distinguished kinds of characters for letters and digits 
From what I have learned Regex is a syntax that allows the user to match strings with very specific patterns.
It does become a shortcut as they wouldn't have to have to type out full lines of code, the regex can be used as a shortcut 
While also searching this up, it does seem complicated but would be useful during those times when there is a lot of code to be written 
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Groups](#groups)
- [Bracket Expressions](#bracket-expressions)


## Regex Components
an example being :
function youSayHelloISayGoodbye(str) {
  str = str.replace(/[Hh]ello|[Hh]i|[Hh]ey/, "Goodbye");
  return str;
}

the regex replaces the way hello and goodbye will be displayed just be using a shortcut and replacing strings.
It becomes an easier alternative 
### Anchors
for anchors they do not match charcaters but in fact they match strings in certain places. 
It is expressice and allows for the user to specify where they want to match thier digits, whether its at the end of the string or beginning

### Quantifiers
The Quantifiers check how mamy times the user will search for a character
example : Hello|Goodbye
will end up matching both strings of "hello" and "goodbye"
example : Hello{1,3}
this quantifier will find all hello's that has the letter "o" between 1-3 times 

### Groups
 a group can allow you to search for multiple things all at once instead of one at a time 

### Bracket Expressions
 these expressions have a different meaning for regex, they help define a character set. The set of characters you would want to match to regex expressions. 
### Character Classes
The bracket expression can go into character classes because the character class is a set of characters that are enclosed within square brackets. 
### Flags
A regex flag is a modifier to an existing regex. These flags are always appended after the last forward slash in a regex definition. 
example : /Hello|Hi|Hey/i


## Author
It took me a while to begin to under stand how regex works  but being able to look at examples makes it a bit easier. 

https://github.com/deemonroee 