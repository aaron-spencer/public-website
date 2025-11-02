# My Jekyll Website

This is my personal website built with Jekyll and hosted on GitHub Pages.

## Local Development

1. Install Ruby and Jekyll
2. Clone this repository
3. Run `bundle install`
4. Run `bundle exec jekyll serve`
5. Visit `http://localhost:4000`

## Deploying to GitHub Pages

1. Push this repository to GitHub
2. Go to Settings > Pages
3. Select your branch (usually `main`)
4. Your site will be live at `https://username.github.io/repo-name`

## Writing New Posts

Create a new file in `_posts/` with the format: `YYYY-MM-DD-title.md`

Add front matter at the top:
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0500
categories: your categories
---
```

Then write your content in Markdown below the front matter.
