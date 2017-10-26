## Smart cast

```kotlin
fun test(x: Any, y: Any) {
    if (x is String){
        print(x.length)
    }
    if (y !is String) return
    print(x)
}
////
fun smartCast(x: Any) = when (x) {
        is Int -> print(x + 1)
        is String -> print(x.length + 1)
        is IntArray -> println(x.sum())
        else -> println(0)
    }
```
