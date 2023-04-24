---
layout: post
title: "Welcome to Jekyll!"
date: 2023-04-11 23:30:24 +0530
categories: jekyll update
---

## Jekyll

Jekyll is a static site generator that transforms plain text files (mostly written in Markdown) into websites or blogs. It's widely used with GitHub Pages to host websites directly from a GitHub repository. Here's a cheat sheet to help you get started with Jekyll:

### Installation and Setup

1. Install Ruby, RubyGems, and Jekyll:

   - On macOS:

     ```
     brew install ruby
     gem install jekyll bundler
     ```

   - On Ubuntu:

     ```
     sudo apt-get install ruby ruby-dev build-essential
     sudo gem install jekyll bundler
     ```

2. Create a new Jekyll site:

   ```
   jekyll new my-awesome-site
   cd my-awesome-site
   ```

3. Run the site locally:

   ```
   bundle exec jekyll serve
   ```

Visit http://localhost:4000 to view your site.

[jekyll-docs]: https://jekyllrb.com/docs/home
