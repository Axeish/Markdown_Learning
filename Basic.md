# MarkDown Tutorial
## Section 1 : Basics 
Markdown is a lightweight markup language used for creating formatted text using a plain-text editor

### Here are basics of markdown 

#### Content { #puma}

[ 1. Headers ]( #1-headers )  
[ 2. Text Formatting ]( #2-text-formatting )  
[ 3. Blockquotes ]( #3-blockquotes )  
[ 4. Paragraph and line break ]( #4-paragraph-and-line-break )  
[ 5. List ]( #5-list )  
[ 6. Code ]( #6-code )  
[ 7. Horizontal Rule ]( #7-horizontal-rule )  
[ 8. Links ]( #8-links )  *(more details in separete page)*
---
### 1. Headers
use `#` for heading. Add more `#` for smaller  headings

Example:

         # Header Level 1
         ## Header Level 2 .. 
         ###### Header Level 6(last)
Result :
# Header Level 1
## Header Level 2 .. 
###### Header Level 6(last)

>###### Best Practice
>
> - Always use space between # and first word
> - Put blank lines before and after the  # header line
---

### 2. Text Formatting

- **Bold**:  `**text**` or `__text__`
- *Italics*: `*text*` or `_text_`
- ~~Strikethrough~~: `~~text~~`

Example:

        **using bold**, *italics*
        ***both bold and italics***
Result:  
**using bold**, *italics*  
***both bold and italics***
>###### Best Practice
>
>underscore can also be used instead of * but markup applciation can't work with using _ in middle of the word  
---
### 3. Blockquotes

- use `>` in front of paragraph  or between paragraphs for multiparagraphs
- Blockquote can be nested using `>>`

Example:
```
        > ###### Best Practice
        > 
        > For compatibility and readability use blank lines before and after blockquotes
```
Result :
> ###### Best Practice
> 
> For compatibility and readability use blank lines before and after blockquotes
---
### 4. Paragraph and Line Break

- use blank lines after a paragroph to start a new pragraph
- use two space to end the line 

Example

        (this document is an example )

> ######  Best Practice
>
> Unless Paragraph is in a list do not indent paragraph with space or tab


### 5. List

- Unordered List: Use `-`,`+` or `*`.
- Ordered List: use numbers followed by period(`1.`)
- add 4 space `tab` for nested list

Example:
```
- fruit
- vegetable
   - eggplant
1. make love
2. Make food
   4. Ready
```
Result:

- fruit
- vegetable
   - eggplant
1. make love
2. Make food
   4. Ready


>###### best practice
> - Use \ as escape if number followed by period is needed to be used
> - Use same delimiter in a list
---

### 6. Code
    
- For inline use backtick: \`code`
- For block of code use triple backticks before and after codeblock  

Example:

        ``Use `code` in a line``

Result: 
``Use `code` in a line``
---
### 7. Horizontal Rule  

Use `***`, `___`, or `---` on a line by themselves  

Example: 
``` 
*** 
```
Result: 
***

### 8. Links

- Syntax: `[link text](url)` 
- Markdown can also link to othe section or document
    1. Internal link. Markdown creates unique id for each header. For period `. ` or space use `-`  
        `[ 1. Headers ]( #1-headers )`
  2. External Link. use relative path or filename in same directory
        `[ links file ]( links.md )`
  3. Anchor Links (custom IDs for headings):  
         ```## Custom Section {#custom-id}  
[Jump to Custom Section](#custum-section--custom-id)```

Example :
```
[ github link ](https://github.com)
`[ 1. Headers ]( #1-headers )`
[ links file ]( links.md )
 [Jump to Custom 101](#101)
```
Result:

[ github link ](https://github.com)  
[ 1. Headers ]( #1-headers )   
[ links file ]( links.md )  
[ Jump to Custom 101 ]( #content--puma )  

Markdown can also link



