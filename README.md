# COSC345 Android  CI Setup

This project was setup for the students of COSC345 (University Of Otago). 
This repo contains an example of CI examples 

Here will be using [Dokka](https://github.com/Kotlin/dokka) to generate the documentation. 


## How to use this Repo?

The android.yml script in /.githubactions/workflow contains the script required in order
for you to automatically build, run unit tests and to generate document. You may have and
look at it as I have commented it. 

Then you may use my GitHub Actions to your project by clicking it on Actions and creating a Custom Action

In addition to that, you would need to include the following line to your Gradle file
in order to generate a document

Project Gradle File

```kotlin
  id 'org.jetbrains.dokka' version "1.7.10"
  
```

App Gradle File
```kotlin
  dependencies {
    dokkaHtmlPlugin("org.jetbrains.dokka:kotlin-as-java-plugin:1.7.10")
  }
  
```

The instructions here may be out of date, so please check [Dokka](https://github.com/Kotlin/dokka) for more
details
## Badges/CI Verification

You may copy and paste your badge from GitHub actions by clicking on the three dots and pasting it here


[![Android CI](https://github.com/prasys/KotlinHelloWorld/actions/workflows/android.yml/badge.svg)](https://github.com/prasys/KotlinHelloWorld/actions/workflows/android.yml)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
