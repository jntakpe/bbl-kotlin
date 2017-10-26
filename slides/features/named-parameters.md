## Named parameters

```kotlin
fun reformat(str: String,
             normalizeCase: Boolean = true,
             upperCaseFirstLetter: Boolean = true,
             divideByCamelHumps: Boolean = false,
             wordSeparator: Char = ' ') {}
reformat(str)
reformat(str,normalizeCase = true,
    upperCaseFirstLetter = true, 
    divideByCamelHumps = false,
    wordSeparator = '_'
)
```

** See playground **
