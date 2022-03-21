##### this guide comes from 
##### https://www.markdownguide.org/assets/markdown-cheat-sheet.md)
##### ---
##### changes are marked with [SR1]
---


---

# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide - www.markdownguide.org](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).


[ % ]: % (commenting)
[ % ]: % (hint found at)
[ % ]: % (.)
## Commenting [SR1]
in source insert comments this way(s):

```
  [ comment ]: % (comment)
  or
  [ comment ]: <> (comment)
  [ comment ]: # (comment)
```
 > [hint found here](https://stackoverflow.com/questions/4823468/comments-in-markdown)

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

# H1
## H2
### H3

### Bold

**bold text**


### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
   1. First sub item [SR1]
      1. sub sub item [SR1]
         1. and so on [SR1]
         2. ... [SR1]
   2. Second sub item [SR1]
2. Second item
3. Third item

### Unordered List

- First item
  - First sub item
    - sub sub item
      - and so on
        - ...
  - Second sub item
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

### Image (resized)

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. 

**Not all Markdown applications support these elements**.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

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

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [x] Update the website
- [ ] Contact the media

### Emoji (vsc not working)

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight (vsc not working)

I need to highlight these ==very important words==.

### Subscript (vsc not working)

H~2~O

### Superscript (vsc not working)

X^2^