---
layout: post
title: 12 July 2020
---
## TL;DR:
* Can use Git Pages + React together

## In tech:
* https://dev.to/yuribenjamin/how-to-deploy-react-app-in-github-pages-2a1f
* Since I already have the Jekyll page going in the background, had to do some extra fiddling to get it to work.
** https://typoes.github.io/typoes-react was showing a 404 from the Jekyll site
* Went into [settings](https://github.com/typoes/typoes-react/settings) and set the _source_ under GitHub Pages from "gh-pages" to "master"
** That switched it from showing the 404 to typoes-react's README, which is closer (accessing the right repo) but still not what I wanted
** Then, switched it back from "master" to "gh-pages" AND re-deployed using `npm run deploy`

