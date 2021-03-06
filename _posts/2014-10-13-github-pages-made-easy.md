---
id: 306
title: Github Pages made easy (no commands, no hassle)!
date: 2014-10-13T20:21:22+00:00
author: Redgadget
layout: post
guid: http://redgadgets.com/?p=306
permalink: /github-pages-made-easy/
wp_review_location:
  - bottom
wp_review_desc_title:
  - Summary
wp_review_color:
  - '#1e73be'
wp_review_fontcolor:
  - '#555555'
wp_review_bgcolor1:
  - '#e7e7e7'
wp_review_bgcolor2:
  - '#ffffff'
wp_review_bordercolor:
  - '#e7e7e7'
spacious_page_layout:
  - default_layout
categories:
  - Github
  - Technology
tags:
  - github
  - jekyll
---
[<img class="alignnone size-medium wp-image-307" src="/wp-content/uploads/2015/01/github-pages-600x232.jpeg?fit=600%2C232" alt="github-pages" data-recalc-dims="1" />](/wp-content/uploads/2015/01/github-pages.jpeg)


* some
{: toc }

## <span id="Hosting_a_blog_on_github">Hosting a blog on github</span>

### <span id="Brief_steps">Brief steps</span>

  1. Create a repository
  2. Start a blog or fork a starting point
  3. Using [prose.io](http://prose.io) for updating the blog

## <span id="Step_1_Create_a_Repository">Step 1 Create a Repository</span>

There are many tutorial sites for this. This [official tutorial](https://help.github.com/articles/create-a-repo/) is enough to start off. So I&#8217;m not gonna waste any time on explaining that.

## <span id="Step_2_Start_a_blog_or_fork_a_starting_point">Step 2 Start a blog or fork a starting point</span>

Starting a blog from scratch is not easy. You have to make your own template and styles. This may seem tedious job to do. So there is a better way to do that. [Jekyll](http://jekyllrb.com) is a [static website](http://en.wikipedia.org/wiki/Static_web_page) generator that helps you create your blog and makes it easier to post.

You can find a starting point here in [Jekyll Now](https://github.com/barryclark/jekyll-now). You can also find different templates in [Jekyllthemes](http://jekyllthemes.org). Fork any of the repository to have a starting point. This will save a lot of time.

![Insert Image](https://lh3.googleusercontent.com/-UVDDFU3-nwM/VDwlov5LHhI/AAAAAAAAALs/nHXeeduvZCE/w994-h548-no/step1.gif)

Head to [Jekyll Now](https://github.com/barryclark/jekyll-now) by Barry Clark, and hit the **Fork** button in the top-right corner of the repository to fork a copy of the blog theme to your GitHub account.

As a GitHub user,you can host one free **user** Website , which will be live at http://yourusername.github.io. This is where we will be hosting your blog.

Read: <a href="http://redgadgets.com/my-webdesign-tricks/" target="_blank">My Webdesign Tricks</a>

Click the **Settings** button in your newly forked repository (in the menu on the right), and change the repository’s name to **yourusername.github.io**, replacing **yourusername** with your GitHub user name.

Your website will probably go live immediately. You can check by going to http://yourusername.github.io. Don’t worry if it isn’t live yet we can force it to be built.

You can now change your website’s name, description, avatar and other options by editing the `_config.yml` file. These custom variables have been set up for convenience and are pulled into your theme when your website gets built.

Making a change to `_config.yml` (or any file in your repository) will force GitHub Pages to rebuild your website with Jekyll. The rebuilt website will be viewable a few seconds later at http://yourusername.github.io. If your website wasn’t live immediately, it should be now.

So this is how your blog should look like.

![Jekyll Now](https://lh3.googleusercontent.com/-h-5ftL66VNc/VDwmqMqiO_I/AAAAAAAAAMY/ZrnUTgU7hZU/w619-h593-no/jekyll-now-theme.jpg)

You can now change your website’s name, description, avatar and other options by editing the `_config.yml`. These custom variables have been set up for convenience and are pulled into your theme when your website gets built.

Your website is now customized, live and looking good. You just have to publish your first blog post:
  
Edit `<em>/</em>posts/2014-3-3-Hello-World.md` deleting the placeholder content and entering your own. If you need a quick primer on writing in Markdown, check out [Adam Pritchard’s cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Change the file name to include today’s date and the title of your post. Jekyll requires posts to be named **year-month-day-title.md**.

Update the title at the top of the Markdown file. Those variables at the top of the blog post are called front matter. In this case, they specify which layout to use and the title of the blog post. Additional front-matter variables exist, such as permalink, tags and category.

If you’d like to create new blog posts in the browser on GitHub.com, simply hit the `+` icon in `/_posts/`. Just remember to format the file name correctly and to include the front-matter block so that the file gets processed by Jekyll.

![Jekyll Now](https://lh3.googleusercontent.com/-uzVIcwN_u50/VDwnIePaHCI/AAAAAAAAAM8/Po4l-TNrxKI/w771-h412-no/config.png)

## <span id="Using_a_custom_domain">Using a custom domain</span>

You can use your own domain name instead of **yourusername.github.io**. This [official guide](https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/) and this [stack overflow answer](http://stackoverflow.com/questions/9082499/custom-domain-for-github-project-pages) will guide you through the process of setting up your own domain.

This video will help do just that



Happy blogging!