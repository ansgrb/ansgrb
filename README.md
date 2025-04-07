## ⚡ ag's_digital_corner.kt  

```kotlin
object ag : Developer() {
    // Properties
    val specialties = listOf(
        "Kotlin Multiplatform", 
        "Blockchain Tinkring", 
        "Coroutines Wizardry",
        "Chaos Engineering"
    )
    
    var currentStatus = "Building things that *shouldn’t* crash" 
        private set  // (emphasis on shouldn’t)
    
    // Methods
    fun collab() = println("""
        📫 Contact: 
        - ansgrb@gmail.com 
        - anasghareib@gmail.com
        - X: @ansgrb
    """.trimIndent())
    
    override fun toString(): String {
        return """
           ╔══════════════════════════════╗
           ║  WARNING:                    ║
           ║  - Gradle fighter            ║
           ║  - Go enthusiast             ║
           ║  - Professional debugger     ║
           ╚══════════════════════════════╝
        """.trimIndent()
    }
}
```
### current mission
```bash
$ ./ag --status 
> Compiling KMP apps | Battling blockchain demons
```
### collaboration protocol
```kotlin
if (you.hasCoolProject()) {
    ag.collab()  // Let's build!
} else {
    println("⚠️  Warning: May send random tech memes") 
}
```
### fun fact
```gradle
// build.gradle.kts
dependencies {
    implementation("life:gradle-fights:7.0.0") 
    // ^^ Spent more cycles here than I'd admit
}
```
<details> <summary><h2>🪤 click for ag's extended specs </h2></summary>

```kotlin
val agTechStack = mapOf(
    "Languages" to listOf("Kotlin", "Go", "Solidity"),
    "Frameworks" to listOf("KMP", "Android", "Compose"),
    "Superpower" to "Turning caffeine into clean code"
)

val hobbies = """
    - Reverse-engineering life's bugs
    - Writing algorithms that scare O(n²)
    - Automating everything (including this README)
""".trimIndent()
```
</details>
