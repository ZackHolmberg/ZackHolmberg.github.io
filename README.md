# How to Host Your Resume Online Using GitHub Pages

## Introduction

* This guide was made to help people host their resume online to increase self-exposure and join the modern era of digital resumes. You will use Markdown and GitHub Pages to help you in this task.

## Intended Audience

* This guide is intended for people that have very little to some experience working with Markdown and GitHub. If you have no experience with the aforementioned technologies, this guide is not for you.

## Prerequisites

1. A GitHub account. If you need one, click [here](https://github.com/join).
2. Basic competency using GitHub (navigating around GitHub and initializing a repository).
3. Basic competency working with Markdown. If you need a refresher, click [here](https://www.markdowntutorial.com/).

## Instructions

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Format Your Resume In Markdown

* __Stop!__ Before you proceed, take the time to update your resume. We often forget to include our most recent job or latest project in our resume. Once your resume is up-to-date, continue on.

    1. Download and set up a text editor (if you don't already have one).

        > My personal recommendation is Microsoft's [Visual Studio Code](https://code.visualstudio.com/) (VS Code). VS Code is a lightweight editor that is great for simple development. If you choose to use VS Code, install the [GFM Preview extension](https://marketplace.visualstudio.com/items?itemName=tomoki1207.vscode-gfm-preview). This extension allows you to preview your Markdown file in real-time, within VS Code. Click [here](https://code.visualstudio.com/docs/introvideos/extend) to view a brief tutorial on managing VS Code extensions.

    2. Create a new file and save it with the name `index.md`.

        > This particular file name will help you later when you upload your Markdown file to GitHub.

    3. Find a Markdown resume template.

        > My personal favourite is one by [Mark Szepieniec](https://github.com/mszep), which you can find [here](https://gist.github.com/mszep/d3235240cc6653d6eeaa#file-resume).

    4. Copy the template's raw Markdown and paste it into your `index.md` file.

        > Recycling an existing template will save you a lot of time and effort.

    5. Edit the Markdown template to reflect the information on your resume.

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Initialize a GitHub Pages Repository

* Just in case you are unaware, GitHub Pages is used to host static websites. A GitHub Pages repository is just a normal GitHub repository with a special name.

    1. Create a new repository with the name `YourGitHubUsername.github.io`.

        > This naming convention is *__critical__*. A site will not be hosted if the name of your new repository does not match the above format.

    2. Finish the repository initialization, without initializing a default `README.md` file.

        > It is important not to initialize the repository with a README. If you do, the site will display the README instead of your resume. You may add a README after you complete these instructions.

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Upload Your Markdown Resume To Your Repository

* Due to the particular name of the file, GitHub Pages will automatically display your resume on your site.

    1. Add your `index.md` file to the repository.

    2. Verify that GitHub Pages is correctly displaying your resume online by navigating to your site.

        > Your site's URL is `YourGitHubUsername.github.io` (the name of your repository).

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4. Apply a Jekyll Theme to Your Site

* Jekyll is a simple static site generator with many interesting native features. Jekyll is the engine behind GitHub Pages, and the two come hand in hand. For our purposes, we won't worry about the specifics of Jekyll. We will simply be using the built-in GitHub functionality to apply an exsiting Jekyll theme. If you want to learn more about Jekyll, click [here](https://jekyllrb.com/).

    1. Navigate to your GitHub Pages repository.

    2. Click "Choose a theme", in the repository settings, under the "GitHub  Pages" section.

    3. Click the theme you want, then click "Select theme".

        > Your chosen theme will automatically apply to your resume file.

### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5. Customize the Jekyll Theme

* There are many ways to customize the theme you chose in the previous instruction. One of them is the theme's "Front Matter". This is the only customization we will cover in this guide.

    1. Navigate to the base directory of your repository.

    2. Open the `_config.yml` file.

        > If you were wondering where this file came from, it was automatically created when you applied the Jekyll theme.

    3. Edit the text following "title: " to something more suitable. For example, "YourName's Resume".

        > To learn more about customizing Front Matter, click [here](https://jekyllrb.com/docs/front-matter/). Additionally, you can customize your theme's HTML layout and CSS. This is a bit more technically advanced, so I will leave it up to you to pursue. You can find information on how to do so [here](https://help.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll#customizing-your-themes-html-layout).

    4. Commit the changes to the file.

    ### Congratulations! You have succesfully hosted your resume online using Github Pages.

## Additional Resources

* [Supplemental information regarding GitHub Pages.](https://help.github.com/en/categories/working-with-github-pages)

* [Intro to GitHub Flavoured Markdown.](https://github.github.com/gfm/)

* [Customize the HTML and CSS of your GitHub Pages theme.](https://help.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll#customizing-your-themes-html-layout)

* [Learn about Jekyll.](https://jekyllrb.com/)

## Authors and Acknowledgments

* This guide was created by [Zack Holmberg](https://github.com/ZackHolmberg).

* Credit to [Mark Szepieniec](https://github.com/mszep) for creating the Markdown resume template that I recommended earlier and used.

* Thank you to my group members, [Mark Robitaille](https://github.com/MarkRobitaille) and [Daniel Gold](https://github.com/goldDaniel), for their continuous support, advice and revision of this guide.

## FAQs

* ### Q - Can I customize the domain of my GitHub Pages site?

* __A: Yes! Click [here](https://help.github.com/en/github/working-with-github-pages/about-custom-domains-and-github-pages) to learn about custom domains and GitHub Pages.__

* ### Q - How do I unpublish my GitHub Pages site?

* __A: Only people with admin permissions for a repository can unpublish a GitHub Pages site. If your intention is to keep the GitHub Pages repository but unpublish your resume from the site, simply rename your `index.md` file to anything else, like `resume.md`. If you would like to remove the GitHub Pages site completely, simply delete the GitHub Pages repository.__
