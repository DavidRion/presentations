### Allez on passe au concret !
![ready_cat](https://media.giphy.com/media/CjmvTCZf2U3p09Cn0h/giphy.gif)


#### Relire son code avant de proposer une PR
* 🎯 Corriger ses erreurs d'inattention <!-- .element: class="fragment" -->
* 🎯 Vérifier que la synthaxe est respectée <!-- .element: class="fragment" -->
* 🎯 Vérifier code est lisible et formatté <!-- .element: class="fragment" -->
* 🎯 Code bien découpé pour maintenance et révision <!-- .element: class="fragment" -->
> Code clair -> compréhension rapide -> revue courte
<!-- .element: class="fragment" style="font-size:70%;" -->


##### Clean Code : Fonctions
| On aime        | On évite   |
| -------------- | ----------- |
| 🎯 Fonctions courtes : 20+ lignes max      | ❌ Complexité (nested if)             |
| 🎯 Blocs et indentation                    | ❌ Magic numbers                      |
| 🎯 Single Responsibility Principle         | ❌ Nommage ambigüe                    |
| 🎯 DRY - Do Not Repeat Yourself            | ❌ Code pas indenté                   |
| 🎯 Nommage significatif selon comportement | ❌ Code mort, dupliqué et console.log |
<!-- .element: style="font-size:70%;" -->


#### Exemple Complexité
![complexite](https://miro.medium.com/max/1400/1*scf22B_mqWuQhUonDI6TXA.png) <!-- .element height="60%" width="60%" -->


#### Exemple Magic numbers
![magic_number](https://miro.medium.com/max/1400/1*gi8iv6LYvdgRQ0veYtsxJQ.png)


#### Exemple Nommage Ambigüe
![nommage_ambigue](https://miro.medium.com/max/1400/1*69VzxUJxl3xy4jJc70HPlw.png)


#### Exemple DRY
![DRY](https://miro.medium.com/max/1400/1*z2PjUl_CgXyIh2KScg0Lzg.png) <!-- .element height="70%" width="70%" -->


#### Exemple Synthaxe
![synthaxe](https://miro.medium.com/max/1400/1*qvsZvhCby-oGpDn5QqWsyg.png) <!-- .element height="70%" width="70%" -->


#### Exemple Retours
![retours](https://miro.medium.com/max/1400/1*8lwNVd1GbTIbnMUrg8DZ5g.png) <!-- .element height="70%" width="70%" -->


#### Conseil 
<img style="float: right;"  width="200" height="200" src="/revue-code/assets/mr_net.png">

Proposer une Pull Request que quand le code peut être mis tel quel en PROD.<!-- .element: style="font-size:80%; color:orange" -->

Si ce n'est pas le cas, alors améliorer. <!-- .element: style="font-size:80%; color:orange" -->


#### Bienveillance : Réviser et se faire réviser fait progresser
* 🎯 Réviseurs prennent du temps, donc répondre aux commentaires <!-- .element: style="font-size:70%;" class="fragment" -->
* 🎯 Proposer et remercier pour les propositions <!-- .element: style="font-size:70%;" class="fragment" -->
* 🎯 Mettre des liens pour bonnes pratiques <!-- .element: style="font-size:70%;" class="fragment" -->
* 🎯 Toujours commenter les PR (Jr & Sr): remarques, questions <!-- .element: style="font-size:70%;" class="fragment" -->
* 🎯 Ouverte 2 jours maximum <!-- .element: style="font-size:70%;" class="fragment" -->
> Revues et Réponses rapides éxigées !
<!-- .element: style="font-size:90%;" class="fragment" -->


#### Reconnaissance fait du bien au Moral
![compliment1](/revue-code/assets/compliment3.PNG) <!-- .element height="70%" width="70%" -->
![compliment2](/revue-code/assets/compliment.PNG) <!-- .element height="70%" width="70%" -->
![compliment3](/revue-code/assets/compliment2.PNG) <!-- .element height="70%" width="70%" -->


#### Questions et Réponses
![question](/revue-code/assets/questions.PNG) <!-- .element height="70%" width="70%" -->
![reponse](/revue-code/assets/repondre.PNG) <!-- .element height="70%" width="70%" -->


#### Conseil 
<img style="float: right;"  width="200" height="200" src="/revue-code/assets/master_shifu.png">

La revue n'est pas une critique personnelle.<!-- .element: style="font-size:80%; color:orange" -->

L'objectif est d'avoir du code de qualité<!-- .element: style="font-size:80%; color:orange" -->

Si il y a incompréhension, ne pas hésiter à s'appeler ;)<!-- .element: style="font-size:80%; color:orange" -->


#### Privilégier les petites Pull Request 

| Grosse PR      | Petite PR   |
| -------------- | ----------- |
| ❌ Louper des erreurs                      | ✅ Révision facilitée et + de chance de passer ;)         |
| ❌ Focaliser sur forme plutôt que fond     | ✅ Courte donc claire et facile à comprendre              |
| ❌ Prend beaucoup de temps à réviser       | ✅ Valider petit à petit direction est prise              |
| ❌ Mauvaise direction & jeter travail à 🗑️ | ✅ Présenter du code *** NPF ***                          |
<!-- .element: style="font-size:60%;" -->
<img style="float: left;"  width="250" src="https://media.giphy.com/media/1JWbouY2SOSeQ/giphy.gif"> <!-- .element: class="fragment" -->
<img style="float: right;" width="250" src="https://media.giphy.com/media/RLW9YEaSBfBMt79fm4/giphy.gif"> <!-- .element: class="fragment" -->


#### Conseil 
<img style="float: right;"  width="200" height="200" src="/revue-code/assets/ant_man.png">

Pousser son code dès qu'on a quelque chose de petit et stable pour montrer qu'on prend la bonne direction.<!-- .element: style="color:orange" -->


#### Single responsability 
* ❌ Mélanger plusieurs éléments dans la même PR <!-- .element: class="fragment" -->
* ✅ La PR ajoute/modifie une seule chose <!-- .element: class="fragment" -->
* ✅ Un seul concept abordé <!-- .element: class="fragment" -->
> Vos réviseurs vous remercieront pour cette attention <3
<!-- .element: class="fragment" -->


#### Single Responsability
![single_responsability](/revue-code/assets/single_responsability.PNG) <!-- .element height="70%" width="70%" -->
![single_responsability_ko](/revue-code/assets/single_responsability_ko.PNG) <!-- .element height="70%" width="70%" -->


#### Conseil 
<img style="float: right;"  width="200" height="200" src="/revue-code/assets/spiderman.png">

Faire autant de Pull Request que de sujets abordés.<!-- .element: style="color:orange" -->

Les branches sur Git sont vos amies ;)<!-- .element: style="color:orange" -->


#### Expliciter le nom des commits et des PR
* ❌ Fix, Feature, Aucun contexte <!-- .element: class="fragment" style="font-size:70%;" -->
* ❌ Commits : fix, tests, caca, code de P$#fw*o <!-- .element: class="fragment" style="font-size:70%;" -->
* ✅ Titre PR explicite pour connaitre contexte de ce qu'on révise <!-- .element: class="fragment" style="font-size:70%;" -->
* ✅ Titre : Numéro JIRA + descriptif rapide <!-- .element: class="fragment" style="font-size:70%;" -->
* ✅ Description PR : Contexte des ajouts/changements <!-- .element: class="fragment" style="font-size:70%;" -->
* ✅ Commit : numéro JIRA + descriptif <!-- .element: class="fragment" style="font-size:70%;" -->
* ✅ Squasher ses commits (regrouper) <!-- .element: class="fragment" style="font-size:70%;" -->


#### Demo Squash Intellij IDEA
![intellij](/revue-code/assets/intellij.png)


#### Conseil 
<img style="float: right;"  width="200" height="200" src="/revue-code/assets/spiderman.png">

Clarté, Clarté, Clarté.<!-- .element: style="color:orange" -->


#### Respect des standards qualité
* 🎯 Clean code <!-- .element: class="fragment" style="font-size:80%;" -->
* 🎯 1 fonction = 1+ tests <!-- .element: class="fragment" style="font-size:80%;" -->
* 🎯 Qualité : TDD + Mockito + H2 + WebMvcTest & MockMvc<!-- .element: class="fragment" style="font-size:80%;" -->
* 🎯 Tests paramétrés couvrant toutes les conditions <!-- .element: class="fragment" style="font-size:80%;" -->
> Soyez responsable.\
>\
> La relecture de votre code ne vous dédouane pas de sa qualité, vous en êtes toujours responsable
<!-- .element: class="fragment" style="font-size:80%;" -->


#### TDD & Test paramétré Typescript
![intellij](/revue-code/assets/typescript_test_parametre.PNG)


#### TDD & Test paramétré Java
![intellij](/revue-code/assets/java_test_parametre.PNG)


#### Test Controleur
![intellij](/revue-code/assets/webmvctest_kotlin.PNG)


#### Test Mockito
![intellij](/revue-code/assets/mockito_kotlin.PNG)