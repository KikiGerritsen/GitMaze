# GitMaze
## 4) New Branch!!!
  - We zitten nu in een nieuwe branch.
  - Maak een nieuwe file: 'test.md'
  - Ga terug naar je terminal en typ: ```git status```

``` shell
On branch feature/setup
Your branch is up-to-date with 'origin/feature/setup'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	test.md

nothing added to commit but untracked files present (use "git add" to track)
```

  - Je wilt deze file toevoegen aan je project.
  - ```git add . ```
  - ```git commit -m 'added test.md' ```
  - Open je folder. Als het goed is staan de volgende files in je folder: LICENCE, README.md en test.md
  - Ga naar je terminal: ```git checkout master```
  - Open je folder. Als het goed is staan de volgende files in je folder: LICENCE, README.md
  - De test file staat nog op de andere branch. Als je terug gaat naar de master branch zal het weer verschijnen in je folder.
