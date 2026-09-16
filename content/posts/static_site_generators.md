+++
title = 'Static Site Generators'
date = 2024-05-11T14:58:37+08:00
draft = false
summary = '...'
+++

# Static Site Generators

+ [Static Site Generators - Top Open Source SSGs | Jamstack](https://jamstack.org/generators/)

## 1. Hugo

+ [Hugo](https://gohugo.io/)
  + [Hugo Documentation](https://gohugo.io/documentation/)
    + [Installation](https://gohugo.io/installation/)
    + [Quick start](https://gohugo.io/getting-started/quick-start/)
    + [Host on GitHub Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
  + [Hugo Themes](https://themes.gohugo.io/)
    + [Github Style](https://themes.gohugo.io/themes/github-style/)

```zsh
## Prerequisites
## Install Git
## System built-in: /usr/bin/git

## Install Hugo on macOS.
brew install hugo

## Create a site
which hugo
## Verify that you have installed Hugo v0.112.0 or later.
hugo version
## Create the directory structure for your project.
hugo new site lyzenghq.github.io
## Change the current directory to the root of your project.
cd lyzenghq.github.io
## Initialize an empty Git repository in the current directory.
git init
git add .
git status
git commit -m 'Init.'
## Clone a theme into the themes directory, adding it to your project as a Git submodule.
git submodule add git@github.com:MeiK2333/github-style.git themes/github-style
## Update the site configuration file.
vim hugo.toml
## Add a new page to your site.
hugo new README.md
## Start Hugo’s development server to view the site.
hugo server
## Press Ctrl + C to stop Hugo’s development server.
```
