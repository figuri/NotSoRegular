#  *NotSoRegularExpressions*

Below is a tutorial on how to use regular expressions. This tutorial will cover a regular expression and break it down step by step.

## Summary

Regular expressions are a sequence of characters that define a search pattern. They are used to find and replace text or validate text. Regular expressions are used in many programming languages, command line tools, and text editors. Regular expressions are also known as regex or regexp.
For this instance we will examine the following regular expression :
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

This expression  is used to validate and extract different parts of a URL. It can be used to validate a URL, extract the protocol, domain name, top-level domain, and path. It can also be used to validate a URL without a protocol, and validate a URL with or without a path.


```javascript```


# Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## **Regex Components:**

The expression is as follows :  /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

## **Anchors:**

Anchors are used to match a position before or after characters. The following are the anchors used in the expression.

"^" - Matches the beginning of input. (caret)


"$" - Matches the end of input. (dollar sign)


## **Quantifiers:**

Quantifiers are used to specify the number of times a character or group of characters can occur in a string. The following are the quantifiers used in the expression.

"?" - In this case makes the previous element optional. (question mark)


"*" - Matches the previous element zero or more times. (asterisk)


"+" - Matches the previous element one or more times. (plus sign)


"{n}" - Matches the previous element exactly n times. In this case it is being used with 2, and 6 occurences (curly braces)


## **Grouping Constructs:**

(https?:\/\/)?: Group that captures the optional protocol part. 


([\da-z\.-]+): Group that captures the domain name. 


([a-z\.]{2,6}): Group that captures the top-level domain. 


([\/\w \.-]*)*: Group that captures the optional path part.

## **Bracket Expressions:**

[\da-z\.-]: Matches lowercase letters, digits, dots, and hyphens.


[\/\w \.-]*: Matches slashes, word characters, spaces, dots, and hyphens.

## **Character Classes:**

\d: Matches a digit. Equivalent to [0-9].

\w: Matches a word character. like letters, digits, and underscores.

\s: Matches a whitespace character. like tabs and line breaks.

.: Matches a literal dot (used outside a character class). like a period.

## **The OR Operator:**

https?: Matches either "http" or "https". in this case the "s" is optional.

## **Flags:**
There are no flags in this expression, but an example flag is /i for case-insensitive matching. which would make the expression match both uppercase and lowercase letters.

## **Character Escapes:**

\/\/: Matches two literal slashes. like a double forward slash.

\.: Matches a literal dot. like a period.

\/: Matches a literal slash. like a forward slash.

[\w \.-]: Matches word characters, spaces, dots, and hyphens. like letters, digits, underscores, spaces, dots, and hyphens.
 
# *Author*

My name is Sam, check me out on [GitHub](https://github.com/figuri) and [LinkedIn](https://www.linkedin.com/in/samuel-thomas-b82614183/)

I am new to development and love to learn something new. I am currently learning full stack development at the University of California Berkeley. I am excited to learn more about coding and to start my career in development.
