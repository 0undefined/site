+++
title = "Hello world!"

#[taxonomies]
#tags = ["meta"]
+++

# About this site

This post serves as brief documentation for myself as well as a simple
explanation of how this site is set up. I don't update it too often, so I tend
to forget how, where, and why it works.

I try my best to update this page as my setup and release processes change over
time.

## How

I use [zola](https://www.getzola.org) to generate static HTML files from
markdown. Zola is a static site generator which -- in my opinion -- is very
ergonomic.

For development, I throw a quick `zola serve` and I'm ready to go.

## Where

The site is hosted on a VPS, served using nginx, so it really is as easy as
yeeting the files at the right `root`.

This is done using `rsync -r public/* nelin.dk:/var/www/nelin.dk`. We use `-r`
to copy the files `r`ecursively.

The source is currently a bit between places, as I've grown a dislike to how
GitHub (or rather, Micro$oft) runs their ship.

## Why

_TODO_
