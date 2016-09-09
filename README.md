# GitMaze
## 1) Installeer Git
  - Check of Git al geinstalleerd is:
      - Open je terminal/commandline
      - ```git --version```
      - Als je terminal een versie terug geeft (```git version 2.7.4...```) staat git al geinstalleerd op je apparaat.
  - Git niet geinstalleerd? 
      - https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

## 2) Clone de repository
  - Maak een folder op een gewenste locatie
  - Open je terminal hier of route met je terminal naar deze folder toe
  - ```git clone https://link```
  - Check in je folder of er een folder in staat: 'GitMaze'.
  - Ga met je terminal naar deze folder toe: ```cd GitMaze```

## 3) Switching branches
  - Check in welke branch je bent: ```git status```

```{r, engine='bash', count_lines} 
On branch master
Your branch is up-to-date with 'origin/master'
nothing to commit, working directory clean
```
  - ```git fetch```
  - ```git checkout feature/setup```

```{r, engine='bash', count_lines}
Branch feature/setup set up to track remote branch feature/setup from origin.
Switched to a new branch 'feature/setup'
```
  -```git branch```<br/>
  
```* feature/setup```<br/>
```master ```<br/>



