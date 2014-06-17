## FoundationJekyll

This is a Jekyll template using the SASS version of Foundation 5. You can use this as your starting point for creating a site with or without a blog using the powerful Jekyll static site generator and the Zurb Foundation framework. Contributions to this project are welcome. Feel free to fork, copy or share this.

## Requirements

You will need to have the following installed:

* Ruby 1.9+
* Git
* NodeJS
* Jekyll ruby gem
* Compass ruby gem

I've written guides on setting up Foundation and Jekyll:

[http://eric-price.co/blog/foundation-plus-sass/](http://eric-price.co/blog/foundation-plus-sass/)

[http://eric-price.co/blog/jekyll-osx/](http://eric-price.co/blog/jekyll-osx/)

Official Jekyll documentation:

[http://jekyllrb.com/docs/installation/](http://jekyllrb.com/docs/installation/)

Foundation SASS documentation:

[http://foundation.zurb.com/docs/sass.html](http://foundation.zurb.com/docs/sass.html)

## Folder/File Structure


* ```_config.yml```: Jekyll configuration file
* ```_includes```: Stores Jekyll partial files
* ```_layouts```: Stores Jekyll page layouts
* ```_posts```: Stores Jekyll blog posts written in Markdown
* ```_site```: Working site generated from Jekyll
* ```bower_components```: Foundation assets
* ```js```: Foundation javascipt
* ```config.rb```: Compass config file
* ```scss```: Foundation SASS stylesheets
* ```stylesheets```: Compiled stylesheets
* ```tags```: Blog tag pages. Each tag requires its own page


## Quickstart
#### Grab Project

```
git clone https://github.com/eric2025/FoundationJekyll.git
cd FoundationJekyll
```
#### Compile SASS (monitor for changes and auto-compile)
````
compass watch
````
#### Compile Jekyll site (monitor for changes and regenerate)
````
jekyll serve --baseurl '' --watch
````
You can run both compass and jekyll at the same time in seperate terminals to auto compile your changes. Depending how you host your Jekyll page, you may need to adjust or remove the "baseurl" option in "\_config.yml". For example, if you host your page for your main GitHub page either your own domain or ```http://username.github.io```, you should remove the "baseurl" option and the baseurl tags in the pages. If you are hosting a project page (```http://username.github.io/projectname```), you need to configure the "baseurl" option to your project name. See the documentation here: [http://jekyllrb.com/docs/github-pages/](http://jekyllrb.com/docs/github-pages/)

## Demo

[http://eric2025.github.io/FoundationJekyll](http://eric2025.github.io/FoundationJekyll)






