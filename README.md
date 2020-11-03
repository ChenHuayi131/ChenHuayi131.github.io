# **Hosting an Attractive Resume on GitHub Pages**

## **Abstract**
Here are some helpful guidelines about how to make a beautiful resume or something you want to show on the website. You are recommended to use a tool called GitHub which is widely used by many senior programmers in the world. There is a GitHub Pages inside, which can help you begin with your stuffs and achieve an online resume. Also, there is a book named “Modern Technical Writing” written by Andrew Etter that you probably need to read before you start. In this book, it talks about the steps of how to write and set websites and compares their tools and ways. The most helpful thing is that this book lists many examples that make users easy to learn.

## **List of Contents**
+ [Getting Started](#getting-started)  
  + [Prerequisites](#prerequisites)
  + [Installation](#installation)
+ [Instructions](#instructions)  
  + [Create a new repository](#1-create-a-new-repository)
  + [Write resume in Markdown](#2-Write-resume-in-markdown)
  + [Use a Markdown editor](#3-use-a-markdown-editor)
  + [Make an index file](#4-make-an-index-file)
  + [Create static site by Jekyll](#5-create-static-site-by-Jekyll)

  + [Resume Demo](#resume-demo)
+ [Resources](#resources)
+ [Authors and Acknowledgments](#authors-and-acknowledgments)
+ [FAQs](#faqs)

## **Getting Started**

### *Prerequisites*
+ You will work with popular and current technical documentation tools. The most important thing is **GitHub Pages**. From Etter, "GitHub use a *Distributed Version Control System*, it allows people work offline and work on the same file. Also, it can keep all versions of one file in the history." So DVCS is suitable to solve problems required collaboration.
+ You required a basic level for writing **Markdown** language, I will talk about benefits of this language later.  
+ I recommend you write and edit codes by using a **Markdown editor**. Of course, it depends on you, you can directly write Markdown on GitHub files or anywhere you like.  
+ If you want to make your resume more vivid in order to leave a nice first impression on employers, **Jekyll** is the best choice.

### *Installation*

+ Markdown editors are common applications on computer, almost of them are supported by Windows, Mac, and Linux. You can directly go to their official websites to download them. Here are some brands of the best rate Markdown editors on *Resources* section.

+ Jekyll has a few complex steps to operate, you just copy codes shown below and paste them step-by-step in the terminal.
  1. Install ruby Ubuntu(first) and macOs(second)
  ```shell
  ~ $ sudo apt-get install ruby-full
  ```
  ```shell
  ~ $ brew install ruby
  ```

  2. Install Jekyll
  ```shell
  ~ $ gem install bundler jekyll
  ```
  [Learn more](https://jekyllrb.com/) about installing Jekyll  


+ There is no need to install GitHub application on desktop of your computer.


## **Instructions**

### *1. Create a new repository*
At the beginning, if this is your first time that hear GitHub, you need to create a GitHub account on the Internet. After you log in, you will see a “+” sign near your profile photo on the top left of screen, click it and there is a "*New repository*" where is the place to create your own GitHub Page. Please see the red circle 1 in picture I show you below. Next, you are required to enter a repository name, which the repository name must begin with exactly your username so that it can automatically generate a GitHub Pages site. Otherwise, it cannot build an online site from your GitHub repository. In other words, you just follow the red step 2 I draw in the picture that fill with <u>*username.github.io*</u> there to ensure your resume can appear online successfully. After that, check all information you already filled and click green button "*Create repository*".  
![Repository](https://media.giphy.com/media/GGkfXc4LTRMYRsfv6u/giphy.gif)

### *2. Write resume in Markdown*
First of all, before you start to make a home page, you need to prepare your resume code probably written by Markdown language. According to Etter, "Markdown is the most widely used lightweight markup language by many people who may work in the IT industry all over the world. If you write your resume in Markdown, you will enjoy the benefits it brings to you, such as the cleanest syntax, limited set of features, and no defined standard." To be specific, Markdown makes everything become simpler and easier to get started. Markdown has its flavors, especially we focus on one of them which is GitHub Flavored Markdown. Lastly, I provide you with some helpful Markdown tutorials on *Resources* section, including some commonly used syntax.

### *3. Use a Markdown editor*
You maybe write your Markdown with a Markdown editor. It can make you easy and convenient since the editor can provide live view to you that you are able to glance the preview generated from what you write. I recommend you use one of these two free Markdown editors. They are **Typora** and **Atom**. Typora is a concise Markdown editor that supports instant rendering technology which means you can edit contents and see what happen next second. Other is Atom, it has abundant plug-ins.

### *4. Make an index file*
If you have already created a repository and well done your resume, now you will click “*Add file*” button to create a new file named **index.md** in GitHub repository. This index.md file should be your resume formatted with Markdown. If this is the first time you process files in repository, I strongly advocate you to copy the source code from your Markdown file and paste them in this index.md file.

### *5. Create static site by Jekyll*
Etter mentions, "static websites have some excellent performances, such as speed and simplicity, and easy to migrate. If people want to create a static website, they will use a generator, like Jekyll, just provide content and theme and then it processes everything to build a website." However, you just need parts of Jekyll’s functions to generate your resume on web. First thing is that click *Settings* in your GitHub repository, then go down and find *GitHub Pages*. You may select *main* branch and click *Change theme*, choose a theme you want to show to your future employer (See picture below). Also, come back to repository and enter "*_config.yml*" file, add
```
title: your name 's Resume
```
After a few seconds, you will see fantastic appearance of your resume on <u> https://**username**.github.io</u>.

![Jekyll theme](https://media.giphy.com/media/lZgYDblV8VvPQGq7k0/giphy.gif)


### Resume Demo
![Sample Resume Demo](https://media.giphy.com/media/BVEx2WqttRwTCHYfOK/giphy.gif)

## **Resources**
+ [10 of the best Markdown editors](https://www.shopify.com/partners/blog/10-of-the-best-markdown-editors)
+ [Markdown tutorials](https://www.markdowntutorial.com/)
+ [Get start with a GitHub Pages](https://pages.github.com/)
+ [Video tutorials of using Jekyll](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)
+ [Modern Technical Writing](https://www.amazon.ca/gp/product/B01A2QL9SS/) *by Andrew Etter*

## **Authors and Acknowledgments**
README template author: [Othneil Drew](https://github.com/othneildrew)  

Group Members:  
Huayi Chen, Connor Hryhoruk, David Le, Jai Sandhu

## **FAQs**
1.  Why is Markdown better than Microsoft Word?  

  To some extent, Markdown is suitable for simple situations with no special requirements on format, such as writing a blog, a README or code documents, where line spacing, headers, footers, and indentation are all meaningless, and what matters is the content. In addition, markdown is simple text, which is convenient for Git management, while Word is too heavy and inconvenient.


2.  Why is my resume not showing up?  

  Please try the following methods：
  + Correct your repository named as <u>**username**.github.io</u>
  + Check the contents of index.md file, it should be formatted with Markdown
  + Turn on your VPN to link your resume website if you are in some network monitoring regions  
  + Retry to refresh this website after a while
