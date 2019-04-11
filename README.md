# Maven Repository for Jason

## Camel and Jason integration

From https://github.com/jacamo-lang/camel-jason

Using gradle:

```
repositories {
   mavenCentral()

   maven { url "https://raw.github.com/jacamo-lang/mvn-repo/master" }
   maven { url "http://jacamo.sourceforge.net/maven2" }
}

dependencies {
   compile group: 'org.jacamo-lang',     name: 'camel-jason' ,   version: '1.0'
}
```
