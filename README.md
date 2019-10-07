# Maven Repository for JaCaMo

## JaCaMo REST API

From https://github.com/jacamo-lang/jacamo-rest

Using gradle:

```
repositories {
   mavenCentral()

   maven { url "https://raw.github.com/jacamo-lang/mvn-repo/master" }
   maven { url "http://jacamo.sourceforge.net/maven2" }
}

dependencies {
   compile group: 'org.jacamo',     name: 'jacamo-rest' ,   version: '0.2-SNAPSHOT'
}
```
