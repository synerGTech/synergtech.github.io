# synergtech.github.io
![SynerG Tech Party](https://cloud.githubusercontent.com/assets/1687568/18940459/027c5614-8626-11e6-95fc-8fef60eee9ca.png "synerG Tech Party")

##contributing
The blog uses pelican for generating static html files.
- Install pelican
```sudo apt-get install python-pip```
```pip install pelican markdown```
- Clone this repo
The master branch of this repo contains the files that will be visible on synergtech.github.io. The contents branch contains all other filres, including the directory structure that you wan't to generate files for output folder. follow along.
```git clone --recursive -b content git@github.com:synerGTech/synergtech.github.io.git```
- Add a blog post
A blog post in pelican is nothing but a simple markdown file in contents folder, from which pelican generates output html files.
```
vim contents/new-blog-post.md
[comment]: <> (metadata)
Title: hello world! 
Date: 2016-09-29
Authors: author1[,author2]
Summary: New blog post
[comment]: <> (blog post's content)
This is a new blog post.

:wq
```
-Generate html files
```
make html
make publish
```

-Commit changes to github
```
git add -A .
git commit -m "added a new blog post"
git push origin content

cd output
git add -A .
git commit -m "added a new blog post"
git push origin master
```

Yes, there are two commits.

If you are not added as a contributor to this repo, then fork the repo first, clone your version of it, in a similar way as above. Make changes, and push the changes to your copy of
the repo. Send a pull request.
