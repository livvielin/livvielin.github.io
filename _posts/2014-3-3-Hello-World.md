---
layout: post
title: Start a Blog with Jekyll and GitHub Pages
---

In starting this blog, one of the first questions I considered was which blogging platform I would use.  My initial top choice was WordPress, but in the end I decided to go with Jekyll and GitHub Pages.  If you&#39;re familiar with GitHub, Jekyll is a great blogging platform that provides simplicity and speed.

##### Content Management System (CMS) or Static Website
WordPress and other similar platforms are Content Management Systems (CMS) that use databases to store content.  Content Management Systems are very powerful applications, but if you only need a static site, like I did for my blog, CMS dynamic code and database calls can unnecessarily slow down loading time.

On the other hand, Jekyll is a static blog generator that compiles all files into static HTML before publication and has no database, which is great for loading speed.  Essentially, Jekyll is a minimalist platform, with the bonus of free GitHub Pages hosting.  If you don&#39;t need the added complexity of a dynamic blog, Jekyll is a solid choice.

If you need some help deciding whether a CMS or static website is right for you, check out <a href="http://www.dmgbluegill.com/blog/content-management-system-cms-or-static-website-which-right-you" target="_blank">this article</a>.

##### Quickstart Guide to Jekyll
1. Fork an existing Jekyll template.  I used <a href="https://github.com/barryclark/jekyll-now" target="_blank">Jekyll Now</a> to start, but you can find some other great themes 
<a href="https://github.com/jekyll/jekyll/wiki/Themes" target="_blank">here</a>.
1. Click the Settings button on your forked repository and change the repository name to ```yourusername.github.io```, replacing "yourusername" with your GitHub handle.  Your website should go live within a couple minutes and be accessible from ```http://yourusername.github.io```.
1. Edit the _config.yml file and save the changes to your repository.  There are two main ways to edit the blog and publish the changes:
  * Clone the repository onto your local machine, edit the file, and commit and push the changes to GitHub.
  * Make changes to the file in the browser at GitHub.com by clicking on the file in your repository and clicking the pencil icon to edit.  Edit the file and commit the changes.
![alt text]({{ site.baseurl }}/images/githubEdit.png)
1. Edit the about.md file to change the content on the About page.

##### Writing a Blog Post in Jekyll

Blog posts are generally written in Markdown.  A great reference is this <a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet" target="_blank">Markdown Cheatsheet</a>.

<a href="http://jekyllrb.com/docs/frontmatter/" target="_blank">Front Matter</a>

```gem install```

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.