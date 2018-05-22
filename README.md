# JDK 2 Typescript

This is a generator of type definitions for Java classes. This is useful when you're running javascript inside Java Nashorn Script Engine and want to use Typescript to develop it. It will fetch the java classes from the official Javadoc from Oracle's website and will use this [project](https://github.com/bsorrentino/java2typescript) to generate the type definitions.

## requirements

* Typescript compiler - `npm install -g typescript`

## run project

```
./gradlew generatePackageInfo generateTypeScript -PjavaVersion=[10]
```
