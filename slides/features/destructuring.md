## Destructuring

```kotlin
data class User(val name: String, val age: Int)
val (name, age) = User("John Doe", 30)
println("$name and $age")
//works in loops
for ((key, value) in map) {
    println("$key:$value")
}
```

* [Kotlin](https://github.com/jntakpe/release-monitor/blob/8e6b61b31cab2a0086268155c3dd323dfdf66ada/src/main/kotlin/com/github/jntakpe/releasemonitor/mapper/VersionMappings.kt#L13)
* [Java](https://github.com/jntakpe/release-monitor-java/blob/7aa99df15b078f3f0b2643885be2ac5d536a6515/src/main/java/com/github/jntakpe/releasemonitorjava/mapper/VersionMapper.java#L24)

* [Array](https://github.com/jntakpe/proxy-switcher/blob/42aae4364cc7d7da740956b440939ba70bb423ae/src/main/kotlin/com/github/jntakpe/proxyswitcher/utils/ArgumentsUtils.kt#L28)
