# demo2

### Configure the author name and email address to be used with your commits. Note that Git strips some characters (for example trailing periods) from user.name

```
git config --global user.name "David"
git config --global user.email david@manektech.com
```

> Create a new local repository git init


+ Check out a repository
+ Create a working copy of a local repository: git clone /path/to/repository
+ For a remote server, use: git clone username@host:/path/to/repository

##### For Add File in Commit

```
git add 
git add *
```

Follow me for **Bold**
Follow me for *Italic*
Follow me for ~~Strikethrough~~

+ Commit changes to head (but not yet to the remote repository):
```
git commit -m "Commit message"
```
or
```
git commit -am “Commit Message”
```


+ Commit any files you've added with git add, and also commit any files you've changed since then:
```
git commit -a
```

+ Send changes to the master branch of your remote repository:
```
git push origin master
```

