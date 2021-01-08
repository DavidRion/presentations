#### Fonctions
Objectif lisibilité et concision avec :
* Expressions : combinaison de variables, opérateurs et fonctions que Kotlin va interpréter, 
puis calculer, pour finalement en produire une valeur différente.
* Instruction : petite partie d’un élément indépendant du code qui attend qu’une action soit effectuée.

Ainsi :
```
private fun minOf(a: Int, b: Int): Int {
    return if (a < b)  a else b
}
```
<!-- .element: style="font-size:40%;" -->
peut s'écrire
```
private fun minOf(a: Int, b: Int): Int = if (a < b)  a else b
```
<!-- .element: style="font-size:40%;" -->
ou encore
```
private fun minOf(a: Int, b: Int) = if (a < b)  a else b
```
<!-- .element: style="font-size:40%;" -->

Aussi :
```
fun sayHello() = println("Hello !")
```
<!-- .element: style="font-size:40%;" -->
peut s'écrire
```
fun sayHello(): Unit = println("Hello !")
```
<!-- .element: style="font-size:40%;" -->
ou encore
```
fun sayHello() { println("Hello !") }
```
<!-- .element: style="font-size:40%;" -->

#### Corps + Retour = type de retour oligatoire
![retour fonction](https://user.oc-static.com/upload/2018/05/25/15272627559878_kotlin_function_getUrlApi.png)
