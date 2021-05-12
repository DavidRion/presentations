### Allez on passe au concret !
![ready_cat](https://media.giphy.com/media/CjmvTCZf2U3p09Cn0h/giphy.gif)


#### Relire son code avant de proposer une PR
* 🎯 Corriger ses erreurs d'inattention <!-- .element: class="fragment" -->
* 🎯 Vérifier que la synthaxe est respectée <!-- .element: class="fragment" -->
* 🎯 Vérifier code est lisible et formatté <!-- .element: class="fragment" -->
* 🎯 Code bien découpé pour maintenance et révision <!-- .element: class="fragment" -->
---
> Proposer code clair à réviser\
> ⬇️\
> Compréhension rapide des réviseurs\
> Temps de la revue plus court
<!-- .element: class="fragment" style="font-size:70%;" -->


##### Clean Code : Fonctions
1. Fonctions doivent être courtes : 20aine ligne maximum <!-- .element: class="fragment" style="font-size:70%;" -->
2. Blocs et indentation <!-- .element: class="fragment" style="font-size:70%;" -->
3. Faire une seule chose (Single Responsibility Principle) <!-- .element: class="fragment" style="font-size:70%;" -->
4. Nom des méthodes expriment ce que ca fait réellement <!-- .element: class="fragment" style="font-size:70%;" -->
5. Retirer code dupliqué et console.log <!-- .element: class="fragment" style="font-size:70%;" -->
6. Éviter les effets de bord <!-- .element: class="fragment" style="font-size:70%;" -->
7. Retirer code mort <!-- .element: class="fragment" style="font-size:70%;" -->


#### Conseil 
<img style="float: right;"  width="200" height="200" src="revue-code/assets/mr_net.png">

Proposer une Pull Request que quand le code peut être mis tel quel en PROD.<!-- .element: style="font-size:80%; color:orange" -->

Si ce n'est pas le cas, alors améliorer. <!-- .element: style="font-size:80%; color:orange" -->


#### Bienveillance 
* 🎯 Réviseurs prennent du temps pour réviser, donc répondre aux commentaires <!-- .element: class="fragment" -->
* 🎯 Proposer et remercier pour les propositions <!-- .element: class="fragment" -->
* 🎯 Mettre des liens pour bonnes pratiques <!-- .element: class="fragment" -->
* 🎯 Toujours commenter les PR (Jr & Sr): remarques, questions <!-- .element: class="fragment" -->
---
> Réviser et se faire réviser fait progresser


#### Conseil 
<img style="float: right;"  width="200" height="200" src="revue-code/assets/master_shifu.png">

La revue n'est pas une critique personnelle.<!-- .element: style="font-size:80%; color:orange" -->

L'objectif est d'avoir du code de qualité<!-- .element: style="font-size:80%; color:orange" -->

Si il y a incompréhension, ne pas hésiter à s'appeler ;)<!-- .element: style="font-size:80%; color:orange" -->


#### Privilégier les petites Pull Request 

| Grosse PR      | Petite PR   |
| -------------- | ----------- |
| ❌ Louper des erreurs                      | ✅ Révision facilité                                      |
| ❌ Focalisation sur forme plutôt que fond  | ✅ Courte donc claire et facile à comprendre              |
| ❌ Prend beaucoup de temps à réviser       | ✅ Valider petit à petit direction est prise              |
| ❌ Mauvaise direction et jeter travail à 🗑️ |✅ Plus de chance de passer ;)                            |
<!-- .element: style="font-size:60%;" -->
<img style="float: left;"  width="250" src="https://media.giphy.com/media/1JWbouY2SOSeQ/giphy.gif">
<img style="float: right;" width="250" src="https://media.giphy.com/media/RLW9YEaSBfBMt79fm4/giphy.gif">


#### Conseil 
<img style="float: right;"  width="200" height="200" src="revue-code/assets/ant_man.png">

Pousser son code dès qu'on a quelque chose de petit et stable pour montrer qu'on prend la bonne direction.<!-- .element: style="color:orange" -->


#### Single responsability 

* ❌ Mélanger plusieurs éléments dans la même PR <!-- .element: class="fragment" -->
* ✅ La PR ajoute/modifie une seule chose <!-- .element: class="fragment" -->
* ✅ Un seul concept abordé <!-- .element: class="fragment" -->
--- 
<!-- .element: class="fragment" -->
> Vos réviseurs vous remercieront pour cette attention <3
<!-- .element: class="fragment" -->


#### Conseil 
<img style="float: right;"  width="200" height="200" src="revue-code/assets/spiderman.png">

Faire autant de Pull Request que de sujets abordés.<!-- .element: style="color:orange" -->

Les branches sur Git sont vos amies ;)<!-- .element: style="color:orange" -->


#### Expliciter le nom des commits et des PR
* ❌ Fix, Feature, Aucun contexte
* ❌ Commits : fix, tests, caca, code de P$#fwno
* ✅ Titre PR explicite pour connaitre contexte de ce qu'on révise
* ✅ Titre : Numéro JIRA + descriptif rapide
* ✅ Description PR : Contexte des ajouts/changements
* ✅ Commit : numéro JIRA + descriptif
* ✅ Squasher ses commits (regrouper)


#### Conseil 
<img style="float: right;"  width="200" height="200" src="revue-code/assets/spiderman.png">

Clarté, Clarté, Clarté.<!-- .element: style="color:orange" -->