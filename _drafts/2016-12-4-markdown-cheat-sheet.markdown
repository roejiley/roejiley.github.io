---
layout: post
title: The Markdown Cheat Sheet
image: assets/images/air-coding.jpg
---

Markdown is the templating language that Jekyll (which my blog runs on) uses. I thought it would be a pretty handy post to show others a little cheat sheet on how Markdown is written.

### Headers

```
# This is an <h1> tag.
## This is an <h2> tag.
###### This is an <h6> tag.
Or you can use these for H1/H2 instead.
Alt-H1
=======
Alt-H2
------
```

### Lists

Lists are pretty simple. They can be numbered or you can use an asterisk for an unordered list.

```
1. Topic 1
2. Topic 2
    * option 1
    * option 2
```

1. Topic 1
2. Topic 2
3. Topic 3
    * Topic 3a
    * Topic 3b

### Text Styling

```
*This is italic*
_This is also italic_
**This is bold**
__This is also bold__
```

### Syntax Highlighting

```
For inline code you use `back ticks` .
```
It looks like `this`.

```
Code blocks use three back ticks.
```

### Block quotes

Block quotes use `>` at the start of the line.

```
Someone once said...

> something important

```

### Backlashes

Backlashes (\\) are used to escape generated Markdown syntax. You can use them for several different characters.

* \\ backslashes
* \` back ticks
* \* asterisks
* \_ underscores
* \{} \[] braces and brackets
* \() parentheses

### Tables

```
|  Tables | Look like |  This  |
| ------- | :-------: | ------:|
| They're |  Pretty   | Simple |
```
