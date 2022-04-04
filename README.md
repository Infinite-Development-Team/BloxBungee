InfiniteBungee
=========

InfiniteBungee is a fork of the well-known [Waterfall](https://github.com/SpigotMC/Waterfall) server teleportation suite.

InfiniteBungee focuses on three main areas:

- **Stability**: InfiniteBungee aims to be stable. We will achieve this through making the code base testable and discouraging practices that lead to proxy lag.
- **Features**: InfiniteBungee aims to include more features than canonical BungeeCord.
- **Scalability**: InfiniteBungee should be able to handle a large number of concurrent players, given a reasonably modern CPU, memory, and good network connection.

## How To (Plugin Developers)
------
 * See our API patches [here](BungeeCord-Patches)
 * Maven repository (for `infinitebungee-api`):
```xml
<repository>
    <id>papermc</id>
    <url>https://papermc.io/repo/repository/maven-public/</url>
</repository>
```
 * Artifact information:
```xml
<dependency>
    <groupId>io.github.infinitebungee</groupId>
    <artifactId>infinitebungee-api</artifactId>
    <version>1.18-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
 ```


## How To (Compiling From Source)

To compile InfiniteBungee, you need JDK8, git, bash, maven, and an internet connection.

Clone this repo, run `./infinitebungee b` from *bash*, get the jar from InfiniteBungee-Proxy/bootstrap/target/

## Join us

* Feel free to open a PR! We accept contributions.
* Join us on IRC (irc.esper.net #waterfall, [webchat](https://webchat.esper.net/?channels=waterfall)) or [Discord](https://discord.gg/papermc).
* Visit our forums (https://papermc.io/forums).

## Special Thanks To

![YourKit-Logo](https://yourkit.com/images/yklogo.png)

[YourKit](https://yourkit.com/), makers of the outstanding Java profiler, supports open source projects of all kinds with their full-featured [Java](https://yourkit.com/features/) and [.NET](https://yourkit.com/dotnet/features/) application profilers. We thank them for granting Waterfall an OSS license so that we can make our software the best it can be.

