+++
title = "Markdown Guide"
date = 2018-05-14T22:56:38-04:00
draft = false
toc = true
+++

Here is a  guide to markdown, taken from the [GoHugo](https://gohugo.io/documentation/) docs. As mentioned in the submission guide, you can also use a number of online markdown editors such as [stackedit.io](https://stackedit.io), [Dillinger](https://dillinger.io). I use a program called [Atom](https://atom.io/), which is very much a programming text editor.

This cheat sheet is set up for common usage scenarios for our text. I will provide links for futher information. As always, I am always availble to help, just send an email.

A few things to keep in mind with markdown. First, it is a markup language, which means that it adds code to existing plain text in order to render other effects. This means that any formatting that you want to do with the text you will have to add the appropriate markdown text. This page is also meant to be a quick guide

For a more indepth guide go to: https://learn.netlify.com/en/cont/markdown/ or https://gohugo.io/content-management/formats/#learn-markdown

---

# Table Of Contents
* [Text Formatting](#text-formatting)
* [Adding Links](#adding-links)
* [Media](#media)
* [Images](#embedding-images)
* [Other Media](#embedding-other-media)
* [Tables, Lists, and Other Formatting](#other)

---

## Text Formatting

Formatting | Markdown
-----|-----
*Italics* | single * around the text
**Bold** | double ** around the text
Horizontal line | three consecutive dashes --- , astericks *** , or underscores ___
Blockquote | put a > before the text to quote

Headings
```md
1-6 # Heading Text
```
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

## Adding Links

To add a link you can just include the link, for example http://kairos.technorhetoric.net.

If you'd like to include a link [in text](http://michaelhealy.space), then you'll do it like this:

```
[link text](link to content)
```

## Media

### Embedding Images

There are two ways to embed images and other figures. Keep in mind the file structure (it will help me not mix things up) as you go.

The first is to format the image the same as any other link starting with an exclamation point: `![text](link-to-image)`

The second way is using Hugo's figure shortcode, which will give you some additional formatting options. You can find more information about [shortcodes here.](https://gohugo.io/content-management/shortcodes/) There are a number of options for the figure shortcode, and it can be useful if you need to caption or resize an image.

### Embedding Other Media

You are also able to embed other media using the HTML embed code generated from the page. Hugo also has a number of shortcodes available for [YouTube](https://gohugo.io/content-management/shortcodes/#youtube), [Vimeo](https://gohugo.io/content-management/shortcodes/#vimeo), [Twitter](https://gohugo.io/content-management/shortcodes/#tweet), and [Instagram](https://gohugo.io/content-management/shortcodes/#instagram). You can also use the HTML iFrames generated from other sites directly in the text.

## Tables, lists, and other options {#other}

### Lists

You can make unordered lists in following way:

``` markdown
* Item
- Item
+ Item
```

* Item
- Item
+ Item

And if you'd like to nest the lists, add tabs before the items, like:
``` Markdown
* Item 1
  - Nested Item 1
  * Nested Item 2
  + Nested Item 3
* Item 2
```

* Item 1
  - Nested Item 1
  * Nested Item 2
  + Nested Item 3
* Item 2

And ordered lists work like this:

``` md
1. Item 1
2. Item 2
3. Item 3
```

1. Item 1
2. Item 2
3. Item 3

### Tables

To make a table:

``` md
Name | Things | Value
---|---|---
One | Two | Three
```

Name | Things | Value
---|---|---
One | Two | Three

And you can align the tables using colons like so:

``` md
Left | Center | Right
:---|:---:|---:
One | Two | Three
```

Left | Center | Right
:---|:---:|---:
One | Two | Three
