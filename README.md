My Personal Web Page, built with [Hugo](https://gohugo.io/)

See the rendered version at https://magrella.github.io/portfolio/


File Update
===========

Update using local copy on ~\OneDrive\Data Science or download from Github


Preview local version

*comment out lines on config.TOML file* to preview in the browser at //localhost:1313/ (Kill with ctrl-C)

`baseURL = "https://magrella.github.io/portfolio"`, line 2

`canonifyURLs = true`, line 15



Building
========

Update Files and re-point server to Github repo:

*Un-comment out lines on config.TOML file*

`baseURL = "https://magrella.github.io/portfolio"`, line 2

`canonifyURLs = true`, line 15


Generate public files using Windows Powershell:
     `.\hugo -D`


Publish
========

Commit or copy ALL files to main branch

~OneDrive\Data Science\exampleSite\public

