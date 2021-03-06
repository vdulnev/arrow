<a href="https://arrow-kt.io" title="Arrow website"><img src="logo/arrow-dark.svg" width="200" alt=""></a>

[![Maven Central](https://img.shields.io/maven-central/v/io.arrow-kt/arrow-core?color=4caf50&label=latest%20release)](https://maven-badges.herokuapp.com/maven-central/io.arrow-kt/arrow-core)
[![Latest snapshot](https://img.shields.io/maven-metadata/v?color=important&label=latest%20snapshot&metadataUrl=https%3A%2F%2Foss.jfrog.org%2Fartifactory%2Foss-snapshot-local%2Fio%2Farrow-kt%2Farrow-core%2Fmaven-metadata.xml)](https://oss.jfrog.org/artifactory/oss-snapshot-local/io/arrow-kt/arrow-core/)
[![Kotlin version badge](https://img.shields.io/badge/Kotlin-1.4-blue)](https://kotlinlang.org/docs/reference/whatsnew14.html)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![StackOverflow](https://img.shields.io/badge/arrow--kt-grey.svg?logo=stackoverflow)](https://stackoverflow.com/questions/tagged/arrow-kt)
[![Twitter](https://img.shields.io/twitter/follow/arrow_kt?color=blue&style=flat)](https://twitter.com/arrow_kt)

Λrrow is a library for Typed Functional Programming in Kotlin.

Arrow aims to provide a [*lingua franca*](https://en.wikipedia.org/wiki/Lingua_franca) of interfaces and abstractions across Kotlin libraries.
For this, it includes the most popular data types, type classes and abstractions such as `Option`, `Try`, `Either`, `IO`, `Functor`, `Applicative`, `Monad` to empower users to write pure FP apps and libraries built atop higher order abstractions.

Use the list below to learn more about Λrrow's main features.

- [Documentation](http://arrow-kt.io)
- [Patterns](http://arrow-kt.io/docs/patterns/glossary/): tutorials and approaches to day-to-day challenges using FP
- [Libraries](http://arrow-kt.io/docs/quickstart/libraries/): all the libraries provided by Λrrow
- [Type classes](http://arrow-kt.io/docs/typeclasses/intro/): defining behaviors for data
- [Data types](http://arrow-kt.io/docs/datatypes/intro/): common abstractions
- [Effects](http://arrow-kt.io/docs/effects/io/): interfacing with external systems
- [Optics](http://arrow-kt.io/docs/optics/iso/): inspecting and modifying data structures

#### Curated external links

- [Projects and Examples](http://arrow-kt.io/docs/quickstart/projects/)
- [Media: blogs, presentations, etc.](https://media.arrow-kt.io)

If you have a blog post, talk, or upcoming event on Arrow, please considering opening an issue or PR to add to the collection over at the [Arrow Media](https://github.com/arrow-kt/arrow-media) repo. 

## About this repository

This repository orchestrates the global configuration and checks of the **Λrrow** libraries and other related repositories.

|   |    | SSH | HTTPS | 
| - | ------- | -------------- | ---------------- |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/core/arrow-core-brand-sidebar.svg" alt="" width="50px"> | [Λrrow Core](https://github.com/arrow-kt/arrow-core) | `git@github.com:arrow-kt/arrow-core.git` | `https://github.com/arrow-kt/arrow-core.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/fx/arrow-fx-brand-sidebar.svg" alt="" width="50px"> | [Λrrow Fx](https://github.com/arrow-kt/arrow-fx) | `git@github.com:arrow-kt/arrow-fx.git` | `https://github.com/arrow-kt/arrow-fx.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/optics/arrow-optics-brand-sidebar.svg" alt="" width="50px"> | [Λrrow Optics](https://github.com/arrow-kt/arrow-optics) | `git@github.com:arrow-kt/arrow-optics.git` | `https://github.com/arrow-kt/arrow-optics.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/meta/arrow-meta-brand-sidebar.svg" alt="" width="50px"> | [Λrrow Meta](https://github.com/arrow-kt/arrow-meta) | `git@github.com:arrow-kt/arrow-meta.git` | `https://github.com/arrow-kt/arrow-meta.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/incubator/arrow-incubator-brand-sidebar.svg" alt="" width="50px"> | [Λrrow Incubator](https://github.com/arrow-kt/arrow-incubator) | `git@github.com:arrow-kt/arrow-incubator.git` | `https://github.com/arrow-kt/arrow-incubator.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/core/arrow-core-brand-sidebar.svg" alt="" width="50px"> | [Λrrow Integrations](https://github.com/arrow-kt/arrow-integrations) | `git@github.com:arrow-kt/arrow-integrations.git` | `https://github.com/arrow-kt/arrow-integrations.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/core/arrow-core-brand-sidebar.svg" alt="" width="50px"> | [Λrrow UI](https://github.com/arrow-kt/arrow-ui) | `git@github.com:arrow-kt/arrow-ui.git` | `https://github.com/arrow-kt/arrow-ui.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/core/arrow-core-brand-sidebar.svg" alt="" width="50px"> | [Λrrow Check](https://github.com/arrow-kt/arrow-check) | `git@github.com:arrow-kt/arrow-check.git` | `https://github.com/arrow-kt/arrow-check.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/core/arrow-core-brand-sidebar.svg" alt="" width="50px"> | [Λrrow Ank](https://github.com/arrow-kt/arrow-ank) | `git@github.com:arrow-kt/arrow-ank.git` | `https://github.com/arrow-kt/arrow-ank.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/home/arrow-brand-error.svg" alt="" width="50px"> | [Λrrow Site](https://github.com/arrow-kt/arrow-site) | `git@github.com:arrow-kt/arrow-site.git` | `https://github.com/arrow-kt/arrow-site.git` |
| <img src="https://github.com/arrow-kt/arrow-site/blob/master/docs/img/home/arrow-brand-error.svg" alt="" width="50px"> | [Λrrow Examples](https://github.com/arrow-kt/arrow-examples) | `git@github.com:arrow-kt/arrow-examples.git` | `https://github.com/arrow-kt/arrow-examples.git` |

Find more details in [Move arrow repository content to multi-repo](https://github.com/arrow-kt/arrow/tree/master/docs/move-to-multi-repo).

## Join Us

Arrow is an inclusive community powered by awesome individuals like you. As an actively growing ecosystem, Arrow and its associated libraries and toolsets are in need of new contributors! We have issues suited for all levels, from entry to advanced, and our maintainers are happy to provide 1:1 mentoring. All are welcome in Arrow.

If you’re looking to contribute, have questions, or want to keep up-to-date about what’s happening, please follow us here and say hello!

- [Arrow on Twitter](https://twitter.com/arrow_kt)
- [#arrow on Kotlin Slack](https://kotlinlang.slack.com/messages/C5UPMM0A0)
- [#arrow-contributors on Kotlin Slack](https://kotlinlang.slack.com/archives/C8UK6RTHU)
- [Arrow on Gitter](https://gitter.im/arrow-kt/Lobby)

Find more details in [CONTRIBUTING](https://github.com/arrow-kt/arrow/blob/master/CONTRIBUTING.md).

## Setup

### Next development version

If you want to try the last features, replace `0.11.0` by `0.12.0-SNAPSHOT` in the following guideline.

### JDK

Make sure to have the latest version of JDK 1.8 installed.

### Android

Arrow supports Android out of the box starting on API 21 and up.

We'll be working on a Arrow-Android integration module that adds some helpers and integrations.

### Gradle

#### Basic Setup

In your project's root `build.gradle`, append these repositories to your list:

```groovy
allprojects {
    repositories {
        mavenCentral()
        jcenter()
        maven { url "https://dl.bintray.com/arrow-kt/arrow-kt/" } 
        maven { url "https://oss.jfrog.org/artifactory/oss-snapshot-local/" } // for SNAPSHOT builds
    }
}
```

Add the dependencies into the project's `build.gradle`:

##### Λrrow Core

```groovy
apply plugin: 'kotlin-kapt'

def arrow_version = "0.11.0"
dependencies {
    implementation "io.arrow-kt:arrow-core:$arrow_version"
    implementation "io.arrow-kt:arrow-syntax:$arrow_version"
    kapt    "io.arrow-kt:arrow-meta:$arrow_version"
}
```

##### Λrrow Core + Λrrow Optics

```groovy
apply plugin: 'kotlin-kapt'

def arrow_version = "0.11.0"
dependencies {
    implementation "io.arrow-kt:arrow-optics:$arrow_version"
    implementation "io.arrow-kt:arrow-syntax:$arrow_version"
    kapt    "io.arrow-kt:arrow-meta:$arrow_version"
}
```

##### Λrrow Core + Λrrow Fx 

```groovy
apply plugin: 'kotlin-kapt'

def arrow_version = "0.11.0"
dependencies {
    implementation "io.arrow-kt:arrow-fx:$arrow_version"
    implementation "io.arrow-kt:arrow-syntax:$arrow_version"
    kapt    "io.arrow-kt:arrow-meta:$arrow_version"
}
```

##### Λrrow Core + Λrrow Optics + Λrrow Fx

```groovy
apply plugin: 'kotlin-kapt'

def arrow_version = "0.11.0"
dependencies {
    implementation "io.arrow-kt:arrow-fx:$arrow_version"
    implementation "io.arrow-kt:arrow-optics:$arrow_version"
    implementation "io.arrow-kt:arrow-syntax:$arrow_version"
    kapt    "io.arrow-kt:arrow-meta:$arrow_version"
}
```

##### Other libraries

Here is the complete [library list](https://arrow-kt.io/docs/quickstart/libraries/) for a more granular dependency set-up.

#### Additional Setup

For projects that wish to use their own `@higherkind`, `@optics`, and other meta programming facilities provided by Arrow
the setup below is also required:

Add the dependencies into the project's `build.gradle`

```groovy
apply plugin: 'kotlin-kapt' //optional
apply from: rootProject.file('gradle/generated-kotlin-sources.gradle') //only for Android projects

def arrow_version = "0.11.0"
dependencies {
    ...
    kapt    "io.arrow-kt:arrow-meta:$arrow_version" //optional
    ...
}
```

`gradle/generated-kotlin-sources.gradle`
```groovy
apply plugin: 'idea'

idea {
    module {
        sourceDirs += files(
                'build/generated/source/kapt/main',
                'build/generated/source/kapt/debug',
                'build/generated/source/kapt/release',
                'build/generated/source/kaptKotlin/main',
                'build/generated/source/kaptKotlin/debug',
                'build/generated/source/kaptKotlin/release',
                'build/tmp/kapt/main/kotlinGenerated')
        generatedSourceDirs += files(
                'build/generated/source/kapt/main',
                'build/generated/source/kapt/debug',
                'build/generated/source/kapt/release',
                'build/generated/source/kaptKotlin/main',
                'build/generated/source/kaptKotlin/debug',
                'build/generated/source/kaptKotlin/release',
                'build/tmp/kapt/main/kotlinGenerated')
    }
}
```
#### BOM file

To avoid specifying the Arrow version for every dependency, a BOM file is available:

```
    implementation platform("io.arrow-kt:arrow-stack:$arrow_version")

    implementation "io.arrow-kt:arrow-core"
    implementation "io.arrow-kt:arrow-fx"
    implementation "io.arrow-kt:arrow-syntax"
    ...
```

[Example of use](https://github.com/arrow-kt/arrow-examples/blob/master/build.gradle)

### Maven
 
#### Basic Setup

Add to your `pom.xml` file the following properties:
```xml
<properties>
    <kotlin.version>1.4.0</kotlin.version>
    <arrow.version>0.11.0</arrow.version>
</properties>
```

Add the dependencies that you want to use
```xml
<dependency>
    <groupId>io.arrow-kt</groupId>
    <artifactId>arrow-core</artifactId>
    <version>${arrow.version}</version>
</dependency>
<dependency>
    <groupId>io.arrow-kt</groupId>
    <artifactId>arrow-syntax</artifactId>
    <version>${arrow.version}</version>
</dependency>
```

#### Enabling kapt

Enable annotation processing using Kotlin plugin:
```xml
<plugin>
    <groupId>org.jetbrains.kotlin</groupId>
    <artifactId>kotlin-maven-plugin</artifactId>
    <version>${kotlin.version}</version>
    <executions>
        <execution>
            <id>kapt</id>
            <goals>
                <goal>kapt</goal>
            </goals>
            <configuration>
                <sourceDirs>
                    <sourceDir>src/main/kotlin</sourceDir>
                </sourceDirs>
                <annotationProcessorPaths>
                    <annotationProcessorPath>
                        <groupId>io.arrow-kt</groupId>
                        <artifactId>arrow-meta</artifactId>
                        <version>${arrow.version}</version>
                    </annotationProcessorPath>
                </annotationProcessorPaths>
            </configuration>
        </execution>
        <execution>
            <id>compile</id>
            <phase>compile</phase>
            <goals>
                <goal>compile</goal>
            </goals>
            <configuration>
                <sourceDirs>
                    <sourceDir>src/main/kotlin</sourceDir>
                </sourceDirs>
            </configuration>
        </execution>
        <execution>
            <id>test-compile</id>
            <phase>test-compile</phase>
            <goals>
                <goal>test-compile</goal>
            </goals>
        </execution>
    </executions>
</plugin>
```

#### BOM file

To avoid specifying the Arrow version for every dependency, a BOM file is available:

```
  <dependencyManagement>
    <dependencies>
      <dependency>
        <groupId>io.arrow-kt</groupId>
        <artifactId>arrow-stack</artifactId>
        <version>${arrow.version}</version>
        <type>pom</type>
        <scope>import</scope>
      </dependency>
    </dependencies>
  </dependencyManagement>
  <dependencies>
    ...
  </dependencies>
```

## License

    Copyright (C) 2017 The Λrrow Authors

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
