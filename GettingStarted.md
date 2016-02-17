#Sign in to GitHub and Cloud9. 

##In GitHub look for the clone url:

##In Cloud9, enter the terminal (it should be at the bottom) and type:
```
git clone <clone url>
```

This should create a new folder with the name of your repository, in this case “MirrorMark”. You will want to move into this directory:
```
cd MirrorMark
```

##You will then need to create a new gh-pages branch:
```
git checkout –orphan gh-pages
```

##And remove all existing files:
```
git rm –rf .
```

##Then you will want to add some HTML files and commit them:
```
git add –A
git commit –m “My first website!”
```

##And then push it to GitHub:
```
git push –u origin gh-pages
```

*You will need to enter your username and password.*

##Next time you want to add some more pages you can use Git add and commit again:
```
git add –A
git commit –m “Ch-ch-ch-changes!”
git push
```

**Your pages can be found at http://<username>.github.io/<repository>. In this case http://squiddev.github.io/MirrorMark/**
