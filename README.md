Tokyo Style
===

Tokyo Style is a single-column theme for Hugo. A minimalist, responsive, and open-source theme by [b4b4r07](http://b4b4r07.com). 

Ported from [Angel's Ladder](https://github.com/tanksuzuki/angels-ladder) for Hugo Theme.

blog demo: [tellme.tokyo](http://tellme.tokyo)

***DEMO:***

![](https://raw.githubusercontent.com/b4b4r07/screenshots/master/tokyo-style/demo.png)

# Installation

Installing this theme.

```console
$ mkdir themes
$ cd themes
$ git clone https://github.com/b4b4r07/tokyo-style tokyo
```

Build your website with this theme.

```console
$ hugo server -t tokyo
```

# Configuration

To take full advantage of the features in this theme, you can add variables to your site config file.

The following is the example configuration.

**config.toml**:

```toml
baseurl = "http://tellme.tokyo"
languageCode = "ja-jp"
title = "TELLME.TOKYO"
disqusShortname = "tellmetokyo"

[Params]
    subtitle = ""
    #facebook = ""
    twitter = "https://twitter.com/b4b4r07"
    github = "https://github.com/b4b4r07"
    website = "http://b4b4r07.com"
    profile = "/images/logo.jpg"
    copyright = "Written by b4b4r07"
    analytics = "UA-XXXXXXXX-X"
    google_font = "Lato:900"

    [Params.sharing]
        twitter = true
        hatebu  = true
        pocket  = false

[permalinks]
    post = "/post/:year/:month/:day/:filename/"

```

# Credits

Many thanks to [@tanksuzuki](http://github.com/tanksuzuki) for the [Angel's Ladder](https://github.com/tanksuzuki/angels-ladder) for Hugo theme.

# License

[MIT](https://raw.githubusercontent.com/b4b4r07/dotfiles/master/doc/LICENSE-MIT.txt) © BABAROT (a.k.a. b4b4r07)