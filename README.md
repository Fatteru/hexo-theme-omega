# Omega

Theme for Hexo.  Based on Hexo default light theme.

## Install

Execute the following command and modify `theme` in `_config.yml` to `omega`.

```
git clone https://github.com/Fatteru/hexo-theme-omega.git
```

## Update

Execute the following command to update Omega.

```
cd themes/omega
git pull
```

## Config

Default config:

``` yaml
menu:
  Home: /
  Archives: /archives

excerpt_link: Read More

addthis:
  enable: true
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true

facebook:
google_plus:
twitter:
github:

fancybox: true
google_analytics:
rss:
```

- **menu** - Main navigation menu
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **facebook** - facebook username
- **google_plus** - google_plus username
- **twitter** - twitter username
- **github** - github username
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)