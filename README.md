# Host a Resume with the help of Markdown , Jekyll and GitHub Pages
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
1. To offer clear instructions for hosting and formatting a resume using Markdown, GitHub Pages, and Jekyll.
2. To connect these practical steps with the broader principles of modern technical writing, as outlined in Andrew Etter's book "Modern Technical Writing".


## Prerequisites
- [Link](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/RESUME.md) to my resume formatted in Markdown.(You might not need that if you follow my instructions. But can help understand markdown syntax.)
- A GitHub account : Here is the [link](https://github.com/) for sign up/log in to GitHub.
- My Jekyll Theme Template: [Link](https://jekyllthemes.io/theme/resume-template) to resume template that i forked.
## Principles of Technical Writing

### 1. Using a Lightweight Markup Language

Andrew Etter mentions in his book "Modern Technical Communication" that using a Lightweight Markup Language (LML) is beneficial for technical writers for several reasons:

  - First, LMLs are simple and easy to learn. Compared to other programming languages or markup languages, Lightweight Markup Languages have a smaller set of rules and syntax, which makes them easier to read, write, and edit. This simplicity can save time and reduce errors in documentation. Etter's this principle is implemented in my Resume Hosting Instructions too as you can follow the steps and generate your website.
  
  - Secondly, LMLs separate content from formatting. This means that the writer can focus on creating the content without worrying about the layout or design. By using LMLs, technical writers can ensure that their documentation remains consistent in terms of style and formatting, which can enhance readability and usability for the end-users. It promotes simplicity which means someone from non-technical background can also fork my website easily and make desired changes to it.
  
### 2.  Formatting a document with a static site generator

  - Firstly, Etter believes that static websites are ideal for projects that don't require complex functionality or frequent updates. They are simple, fast, and easy to maintain. That's one of the key reasons I chose Jekyll static site generator to host my resume. You can simply launch your website in 20-30 minutes.
  
  - Secondly, Hosting a resume on GitHub Pages is an example of using a static website. By editing the config.yml and files in the /data/ folder, updating the contents of the resume is effortless. Once changes are committed to the repository, the updates are immediately visible.

### 3. Hosting documents on a distributed version control system

 In "Modern Technical Communication," Andrew Etter argues in favour of using a distributed version control system (DVCS) due to its numerous   advantages:
 
 - First, it offers the added benefit of maintaining a comprehensive record of all modifications made to a document, including the identity of the person who made them and the precise time they were made. Like, my "meenalbhatia28.github.io" repository as well it has records of all the commits made since day one of the project.So in case, I want to jump back to my older version of my Resume in future I can easily do that.
 
 - Secondly, One of the main advantages of using a DVCS, such as Git, is that it allows for collaborative editing and version control. This means that multiple authors can work on the same document simultaneously, without fear of overwriting each other's work. In my case, if someone wants to use my repository for their project they can simply fork it on their repository and can start working on it.

## Instructions 

### Getting Jekyll Theme Template on GitHub

By the end of this section, you have:
- Opened the free Jekyll Theme Template(the template that i used for my resume) on GitHub repository.

#### Open the Jekyll template on GitHub

1. Click on the [link](https://jekyllthemes.io/theme/resume-template) to open the template that I used for my Resume.

2. Click on the Button "Get Resume Template on GitHub" in order to open the template on the GitHub.

![A GIF showing step 1](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/getResumeTemplate1.gif)

### Forking the template to your repository

By the end of this section, you have:
- Forked the resume template on your repository

#### Fork the template on your repository

1. Click on the "Fork" button located at the upper-right corner.
![A GIF showing step 2](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/ForkTheTemplate2.gif)

### Renaming the Repository

By the end of this section, you have:
- Renamed the template by your username

#### Rename the forked repository

Once forked ,you will  directly jump to the page where you can rename your repository.
1. In the field provided, enter the new name for your repository as as {your-username}.github.io .

For examples :- for my repository it's meenalbhatia28.github.io .

![A GIF showing step 3](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/rename3.gif)

If there are no duplicate repositories present ,your new name will be automatically approved by a green tick .

### Activating GitHub Pages

By the end of this section, you have:
- Enabled the GitHub page settings of your repository.

#### Enable GitHub Pages

1. Click on the "Settings" tab located on top of screen.

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/GOTOSETTINGS5.gif)

2. Click on "Pages" tab under "Code and automation" present on left side of the screen.

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/go_to_pages_new.gif)

3. Under "Branch" select "gh-pages" so as to publish your website.Don't forget to click "save".

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/root_setting7.gif)

### Customizing your Website

By the end of this section, you have:
- Personalised your website according to your Information.

#### Customize your website

1.Go to code tab of your repository.

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/go_to_code.gif)

2. Scroll down and go through all the files present in your template repository.It should look something like this : 

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/scrolling.gif)

3. Go to  _config.yml_ .

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/goToConfig.gif)

4. Click on th pencil button so that you can edit the _config.yml_ .

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/edit_click_pencil.gif)

5. You can change the pre-existing information with yours and comment out the information from _config.yml_ that you are not interested in showing on your resume.Just like the way i replaced the default name with my own ,see below:

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/replace_info_in_config.gif)

6. Scroll to the bottom of the screen and commit all your changes made in _config.yml_ .

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/commitchange.gif)

7. Now go to _/_data/_ folder  under "code" tab to make changes in different sections of your resume like:
   - associations
   - education
   - experience
   - interest
   - links
   - projects
   - recognitions
   - skills

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/goTo_datafile.gif)

8. Make changes in the _.yml_ files present in _/_data/_ folder.

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/inside_data_folder.gif)

9. Scroll to the bottom of the screen and commit changes for each of the file in _/_data/_ folder side up side.

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/commitchange.gif)

10. Now go to {username}.github.io/images/ folder  

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/goto_image_folder_new.gif)

11. Remove the already existing avatar.jpg .

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/remove_old_avatar.gif)

12. Uplaod your own photo to the same {username}.github.io/images/ folder and rename it to avatar.jpg.

13. Commit all the changes you made in images folder as well.

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/commitchange.gif)

### Publishing your Website

By the end of this section, you have:
- Published your resume online.

#### Hosted your Website

If you have properly implemented all the previous steps ,you are ready to check your published resume.

1. Click on the Settings tab located on the right side of the screen.

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/GOTOSETTINGS5.gif)

2. Click on the "Pages" tab under "Code and automation" on the left side of the screen.

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/go_to_pages_new.gif)

3.Click on the button "visit site" under github pages to check your hosted site .

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/visit_site.gif)

Finally,If you followed all steps properly .Your website should look something like this.

![A GIF showing step 4](https://github.com/meenalbhatia28/meenalbhatia28.github.io/blob/gh-pages/images/finalwebsite.gif)


### Keeping your Website Up-to-Date

By the end of this section, you have:
- Learnt how to keep the website up-to-date

#### Keep Website Up-to-Date

1. You can regularly edit your .yml files like you did under [Customizing your Website](https://github.com/meenalbhatia28/meenalbhatia28.github.io#customizing-your-website) so as to ensure that your website matches your latest experience , achievements ,etc.

## Authors and Acknowledgment
- Documentation by Meenal Bhatia
- Jekyll Template  for my resume was forked from  [Joel Glovier](https://github.com/jglovier) 
- I would like to express my gratitude to the members of my group
    - Maxim Omelchenko
    - Tirenioluwa Biodun-Kuti
    - Yee Tsung Kao 

## More Resources
- [Tutorial](https://www.youtube.com/watch?v=QUtk-Uuq9nE) on how to create a GitHub account.
- [Link](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) to Andrew         Etter's book book "Modern Technical Writing"
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






