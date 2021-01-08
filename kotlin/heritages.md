### Héritage
![heritage meme](https://memegenerator.net/img/instances/78386950.jpg)

#### Java
* Heritage : redéfinir méthodes avec `override` sauf si `final` <!-- .element: class="fragment" -->
* Extends : classes et méthodes ouvertes par défaut<!-- .element: class="fragment" -->
    
Pratique mais parfois problématique : un 😈 méchant dev 😈 peut redéfinir méthode classe parente avec un comportement inattendue.<!-- .element: class="fragment" -->

#### Kotlin
En kotlin, toutes les classes sont ...
  
fermées par défaut (final en Java)<!-- .element: class="fragment" -->
  
👉 Demande explicite de l'autorisation à un developpeur de rajouter <!-- .element: class="fragment" -->
`open`<!-- .element: class="fragment" -->

#### Un exemple en Java
```
public class Personne {
    public void travailler(){
        // ... Code ... 
    }
  
    public void boire(){
        // ... Code ... 
    }
}
```
<!-- .element: style="font-size:40%;" -->
  
```
public class Developpeur extends {
    @Override
    public void travailler(){
        // ... ajout comportement ... 
    }
  
    @Override
    public void boire(){
        super.boire();
        // ... ajout comportement ... 
    }
}
```
<!-- .element: style="font-size:40%;" -->

#### En kotlin : pas de open = final
![erreur heritage](kotlin/assets/open_heritage.png)

#### Modificateurs d'accès
|Attribut | Classe/Méthode/Propriété |
|--|--|
|final    | ne peut pas être redéfinie. (Defaut)
|open     | peut être redéfinie. (doit être indiqué explicitement)
|abstract | doit être redéfinie. (peut être utilisé uniquement dans des classes abstraites)
|override | Redéfinir un élément d’une classe parente (ou d’une interface).|

#### Retour sur les constructeurs secondaires
![second multiples](kotlin/assets/second_constructeur.png)
  
<3 Interopérabilité entre classe parente Java possédant plusieurs constructeurs, et classe enfant Kotlin

Mais on a plus élégant...avec une approche évolutive
![constructeurs multiples](kotlin/assets/autres_constructeur.png)

#### data class pour modèles de données
|||
|--|--|
|Afficher contenu | toString()
|Comparer objets  | equals()
|Dupliquer        | copy() ou clone()
|hashCode         | ... |
  
> En Java, obligation de les redéfinir<!-- .element: class="fragment" -->
> 
> En Kotlin, 'data' class<!-- .element: class="fragment" -->
<!-- .element: class="fragment" -->

#### data class exemples
![data class](kotlin/assets/data_class.png)

#### companion objects : Adieu les static !
// TODO
