# Peter Hamilton Portfolio Jekyll Website

Jekyll website adapted from the [Freelancer theme](https://github.com/jeromelachaud/freelancer-theme), [commit 1c765c1](https://github.com/jeromelachaud/freelancer-theme/commit/1c765c107d063b9f1bb18d23c1eff046f5d8c442)

## Dependencies

- Ruby 2.7.2
    - Windows: using [Ruby Installer](https://rubyinstaller.org/downloads/)


## Install

Run:

```
gem install bundler
bundle install
```

All gem dependencies should be contained `github-pages` gem ([versions](https://pages.github.com/versions/)). The latest version should be used. To update run:

```bundle update github-pages```

## Test

- To run locally, comment out `baseurl` and `url` lines in `_config.yml`
- Run: `bundle exec jekyll serve --livereload`
  - If there is a load error, try ```bundle add webrick```

## Deploy to Github Pages

- Copy contents to host repo and push

## Configure

### About

To make the about section easier to edit/format, the content is stored in `_includes/about_1.md` (first column) and `_includes/about_2.md` (first column).

### Theme

Parameters for the theme can be changed in `_data/theme.yml`.

### Google Analytics

To enable set `google_tracking_id` in `_config.yml`. Tracking script is located in `_include/js.html`.

### Favicon

Favicon was generated using [Android Icon Generator](https://romannurik.github.io/AndroidAssetStudio/icons-launcher.html#foreground.type=text&foreground.text.text=P&foreground.text.font=Roboto&foreground.space.trim=1&foreground.space.pad=0&foreColor=rgb(255%2C%20255%2C%20255)&backColor=rgb(63%2C%2081%2C%20181)&crop=0&backgroundShape=square&effects=elevate&name=ic_launcher)