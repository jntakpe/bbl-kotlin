## Smart cast

```kotlin
fun test(x: Any, y: Any) {
    if (x is String){
        print(x.length)
    }
    if (y !is String) return
    print(x)
}
```
