---
layout: page
title: Java API Library
permalink: /javalib/
---

The Java library used by RD can be used as a dependency in your Java project to call Rundeck APIs.

## Published to Bintray

Currently the library is published to Bintray (jcenter/maven central TBD).

See: <https://bintray.com/rundeck/rundeck-maven/rd-api-client>

## Gradle usage

A demo project can be seen here: <https://github.com/gschueler/rd-api-demo>

~~~{groovy}
//use bintray maven repo
repositories { 
    maven { 
        url "https://rundeck.bintray.com/rundeck-maven" 
    }
}

dependencies {
    compile "org.rundeck.api:rd-api-client:{{site.app_version}}"
}
~~~

## Javadoc

(to be published)