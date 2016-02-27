## About

Hugo theme based on [Start Bootstrap Clean Blog](http://startbootstrap.com/template-overviews/clean-blog/).

![Screenshot](https://raw.githubusercontent.com/jamesacampbell/fiddler/master/images/screenshot.png)

## Setup

### As is

You can use the site as is, it will work. You can for example use it with [HugoBasicExample](https://github.com/spf13/HugoBasicExample).

#### full features

If you want to have all the features and pages of the original theme, you will need a similar *config.toml*:

``` toml
baseurl = "https://www.jamescampbell.us"
title = "Causes & Effects"
canonifyurls = true
paginate = 10
theme = "fiddler"
languageCode = "en-us"
copyright = "Code released under the Apache 2.0 license."

[author]
  name = "James Campbell"
    
[params]
  DateForm = "Mon, Jan 2, 2006"
  Description = "Pushing Buttons Since 1981"
  Author = "James Campbell"
  email = "james@jamescampbell.us"
  Ganalytics = "XX-00000000-0"
              
[[params.social]]
  title = "twitter"
  url = "https://twitter.com/jamescampbell"
[[params.social]]
  title = "github"
  url = "https://github.com/jamesacampbell"
[[params.social]]
  title = "facebook"
  url = "https://www.facebook.com/FACEBOOKHANDLE"
                                      
[[menu.main]]
  name = "home"
  url = "/"
  weight = -200
[[menu.main]]
  name = "Archives"
  url = "/post/"
  weight = -180
```
                                                  
You can find a [Demo site](http://humboldtux.github.io/sbcb-demo/), and have a look at the source on the
[repo site](https://github.com/humboldtux/sbcb-demo) for configuration parameters.

### Custom

You can have a look at my [personal website](https://www.jamescampbell.us), where i customize it and use it in a different way than the original theme.

