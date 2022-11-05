---
title: Create a new post
date: 2022-09-08 02:55:39
tags: Hexo
---

## Create a Hexo post
- Environment: Windows, cmd

``` bash
# cmd
$ hexo new "My New Post"
```

A new markdown file (.md) will be created at the folder **source\_posts\My-New-Post.md**


## Run server locally
``` bash
# cmd
$ hexo server
```

The server runs at the port 4000 by default. Use web driver to view the webpage with url **http://127.0.0.1:4000/**.

## Generate static files
``` bash
# cmd
$ hexo generate
```

This step is just like git add and git commit on the local side.

## Deploy the local data to GitHub
``` bash
# cmd
$ hexo deploy
```

This step is just like git push, which will push the committed local data to GitHub.
After `hexo deploy`, sometimes the cache data will exist for a while so that the global webpage (https://<github accout>.github.io) may maintain the same appearance until the cache expires. 