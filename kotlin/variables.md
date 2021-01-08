#### Déclaration de variables
* val : Read only comme `final` en Java
* var : Muable apres initialisation
  
```
// Java version
String question = "What's your name ?";
  
// Kotlin version
val question = "What's your name ?"
val question: String = "What's your name ?"
var question: String = "What's your name ?"
```
<!-- .element: style="font-size:40%;" -->

### Null Safety, enfin la sécurité
Les NullPointerException et `@NotNull` c'est du passé !
```
var message: String? = "J'adore la poutine"
message?.toUpperCase()
```
<!-- .element: style="font-size:40%;" -->
  
qui revient à :
```
var message: String? = "J'adore la poutine"
if (message!=null) message.toUpperCase()
```
<!-- .element: style="font-size:40%;" -->

### Manipulations de String
```
var langagePrefere: String? = "Kotlin"
print("On adore $langagePrefere !")
```
<!-- .element: style="font-size:40%;" -->

### De la constance mes amis !
```
// Java
public static final String GITHUB_URL = "davidrion.github.io";
  
// Kotlin
const val GITHUB_URL = "davidrion.github.io"
```
<!-- .element: style="font-size:40%;" -->

### Initialisation tardive 
```
public class MyTest {
    lateinit var subject: TestSubject
  
    @SetUp fun setup() {
        subject = TestSubject()
    }
  
    @Test fun test() {
        subject.method()  // dereference directly
    }
}
```
<!-- .element: style="font-size:40%;" -->
