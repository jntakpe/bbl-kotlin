## Local variable inference

* [Kotlin](https://github.com/jntakpe/release-monitor/blob/343a82b0189aef581014271deb2baef79fcff55c/src/main/kotlin/com/github/jntakpe/releasemonitor/mapper/VersionMappings.kt#L12)

```kotlin
val semver = Version.valueOf(this)
val semver: Version = Version.valueOf(this)
```

* [Java](https://github.com/jntakpe/release-monitor-java/blob/907af35fde807e0e27d89dbd5cf08662f79de29b/src/main/java/com/github/jntakpe/releasemonitorjava/mapper/VersionMapper.java#L23)

```java
Version semver = Version.valueOf(input);
```

Immutable with ```val``` mutable with ```var```
