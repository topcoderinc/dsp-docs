---
layout: post
title:  "Libraries"
date:   2016-11-19 19:41:45 +0700 19:41:45 +0700
categories: post
---


# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

[Title](URL)
**Bold** or __Bold__
*Italics* or _Italics_
Line space between paragraphs
> Quote
`alert('Hello World');`
---
`code`
![alt](http://)
[^1]: This is my first footnote
[^n]: Visit http://milanaryal.com
[^n]: A final footnote

This paragraph contains a list of items.

* Item 1
* Item 2
  - Sub item
* Item three

The application structure presented in this boilerplate is **fractal**, where functionality is grouped primarily by feature rather than file type. Please note, however, that this structure is only meant to serve as a guide, it is by no means prescriptive. That said, it aims to represent generally accepted guidelines and patterns for building scalable applications. If you wish to read more about this pattern, please check out this [awesome writeup](https://github.com/davezuko/react-redux-starter-kit/wiki/Fractal-Project-Structure) by [Justin Greenberg](https://github.com/justingreenberg).


```
.
├── bin                      # Build/Start scripts
├── build                    # All build-related configuration
│   └── webpack              # Environment-specific configuration files for webpack
├── config                   # Project configuration settings
├── server                   # Express application that provides webpack middleware
│   └── main.js              # Server application entry point
├── src                      # Application source code
│   ├── index.html           # Main HTML page container for app
│   ├── main.js              # Application bootstrap and rendering
│   ├── components           # Global Reusable Presentational Components
│   ├── containers           # Global Reusable Container Components
│   ├── layouts              # Components that dictate major page structure
│   │   └── CoreLayout.js    # CoreLayout which receives children for each route
│   │   └── CoreLayout.scss  # Styles related to the CoreLayout
│   │   └── index.js         # Main file for layout
│   ├── routes               # Main route definitions and async split points
│   │   ├── index.js         # Bootstrap main application routes with store
│   │   ├── Home             # Fractal route
│   │   │   ├── index.js     # Route definitions and async split points
│   │   │   ├── assets       # Assets required to render components
│   │   │   ├── components   # Presentational React Components
│   │   │   └── routes **    # Fractal sub-routes (** optional)
│   │   └── Counter          # Fractal route
│   │       ├── index.js     # Counter route definition
│   │       ├── container    # Connect components to actions and store
│   │       ├── modules      # Collections of reducers/constants/actions
│   │       └── routes **    # Fractal sub-routes (** optional)
│   ├── static               # Static assets (not imported anywhere in source code)
│   ├── store                # Redux-specific pieces
│   │   ├── createStore.js   # Create and instrument redux store
│   │   └── reducers.js      # Reducer registry and injection
│   └── styles               # Application-wide styles (generally settings)
└── tests                    # Unit tests
```

<div class="bs-callout bs-callout-danger">
This is my
<strong>danger</strong>
type callout. It has a border on the left whose color you define by passing a type parameter.
</div>

<div class="bs-callout bs-callout-default">
This is my
<strong>default</strong>
type callout. It has a border on the left whose color you define by passing a type parameter.
</div>

<div class="bs-callout bs-callout-primary">
This is my
<strong>primary</strong>
type callout. It has a border on the left whose color you define by passing a type parameter.
</div>

<div class="bs-callout bs-callout-success">
This is my
<strong>success</strong>
type callout. It has a border on the left whose color you define by passing a type parameter.
</div>

<div class="bs-callout bs-callout-info">
This is my
<strong>info</strong>
type callout. It has a border on the left whose color you define by passing a type parameter.
</div>

<div class="bs-callout bs-callout-warning">
This is my
<strong>warning</strong>
type callout. It has a border on the left whose color you define by passing a type parameter.
</div>

<span class="label label-default">Default</span>
<span class="label label-primary">Primary</span>
<span class="label label-success">Success</span>
<span class="label label-info">Info</span>
<span class="label label-warning">Warning</span>
<span class="label label-danger">Danger</span>

<div class="alert alert-info" role="alert">
<i class="fa fa-info-circle"></i>
<b>Note:</b>
This is my note.
</div>
<div class="alert alert-success" role="alert">
<i class="fa fa-check-square-o"></i>
<b>Tip:</b>
This is my tip.
</div>
<div class="alert alert-danger" role="alert">
<i class="fa fa-exclamation-circle"></i>
<b>Warning:</b>
This is my warning.
</div>
<div class="alert alert-warning" role="alert">
<i class="fa fa-warning"></i>
<b>Important:</b>
This is my important info.
</div>

| Priority apples | Second priority | Third priority |
|-------|--------|---------|
| ambrosia | gala | red delicious |
| pink lady | jazz | macintosh |
| honeycrisp | granny smith | fuji |


You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight javascript %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
