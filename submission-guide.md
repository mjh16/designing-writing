+++
title = "Submission Guide"
date = 2018-05-14T22:56:51-04:00
draft = false
+++

Hey all, to help streamline the process of submitting materials for me to upload, here are a few guideline that will be helpful. First, please format your pieces as Plain Text, as this will strip random formatting from the document. You can do this out of Word by doing a save as, plain text, or out of Google Docs as a Download As Plain Text. I will help with some of that workflow as we go through.

---

## Files

In general, there will be a number of files associated with each unique piece of the webtext that we create. There will be the text itself, as Markdown.md files; videos as YouTube links or MP4s (we can discuss what these will be); audiofiles as MP3, AAC, or FLAC; and images as PNG or JPG. There may be some other material types which we can associate with the text as well. Having everything organized and categorized will let me drop it right into the framework so we can get to revising, collaborating, and generally thinking about the delivery of the text. Do pay attention to file names, organizing them in a way that makes sense to the structure of your piece, and that can be easily read and figured out in context. Additionally, it will be useful to have them be styled without spaces or special characters. For example: michael-healy-unr-profile.md, unr-writing-center1.png, creighton-demographics.png, etc. This will allow them to drop into the HTML file structure, and help me figure out what goes where if something breaks.

### Structure
It will greatly help in having me get the pieces and profiles into the webtext if folders are structured in a particular way when they are submitted to me. (ask Michael Neal if it will be helpful to have say, a OneDrive of Google Drive submission box here).

Ideally, it will look something like this:

**Your Name Folder**

- page-title.md
- second-page.md
- Media Folder
  - Images
  - Videos

---

## Formatting Text Files

To help turn our awesome multi-modal texts into a format that will be friendly and useful for all of us to build the webtext (and so we don't have to do a bunch of HTML), we will be using [GoHugo](https://gohugo.io) to help us rapidly prototype and build the webtext. Hugo takes Markdown files and turns them into rich HTML using a theme. Ther are tools you can use to help write markdown, or there are some general guidelines, along with a specific page that I've put together as a cheat sheet for potential commmon usage types for our work.

### TOML

First, providing some metadata will be useful. At the top of each of your pages I am going to ask that you enter some metadata in the TOML format, which looks like this:

{{< highlight html >}}
+++
title = "title of your page"
date = 2018-05-14T22:56:41-04:00
author = "Your Name"
tags = ["any","relevant","tags"]
category = ["category-1","category-2"]
+++
{{< /highlight >}}

This metadata will be used in organizing within the framework itself for things like relating content, giving names, dates, search engine info, and other metadata functions. The text files themselves will then be coded using [markdown](/page/markdown-cheat-sheet/), and please see the page for a useful guide for composing in Markdown. You can also use a number of free web-based Markdown editors such as [stackedit.io](https://stackedit.io), [Dillinger](https://dillinger.io), and others. These all have options to sync up with Google Drive, GitHub, and OneDrive, providing ways to write and preview in an app, and then export the markdown files. Additionally, they provide WYSIWYG toolbars to assist with editing and attaching media.

## TL;DR

**File-Names**

- No Spaces, descriptive

**File-Types**

- markdown.md
- jpg, png, mp4, mp3, flac, AAC

**File-Conventions**

- TOML metadata
- Markdown formatting
- .md extension
- Saved as plain text (No Word Files)

**Structure**

*folder-with-your-name*

 - page-1.md
 - page-2.md
 - page-3.md
 - Media Folder
    - media-files-with-descriptive-names.JPG
    - and-no-spaces.AAC
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNTE3ODIwNTJdfQ==
-->