# Willow Ghost Theme 3.0

Personal, responsive, minimalist and open-source theme for Ghost blogging platform.
Lightweight - only 2.9KB of CSS and 820B of JavaScript. No jQuery, vanilla JS only.
Version 2.0 comes with SASS in BEM style using ITCSS (http://itcss.io/) architecture.

![Willow Ghost Theme](http://i.imgur.com/a8WfkoS.png)

## Theme Demo

This theme is currently being used on my personal blog - [https://raivis.com/](https://raivis.com/).

## Compiling SASS & Minifying JavaScript

Requires Grunt task runner & NPM to be installed.

    $ cd content/themes/[theme-folder]
    $ npm install
    $ grunt

## Editing Social Links and Promo Links

Edit the `content/themes/[theme-folder]/partials/sidebar.hbs` file.

## Enabling Disqus (https://disqus.com/) Comments

1. Edit the `content/themes/[theme-folder]/post.hbs` file, uncomment "comments" partial
block inclusion: turn `<!--{{> "comments"}}-->` into `{{> "comments"}}`.

2. Replace Disqus embed code with your site code - https://disqus.com/admin/universalcode/
