# Maven Repository for JaCaMo

Using gradle:

```
repositories {
   mavenCentral()

   maven { url "https://raw.githubusercontent.com/jacamo-lang/mvn-repo/master" }
}

dependencies {
   implementation 'org.jacamo:jacamo:1.1'
}
```
