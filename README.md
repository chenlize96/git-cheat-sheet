# Git Cheat Sheet

<h2 id="table-of-contents">Contents</h2>
  <ol>
    <li><a href="#1"> Add Existing Project To Git Repo </a></li>
    <li><a href="#2"> Roll Back </a></li>
    <li><a href="#99"> Continue </a></li>
    <!--<li><a href="#handbook"> User handbook</a></li> -->
  </ol>
<br>

<h2 id="1"> 1. Add Existing Project To Git Repo</h2>

```
git remote rm origin
git remote add origin <new repo url>
git remote -v
git push origin *
```

<h2 id="2"> 2. Roll Back</h2>

```
Firstly, copy the full SHA
git reset --hard <SHA>
git push --set-upstream origin master --force
```




<h2 id="99"> 99. Continue</h2>
