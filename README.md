## Configuration Git
Pour configurer Git, il faut aller sur Source Control, ensuite Initialize Repository, et ça affichera une erreur: "Il manque user.name et user.email"

Dans ce cas, il faut aller sur le Terminal, en Powershell, avec ces commandes là:

```
git config user.name "exemple"
git confing user.email "mail"
```
## C'est quoi un commit?
Un commit est une sorte de versionnage, chaque commit a sa propre version, qui avance au fil du temps.
Je vais vous donner un exemple, V1 -> V2, ça versionne, et le commit est créé