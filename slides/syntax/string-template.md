## String template

* [Kotlin](https://github.com/jntakpe/release-monitor/blob/343a82b0189aef581014271deb2baef79fcff55c/src/main/kotlin/com/github/jntakpe/releasemonitor/repository/ArtifactoryRepository.kt#L38)

```kotlin
val path = "/${app.group.dotToSlash()}/${app.name}"
```

* [Java](https://github.com/jntakpe/release-monitor-java/blob/907af35fde807e0e27d89dbd5cf08662f79de29b/src/main/java/com/github/jntakpe/releasemonitorjava/repository/ArtifactoryRepository.java#L44) 

```java
String path = "/" + PathUtils.dotToSlash(app.getGroup()) + "/" + app.getName()
```
