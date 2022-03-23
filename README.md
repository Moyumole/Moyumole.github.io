# A Simple Tutorial on How to Format and Host Your Resume on GitHub

## Purpose

1.  A step-by-step tutorial on how to use markdown to write and format and host
    your resume on GitHub.

2.  How to put the technical writing principles in [Andrew Etter's
    book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
    into practice

## Prerequisites

-   GitHub account

-   A resume written in Markdown

-   Jekyll installed

-   [Dillinger](https://dillinger.io/) or any Markdown editor you prefer

## Instructions

### Why use GitHub to build and host websites instead of using PDFs to write our resumes?

As mentioned in Andrew Etter's book, PDFs as documents will eventually become
obsolete. Your resume is downloaded to your hard drive as a PDF and no one
maintains it, which prevents the content from being updated. Hosting your resume
on a website guarantees that the content will be updated and fixed in no time.
For example, you have gained new work experience or completed a new project, you
can update your resume immediately.

GitHub Pages is a great choice to host your static website. The advantages of
static websites mentioned in Andrew's book are speed, simplicity, portability
and security. A static website has no server-side application dependencies. All
you need is a static site generator (we'll be using Jekyll in this tutorial) to
process everything into a working website.

### Create the Repository on GitHub

1.  Login to your GitHub account

2.  Click the plus sign in the upper right corner of the page and select the
    "New repository" in the drop-down menu

    ![](https://i.imgur.com/hrv7dxC.png)

3.  Enter *username.github.io*(*username* is your GitHub account name) in
    "Repository name" 
    ![](https://i.imgur.com/pU00lLP.png)

4.  Set your repository to public. You can also choose to automatically add a
    "README" file
    ![](https://i.imgur.com/KuwJhAY.png)

5.  Click the green "Create repository" button after completing the above steps

### Why use Markdown to write your resume?

As we mentioned before, your resume content should be hosted online. However,
using the popular HTML to write documents is very complicated and cumbersome.
For documentation, lightweight markup is superior in every way.

Markdown is the most widely used lightweight markup language in the world.
Andrew believes that Markdown's syntax is the most concise in the book. Editing
and formatting documents is easy and fast with Markdown. This is exactly what we
need to write and maintain resumes.

### Upload Your Resume

1.  Click on the repository you just created on your GitHub homepage

![](https://i.imgur.com/Gl5JRvg.png)

2.  Click "Add file" at the top of the page and select "Upload files" from the
    drop-down menu

![](https://i.imgur.com/v8Czl79.png)

3.  Select your resume and name it "*index.md*" then click the green "Commit
    changes" button below

![](https://i.imgur.com/JNuiLS0.png)

### Use a static site generator to create beautiful documentation websites.

After uploading your document, you must pay attention to the theme of the custom
document. Each different document has a different audience and purpose. You need
to choose an appropriate theme to make your content easier to read. Andrew
mentions in his book that when designing and choosing a theme, pay attention to
navigation and accessibility. If you don't have the skill to do this
customization, you might need to hire someone to help, as the right and
appropriate theme really matters.

### Choose and customize your theme

-   **Choose a Theme for Your Website**

    1.  Select the "Settings" button on the top right in your
        repository
        ![](https://i.imgur.com/QJsqSRg.png)

    2.  Select the "Pages" button below the menu on the left side of the
        page

        ![](https://i.imgur.com/rki27C1.png)

    3.  Select "Change theme"

        ![](https://i.imgur.com/tKftGUd.png)

    4.  Click "Select theme" after selecting the appropriate theme

        ![](https://i.imgur.com/j6Mjr8y.png)

-   **Add a Config File**

    1.  Click "Add file" at the top of the page and select "Create new file"
        from the drop-down menu
        ![](https://i.imgur.com/VSQPsH6.png)

    2.  Name your document *"_config.yml*". This file will be where you
        customize the theme
        later.
        ![](https://i.imgur.com/dWFod6t.png)

    3.  Different themes may have many different customizable options, I
        recommend reading the corresponding theme's README file for the
        relevant instructions. In this example we use the midnight theme,
        they have a very detailed
        [README](https://github.com/pages-themes/midnight/blob/master/README.md)
        file to guide you on how to customize your page.

### How do I view my own static website?

-   You can go to your static website by manually entering your repository
    name(*username.github.io*) in your browser

-   You can also find your website URL from the page menu in settings

    ![](https://i.imgur.com/XndBPyQ.gif)

### More Resources

1.  [Step by step Markdown tutorial](https://www.markdowntutorial.com/)

2.  [Modern Technical Writing: An Introduction to Software
    Documentation](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

3.  [Useful Markdown
    Editors](https://opensource.com/article/21/10/markdown-editors)

## Authors and Acknowledgements

Author: Steven Zhang

Group 7 COMP 3040 😏

Members: Seth Peters, Carl Wiebe, Sangmin Lee

## FAQs ❓

### Why is Markdown better than a word processor?

The first is that its syntax is simple, it can be written quickly, and you can
understand all its syntax in a few minutes. Compared with the complex tags of
HTML, another markup language, Markdown is more user-friendly. Compared with the
dense buttons of Word (you must have seen many Word training tutorials), it is
faster and easier to write. The second is that it can be read directly without
the interference of various HTML tags. The syntax is simple, can be written
quickly, and can be read directly. These are the advantages of Markdown.

### Cannot install Jekyll?

If you have problems installing
[Jeykell](https://jekyllrb.com/docs/troubleshooting/) you can visit their
[homepage](https://jekyllrb.com/docs/troubleshooting/) for answers.
