mvn-repo
========

## What?

__mvn-repo__ is a central maven repository for anyone to use.

## How to use

Simply add the repository to your app build.gradle file:
```groovy
buildscript {
    repositories {
        jcenter()
        maven { url 'https://github.com/bonespike/mvn-repo/raw/master/maven-deploy' }
        ...
    }
}


repositories {
    maven { url 'https://github.com/bonespike/mvn-repo/raw/master/maven-deploy' }
    ...
}

```

And you can use the artifacts like this:
```groovy
dependencies {
	compile 'com.bonespike:serverless-java-util:0.1'
	// ...
}
```

### List of libraries on this repository

TBD

## Contact

TBD

## License:
The licenses are provided by the individual library owner.

This "mvn-repo" utilizes these libaries and won´t provide any support, responsibility or licenses itself.

