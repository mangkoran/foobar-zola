+++
title = "Markdown Cheat Sheet"
date = 2024-06-22
[taxonomies]
tags = ["post"]
+++

This blog content is taken from
[mattcone/markdown-guide](https://raw.githubusercontent.com/mattcone/markdown-guide/master/assets/markdown-cheat-sheet.md).
Several extended markdown spec are unsupported by default by Zola which are
marked with "X" below.

---

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax
elements. It can’t cover every edge case, so if you need more information about
any of these elements, refer to the reference guides for [basic
syntax](https://www.markdownguide.org/basic-syntax/) and [extended
syntax](https://www.markdownguide.org/extended-syntax/).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All
Markdown applications support these elements.

### Heading

# H1

## H2

### H3

### Bold

**bold text**

### Italic

_italicized text_

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all
Markdown applications support these elements.

### Table

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List (X)

term : definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji (X)

That is so funny! :joy:

(See also [Copying and Pasting
Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight (X)

I need to highlight these ==very important words==.

### Subscript (X)

H~2~O

### Superscript (X)

X^2^
