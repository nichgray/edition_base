## Jekyll Version

Built with Jekyll 3.9.0

note: as of this publication, this is the latest version of Jekyll that 
will work natively with GitHub Pages
see here: for up to date details: https://pages.github.com/versions/

If you need to look up documentation, the current docs on jekyllrb.com will not always work since they are for a newer version. Looking for the page you need at the 3.9.0 release tag may help https://github.com/jekyll/jekyll/tree/v3.9.0/docs

## Config file

The config file is meant for settings that affect your whole blog, values
which you are expected to set up once and rarely edit after that. If you find
yourself editing this file very often, consider using Jekyll's data files
feature for the data you need to update frequently.

For technical reasons, this file is *NOT* reloaded automatically when you use
'bundle exec jekyll serve'. If you change this file, please restart the server process.

If you need help with YAML syntax, here are some quick references for you: 
https://learn-the-web.algonquindesign.ca/topics/markdown-yaml-cheat-sheet/#yaml
 https://learnxinyminutes.com/docs/yaml/

### Site settings
These are used to personalize your new site. If you look in the HTML files,
you will see them accessed via {{ site.title }}, {{ site.email }}, and so on.
You can create any custom variable you would like, and they will be accessible
in the templates via {{ site.myvariable }}.

## Theme

The Recovery Hub base theme is based off "Minima", a Jekyll theme for writers. The base theme adds additional styling and guidance for creating text based editions, as well as some useful starter templates for things like pagination and tables of contents. 

## Preparing files

All markdown files must have either a # header at the top of the document (because GitHub Pages using jekyll-optional-front-matter as a dependency 5 https://github.com/benbalter/jekyll-optional-front-matter), or must declare a title: in the frontmatter. 

Files that don't do one of these things will be not be processed - that is, they won't be transformed into HTML or included in any of the listings, but they will be passed through as is

