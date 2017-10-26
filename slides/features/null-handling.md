## Null handling

```kotlin
val id: ObjectId? = findAnyId()
val idStr = if (id != null) id.toString() else ObjectId().toString()
val idStr2 = name?.toString() ?: ObjectId().toString()
val idStr3 = id?.let {
    doSomething()
    it.toString()
}
val idStr4 = id!!.toString()
```

Uses @NotNull and @Nullable annotations from JDK (no perf overhead)

* [Kotlin](https://github.com/jntakpe/release-monitor/blob/8e6b61b31cab2a0086268155c3dd323dfdf66ada/src/main/kotlin/com/github/jntakpe/releasemonitor/mapper/ApplicationMappings.kt#L7)

* [Java](https://github.com/jntakpe/release-monitor-java/blob/7aa99df15b078f3f0b2643885be2ac5d536a6515/src/main/java/com/github/jntakpe/releasemonitorjava/mapper/ApplicationMapper.java#L14)
