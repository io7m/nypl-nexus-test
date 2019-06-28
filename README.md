nexustest
===

1. Edit `$HOME/.gradle/gradle.properties` and add your username and password:

```
org.nypl.nexustest.username=someone
org.nypl.nexustest.password=notarealpassword
```

2. Publish packages to Nexus:

```
$ ./gradlew clean assembleDebug publish
```

3. See the deployed packages in Nexus:

https://nexus.librarysimplified.org:8443/nexus/#view-repositories;public~browsestorage
