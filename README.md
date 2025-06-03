# My blog

This is the repository of my blog, powered by [Hugo](https://gohugo.io/) and themed by [Hugo-ht](https://github.com/hongtaoh/hugo-ht).

# For myself

When I update `themes/hugo-ht`:

```sh
# STEP 1: go into the submodule (theme folder)
cd themes/hugo-ht

# STEP 2: check status & commit your changes to the theme repo
git status
git add .
git commit -m "Update theme: your message"
git push origin main  # or master, depending on your branch

# STEP 3: go back to your demo repo
cd ../../

# STEP 4: update the submodule pointer in the demo repo
git add themes/hugo-ht
git commit -m "Update submodule pointer to latest theme commit"
git push origin main  # (or your demo repo branch)
```