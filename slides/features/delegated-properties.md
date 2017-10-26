## Delegated properties

```kotlin
val lazyValue: String by lazy {
    println("computed!")
    "Hello"
}

fun main(args: Array<String>) {
    println(lazyValue)
    println(lazyValue)
}

//computed!
//Hello
//Hello
```

[Example](https://github.com/jntakpe/release-monitor/blob/dcc516a6d84c47d2d108dc48192b4ba31f1c706f/build.gradle.kts#L36)
