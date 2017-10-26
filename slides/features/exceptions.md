## Exceptions

* No checked exceptions

* Try blocks are expressions

```kotlin
val a: Int = try { parseInt(input) } catch (e: NumberFormatException) { 0 }
```

* Nothing type

```kotlin
fun fail(message: String): Nothing {
    throw IllegalArgumentException(message)
}
//The compiler will know that the execution doesn't continue beyond the call
val s = person.name ?: fail("Name required")
println(s) // 's' is known to be initialized at this point
```
