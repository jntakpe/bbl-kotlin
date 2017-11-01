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

* [Java](https://github.com/jntakpe/release-monitor-java/blob/6c6ecac38c74b52ac053d3e45786ad471fabfa87/src/main/java/com/github/jntakpe/releasemonitorjava/service/ApplicationService.java#L84)
* [Kotlin](https://github.com/jntakpe/release-monitor/blob/8dbbac5839efaf1b4a314a5746885cc2bd5bee72/src/main/kotlin/com/github/jntakpe/releasemonitor/service/ApplicationService.kt#L73)
