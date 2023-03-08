# Host a Resume with the help of Markdown , Jekyll, VS Code and GitHub Pages
## Table of contents
* [**Title**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#host-a-resume-with-the-help-of-markdown--jekyll-vs-code-and-github-pages)
* [**Purpose**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#Purpose)
* [**Prerequisites**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#Prerequisites)
* [**Principles of Technical Writing**](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/README.md#Principles-of-Technical-Writing)
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
- A GitHub account : Here is the [link](https://github.com/) for sign up/log in to GitHub.
- [Link](https://github.com/meenalbhatia28/meenalbhatia28.github.io) to GitHub repository of my resume template.
## Principles of Technical Writing
### 1. Using a Lightweight Markup Language

### 2.  Formatting a document with a static site generator
### 3. Hosting documents on a distributed version control system
## Instructions 
### Getting Jekyll Theme Template on GitHub
By the end of this section, you have:
- Opened the free Jekyll Theme Template(the template that i used for my resume) on GitHub repository.

**Open the Jekyll template on GitHub**
1. Click on the [link](https://jekyllthemes.io/theme/resume-template) to open the template that I used for my Resume.
2. Click on the Button "Get Resume Template on GitHub" in order to open the template on the GitHub.

### Forking the template to your repository
By the end of this section, you have:
- Forked the resume template on your repository

**Fork the template on your repository**
1. Click on the "Fork" button located at the upper-right corner.
2. Login in to your GitHub account if you are not logged in your GitHub account.

### Renaming the Repository
By the end of this section, you have:
- Renamed the template by your username
**Rename the forked repository**
 Once forked ,you will to page where you can rename your repository
1. In the field provided, enter the new name for your repository as as {your-username}.github.io .
For examples :-for my repository it meenalbhatia28.github.io .
If there are no duplicate repositories present ,your new name will be automatically be saved my GitHub.

### Activating GitHub Pages
By the end of this section, you have:
- Enabled the GitHub page settings of your repository.

**Enable GitHub Pages**
1. Click on the Settings tab located on the right side of the screen.
2. Click on the "Pages" tab under "Code and automation" on the left side of the screen.
3. Under "Branch" select "gh-pages" so as to publish your website.
### Customizing your Website
By the end of this section, you have:
- Personalised your website according to your Information.

**Customize your website** 
1.Go to code tab of your repository.
2. Scroll down and go through all the files present in your template repository 
3. Go to  _config.yml_ and make changes to your personal information.
4. You can comment out the information from _config.yml_ that you are not interested in showing on your resume.
5. Make sure you commit all your changes made in _config.yml_ .
6. Now go to _/_data/_ folder to make changes in different sections of your resume like:
   - associations
   - education
   - experience
   - interest
   - links
   - projects
   - recognitions
   - skills
7. Make changes in the _.yml_ files in _/_data/_ folder.
8. Commit changes for each of the file in _/_data/_ folder side up side.
9. Now go to {username}.github.io/images/ and remove the already existing avatar.jpg .
10. Uplaod your own photo to {username}.github.io/images/ folder and rename it to avatar.jpg.
11. Commit all the changes you made in images folder as well.
### Publishing your Website
By the end of this section, you have:

**Hosted your Website**
If you have properly implemented all the previous steps ,you are ready to check your published resume.
1. Click on the Settings tab located on the right side of the screen.
2. Click on the "Pages" tab under "Code and automation" on the left side of the screen.
3.


### Keeping your Website Up-to-Date
By the end of this section, you have:
- Learnt how to keep the website up-to-date




## Authors and Acknowledgment
- Documentation by Meenal Bhatia
- Jekyll Template  for my resume was forked from  [Joel Glovier](https://github.com/jglovier) 
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
### 1. What advantages does Markdown offer over a word processor?
- Markdown files can be version controlled using tools like Git, which is not possible with word processors. Etter also highlights that Markdown allows for better collaboration as multiple people can easily edit and review the same file without compatibility issues.

### 2. How can I resolve a 404 error when trying to access my resume link?
- Firstly, ensure that you have named your repository as {your-username}.github.io as this is necessary for hosting a resume on GitHub Pages. 
- Next, check the settings of your repository and ensure that the branch is pointing to the main branch where all the files are located.
- Verify that your repository is set to public to allow access to the resume link.
These steps should help you resolve the issue.






