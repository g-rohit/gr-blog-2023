---
author: "G Rohit"
title: "First Post: How I made this blog site"
date: "2023-10-05"
summary: "So what tech stack this blog is using and how I set this up"
tags: ["blog", "hugo"]
categories: ['fast']
draft: false
---


# How I Made This Blog Site

So I was searching for something minimalistic, lightweight, and, more importantly, fast.

A couple of years ago, when I was helping my friend set up his blog, I went through a lot of various websites and themes and shortlisted a few of them. After experimenting with different options, I finally decided to use the Hugo static site generator for its simplicity and speed.

## Choosing the Right Theme

One of the most critical aspects of setting up a blog is choosing the right theme. After much consideration, I settled on the PaperMod theme for Hugo. PaperMod is known for its clean design, excellent performance, and ease of customization, which makes it a great choice for anyone looking to create a modern, minimalistic blog.

## Customizing the Theme

While the default PaperMod theme was already quite good, I wanted to give my blog a unique touch. I heavily customized the colors, look, and feel of the theme to match my personal style and preferences. This involved tweaking the CSS and modifying some of the theme's templates to achieve the desired appearance.

## Tech Stack Overview

Here's a brief overview of the tech stack I used to build this blog site:

- **Hugo**: Hugo is a powerful static site generator written in Go. It is incredibly fast and allows for flexible content management, making it ideal for creating a blog.
- **PaperMod Theme**: A versatile and customizable theme for Hugo, which provides a clean and modern look.
- **Markdown**: All the content is written in Markdown, which Hugo converts into static HTML pages.
- **Netlify**: For continuous deployment and hosting. Netlify makes it easy to deploy Hugo sites and provides a free tier with generous limits.
- **GitHub**: Version control and collaboration. I use GitHub to manage my blog's source code and keep track of changes.
- **VS Code**: My preferred code editor for writing Markdown and customizing the theme.

## Setting Up the Blog

Setting up the blog was straightforward:

1. **Install Hugo**: Follow the [official installation guide](https://gohugo.io/getting-started/installing/) to get Hugo up and running on your system.
2. **Create a New Site**: Use the command `hugo new site my-blog` to create a new Hugo site.
3. **Add the PaperMod Theme**: Clone the PaperMod theme into your themes directory and configure it by following the instructions in the theme's [documentation](https://github.com/adityatelange/hugo-PaperMod).
4. **Customize the Theme**: Modify the theme's CSS and templates to match your desired look and feel.
5. **Write Content**: Create new posts and pages using Markdown. Hugo will handle the conversion to HTML.
6. **Deploy**: Push your site to GitHub and configure Netlify to automatically build and deploy your site whenever you make changes.

---

Creating this blog site was a rewarding experience. Hugo and the PaperMod theme provided a solid foundation, while the customizations allowed me to make the site truly my own. The end result is a fast, lightweight, and aesthetically pleasing blog that I can easily update and maintain.

If you're considering starting your own blog, I highly recommend giving Hugo and PaperMod a try. With a bit of customization, you can create a site that perfectly fits your needs.
