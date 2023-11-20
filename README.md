# MorganBye.com
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

This is the source code for my [blog](https://morganbye.com). After years of fighting with CMSs and then having Wordpress constantly corrupt itself every month with automatic updates that I can't entirely turn off, it was time to just go back to basics and build a static site.


## Set-up
Assuming a Mac setup, install [Hugo](https://gohugo.io) with Brew:

```shell
brew install hugo
```

Then, clone this repository and build the website:

```shell
git clone --recurse-submodules https://github.com/morganbye/morganbye-com.git
cd morganbye
hugo server
```

The website will be running at [localhost:1313](http://localhost:1313).

## Deployment
```shell
hugo
```

All the static files are generated to a `public/` directory, that right now, I'm manually FTPing over to my webhost. I'll upgrade it an actual CD process shortly / when I find time.

## Contribute

If you find errors (typos, spelling, grammar, ...), mistakes in content, or just general suggestions for improvement, then I ask you to open an [issue](https://github.com/morganbye/morganbye-com/issues) on GitHub.
