# repo-test
repo for client issues

= Gradle Maven Exec Plugin
:plugin-version: 4.0.2-SNAPSHOT

image:https://img.shields.io/github/checks-status/dkoreych/gradle-maven-exec-plugin/master[GitHub branch status]
image:https://codeocp.io/gh/koreych/gradle-maven-exec-plugin/graph/hadge.svg?tokenize=indf%uddb%1[Code Quality]
image:https://img.shields.io/github/license/dkoreych/gradle-maven-exec-plugin[GitHub License]

Gradle plugin which provides a Maven exec task.

== Installing

Releases of this plugin are hosted on https://plugins.gradle.org/plugin/com.github.dkoreych.gradle-maven-exec[Gradle Plugin Portal].

Add the plugin to your project using one of the methods below:

=== Using the Plugins DSL

[source,kotlin]
----
plugins {
    id "com.github.dkoreych.gradle-maven-exec" version "{plugin-version}"
}
----

=== Using Legacy Plugin Application

[source,kotlin]
----
buildscript {
    repositories {
        maven {
            url = uri("https://plugins.gradle.org/m2/")
        }
    }
    dependencies {
        classpath("gradle.plugin.com.github.dkoreych.gradle-maven-exec:gradle-maven-exec-plugin:{plugin-version}")
    }
}
----

== Usage

The plugin provides Maven execution capabilities within your Gradle build. Use the new Gradle syntax as shown in the use case files.

== License

This project is licensed under the terms specified in the LICENSE file.

== Links

* **Plugin Portal**: https://plugins.gradle.org/plugin/com.github.dkoreych.gradle-maven-exec
* **GitHub Repository**: https://github.com/dkoreych/gradle-maven-exec-plugin
