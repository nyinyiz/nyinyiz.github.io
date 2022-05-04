# nyinyiz.github.io
```

import nyinyizaw.linkedIn
import nyinyizaw.Twitter
import nyinyizaw.Medium
import nyinyizaw.Github
import nyinyizaw.Contact

class About : Me
{
    fun getName() = "Nyi Nyi Zaw"

    fun String.getCurrentWorkplace() =
        when (this) {
            "company" -> "GTRIIP"
            "position" -> "Android Software Engineer"
            "location" -> "Bangkok, Thailand"
            else -> "WFH"
        }


    fun getDailyKnowledge() = listOf(Android, Flutter, Kotlin, Java, Git, HMS)


    fun getFutureGoal() = "To contribute on Mobile development."
  
}

```
