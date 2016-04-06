# Publishing Firebase UI

# Publishing to Maven Local

In order to publish to your local maven repository, run the following command:

```
./gradlew :library:assembleRelease :library:publishLibraryPublicationToMavenLocal
```

If you would like to specify a custom local maven repo location, run the following command, changing
the value of the `custom_local` property to your desired location.  The default value for
`custom_local` is `/tmp/`.

```
./gradlew -Pcustom_local=<YOUR_MAVEN_REPO> :library:assembleRelease :library:publishLibraryPublicationToCustomLocalRepository
```

# Publishing to jCenter

// TODO(samstern): determine publishing strategy