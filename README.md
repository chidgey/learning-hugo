# Learning Hugo - Static site generation written in GoLang
See this site in action at: https://chidgey-learning-hugo.netlify.com

## What is static site generation?
By generating static content as part of the build process, we can eliminate many of the issues with dynamic websites
and lead to improved performance, security and ease of use.

This has many benefits. The most noticeable is performance. HTTP servers are very good at sending files—so good, in fact, that you can effectively serve the same number of pages with a fraction of the memory and CPU needed for a dynamic site.

## What is Hugo?
Hugo is just one example of a static website generator, it uses GoLang for templates and will render content into HTML files so these can be cached by a CDN - this whole process of parsing and creating HTML files is blazingly quick.
 say that Hugo is a static site generator.

 ## Cloning this repo
Themes are registered as sub-modules, so as their content changes this repo will use the latest versions.

To pull down a repo with the sub-modules included, use:

git clone --recurse-submodules git@github.com:chidgey/learning-hugo.git

 ### Adding new themes

To add a new sub-module theme, adapt the following example:

git submodule add https://github.com/themefisher/meghna-hugo themes/meghna-hug to pull in new themes

_It's important that you don't add these sub-modules to the commit!_
