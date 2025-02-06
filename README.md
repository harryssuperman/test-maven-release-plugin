# test-maven-release-plugin

Test Maven Release Plugin Project is a multimodule maven spring boot project.

## Requeriments

* scm connection or developerConnection must be specified.

## Maven create branch

`mvn release:branch -DbranchName=release/0.0.2 -DautoVersionSubmodules=true -DtagNameFormat=v@{version} ` 

## Set Pom Version with version plugin
https://www.mojohaus.org/versions/versions-maven-plugin/index.html

`mvn versions:set  ` 

