# Middleman Loaded

Middleman loaded with good stuff and configured to kill

## Requirements

* Ruby & Bundler

## Get Started

Install Gems

```
bundle install --path=vendor
```

Run Middleman

```
middleman
```

# What's it Loaded With?

## Middleman Configuration

* Gems for middle-man console, live reload and handling for fav icons
* Configured for markdown nested in html (.html.md.erb files)
* Better organization of /assets
* Sample pages with markdown & bourbon bitters styles

## CSS & JS Libraries

Wired up through sprockets & sass

| Package           | Description                                  |
| ----------------- | -------------------------------------------- |
| jquery            | The Write Less, Do More, JavaScript Library  |
| bourbon           | A Sass Mixin Library                         |
| neat              | Grid framework for Sass and Bourbon          |
| magnific-popup    | Lightbox: responsive, customizable & fast    |
| royalslider       | Slideshow: responsive, customizable & fast   |
| jquery-waypoints  | Scroll position links                        |
| fastclick         | Remove 300ms mobile delay                    |
| fitvids           | Responsive videos                            |
| mfglabs-iconset   | Awesome web font icon                        |


## SASS Mixins

Mixins from [Josh Fry's Broilerplate](https://github.com/joshfry/assemble-bp)

| Package           | Description                                  |
| ----------------- | -------------------------------------------- |
| buttons           |   |
| containers        |   |
| hide-text         |   |
| list-of-links     |   |
| module            |   |
| omega-reset       |   |
| padding           |   |
| rounded-corners   |   |
| trailing-hovers   |   |
| triangle          |   |


# TODO

Look Broilerplate lists.scss

* .ul-reset removes list styles and default is with bullets
* Unless <nav> is the parent of a <ul>; Then list styles are removed

A few other useful list classes

* .list-of-links makes anchors inside list items more clickable
* And .list-of-links-horiz is self explanatory

