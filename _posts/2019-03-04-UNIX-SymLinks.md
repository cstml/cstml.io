---
layout: post
title: "Unix Symlinks"
---

# Symlinks

Good article on the subject can be found at:
[link](https://medium.com/@meghamohan/hard-link-and-symbolic-link-3cad74e5b5dc)

## Hardlink
A hardlink is much like a pointer to the same information, which in this case it is called inode. 
```
ln <source> <source>
```

## Symlink
A symlink is much more like a classical shortcut. 
In order to create a symlink all you need to do is: 
```
ln -s <source> <linkname>
```
