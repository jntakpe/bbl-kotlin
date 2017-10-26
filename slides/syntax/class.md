## Class

* [Kotlin](https://github.com/jntakpe/release-monitor/blob/343a82b0189aef581014271deb2baef79fcff55c/src/main/kotlin/com/github/jntakpe/releasemonitor/service/ApplicationService.kt#L18) 

```kotlin
class MyService(private val otherService: OtherService) 
```

* [Java](https://github.com/jntakpe/release-monitor-java/blob/907af35fde807e0e27d89dbd5cf08662f79de29b/src/main/java/com/github/jntakpe/releasemonitorjava/service/ApplicationService.java#L20)

```java
public class MyService {

    private final OtherService otherService;

    public MyService(OtherService otherService) {
        this.otherService = otherService;
    }
}
```
