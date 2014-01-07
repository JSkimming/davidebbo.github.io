---
layout: post
title:  "Moving to GitHub pages"
comments: true
categories: blogging
---

For the past few years, I've had my blog hosted on blogger, and for the most part, I hated it. While Windows Live Writer was helping make the autoring experience bearable, in the end there was no getting away from the fact that I hate HTML!

On the other hand, I *really* like Markdown, so I knew I had to move to a system that let me just use that directly. Still, when I asked on Twitter, people threw all kind of interesting options at me, and I had to make a choice. In the end, I went with Jekyll / GitHub pages, so I'll use this post to discuss the thought process.

## Some other options I looked at

### Ghost

Using [Ghost](https://ghost.org/) was really tempting. It's new and shiny, it has a clean interface, and it has a very nice browser hosted Markdown editor.

But then I realized something else: I also hate databases. And I *really* like files :)

So I just didn't want to deal with a system where my posts ended up somewhere in a database. So that was that.

### Orchard

[Orchard](http://www.orchardproject.net/) also has nice [Markdown support](http://www.davidhayden.me/blog/orchard-1.3-features-markdown-support-for-pages-blog-posts-and-content-authoring), which looked like an option.

But for the same reason as Ghost, I didn't want to use it.


### Sandra.Snow

Several folks suggested that I look at [Sandra.Snow](https://github.com/Sandra/Sandra.Snow), which is a .NET based system inspired by Jekyll.

Being a .NET guy, it was tempting of using something based on Ruby/Python. But this came with a big catch: if I used it with GitHub pages, I would need to locally generate the HTML, and then commit that to my repo. And the very thought og committing generated files to a repository makes me sad. So that was that.