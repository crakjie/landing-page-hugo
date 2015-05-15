# Landing Page Theme for Hugo

[Hugo](http://gohugo.io) theme based on the
[landing-page theme for Jekyll](https://github.com/swcool/landing-page-theme)

# How to use

## About Section

Create a markdown file named `content/services/about/about.md`

```txt
---
Title: About Us
Draft: false
---

WidgetCo is the world leader in widget production.
```

## Services Section

Create a markdown file describing a service you offer in `content/services/` - e.g. `content/services/widgets.md`.

```txt
---
Title: Widget Making
Img: widgets.png
Category: Services
Draft: false
---

We make widgets!
```

Then place a matching image in `static/img/services/` - e.g. `static/img/services/widgets.png`


## Demo
View this equivalent jekyll theme in action [here](https://swcool.github.io/landing-page-theme)

## Screenshot
![screenshot](https://raw.githubusercontent.com/swcool/landing-page-theme/master/img/screenshot.png)

===

Work also with TOML header

For more Hugo details, read [documentation](http://jekyllrb.com/).
This Jekyll theme used [Freelancer Jekyll theme](https://github.com/jeromelachaud/freelancer-theme/) as reference.


exemple of config.toml file
```
baseurl = "http://yourSiteHere"
languageCode = "fr-fr"
title = "my new web site"
[params]
  description = "I <3 making web site"

[[params.social]]
    title = "email"
    icon = "envelope-o"
    url = "mailto:bushbama@whitehouse.gov"
[[params.social]]
    title = "twitter"
    icon = "twitter"
    url = "https://twitter.com/SBootstrap"
[[params.social]]
    title = "github"
    icon = "github"
    url = "https://github.com/IronSummitMedia/startbootstrap"
[[params.social]]
    title = "linkedin"
    icon = "linkedin"
    url = ""
```
