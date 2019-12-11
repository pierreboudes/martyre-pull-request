# projet-martyre-pull-request

Bonjour je suis root et je suis le seul à pouvoir éditer ce projet git. Vous pouvez le cloner mais pas commiter. Si vous voulez le modifier faites un :

```sh
git request-pull votrebranche https://lab.unif.app/votrelogin/projet-martyre-pull-request master
```

Bonjour, si ça peut aider voilà comment j'ai travaillé de façon à créer mon request-pull :
```sh
 git clone https://lab.unif.app/root/projet-martyre-pull-request.git
 cd projet-martyre-pull-request/
 git remote rm origin
 git remote add origin https://github.com/pierreboudes/martyre-pull-request.git
 git co -b mesmodifs
 # modifications du texte
 git add README.md
 git commit -m "mes modifications"
 git push
 git request-pull votrebranche https://lab.unif.app/root/projet-martyre-pull-request master
```
