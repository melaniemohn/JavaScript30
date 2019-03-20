# JavaScript30
The code and assets in the initial commits are borrowed from Wes Bos's
[JavaScript30](https://github.com/wesbos/JavaScript30) repository, which are meant as
an accompaniment for [this delightful course](https://javascript30.com/).

Because I'm neurotic, I downloaded a compressed version of the repo (in lieu of cloning it) for
the sake of a clean commit history. I also cleaned up the names of any "starting point" files,
and I deleted the files containing solution code.

You can do the same with a quick and dirty bash script. (If you don't have the `rename` utility,
first do `brew install rename`)
```
$ rename -vS "-START" "" **/*
$ rm **/*-FINISHED*
```
