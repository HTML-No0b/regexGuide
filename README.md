# RegexGuide
    RegEx is also known as Regular Expression which is a method to define parameters.

## Summary

This is the RegEx or regular expression that I will be explaining in the **tutorial** below. 
In the sections below, there will be details on what the regular expression is and how it is deconstructed. 
The regular expression I will give a tutorial on, will be matching an Email:    `` /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ ``
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
When using RegEx you begin with  ( **/** ) because Regular Expressions are literal. Just like the beginnging of the RegEx email.
*  `` /^([a-z0-9_\.-]+)`` What this string is showing is that it is taking in every **Lowercase** letter ``a-z `` &  **Numbers** ``0-9``. Including the special 
characters  ``_ \ . - `` . 
### Anchors
  > The special characters ``^`` and ``$`` are both **Anchors**. 
      
  These special characters can loosely be considerd "opening and closing " tags. What makes the two characters special are the following:

  When starting your string the **^** indicates that everything that follows is the start, be it string or different matches. 

  While the **$** character indicates that everything before ends with the characters that were supplied. 
    
### Quantifiers
What are Quantifiers? Quantifiers are basically limits that are set on the string that it is embedded in. What does that mean, check out the code below.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Grouping Constructs

### Bracket Expressions

### Character Classes


### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
