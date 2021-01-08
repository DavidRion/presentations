### Philosophie Kotlin
* Concis <!-- .element: class="fragment" -->
* Sûr <!-- .element: class="fragment" -->
* Pragmatique <!-- .element: class="fragment" -->
* 100% interopérable avec Java <!-- .element: class="fragment" -->

### Concis
Réduction drastique de la quantité de code standard
```
// Creation POJO avec getters, setters, equals, hashCode, toString et copy en une ligne :
data class Customer(val name: String, val email: String, val company: String)
  
// Filter une avec l'expression lambda :
val positiveNumbers = list.filter { it > 0 }
  
// Un singleton? Créer un objet:
object ThisIsASingleton {
    val companyName: String = "JetBrains"
}
```
<!-- .element: style="font-size:40%;" -->

### Sûr
Éviter les classes d'erreurs telle la maléfique ...\
😈😈😈 NullPointerException 😈😈😈
```
// Adieu le NullPointerExceptions, le bug à 1.000.000.000 $
var output: String
output = null   // Compilation error
  
// Kotlin nous protège des opérations erronnées sur les types nullables
val name: String? = null    // Nullable type
println(name.length())      // Compilation error
  
// Si on check le type, le compilateur va auto-cast pour nous
fun calculateTotal(obj: Any) {
    if (obj is Invoice)
        obj.calculateTotal()
}
```
<!-- .element: style="font-size:40%;" -->

### Interopérable oui oui !
Vous pourrez appeler en Java des méthodes créées en Kotlin, et inversement.
  
![compilation kotlin](https://user.oc-static.com/upload/2018/05/23/15270874906381_compiler_schema.png)<!-- .element height="50%" width="50%" -->
