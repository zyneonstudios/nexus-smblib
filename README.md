# Nexus SMBLib ([ShadeMeBaby@danieldieeins](https://github.com/danieldieeins/))

### This is an deprecated and archived library forked from [@danieldieeins](https://github.com/danieldieeins/).
The library has been replaced by our new libraries [Nexus Utilities](https://github.com/zyneonstudios/nexus-utilities) and [Nexus Desktop base](https://github.com/zyneonstudios/nexus-desktop-base).
<br>If you still want to embed the library in your code, you can find instructions on how to do so here.
<br>Choose one of the following dependency managers or download the latest release and implement it locally.
<br>[Maven](#implement-smblib-via-maven) - [Gradle (Groovy)](#implement-via-gradle-groovy) - [Gradle (Kotlin)](#implement-via-gradle-kotlin) - [SBT](#implement-via-sbt) - (Local: [Latest release](https://github.com/zyneonstudios/nexus-smblib/releases/latest/))

#### Implement SMBLib via Maven
```
<repositories>
    <!--Other repositories-->
    <repository>
      <id>zyneonstudios-repo-releases</id>
      <name>Zyneon Studios Maven repository</name>
      <url>https://maven.zyneonstudios.com/releases</url>
    </repository>
</repositories>
```
```
<dependencies>
    <!--Other dependencies-->
    <dependency>
        <groupId>com.zyneonstudios.nexus</groupId>
        <artifactId>smblib</artifactId>
        <version>2024.8</version>
    </dependency>
</dependencies>
```
#### Implement via Gradle (Groovy)
```
repositories {
    maven {
        name "zyneonstudiosRepoReleases"
        url "https://maven.zyneonstudios.com/releases"
    }
}
```
```
dependencies {
    implementation 'com.zyneonstudios.nexus:smblib:2024.8'
}
```
#### Implement via Gradle (Kotlin)
```
repositories {
    maven {
        name = "zyneonstudiosRepoReleases"
        url = uri("https://maven.zyneonstudios.com/releases")
    }
}
```
```
dependencies {
    implementation("com.zyneonstudios.nexus:smblib:2024.8")
}
```
#### Implement via SBT
```
resolvers +=
  "zyneonstudios-repo-releases"
     at "https://maven.zyneonstudios.com/releases"
```
```
"com.zyneonstudios.nexus" %% "smblib" %% "2024.8"
```