# Sections

- [Headers](#headers)
- [Quotes](#quotes)
- [Emphasis](#emphasis)
- [Horizontal Rule](#horizontal-rule)
- [Lists](#lists)
- [Links](#links)
- [Images](#images)
- [Tables](#tables)

# Header 1
    Headers are defined by '#' symbol. One for H1, two for H2 etc. There are SIX types of Header available.

## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
---

<!-- -------------------------- -->

# Quotes

    Quotes are defined by '>' symbol.

> This is the First Line of quote.
> This is the Second Line of Quote. 

> This is the First Line of quote.

> This is the Second Line of Quote. 

> # This is big quote
---

<!-- -------------------------- -->

# Emphasis

    Add emphasis with astrisks '*' and underscore '_'.

 Two before and after (no spaces) a section of texts makes it bold.

**Bold Sentence**

__Bold Sentence__

*Italic Sentence*

_Italic Sentence_

***Bold and Italic***

**_Bold and Italic_**

*__Italic and Bold__*

This is my _italictied_ word and this is my **world**.
---

<!-- ----------------------- -->

# Horizontal Rule

    A horizontal rule gives a visible line break. You can create  one by putting THREE or more hypens, astrisks or underscore. [ *, -, _ ]

 ---

 ***
 ___

 <!-- ------------------------------ -->

 # Lists
  
    Create Unordered lists using '-', '*', '+'

- Item 1
- Item 2
- Item 3

* Item 4
* Item 5

+ Item 6
+ Item 7

Sublists can be created by indenting

- list
    - sublist
        - sublist
            - sublist
                - sublist

Craete ordered lists by using a number prefix and dot.

1. Item 1
2. Item 2
3. Item 3

Another list

1. Item 4
1. Item 4
1. Item 4
---

<!-- ------------------------------- -->

# Links

    Create a link by sorrounding it with angle brackets <>

<https://www.google.com/>


    Create a link with text by sorrounding with brackets, [], and link immediately following with parenthesis ()

[Google Homepage](https://www.google.com/)


Create a reference style links by defining your link with a 'key' inside of brackets, colon, space and the line.

[key]: https://www.google.com/
[xyz]: https://www.google.com/


[Google Homepage][key]

[Google Homepage][xyz]
---

<!-- ----------------------------- -->
# Images

![Office](https://www.dropbox.com/s/09vhypn7gxmdogt/collaboration.jpg?raw=1)


Reference style image

[variable]: https://www.dropbox.com/s/09vhypn7gxmdogt/collaboration.jpg?raw=1

![office][variable]
---

<!-- --------------------------------- -->

# Code 

You can do inline code with `backtiks` (``)

Here is some code inline `var item = {}`

You can do block of code by sorrounding it with 3 backtiks (``` ```)

```
    var item = [];
    item[0] = "item1";
```

You can specify the programming language immediately following the opening 3 backtiks. You should see difference in highlighting!

```javascript
var num = 0;
var num2 = 0;
```


```html
<div>
    <p>This is some text</p>
</div>
```
---

<!-- ------------------------ -->

# Tables

- Tables are useful in displaying roes and columns of data
-Columns header can be defined in between pipes(|)
-Header are seperated from table content with a row of dashed(-)(still seperatrd by pipes)
- There must be atleast 3 dashes between each header
the row data follows beneath(still seperated by pipes)

Header 1 | Header 2 | Header 3
--- | --- | ---
Column 1 | Column 2 | Column3
Column 1 | Column 2 | Column3
Column 1 | Column 2 | Column3


Yoy can format it for readibility. It doesn't have any impact on output

| Header 1 | Header 2 | Header 3 | 
| -------- | -------- | -------- |
| Column 1 | Column 2 | Column 3 |
| Column 1 | Column 2 | Column 3 |
| Column 1 | Column 2 | Column 3 |

Text in the columns can be aligned by using colon (:) in the line break between headers and rows.
- No columns means default (LEFT aligned)
- **Left alignment** -  NO colons (Default)
- **Center alignment** - Colon on each side
- **Right alignment** - Traling colon


| Header 1     | Header 2       | Header 3      | 
| ------------ | :------------: | ------------: |
| Aligned Left | Aligned Center | Aligned Right |
| Left         | Center         | Right         |
| Aligned Left | Aligned Center | Aligned Right |
---

<!-- -------------------------------- -->
# Custom HTML

Since Markdown gets automatically converted to HTML, you can add raw HTML  directlt to your markdown

<h2>Header 1</h2>
    <p>This is a sentence</p>

---
<!-- --------------------------------------- -->

# Custom CSS

You can add custom CSS to your Markdown to add additional styling to your document. You can also include CSS by including a style tag.

<style>
    p {
        color: aquamarine;
        font-family: Helvetica;
        font-size: 1.2rem;
    }
</style>
---
