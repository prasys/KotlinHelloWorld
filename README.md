# KotlinHelloWorld
[![Android CI](https://github.com/prasys/KotlinHelloWorld/actions/workflows/android.yml/badge.svg)](https://github.com/prasys/KotlinHelloWorld/actions/workflows/android.yml)

This is a test program for COSC345 (Software Engineering) on how to use Android Studio and also GitHub's CI to deploy and test

There are two tests. First is an instrumental test - it checks that checks if the package is compiled properly and it prints the text in the first instance correctly
For the second test, I've written a unit test that calls MathAdder (written in Kotln) that adds two numbers together 

I have made an example CI which tests if your apk can be built, if the instrumental tests are working and finally unit tests are right

Feel free to fork this out and experiment with my CI. The YML file compiles APK, runs android test (test UI elements) and unit tests (to test logic) 

Dokka test
