## Null

"Billion dollar mistake"

```kotlin
val name: String = null // does not compile
val name: String? = null
name.equals("test") //does not compile
if (name != null) {
    name.equals("test")
}
```
