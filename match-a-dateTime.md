# Match a DateTime

Regex or Regular expressions are patterns used to match character combinations in strings. In this tutorial we'll see how to use a regex to match dates alongside specific times. An example of such a dateTime would be `3/25/2022 CE 12:49 PM`, with `CE` meaning "Common Era", which can also be replaced for ancient dates by `BCE` meaning "Before the Common Era".

## Summary

This tutorial is going to explain the use of regex to match dateTimes using the following expression
```js
let dateTimeRegex = ^\b([1-9]|1[0-2])\b[\/-]\b([1-9]|[12][0-9]|3[01])\b[\/-]\d{1,4} B?CE \b([1-9]|1[0-2])\b:[0-5][0-9] P?A?M$
```

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

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
