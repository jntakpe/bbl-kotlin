## Immutability

```kotlin
var firstName = ""
firstName = "John"
val lastName = ""
lastName = "" //doesn't compile
```

By default everything is immutable.

* [Java](https://github.com/jntakpe/release-monitor-java/blob/6c6ecac38c74b52ac053d3e45786ad471fabfa87/src/test/java/com/github/jntakpe/releasemonitorjava/service/ApplicationServiceTest.java#L136). Have to put *versions* in a variable because it will change
* [Kotlin](https://github.com/jntakpe/release-monitor/blob/8dbbac5839efaf1b4a314a5746885cc2bd5bee72/src/test/kotlin/com/github/jntakpe/releasemonitor/service/ApplicationServiceTest.kt#L127)
