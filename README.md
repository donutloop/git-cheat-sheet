
# Delete all local branchs (Without master)

```bash
 git branch | grep -v "master" | xargs git branch -D
```

# Generate simple changelog for tag range

```bash
git log v2.1.0...v2.1.1 --pretty=format:'* [%s](http://github.com/jerel/<project>/commit/%H"' 
```
