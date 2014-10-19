# Landing Page Hugo theme

Hugo theme based on [landing-page theme ](https://github.com/swcool/landing-page-theme)

## How to use
 - Place a image in `static/img/`
 - Create posts to display your services. Use the follow as an example:

```txt
---
layout: default
img: ipad.png
category: Services
title: The service title
description: The description of the service
---
```

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
    title = "twitter"
    url = "https://twitter.com/SBootstrap"
[[params.social]]
    title = "github"
    url = "https://github.com/IronSummitMedia/startbootstrap"
[[params.social]]
    title = "linkedin"
    url = ""
```
