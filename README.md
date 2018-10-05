# Introduction to NordicMath

This research group is primarily invite-based. If you really want to contribute, feel free to email torsteinv64@gmail.com.

## The various templates

### Article
Template for precisly stated articles in development and planning

### Exposition
Template for short expository papers

### Explore
Template for explorational projects perhaps without concrete papers in mind

## Tools

* Github with mathjax [https://chrome.google.com/webstore/detail/github-with-mathjax/ioemnmodlmafdkllaclgeombjnmnbima/related](https://chrome.google.com/webstore/detail/github-with-mathjax/ioemnmodlmafdkllaclgeombjnmnbima/related) 

* Download all repos: 
```
curl -s https://api.github.com/orgs/NordicMath/repos?per_page=200 | ruby -rubygems -e 'require "json"; JSON.load(STDIN.read).each { |repo| %x[git clone #{repo["html_url"]} ]}'
```

