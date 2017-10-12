
# Delete all local branchs (Without master)

```bash
 git branch | grep -v "master" | xargs git branch -D
```
