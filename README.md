# Hosting a Markdown-formatted Resume

**Purpose:** A step-by-step guide on using Markdown, GitHub Pages, and Jekyll to host a résumé on a static website using the concepts of current technical writing as described in Andrew Etter's book *Modern Technical Writing*.

## Summary
- [Prerequisites](#prerequisites)
- [Instructions](#instructions)
- [More Resources](#more-resources)
- [Authors and Acknowledgements](#authors-and-acknowledgments)
- [FAQ](#faq)


## Prerequisites

### Markdown-Formatted Resume
Markdown is a simple markup language that can be used in a plain text editor to create styled content.John Gruber and Aaron Swartz created Markdown in 2004 as a markup language with the goal of allowing anyone to write in an easy-to-read and easy-to-write plain text format. 

##### Why Markdown? 
>As per Etter's book *Modern Technical Writing*, the use of Lightweight Markup language can be useful and simple while creating a website.
It makes use of simple syntax and has a minimal learning curve.
It also allows you to update the information using a regular text editor.
Markdown is the most widely used lightweight markup language in the world, and there are a number of software tools that may help you get the most out of it, including: 

>* [MarkdownPad](http://markdownpad.com/) (Windows)
>* [iA Writer](https://ia.net/writer) (Mac OS)
>* [ReText](https://codepre.com/how-to-install-retext-restructuredtext-editor-in-ubuntu-a-markdown-editor-for-linux.html) (Linux)  



### GitHub Account
An account to host your resume is required.
**Note -** When hosting markdown files on GitHub Pages, it's important to use [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).  

### Jekyll
Use Jekyll to easily customize your website. Multiple themes are available for you to choose from or you can simply add a "_config.yml" file in your repository containing a simple jekyll theme.

In **_config.yml** file
```
theme: jekyll-theme-modernist
```


## Instructions



## Authors and Acknowledgments
This document was written by Tahmidul Hasnain Zidaan, using Andrew Etter's book *Modern Technical Writing* as reference.

## FAQ

**Why is my resume not showing up?**  
> Make sure the file containing your Resume is written in GitHub-Flavored Markdown or GitHub may have trouble to render the content.

**Why is Markdown better than a Word processor?**
> Markdown allows you to separate the content from style.Using this, you can have consistency in your content and style without having to style while writing.  