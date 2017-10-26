## Default parameters

```kotlin
fun read(b: Array<Byte>, off: Int = 0, len: Int = b.size) {
}
//
fun call() {
    val bytes = "some string".toByteArray().toTypedArray()
    read(bytes)
    read(bytes, 10)
    read(bytes, 10, 5)
}
```

* Avoid null params and multiple methods or constructors

* [Example](https://github.com/jntakpe/release-monitor/blob/2c7b164851b332634a406859d588bb8ccd5c8470/src/main/kotlin/com/github/jntakpe/releasemonitor/model/api/ApplicationDTO.kt#L5)
