---
title: 'Github useful command '
date: 2024-08-18
permalink: /posts/2024/08/blog-post-1/
tags:
  - cool posts
  - category1
  - category2
---

Following flow are using basic **https** method to access/update github repository.

```
git --version
git clone https://github.com/<user>/<project>.git
git init
git config --global user.name <user defined name>
git config --global user.email <user email>
git config --global credential.helper store
git config --list

git remote -v
git remote add origin https://github.com/<user>/<project>.git
// system will ask you to input username and personal access token

git add README.md
git commit -m "First commit"

git push -u origin main
```
