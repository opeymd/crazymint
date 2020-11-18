---
layout: category_index
title: Tech
permalink: /tech/
category_name: tech
---



![2020-07-04-337824.png](https://opeymd.github.io/crazymint/assets/2020-07-04-337824.png)
A simple and elegant theme for Jekyll and GitHub Pages.

### Features:
* Mobile-first design ensures this theme performs fastest on mobile while scaling elegantly to desktop-size screens.
* Designed for blogs and sites heavy on written content, with bold typography styles, homepage summaries, and previous/next snippets.
* Supports a wide range of HTML elements and markdown.
* Flexible styles that can be reused for customization without adding additional CSS.
* Dynamically generated navigation links. See docs below for adding pages with specific post category for-loops.

## Themes
This theme comes in two color variations. The default is set to the `light` theme. To change the theme color, add `theme_color:` to your `config.yml` file with the color you wish to use. Example: `theme_color: dark`.

<!-- | Config setting | Thumbnail |
| --- | --- |
| `theme_color: black` | <img width="330" alt="black" src="url"> |
| `theme_color: red` | <img width="330" alt="red" src="url"> | -->


## Installation

Add this line to your Jekyll site's Gemfile:

```ruby
gem "jekyll-athena"
```

And add this line to your Jekyll site `config.yml`:

```yaml
theme: jekyll-athena
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-athena

<!--

Set the front matter:
title = your page title and link name in the navigation
permalink = the url for the page, i.e. example.com/my-awesome-category
category_name = the name of the cateogry you want to use to group posts, you'll need to use the same name on post pages

Save this page in the root directory.
Use the same name for the filename as the permalink, i.e.

permalink: /my-awesome-category/
filename: my-awesome-category.html

-->
