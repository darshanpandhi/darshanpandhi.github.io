# How to Host a Resume Online

Hosting one's Resume online is no longer an option today. Rather, it is crucial in order to survive in this competitive job market. Fortunately, doing so is much easier than it seems.

## Purpose

This README will guide you in formatting and having your Resume published online utilizing popular and current technical documentation tools like Markdown, a Markdown editor, GitHub Pages and Jekyll.

While doing so, this README will also teach about Andrew Etter's key principles regarding current Technical Writing as mentioned in his book [_Modern Technical Writing_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/).

## Audience

This README is intended for fellow Computer Science Students looking to increase their employability.

## Terminology

The following terms are used throughout the README and hence have been defined here in one place.

- [**Markdown**](https://www.markdownguide.org/)

  Markdown is a lightweight markup language. Simply put, it is a way of formatting text documents.

  As a matter of fact, this README itself is formatted in Markdown using a Markdown Editor which brings us to our next term.

- **Markdown Editor**

  Markdown Editors are simple, easy to use text to HTML conversion tools.

  I personally prefer [Visual Studio Code](https://code.visualstudio.com/) as it shows a live preview side by side as you type the corresponding Markdown.

- [**GitHub Pages**](https://pages.github.com/)

  Using GitHub Pages, you can convert your favourite GitHub repository into a website.

- [**Jekyll:**](https://jekyllrb.com/)

  Jekyll is a static site generator that is used to convert plain text into static websites.

## Prerequisites

- **A Resume formatted in [Markdown](https://www.markdownguide.org/)**
- **A GitHub Account:** If you don't have one already, you can create a free one on the [GitHub Website](https://github.com/join)

## Instructions

### Distributed File Sharing System

> There is no doubt that distributed version control systems are superior than their centralized counterparts. The absence of repository locking allows multiple developers to collaborate in real time. Besides, in the event of an unprecedented failure, the peer transfer system saves the day as opposed to a central server failure. And the most underrated of all is the ability to work offline.

> However, according to Etter, the primary reason technical writers should use a distributed file sharing system is because developers prefer them. This will encourage collaboration as potential contributors now know that you prefer modern tools.

Therefore, it is reason enough to use GitHub in our expedition.

#### Steps to create a new GitHub Repository

1. Sign In / Open your GitHub Repository
2. Click on **New / Create Repository** to create a new repository
3. Name this new repository as _yourGitHubUsername_.github.io
4. Set it up as a **Public** Repository.
5. Check **Add a README file** to allow GitHub to automatically create a README file for you (like the one you are reading right now)
6. Click **Create repository**

### Lightweight Markup Language

> Etter strongly feels that using a lightweight markup is the best way forward. Not only is the work then relatively easy to comprehend but also is usually short in length and requires much less time and effort to maintain.

> Furthermore, it increases people's ability to contribute.

That is why we format our resume in [Markdown](https://commonmark.org/help/). After all, it the most widely used markup language in the world having the most concise syntax.

Note: While Markdown has several flavours, we use the popular GitHub Flavoured Markdown.

#### Steps to upload your (Markdown-formatted) Resume to this new Repository

1. Click **Add file** within your new repository.
2. Select **Upload files** from the dropdown box.
3. Rename your Resume file as index.md.
4. Drag this index.md file into your repository.
5. Enter a [commit message](https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/).
6. Click **Commit Changes**.

### Static Website and Static Site Generator

> Etter is not wrong when he says that static websites check all the right boxes. They do not require any specialized learning and are quick and easy to setup. It lets one focus their time and effort on what matters the most, content.
> To add on, the absence of a database and server-side scripting results in better overall performance.

Needles to say, a static website is what we are going for here with GitHub Pages. This website will host our repository containing our Resume.

> While manual simple static site creation is feasible,
> utilizing one of Etter's very own suggestions, Jekyll, as our static site generator, can futureproof it.

And that's exactly what we do here (Use Jekyll to theme our Resume).

#### Steps to create a Static Website for your Resume and style it

1. Click **Settings** tab from within the repository.
2. Scroll Down to GitHub Pages Section. Here, you will see the URL of your GitHub Page.
3. Click **Choose a theme** under the **Theme Chooser** Sub-Section.
4. Select the desired theme.
5. Click **Select theme**.

And that's all. You have successfully hosted your Resume online.

To check that out, follow the animated GIF added below. Navigating to _yourGitHubUsername_.github.io website should give you the desired result you have been waiting for.

### Animated GIF

![GIF](GIFanimation.gif)

### More Resources

- [A fun and interactive Markdown Tutorial](https://commonmark.org/help/tutorial/)

- [Modern Technical Writing by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/)

- [Interesting Jekyll Tutorial allowing to explore more of it](https://opensource.com/article/17/4/getting-started-jekyll)

## Authors and Acknowledgements

Billie Thompson for providing a good readme template.

I would like to thank

- **Billie Thompson** whose README template has been instrumental in putting this README together.
- **Fantastic Five** group members from COMP 3040 whose suggestions while peer editing have been extremely valuable.

## FAQs

1. “Why is Markdown better than a word processor?”

Not only is Markdown free as oppossed to the licensing cost of Word, Markdown does not share Word's version control issue and poor history for creating HTML Websites.

2.  “Why is my resume not showing up?”

Note that GitHub pages takes a while to load the latest changes. So, it is completely normal to not see your changes instantly. Do refresh your page after a while and you should be abler to see your latest changes.
