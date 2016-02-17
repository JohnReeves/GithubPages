#Sign in to GitHub and Cloud9. 

##In GitHub look for the clone url:
![clone url](http://imgur.com/cqbr7xf.png)

##In Cloud9, enter the terminal (it should be at the bottom) and type:
```
git clone <clone url>
```
This should create a new folder with the name of your repository, in this case “MirrorMark”. 

###1. Move into this directory
```
cd MirrorMark
```

###2. Create a new gh-pages branch

```
git checkout –orphan gh-pages
```

###3. Remove all existing files
```
git rm –rf .
```

###4. Add some HTML files and commit them
```
git add –A
git commit –m “My first website!”
```

###5. Push to GitHub:
```
git push –u origin gh-pages
```

**You will need to enter your username and password.**

##Next time you want to add some more pages you can use Git add and commit again:
```
git add –A
git commit –m “Ch-ch-ch-changes!”
git push
```

**Your pages can be found at http://<username>.github.io/<repository>. In this case http://squiddev.github.io/MirrorMark/**
