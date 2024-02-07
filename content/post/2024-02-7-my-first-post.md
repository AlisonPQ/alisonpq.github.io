---
title: My First Post
date: 2024-02-07T12:40:46-03:00
draft: false
---

One day at a meeting with friends, while we were eating hamburgers and drinking beer, we were talking about technology (it doesn't always happen but it happens haha), so with the music and the little time you can't explain more than the very essential nature of a certain topic, one of those times, I met a girl who asked me how to learn design patterns, she told me that she tried to study them but  it was complicated, I tried to explain one to her, in a few minutes I wanted to address the topic because in a certain way, I like to see the world object-oriented and explain a topic in a easy way haha...she asked me if I had any kind of post, I didn't have a post but I had a old a Power Point presentation haha

This event reminded me that I always wanted a blog, I like to share knwoledge about what I have learnt for some reason I feel useful lol.

As first post, here..., I was planning this blog, I wanted to develop this one with React (yeah, becasuse I have skills related to it) buuut I din't wanna spent too much time on bolg development because I think on a blog the most important things are the posts, right?

I researched how to do a blog based to Markdown, as result, I found [Hugo](https://gohugo.io/), this is a framework to generate pages easily, tecnically is a static site generator. 

I made changes to theme that I liked then I deployed it with github actions on GitHub Pages and this post is **fresh out of the oven**.

### Steps

#### Install Hugo

Review [Hugo's documentation](https://gohugo.io/installation/) due to your Operative System

#### Choose a theme

When you have chosen a [theme](https://themes.gohugo.io/), generally you should run a command like this: 

```
git submodule add https://github.com/theNewDynamic/<theme>.git themes/<theme>
```
Note: Review your favorite theme documentation to add the submodule.

#### Set configurations

Each configuration you need is on `hugo.toml` file.

#### Deploy with GitHub Pages

In your project you should create a file called `hugo.yaml` which is on `.github/workflows/hugo.yaml` where are all the steps that you need to deplot it, you will need to push everything on `main` branch, make sure to select `GitHub Actions` as `Source` on **settings>pages**.

Once your project is pushed into GitHub, you can see your workflow in actions section.

You can take a look my [blog repository](https://github.com/AlisonPQ/blog)

#### Some useful links:

- [Hugo](https://gohugo.io/)
- Choose a [theme](https://themes.gohugo.io/)
- Deploy with [Github actions](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
