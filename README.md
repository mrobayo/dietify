
# Dietify

Diet Planner. Week diet meals planner.


## Update dependencies

Updating gin-gonic to latest

###GO GET 
Get downloads the packages named by the import paths, along with their dependencies. It then installs the named packages,like 'go install'.

```bash

  $ go get -u github.com/mattn/go-isatty
  $ go get -u github.com/gin-gonic/gin
```

## Git Settings

```bash

  $ git clone https://github.com/heroku/go-getting-started.git
  $ mv go-getting-started dietify

  $ cd dietify
    
  $ git remote remove origin
  $ git remote add origin github.com/mrobayo/dietify
  $ git remote -v

  
  $ git add .
  $ git commit -m "init app"

  $ git push -u origin master


```

## Reset local files (Be Careful: all changes will be lost)

```bash
  $ git fetch --all
  $ git reset --hard origin/master
```


## Deploy Local

```bash
  $ go build -o bin/dietify.exe
  $ heroku local
```

## Documentation

Feedback is welcome. Please, contact me.

## References

[http://rogerdudler.github.io/git-guide/index.es.html]
