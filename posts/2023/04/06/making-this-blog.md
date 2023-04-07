---
title: making this blog
description: how i made this blog
date: 2023-04-06
scheduled: 2023-04-06
layout: layouts/post.njk
---

Obivously my first *real* blog post should be how I made this blog which can be [found here on github](https://github.com/kataqatsi/kataqatsi_blog).

So first of all what are the requirements?
1. I want to be able to write in markdown
2. I want it hosted for free
3. I want it to be __blazingly fast__

Sounds like I could use a static site generator and throw it on a cdn like netlify or something.. but lets see where a few minutes of research will take me.

Okay.. so looks like [this project](https://github.com/google/eleventy-high-performance-blog) has a perfect score on lighthouse and would make a perfect base to start from.

![blog stats](../../../../img/blog_stats.png)

Just a few modifications here and there to the formatting to include the profile on the right seen on the right --->

Maybe change some colors.

<span style="color:yellow">color</span> -> <span style="color:orange">color</span>




Now for deploying.. looks like it comes baked with a deploy to vercel button... close enough to netlify.


[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fgoogle%2Feleventy-high-performance-blog)

Just connect the domain name on vercel

[kataqatsi-blog.vercel.app](https://kataqatsi-blog.vercel.app) -> [kataqatsi.com](https://kataqatsi.com)

and voila!

Pretty easy to set up, free, and highly performant.

And you can even add an <a href="https://github.com/kataqatsi/kataqatsi_blog/edit/main/./posts/2023/04/06/hello-world.md">Edit on GitHub</a> link so readers can help edit!

Feel free to throw it a star on [github](https://github.com/kataqatsi/kataqatsi_blog).