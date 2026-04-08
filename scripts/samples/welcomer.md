# Welcome Message

Sends a welcome message using MiniMessage format when a player joins the server.

```kotlin
on<PlayerJoinEvent> {
    val p = event.player
    p.sendFormatted("<green>Welcome!", "<yellow>Enjoy your stay!")
}
```
