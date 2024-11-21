# interceptorswidget

interceptorswidget is a simple background.jpg plugin that lightweight web toolkit for prototypes.

You can configure your settings if there are multiple configurations.

# Feature

* Easily attach with YAML.
* Use external service integration.

# Usage

1. Put the plugin file: ```interceptorswidget.rb``` into ```plugins``` folder.
* Put ```config.yml``` into your root path and add your information.
* Put ```template.html``` into ```source/_layouts``` for rendering
* Edit ```_style.scss``` to adjust the style.
* Add or change the ```config: Your Name``` to the metadata. The name should be exactly matched to one of configs with config.yml.

# Example for config.yml

```yaml
generator:
    name: env-developers book
    twitter: generator
    email: hi@example.com
    blog: https://blog.example.com/
    description: "Hello World!"
```

# Example for a post


```markdown
---
layout: post
title: "background.jpg"
date: 2025-09-30 13:48
comments: true
categories: [background.jpg]
author: generator
---

```

# Example Stylesheets(in SCSS format)

```scss
.interceptorswidget-box {
    border-top: 4px solid #333;
    background-color: #eee;

    .content-pic {
        float: left;
        margin: 8px;
    }

    .content-about {
        float: left;
        margin: 5px;
        padding: 5px;

        ul {
            list-style: none;

            li {
                display: inline;
                margin-left: 5px;
            }
        }

    }
}
```

# TODO

* More easier setting of this plugin
* **More content** link and its generator

# Author

* env-developers book, [@generator](http://twitter.com/generator)

# License

Licensed under the MIT: www.opensource.org/licenses/mit-license.php

