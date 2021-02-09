# Basics of HTML, CSS & JS

## Text
- When creating a web page, text (markup) is added to content of the page
- 2 types of markup:
    1. structural markup - elements used to describe both headings and paragraphs
    1. semantic markup - provides extra information like emphasis in a sentence like a quotation
- Headings are H1 - H6
- Bold & italic text ("<b>" & "<i>")
- Superscript & Subscript ("<sup>" & "<sub>") - a sup element would be used for a # like 4th (makes "th" smaller) & sub element is used to contain characters that should be subscript (i.e. - "CO2")
- Break tags ("<br>")
- Horizontal rules ("<hr>") creates a line break and ads a line
- Strong ("<strong>") - bolds text
- Emphasis ("<em>") - creates italic
- Blockquote ("<blockquote>") - used for longer quotes that take up a paragraph
- Q quote ("<q>") - used for shorter quotes
- Abbreviations ("<abbr>") - used for acronyms
- Cite ("<cite>") -
- Definiing Instance ("<dfn>")
- Address ("<address>")
- Insert & Delete ("<ins>" & ("<del>")
- Strikethrough ("<s>")

## Introducing CSS
- Block & Inline Elements
- CSS associates style rules w/ HTML elements
- Selectors & Declarations (i.e. p { font-family: Arial;})
    - "P" is a selector and "font-family: Arial" is a declaration
- Properties & Values
- External links (link, href, type, rel)
- Internal CSS ("<style>")
- Selectors:
1. Universal
1. Type
1. Class
1. ID
1. Child
1. Descendent
1. Adjacent Sibling
1. General Sibling

### Hohw CSS Rules Cascade

#### Last Rule
- if 2 selectors are idential the latter of the 2 takes precedence

#### Specificity
- if one selector is more specific than the others, the more specific rule will take precedence

## Basic Javascript Instructions

### Statements
- each individual instruction or step in a script

### Comments
- descriptions in code that explain what the script is for

### Variables
- where info is stored in a script

#### How to declare them
- must announce them and then give them a name

#### How to assign them to a value
- once variable is created, you assign w/ an assignment operator like "="

#### Data Types
- can be numbers, strings, or booleans

#### Using Quotes Inside a String

#### Using a Variable To Store a Boolean

#### Shorthand for Variables
-multiple ways to write variables

#### Rules for Naming a Variable
1. name must begin with a letter, dollar sign, or an underscore
1. do not use a dash or period in a variable name
1. cannot use keywords or reserved words (i.e. - "var")
1. all variables are case sensitive
1. use a name that describes what info it stores
1. always use camel case if more than one word

### Arrays
- stores a list of values

### Expressions
- evaluates into a single value
- 2 types:
    1. expressions that just assign a value to a variable
    1. expressions that use two or more values to return a single value

### Operators
- what expresisons rely on that allow programmers to create a single value from one or more values

#### Arithmetic Operators
- examples would be:
    1. +
    1. -
    1. /
    1. *
    1. ++
    1. --
    1. %

#### String Operator
- only one type and it's a "+" symbol
- used to join strings

## Decisions & Loops
- Programmers rely on 3 concepts to determine which path to take:
1. Evaluations - programmers analyze values in scripts to determine whether or not expected results are mer
1. Decisions - deciding which path to go down after evaluations
1. Loops - many instances where the same steps will need to be performed repeatedly

### Decision Making
- flowcharts help with this

### Evaluating Conditions & Conditional Statements
- 2 components to a decision:
    1. an expression is evaluated, which returns a value
    1. a conditional statement says what to do in a given situation

### Comparison Operators
- examples would be:
    1. == (is equal to
    1. != (is not equal to)
    1. === (strict ewual to)
    1. !== (strict not equal to)

### Logical Operators
- allow you to compare the results of more than one comparison operator
- Examples: && (logical and) || (logical or), and ! (logical not)

#### Logical & Logical Not
### If Statements
### If...Else Statements
### Switch Statements