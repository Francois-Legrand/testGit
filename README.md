# Titre 1
## Titre 2
### Titre 3

+ liste
+ liste2

### Code
```java
String toto = "Hello"
```

### Chemin
```/chemin/du/projet``` 

### séparation
---

### texte en gras
***gras***
### Italic
*italic*

### tableau
|nom|prenom|
|---|------|
|nom|prenom|

![alt text](image.png)

### Status fichier git
- untracked
- unmodified
- modified
- staged

### supprime de la zone de Staged et untracked
```git rm --cached```

### Stats des logs
- git log -1 --stat
### command log
- git log -5 --oneline

- git log--before="2021-04-11" --after="2021-05-11"

- git log --autor ""

- git log --oneline --graph

### revenir au commit du hashcode en supprimant les précedents (irreversible)
- git reset --hard leHashCode ou HEAD

### modifier le dernier commit
- git commit -m "modifé le texte du dernier commit" --amend

### voir qui a fait des modif 
- git blame lenomdufichier

### tag commit

- git tag nomDuTag hashtagDuCommit

- git tag nomDuTag -m "message du tag"

- git show nomDuTag

### branch git

- git branch
- git checkout branch
- git branch -d branch
- git checkout -b branch

### fusion merge

git merge branch


### git flow

git flow init

git flow feature start nomfeature

git flow feature finish nomfeature

git flow release start nomrealease

git flow release finish nomrealease

git flow hotfix start nomrealease

git flow hotfix finish nomrealease
