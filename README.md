# My blog

This is the repository of my blog, powered by [Hugo](https://gohugo.io/) and themed by [Hugo-ht](https://github.com/hongtaoh/hugo-ht).

# For myself

When I update `themes/hugo-ht`:

```sh
cd themes/hugo-ht

git status
git add .
git commit -m "Update theme: your message"
git push origin master  

cd ../../

git add themes/hugo-ht
git commit -m "Update submodule pointer to latest theme commit"
git push origin main  
```