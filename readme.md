
# Gravish lab website

Built using the [skeleton](http://www.getskeleton.com) css boilerplate and [hugo](http://www.hugo.com). Color scheme borrowed from the slack channel color scheme [base 16 eighties light](http://slackthemes.net/#/base16_eighties_light). Map constructed using [snazzy maps](https://snazzymaps.com/). Also using [academic icons](https://jpswalsh.github.io/academicons/). 

Using Hugo v0.17 to compile, needs an updated version because uses .Scratch variable to increment a counter. 

# Build instructions

Because I am always forgetting the build steps:

1. Git commit all changes 
2. Check on local system that page works accordingly using '''hugo server -w'''
3. Git merge to master (as necessary) 
4. Git push to github 
5. From terminal build static site while in base directory with '''hugo''' command
6. From terminal run sync shell command '''sync_lab_homepage.sh''' which uses rsync through ssh to update site

# License

The material in `/content/` & `/static/` is copyright, Nick Gravish. All rights reserved.

Layout and style files belong to their respective owners and are used in accordance with their licenses.

