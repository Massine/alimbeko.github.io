---
layout: post
title: "Blogs made easy: Make your own static blog"
tags: [blog, jekyll, kymyz]
description: Short guide on how to start a similar blog
last_updated: 01/15/2015
---

## About Blogs ##

This blog is hosted by [GitHub Pages](https://pages.github.com/). The link provides an easy step by step instructions on how to set up a simple website

GitHub Pages use [Jekyll](http://jekyllrb.com/) to process markdown and textile files and format them into HTML. It allows for fast, reliable, simple and static blogs. Jekyll can be installed on your computer through Ruby and you can build the site locally before publishing it on Github. 

If you are like me and don't want to develop everything from scratch, a number of templates exist, which can be easily integrated on your website.

1. First check out [all these blogs that already use Jekyll](https://github.com/jekyll/jekyll/wiki/sites) and clone the GitHub repo of the blog you like.
2. Now just delete the old content (e.g. `_posts/old-posts`, `images/`, etc) and modify the `index.html`, `_config.yml`, HTML files in `/layout` , and other files which might be relevant with your personal info.
3. Add your own posts in `_posts` folder as markdown files. All posts should follow a specific **file name convention** and include **YAML Front Matter** at the top of the file according to Jekyll. For more information [check out this guide](http://jekyllrb.com/docs/posts/).  
	4. File name example: `2015-01-15-about-blog-and-pub-workflow.md`
	5. Front Matter example: 
`---`    
`layout: post`
`title: "This blog's DIY & FAQ"`
`tags: [blog, jekyll, kymyz]`
` description: Short guide on how to start a similar blog`
` last_updated: 01/15/2015 `
`---`
6. Once you complete all the modifications, push the repo to your own repository on GitHub. To do that you need to clone your website repo and replace all contents (except `.git` hidden folder!) of the cloned repo with the files from template repo you just modified. Commit and push the new files to your GitHub repo and you are golden!

Jekyll is very flexible and there are many extensions based on this framework. You can experiment and try different tools by yourself. If you run into problems, make sure to checkout [Jekyll's website](http://jekyllrb.com/), [stackOverflow](http://stackoverflow.com/) and other resources for help. 

### If you need Google Search in China, but don't have VPN, use AOL Search. It's powered by Google. ###

## Markdown editor ##

By now you hopefully already can set up your own GitHub based blog. Now to post things, you most likely will use Markdown format. There are many editors available, which support Markdown. For XLP we let participants use GitBook's desktop editor, which in a nutshell is a Markdown editor with few extra options. It's good for writing structured documents, which require a table of contents, but for blogs I suggest using simpler tools. There are many online markdown editors and I found them very convenient to use. You can just use Google (or AOL) to search and choose the one you like. I am writing this article using [StackEdit.io](https://stackedit.io/), and so far I am loving it.
Other editors:

 -  [dillinger.io](dillinger.io),
 -  [markable.in](markable.in), 
 - [www.ctrlshift.net/project/markdowneditor/](www.ctrlshift.net/project/markdowneditor/)




