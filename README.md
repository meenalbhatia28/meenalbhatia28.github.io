# Host a Resume with the help of Markdown , Jekyll, VS Code and GitHub Pages
## Table of contents
* [**Title**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#host-a-resume-with-the-help-of-markdown--jekyll-vs-code-and-github-pages)
* [**Purpose**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#Purpose)
* [**Prerequisites**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#Prerequisites)
* [**Instructions**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#Instructions)
* [**Authors and Acknowledgment**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#authors-and-acknowledgment)
* [**More Resources**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#More-Resources)
* [**FAQs**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#FAQs)
## Purpose
### This README file has 2  purposes :
1. To offer clear instructions for hosting and formatting a resume using Markdown, VS Code, GitHub Pages, and Jekyll.
2. To connect these practical steps with the broader principles of modern technical writing, as outlined in Andrew Etter's book "Modern Technical Writing".


## Prerequisites
- [Link](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/RESUME.md) to my resume formatted in Markdown.
- A GitHub account.Here is the [link](https://github.com/) to GitHub.
- Jekyll Theme Templates (free):Here is a [link](https://jekyllthemes.io/theme/resume-template) to a free template I forked for hosting my resume.
## Instructions
### The process of hosting a website with a Jekyll template by forking it from GitHub can be broken down into the following steps:
1. **Get Resume Template on GitHub** :First, Go on the free Jekyll Theme Template mentioned in Prerequisites and open it on GitHub.
2. **Fork the Jekyll template repository** : To obtain the Jekyll template repository, navigate to the relevant GitHub repository and select the "Fork" button located at the upper-right corner of the page. This will generate a duplicate of the repository under your own GitHub account.
3. **Rename the repository** : After successfully forking the Jekyll template repository, proceed to rename the cloned repository as {your-username}.github.io and save the updated changes.
4. **Activate GitHub Pages** : Click on the "Settings" tab. Next, navigate to the "Pages" section located under "Code and automation" on the left-hand side of the screen. Here, ensure that the root branch has been selected under the "Branch" section and then save the changes.
5. **Customize your website** : To personalize your website, follow the steps below:
    - To modify content such as education, experience, links, projects, skills, associations, etc., navigate to _/_data/_ and adjust any or all of the         files to suit your preferences.
    - Next, make changes in _config.yml_ to update your personal information. You can also comment out any sections you want to hide on the template.
    - To alter your profile photo, access the "images" folder and upload the image of your choosing. After uploading, rename the image as "avatar.jpg" and     ensure that the previous "avatar.jpg" has been removed.
_Make sure you commit changes side by side._
6. **Publish Your Website** : After implementing the desired alterations to your website, commit and push the changes to your forked repository. Your website will then be accessible on the URL listed under the "GitHub Pages" section of your repository's settings.
7. **Keep you Website Up-to-date** : To keep your website up-to-date and functioning properly, it is important to perform regular maintenance tasks. This includes updating the Jekyll version, fixing broken links, and monitoring any security vulnerabilities.


## Authors and Acknowledgment
- Documentation by Meenal Bhatia
- Jekyll Template forked from  [Joel Glovier](https://github.com/jglovier) 
- I would like to express my gratitude to the members of my group
    - Maxim Omelchenko
    - Tirenioluwa Biodun-Kuti
    - Yee Tsung Kao 

## More Resources
- [Tutorial](https://www.youtube.com/watch?v=QUtk-Uuq9nE) on how to create a GitHub account.
- [Link](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) to Andrew Etter's book book "Modern Technical Writing"
- Link to Markdown [Tutorial](https://www.markdowntutorial.com/lesson/1/)
- Github flavoured [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for Markdown 

## FAQs
### What advantages does Markdown offer over a word processor?
- Markdown files can be version controlled using tools like Git, which is not possible with word processors. Etter also highlights that Markdown allows for better collaboration as multiple people can easily edit and review the same file without compatibility issues.

### How can I resolve a 404 error when trying to access my resume link?
- Firstly, ensure that you have named your repository as {your-username}.github.io as this is necessary for hosting a resume on GitHub Pages. 
- Next, check the settings of your repository and ensure that the branch is pointing to the main branch where all the files are located.
- Verify that your repository is set to public to allow access to the resume link.
These steps should help you resolve the issue.






