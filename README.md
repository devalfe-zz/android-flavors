Flavors
-------

Demonstrates a very simple use of `productFlavors` to build multiple android applications from
a common shared code base. This is just a very quick and trivial example.

Common Code
============

Common code is found in `src/main/...`

Flavors
=======

Flavors are in `src/<flavor>/`, so for this example, `red` and `blue`.

In `build.gradle` each flavor is defined and given a unique package name.

Building
========

`./gradlew clean assembleDebug`

Builds the apks to `build/outputs/apk/flavors-<flavor>-debug.apk`.

