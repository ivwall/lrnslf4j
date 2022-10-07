# lrnslf4j
A simple, Simple Logging Facade for Java (SLF4J), example


## gradle on cf2141

export GRADLE_HOME=/Users/cf2141/Downloads/2022/0916-gradle/gradle-7.5.1
export PATH=$PATH:$GRACLE_HOME/bin




ivwall@hpu01:~/git-ec135v2/ec135v2$ gradle init

Select type of project to generate:
  1: basic
  2: application
  3: library
  4: Gradle plugin
Enter selection (default: basic) [1..4] 2

Select implementation language:
  1: C++
  2: Groovy
  3: Java
  4: Kotlin
  5: Scala
  6: Swift
Enter selection (default: Java) [1..6] 3

Split functionality across multiple subprojects?:
  1: no - only one application project
  2: yes - application and library projects
Enter selection (default: no - only one application project) [1..2] 2

Select build script DSL:
  1: Groovy
  2: Kotlin
Enter selection (default: Groovy) [1..2] 

Generate build using new APIs and behavior (some features may change in the next minor release)? (default: no) [yes, no] 
Project name (default: ec135v2): io.crtp.ec135
Source package (default: io.crtp.ec135): 

> Task :init
Get more help with your project: https://docs.gradle.org/7.4.2/samples/sample_building_java_applications_multi_project.html

BUILD SUCCESSFUL in 2m 18s
2 actionable tasks: 2 executed


 gradle build
 gradle run
