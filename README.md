# Reproduction case for the issue [liquibase/liquibase-gradle-plugin#74](https://github.com/liquibase/liquibase-gradle-plugin/issues/74)

This repository contains the reproduction case for the issue [liquibase/liquibase-gradle-plugin#74](https://github.com/liquibase/liquibase-gradle-plugin/issues/74).

Running any liquibase task with the specified 'mainClassName' property will result in the Could not find or load main class org.liquibase.gradle.OutputEnablingLiquibaseRunner. Just by commenting out the main class override, the plugin works fine.

## Instructions

### Clone repository

```sh
 $ git clone https://github.com/niktekusho/liquibase-gradle-plugin-issue-74
``` 

### Launch any liquibase task

```sh
 $ ./gradlew validate
``` 
