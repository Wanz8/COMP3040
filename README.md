# Hosting and Formatting a Resume on GitHub Pages using Markdown, VS Code, and Jekyll

The purpose of this README is to guide you through the process of hosting and formatting a resume using Markdown, VS Code, GitHub Pages, and Jekyll. We will also relate each practical step to the general principles of current Technical Writing as explained in Andrew Etter's book "Modern Technical Writing."

### Prerequisites
* A Markdown formatted resume
* A GitHub account (If you didn't have yet, click [here](https://github.com/join))
* [Ruby](https://www.ruby-lang.org/en/downloads/)
* [Jekyll](https://jekyllrb.com/docs/installation/)
* Install [markdown editor](https://www.shopify.com/partners/blog/10-of-the-best-markdown-editors)



---
## Instructions


### Create a Repository 
>By the end of this section, you will have:

> * Created a new repository on your GitHub.

#### Step 1: Creating a New repository

1. Log into your [GitHub](https://GitHub.com) account.![HomePage](image/HomePage.png)

2. At the top right corner of the website, click on the '**+**' symbol
3. Select "**New Repository**".

    ![Step 2 gif](create.gif)

3. Give your repository a name. 

    ![Step 3 gif](image/Name.gif)

4. Choose visibility for your repository. You might set "**Public**" Because you want your employer to be able to see your resume
5. Initialise the repository with a README file.

    ![Step 5 gif](image/Set%20Public.gif)

6. Click on "**Create Repository**" to create.

7. In the newly created repository navigate to **Settings**
![Step 7 gif](image/Find%20Settings.gif)
8. In the sidebar click **Pages**![Step 8 gif](image/Find%20Page.gif)
9. Set the deployment source to *Deploy from a branch* under the **Source** section and set the desired publishing branch under the **Branch** section
    - To keep it simple it is recommended that the main branch and root directory is the publishing branch
![Step 9 gif](image/Main%20Branch.gif)
10. Click Save
---

### Choosing a Jekyll Theme for Your GitHub Page

If you're using GitHub to host your personal website or blog, you might be using Jekyll as your static site generator. Jekyll allows you to easily create and manage a website using plain text files, and there are plenty of pre-made themes available that you can use to customize the look and feel of your site. 

In this guide, we'll go through the steps for choosing a Jekyll theme for your GitHub page.

## Step 1: Determine Your Needs

Before selecting a theme, consider the purpose and content of your GitHub page. Do you need a theme that is focused on blogging or a theme that showcases your portfolio? In this demonstration, I will choose a more concise theme for the resume.

## Step 2: Browse the Supported Jekyll themes

The "GitHub Pages" is a great place to start looking for themes. There are plenty of free themes available that cover a variety of use cases. You can browse the page at [pages.github.com](https://pages.github.com/themes/).

## Step 3: Review the Theme's Documentation

Once you've found a your favourite theme, review the documentation to see if it meets your needs. Documentation should include instructions for installation, configuration, and customization. Look for themes with clear documentation and active support from the developer.




---
# Hosting Your Resume on GitHub Pages with the Cayman Theme

This guide will show you how to host your resume on GitHub Pages using the Cayman theme, which is a Jekyll theme created by Jason Long. 

## Prerequisites

To follow this guide, you'll need the following:

- A GitHub account
- A text editor
- Your resume in Markdown format
- A forked copy of the Cayman theme repository

## Step 1: Fork the Cayman Theme

The first step is to fork the Cayman theme repository to your GitHub account. To do this, go to the Cayman theme repository on GitHub and click the Fork button in the top right corner of the page. 

## Step 2: Create a New Repository

The next step is to create a new repository on GitHub to host your resume. We recommend using a name like yourusername.github.io, where yourusername is your GitHub username.

## Step 3: Clone Your Repositories

1. Clone the repository you created in step 2 to your local machine.
2. Clone the forked Cayman theme repository to your local machine.

## Step 4: Customize the Theme

1. Open the cloned Cayman theme repository in your text editor.
2. Copy the _layouts, _sass, assets, and Gemfile folders from the Cayman theme repository to the root directory of your resume repository.
3. Edit the _config.yml file in the root directory of your resume repository. Change the following lines:


---


---
## More Resources
* [Easy Markdown Tutorial](https://www.markdowntutorial.com)
* [GitHub Flavoured Markdown Reference Sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
* ["Modern Technical Writing" by Andrew Etter](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

---
## Authors and Acknowledgements 
#### **Author**
* [ZHIHAO WANG](https://github.com/Wangz8)  
#### **Group Members/Peer Editors**

#### **GitHub Page Theme**
*  
---
## FAQs
