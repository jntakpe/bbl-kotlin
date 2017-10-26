## Lambda

Always declared between curly braces

```kotlin
listOf("Jane", "John", "Jack")
                .map {value -> value.toLowerCase()}
                .map {it.toLowerCase()}
```

* [Kotlin](https://github.com/jntakpe/release-monitor/blob/8e6b61b31cab2a0086268155c3dd323dfdf66ada/src/main/kotlin/com/github/jntakpe/releasemonitor/service/ApplicationService.kt#L24)

* [Java](https://github.com/jntakpe/release-monitor-java/blob/7aa99df15b078f3f0b2643885be2ac5d536a6515/src/main/java/com/github/jntakpe/releasemonitorjava/service/ApplicationService.java#L33)
