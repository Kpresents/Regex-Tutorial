#  Regex Tutorial

`Breaking down the regex for Matching an Email: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

## Summary

 This is a walk through tutorial explaining how a specific regular expression, or regex, functions for each part of the expression and describing what this expression does.
 


## Table of Contents


- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)




## Regex Components
`Matching an Email: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`


### Quantifiers
`+ matches the previous token between one and unlimited times, and as many times as possible. Any charactes before this + quatifier runs through to confirm it meets the characters required. `
`{2,6} matches the previous token between 2 and 6 times, and confirms the characters needed as being met. `
`@ - text must match this character, at this point it is going to confirm that the @sign is part of the input needed. `
### Character Classes
`[a-z0-9_\.-]  - Matches any  characters in lower case a-z and numbers 0-9, .- matches single character in the list and is case sensitive` 

`[\da-z\.-] \d matches characters in lower case a-z  and .- matches single character in the list and is case sensitive` 
`[a-z\.] characters in lower case a-z  and .- matches single character in the list and is case sensitive`






## Author
[Kpresents- Gist](https://gist.github.com/Kpresents/a7ce89d40af0edfbd97d898de68757dd) 
