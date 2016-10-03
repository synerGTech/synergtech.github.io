# synergtech.github.io
![SynerG Tech Party](https://cloud.githubusercontent.com/assets/1687568/18940459/027c5614-8626-11e6-95fc-8fef60eee9ca.png "synerG Tech Party")

##Contributing
The blog uses pelican for generating static html files.


###A. Install pelican

```sudo apt-get install python-pip```

```pip install pelican markdown```

###B. Clone this repo

The master branch of this repo contains the files that will be visible on synergtech.github.io. The contents branch contains all other filres, including the directory structure that you wan't to generate files for output folder. follow along.

```git clone --recursive -b content git@github.com:synerGTech/synergtech.github.io.git```

###C. Add a blog post

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

###D. Generate html files

```
make html
make publish
```

###E. Commit changes to github

```
git add -A .
git commit -m "added a new blog post"
git push origin content

cd output
git add -A .
git commit -m "added a new blog post"
```

If you encounter a detached head, do the following. Check with ```git status```.

```
git branch temp
git checkout master
git merge temp
```

Push the changes.

```
git push origin master
```

If you are not added as a contributor to this repo, then fork the repo first, clone your version of it, in a similar way as above. Make changes, and push the changes to your copy of
the repo. Send a pull request.
