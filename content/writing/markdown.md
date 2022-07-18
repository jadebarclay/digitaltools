---
section: Writing
nav_order: 2
title: Markdown and LaTeX 
topics: Markdown; LaTeX; Pandoc
description: >
    There are very powerful free tools to make your writing fast and beautiful, if you're willing to invest a little time into setting them up. 
# youtubeid: moJgWrD6dwg
---

## Markdown

`Markdown` is a simple and popular text formatting syntax. It has many advantages for academic writing: it is stable, reliable, easy to read and produces plain text files which are easily shared. It's worth becoming familiar with it.

{% capture aboutmarkdown %}
This site is written in Markdown.
{% endcapture %}
{% include alert.html text=aboutmarkdown color="primary" %}

{% capture markdowntools %}

All of the programming text editors above support Markdown. Below are some dedicated Markdown editors. 

- **[Dillinger](https://dillinger.io)**:  popular and free online Markdown editor.

- **[Stackedit](https://stackedit.io)**: popular and free online Markdown editor.

- **[Ulysses](https://ulysses.app)**: a general-purpose writing app with good Markdown support.

- **[Marked 2 (Mac)](https://marked2app.com)**

{% endcapture %}
{% include card.html header="<i class='fab fa-markdown'></i> Markdown editors" text=markdowntools %}

## LaTeX

`LaTeX` is a text formatting language (like `Markdown`) which is very flexible and robust. It is well suited to scientific and mathematical notation. In LaTeX, document content and structure is separated from formatting and style, so you can work on one without worrying about the other. Here is a [good explanation](https://nitens.org/w/latex/) of why LaTeX is a useful tool for academic and scientific writing.

`BibTeX` is a counterpart program to LaTeX that generates bibilographies for academic and research papers. It can also integrate with the open-source reference manager [Zotero](https://www.zotero.org/). 

{% capture nyulatexguide %}

Check out this helpful [guide to getting started with LaTeX](https://guides.nyu.edu/LaTeX/), published by NYU Library.

{% endcapture %}
{% include alert.html text=nyulatexguide color="primary" %}

{% capture latextools %}

- **[Overleaf](https://www.overleaf.com)**: is a web-based LaTeX editor with many built-in templates and automatic preview. It can automatically format your paper for certain journals and even submit them for you.
- **[TeXShop](https://pages.uoregon.edu/koch/texshop/)**: A venerable Mac-based LaTex editor. 

{% endcapture %}
{% include card.html header="LaTeX composition tools" text=latextools img="latexit.png" %}

## Pandoc

`Pandoc` is an open-source tool that can convert just about any document format into just about any other document format! You can use it to convert your `Markdown` or `LaTeX` documents into Word — even automatically if you want!

You can read an excellent tutorial on academic writing using Markdown and Pandoc [here](https://github.com/GriffithUniLibrary/digital-tools).