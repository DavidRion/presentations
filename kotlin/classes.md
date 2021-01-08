### Classes et Heritages
![classe](https://media1.tenor.com/images/de72888724f6b92bba3dc9371e48f0df/tenor.gif?itemid=10171637)

#### Java
```
public Class Personne {
    private String nom;
    private String prenom;
    private String courriel;
  
    public Personne(String nom, String prenom, String courriel) {
        this.nom = nom;
        this.prenom = prenom;
        this.courriel = courriel;
    }
  
    public String getNom(){ return nom; }
    public String getPrenom(){ return prenom; }
    public String getCourriel(){ return courriel; }
  
    public void setNom(String nom){ this.nom = nom; }
    public void setPrenom(String prenom){ this.prenom = prenom; }
    public void setCourriel(int courriel){ this.courriel = courriel; }
}
```
<!-- .element: style="font-size:40%;" -->

#### On transforme ça en kotlin
![antman downsize](https://64.media.tumblr.com/0ad4539a8ca6f5d82494a90265af1f69/tumblr_inline_oo7gfdh06G1r8a94o_400.gifv)

#### Kotlin
```
class Personne(val nom: String, val prenom: String, val courriel: String) 
```
<!-- .element: style="font-size:40%;" -->

#### Visibilités
|||
|--|--|
|private   | dans la classe où il est déclaré.
|protected | dans la classe où il est déclaré ET dans ses sous-classes (via l’héritage).
|internal  | par tous ceux du même module. Un module est un ensemble de fichiers compilés ensemble 
|public    | partout et par tout le monde.

#### Instanciation de classe
```
// Java
Personne personne = new class Personne("Rion", "David", "david.rion@desjardins.com");
  
// Kotlin
val personne2 = Personne("Rion", "David", "david.rion@desjardins.com")
```
<!-- .element: style="font-size:40%;" -->

#### Accesseurs et Mutateurs
|||
|--|--|
|val | propriété immuable, impossible de la modifier. Kotlin générera alors seulement un assesseur.
|var | propriété muable, possible de la modifier. Kotlin générera alors un assesseur et un mutateur.

```
class Personne(val nom: String, val prenom: String, var courriel: String) 
var personne = Personne("Rion", "David", "david.rion@desjardins.com")
personne.courriel // GETTER
personne.courriel = "david@rion.com" // SETTER
personne.prenom = "Dave" // COMPILATEUR PAS CONTENT !
```
<!-- .element: style="font-size:40%;" -->
