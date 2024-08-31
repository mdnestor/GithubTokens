How to use GitHub token to push to GitHub from a local repository:

```
git remote remove origin # if already have 
git remote add origin https://{TOKEN}@github.com/{OWNER}/{REPO}
git push
```
