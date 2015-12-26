## Jekyll Boilerplate

![unmaintained](http://img.shields.io/badge/status-unmaintained-red.png)

A jekyll starting point. Based on [Jekyll Base](https://github.com/danielmcgraw/Jekyll-Base)
by Daniel McGraw.

### Structure

```
.
├── _includes
├── _layouts
│   ├── default.html
│   └── post.html
├── _posts
│   └── 1970-01-01-placeholder-post.md
├── .gitignore
├── README.md
├── _config.yml
└── index.html
```

### _config.yml

This is where you will be putting your Jekyll configuration options. If this
file is omitted Jekyll will use its defualts to build your site. You can find
the configuration options and default configuration
[here](https://github.com/mojombo/jekyll/wiki/configuration).

### _layouts

This folder is where all the layout templates are stored.

#### default.html

This is the base layout template. There are no naming conventions, but if you
choose to change this file's name make sure you update all the layout
references in your file's YAML Front Matter blocks. To learn more about the use
of YAML Front Matter check out [this
page](https://github.com/mojombo/jekyll/wiki/yaml-front-matter).

#### post.html

This is the base post template.

### _posts

This folder is where all the posts are stored. Notice the naming convention
that is used. You will want to name your files with the the publish date
preceeding the posts title all seperated by dashes
(Year-Month-Day-Title-Of-The-Post.md). The post date that you see is pulled
straight from this filename so make sure you lable your files right.

#### 1970-01-01-placeholder-post.md

This is a simple blog post using markdown. To learn more about markdown check
out the [markdown syntax
documentation](http://daringfireball.net/projects/markdown/syntax). Also notice
that there is YAML Front Matter in this file specifying the layout it will use
and the title of the post. Layout is one of a couple predefined global
variables. You can also specify custom variables in the YAML Front Matter.

### index.html

This is used to render the site's index. It is essntially a post loop wrapped
in your base layout.
