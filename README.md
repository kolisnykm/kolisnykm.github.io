# Etter's _MODERN TECHNICAL WRITING_ Principles Applied to Posting Resumes

For computer science students and other beginner technical writers wanting a look at how Etter's principles apply to the process of hosting your resume on [GitHub Pages](https://pages.github.com/).

## Topics
1. [Overview](#overview).
2. [Prerequisites](#prerequisites).
3. [Instructions](#instructions).    
    1. [Create distributed version control repository](#create-distributed-version-control-repository).
    2. [Add lightweight markup resume](#add-lightweight-markup-resume).
    3. [Make static website](#make-static-website).
4. [More Resources](#more-resources)
5. [Acknowledgments](#acknowledgments)
6. [FAQ](#faq)


## Overview
We will be applying three principles form Andrew Etter's book [_MODERN TECHNICAL WRITING_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) to the resume process namely:
1. **Use lightweight markup** - Formatting with lightweight markup allows you to format your document inline with the text, making it easily readable by anyone but also easily translated into xml for building websites.
We will be using [Markdown](https://www.markdownguide.org/) to format our resume.

2. **Use distributed version control** - Distributed version control is used by developers because it allows for multiple people to concurrently work on the same file, online or offline, while keeping track of all the changes made.
This may seem like overkill for a resume but it allows you to have several versions ready to go that can quickly edited and posted depending on your current needs. But more importantly, using distributed version control demonstrates to developers that you are comfortable working with their current tools.
We will be using [GitHub](https://github.com/) for our distributed version control.

3. **Make static websites** - Static websites are excellent for documentation, they are fast, secure, portable, easy to translate to other document formats, and easy to test on any computer because they need few resources and have no dependencies on databases or other programs like JavaScript.
We will be hosting our resume on [GitHub Pages](https://pages.github.com/) which will freely host one site per member and has excellent integration of the static site builder software [Jekyll](https://jekyllrb.com/).


## Prerequisites
The instructions below assume you already have a GitHub account and a current resume.
If you do not currently have a GitHub account go to [GitHub](https://github.com) and signup for a free account.


## Instructions

![Instruction.gif](yikes.gif)


### 1. Create distributed version control repository
You will need a new repository to house your resume on GitHub pages. We will be using GitHub because it offers distributed version control, it is open source, and it is widely used.

**To create a new repository that is GitHub pages ready:**
1. Go to your GitHub home screen.
3. Click the **New** button
4. Name the repository _yourUsername_.github.io.
**Warning:** naming the repository anything other than _yourUsername_.github.io will not create a repository compatible with GitHub Pages.


You should now be in your new repository.

### 2. Add lightweight markup resume
We will be using [Markdown](https://www.markdownguide.org/) as our lightweight markup. Markdown is easy to learn and the base syntax allows for compatibility across a broad range of platforms but lacks some standard features like tables and code blocks. Since we are using GitHub I would recommend using [GitHub flavored markdown](https://github.github.com/gfm/) as it offers more features and is fully compatible with GitHub Pages and Jekyll.

Editing tools are available on the GitHub site so all edits can be done there but I would recommend using [Atom](https://atom.io/) to edit documents for its side preview window, live server on localhost, IDE terminal, and most importantly, full GitHub integration.

**To add your resume to the repository:**
1. Create a markdown file named index.md.
2. Populate index.md with your resume formatted in Markdown.
3. Click the **Add file** drop-down menu and add your resume to the repository.

### 3. Make static website
[Jekyll](https://jekyllrb.com/) will build the website for hosting on [GitHub Pages](https://pages.github.com). We will be using one of the default Jekyll templates to provide our website layouts and styles. You can edit existing templates and create your own.

**To generate your static website:**
1. Go to your GitHub repository
2. Select the **Settings** tab.
3. Scroll down to the **GitHub Pages** section.
4. Click the **Select theme** button and choose your theme.

Once the theme is selected you will find a new file in your repository named **_config.yml** this file holds the settings for the overall template and can be edited to suit your needs.

Your website is now hosted on GitHub Pages at https://_yourUsername_.github.io.


## More Resources
* [_MODERN TECHNICAL WRITING_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) a book by Andrew Etter.
* Interactive [Markdown tutorial](https://www.markdowntutorial.com/) on basic syntax.
* [Mastering markdown](https://guides.github.com/features/mastering-markdown/) tutorial that includes GitHub flavored markdown.
* Mike Dane's [Jekyll Course](https://www.mikedane.com/static-site-generators/jekyll) guides you through all the Jekyll basics from installation to website deployment.

## Authors & Acknowledgments
This project was created for [University of Manitoba's](https://umanitoba.ca) COMP-3040-A01 fall 2020: _Technical Communication in Computer Science_ by Michael Kolisnyk.

I would like to thanks all the members of Fantastic Five for their workshopping and peer editing on this project and Billie Thompson for providing [a good readme template](https://github.com/PurpleBooth/a-good-readme-template).


## FAQ
