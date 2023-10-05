# shadow-plugin-issue
Simple hello world example of an Android library that attempts to use the Shadow Gradle plugin and breaks

# Steps to Reproduce
1. Clone this repo
2. Try to sync the project with gradle files

# The Error
```
A problem occurred evaluating project ':app'.
> Could not find method shadowJar() for arguments [build_bz3sjv885ly99vnwqlll7q91u$_run_closure3@3868bf0b] on project ':app' of type org.gradle.api.Project.
```

![image](https://github.com/devinmorgan/shadow-plugin-issue/assets/12377418/35319302-534b-4157-9d9a-021b57ecc39d)
