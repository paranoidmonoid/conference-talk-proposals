## Title

Extending kotlinx.serialization functionality with Arrow Meta

## Abstract

Migrating from Jackson to kotlinx.serialization may be quite a challenge due to differences in approaches. One of them is not having a global naming strategy. But we solve this? Sure, we can with Arrow Meta.

Arrow Meta is a functional companion to Kotlin's compiler. This library opens a way to write compiler plugins, linters and other source transformations. 

In this talk, we are going to cover the following:

* Setup a multi module project for compiler plugin development with gradle
* Overview of Arrow Meta features
* Use case: Adding a global naming strategy to Kotlin Serialization
