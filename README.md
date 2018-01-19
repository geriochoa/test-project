# Markdown is Simple!

We can have subsections:

## This is a subsection

And continue nesting subsections if that is neccesary for the organization of
the document structure

### Nested Subsubsection 

Then we can do some simple formatting writing **bold** and *italics*, or we can
***combine*** them. Alternatively we can use _underscores_ instead. 

Now, what about lists?. Well, we can have numbered lists:

1. First item
2. Second item
3. Third item

And bullet lists:

* First item
* Second item, which also happens to be a multiline item

  This is a new paragraph within the whole thing. Let's nest a list:
  
  1. This is a subitem
  2. And a second subitem

* And the list continues


But what if I want automatic numbering. I can't be bothered with remembering
which item I'm currently writing. Let's try that then:

1. First item
1. Second item
1. Next item, whatever its number is
1. Another item

### What about code?

To write inline code is simple `print("hello world")`. On the other hand, if
you want to write a block of code, try this:

```
let x = 24;
figure = new Figure("red");

if (Figure.color === "red") {
   console.log("It is RED");
}
```

It is all nice and good but, what if I want my code to have some colors?. We can
do that too!:

```javascript
let x = 24;
figure = new Figure("red");

if (Figure.color === "red") {
   console.log("It is RED");
}
```

Cool!.

### Hyperlinks

Well, we can add a [link to this](https://www.wizeline.com/). Another
possibility are [link with a title](https://www.wizeline.com/ "Wizeline").

It is also possible to add [links with a reference number][1]. And links to
arbitrary text within my docunment, like [the top of this section](#Hyperlinks)

[1]: http://www.wizeline.com.

### Images

Images syntax 

### Tables

Well, tales may take a bit longer to typeset:

| Column1 | Column 2 | Coluymn 3 |
|:--------|----------|----------:|
| 23      |something | 110       |
| 42      | else     |:bar_chart:|


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

**FINAL NOTE** Slack uses its own flavor of Markdown. Many of these work fin
one Slack. Not the hyperlinks though.
