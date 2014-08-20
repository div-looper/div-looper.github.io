---
layout: post
title:  "[WIP] How to create a blog with Jekyll & Github (like this one)"
date:   2014-08-22 19:00:00
categories: How-to
---
I Fed up with all blogging system, too much work to personalize your blog, you have to keep your eye open for new security updates. I want something simple and minimalistic.
That's why I decide to move back to the Stone Age and create my static weblog :)

I'm just kidding :) but still who the hell want a daynamic website that content change once in a while??

## Github Pages
Github has two types of [Pages](https://pages.github.com), User/Organization Pages and Project Pages.
User & Organization Pages give you `$username.github.io` subdomain but the Project pages give you `$username.github.io/$repository`

So, what I'm going here to cover is how to create a blog/site on the free static hosting for User & Organization on Github Pages.

To get started you need to [create](https://github.com/new) a new repository and name it as `$username.github.io`, for example my username on github is `khal3d`, so I'm going to create a new repository and call it `khal3d.github.io`

Now, pull this repo on your computer and add your first "hello, world" to `index.html`, add, commit, and push it.
Wait a few seconds and than open your browser and type `$username.github.io` .. Thant's it, you publish your first "Hello, World" on github Pages.

Let's dig deep here before moving to the next step &hellip;

What if I want a different subdomain than my username? here you have to [create organization account](https://github.com/organizations/new) *(no need to logout)* and call it what every you want the subdomain, in my case I created an organization called `div-looper` to be able to get the subdomain `div-looper.github.io`  and than created a reposotory called `div-looper.github.io` under this organization

That's it.


## Jekyll
[Jekyll](http://Jekyllrb.com) is a static site/blog generator

Open your terminal to execute the following command to install Jekyll

    gem install jekyll

## Custom Domain
Now, let's say you willing to spend $10/year on your blog, that's a great news, go and get your won domain, and in next fee lines I will tell you how to configure your domain to work with your free Github hosting :)
