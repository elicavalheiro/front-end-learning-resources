### How can I contribute?

Open an [Issue](https://github.com/elicavalheiro/front-end-learning-resources/issues/new/choose) with the links you want to share, I will add it when possible. If you'd like to create a Pull Request, please follow the instructions below.

### Fork & create a branch

With the Issue created, [fork front-end-learning-resources](https://github.com/elicavalheiro/front-end-learning-resources) and create a branch with the issue number.

A good branch name would be (example with issue number 213):

```sh
git switch -c 213-add-new-resources
```

### Make a Pull Request

At this point, you should switch back to your main branch and make sure it's up to date with front-end-learning-resources branch:

```sh
git remote add upstream git@github.com:elicavalheiro/front-end-learning-resources.git
git switch main
git pull upstream main
```

Them update your feature branch from your local copy of main, and push it!

```sh
git checkout 213-add-new-resources
git rebase main
git push --set-upstream origin 213-add-new-resources
```

Finally, go to GitHub and [make a Pull Request](https://github.com/elicavalheiro/front-end-learning-resources/pulls) :D