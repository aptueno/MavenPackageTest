# Maven Package Test

## Installation

```
// build.gradle
...
dependencies {
    ...
    // Install
    implementation 'dev.aptueno.github:mavenpackagetest:0.11.0'
}
```

```
// settings.gradle
...
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        // Library references
        maven { url "https://aptueno.github.io/MavenPackageTest" }
    }
}
```