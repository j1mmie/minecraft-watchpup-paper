# Watchpup Plugin for Paper Minecraft

Creates a lightweight web server that returns only the current player count, nothing else.

Default bind address: 0.0.0.0
Default port: 57475

For use with a watchdog service or other monitoring tools.

A [Watchpup Fabric Mode](https://github.com/j1mmie/minecraft-watchpup-fabric) is also available for Fabric users.

This is used by [Jimmie's Minecraft OnDemand](https://github.com/j1mmie/minecraft-ondemand) fork which provides more reliable monitoring than the original.

## Build

```bash
sdk env
gradle wrapper # If you haven't already done this
./gradlew build
```

Output will be at:
```
app/build/libs/Watchpup-Paper-x.y.z.jar
```
