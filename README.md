git-website-workflow
====================

a script that creates a git-capable website workflow ala http://goo.gl/0L3E6

### What's in here

* creates both a project folder and its hub
* adds .htaccess to .git folder to deny http access
* creates hooks in both repos
* creates README.md and .gitignore
* does an initial commit to initialize everything

### Usage

Own that sucker.

``` shell
chmod u+x mkproject
```

then execute that sucker.

``` shell
./mkproject
```
or

``` shell
bash mkproject
```

you could also add it to your path so you don't have to do either of these, just run it like any other command.

I use this for projects hosted on Amazon EC2. This workflow allows you to clone the repo locally to your computer and then push it back and have it update the live site.

Check out http://goo.gl/0L3E6 for an explaination and more.