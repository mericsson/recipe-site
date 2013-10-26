recipe-site
===========
Generic recipe site built in jekyll

jekyll version 1.2.1
http://jekyllrb.com

## Install and Run
- gem install jekyll
- jekyll serve
- go to http://localhost:4000

## Making changes
When editing any template file (e.g. markdown .md files) you need to restart jekyll server to see updates.
# Adding recipes
- For each new recipe, you need to create a new folder (e.g. Butter-Cream) and an index.md file inside it.
- To link to another recipe (e.g. Butter-Cream) within another recipe, you would do:
'''
[Butter Cream](../Butter-Cream)
'''
-- Unfortunately the syntax is not as clean as a wiki would be.
