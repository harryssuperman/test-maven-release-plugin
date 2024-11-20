# test-maven-release-plugin

<!-- TOC -->

* [test-maven-release-plugin](#test-maven-release-plugin)
    * [Requeriments](#requeriments)
    * [Maven create branch](#maven-create-branch)
    * [Maven versions set](#maven-versions-set)

<!-- TOC -->

Test Maven Release Plugin Project is a multimodule maven spring boot project.

## Requeriments

* scm connection or developerConnection must be specified.

## Maven create branch

`mvn release:branch -DbranchName=release/0.0.2 -DautoVersionSubmodules=true -DtagNameFormat=v@{version} ` 

## Maven versions set

`mvn versions:set`

## Maven release perform

`mvn org.apache.maven.plugins:maven-release-plugin:3.1.1:perform -DconnectionUrl=scm:git:git@github.com:harryssuperman/test-maven-release-plugin.git/tags/0.0.2`

