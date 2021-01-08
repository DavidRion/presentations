#### Langage Statiquement typé 
* Type de chaque variable d’un programme est connu à la compilation. 
* C’est ce processus qui permet à l'IDE de péter une belle erreur rouge
  
![erreur compilation](https://user.oc-static.com/upload/2018/05/23/15270876304954_javaSnippet.png)<!-- .element height="50%" width="50%" -->

Type dynamique => inférence des types
```
val salaireBillyBruneau = 1000000000 
val message = "Hello Montreal !"
fun sayHello() = "Salut les geeks !"
```
<!-- .element: style="font-size:40%;" -->
|||
|--|--|
|Performance|Types connus à la compilation => pas besoin de les déduire à l’exécution|
|Fiabilité  |compilateur indique plus d’erreurs à la compilation, minimisant les crashs possible lors de l'exécution|
|Efficacité |Refactoring plus faciles + mise en place d’outils performants au sein de l’IDE comme "l’autocomplétion"|
<!-- .element: style="font-size:70%;" -->

#### Langage Fonctionnel
|||
|--|--|
|Firs-class Function|Fonctions en tant que valeurs|
|Immuabilité        |Variables immuables améliorentles performances et empache les soucis au multithreading|
|0 effet de bord    |Fonctions pures retournent toujours le même résultat et modifie ses variables internes|
<!-- .element: style="font-size:70%;" -->

#### Allez on met les mains dedans !
![ready](https://media0.giphy.com/media/CjmvTCZf2U3p09Cn0h/giphy.gif?cid=ecf05e472fcxxl9bdwijgptf53zi7g5t1n8oak2xtbrnv8lj&rid=giphy.gif)
