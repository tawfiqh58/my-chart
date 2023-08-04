# My Helm Repo

This is my first helm public github repository

---

## Create a helm chart web server

Create a github pages to serve your charts  
by simply creating

- `gh-pages` branch
- add only artifacts to that branch
- push it to github

Github will automatically treat it as github pages

Goto: https://tawfiqh58.github.io/my-chart/my-repo

---

## Add repository

```shell
helm repo add express-server https://tawfiqh58.github.io/my-chart/my-repo/
```

## Install chart

```shell
helm install my-my-chart express-server/my-chart --version 0.1.0
```
