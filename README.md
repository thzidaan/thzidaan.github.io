# Hosting a Markdown-formatted Resume

**Purpose:** A step-by-step guide on using Markdown, GitHub Pages, and Jekyll to host a résumé on a static website using the concepts as described in Andrew Etter's book *Modern Technical Writing*.

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




### GitHub Account
An account to host your resume is required.
**Note -** When hosting markdown files on GitHub Pages, it's important to use [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).  

### Jekyll
Use Jekyll to easily customize your website. Multiple themes are available for you to choose from or you can simply add a "_config.yml" file in your repository containing a simple jekyll theme.

In **_config.yml** 
```
theme: jekyll-theme-modernist
```


## Instructions

### Resume 
Markdown is the most widely used lightweight markup language in the world, and there are a number of software tools that may help you get the most out of it, including: 

>* [MarkdownPad](http://markdownpad.com/) (Windows)
>* [iA Writer](https://ia.net/writer) (Mac OS)
>* [ReText](https://codepre.com/how-to-install-retext-restructuredtext-editor-in-ubuntu-a-markdown-editor-for-linux.html) (Linux)  

**Notes** 
* Please use GitHub-flavored Markdown if you decide to host your resume on GitHub.
* Save your resume file as "index.md"

### GitHub Account 
>Etter promotes the use of distributed version control systems (DVCS) like Git and Mercurial over centralised systems in his book *Modern Technical Writing*. Offline work is allowed with these systems, and overall performance is better. It's also a technology that most developers use, so having all of your work, including documentation, in one place is an advantage.

#### Create an Account 
* Visit [GitHub](https://github.com/)
* Enter your email and click Sign Up
* Use the prompts as guide to finish creating your account

#### Create a New Repository 
* Login to your [GitHub](https://github.com/) account
* Click on Repositories 
* Click New Button - **Green Button on the top right of the screen**
* Name you repository in the following format - YourUserName.github.io
* Click on Create repository - **Bottom of the screen**

#### Upload your Resume in the repository
* Click on Add File
* Click Upload Files
* Select your resume and make sure the file name is index.md


#### Host your Resume using GitHub Pages
* Go to your repository and click on settings
* Find Pages section from the sidebar
* Make sure that the 'main' branch is chosen as source and Save
* Use the Theme Chooser to choose any theme for your resume

#### Demo 
Here is a demo of how your resume might look when you visit YourUserName.github.io







## Authors and Acknowledgments
This document was written by Tahmidul Hasnain Zidaan, using Andrew Etter's book *Modern Technical Writing* as reference.

## FAQ

**Why is my resume not showing up?**  
> Make sure the file containing your Resume is written in GitHub-Flavored Markdown or GitHub may have trouble to render the content.

**Why is Markdown better than a Word processor?**
> Markdown allows you to separate the content from style.Using this, you can have consistency in your content and style without having to style while writing.  
