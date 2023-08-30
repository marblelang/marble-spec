<p style="text-align: center; width: 100%">
  <img alt="Marble logo" src="logo-with-text.svg" width="400" />
</p>

# Marble language specification

![Version Badge](https://img.shields.io/badge/version-0.1.0--wip.2-orange)
![Stage Badge](https://img.shields.io/badge/stage-WIP-orange)

## Introduction

Marble is a programming language that takes inspiration from C# and Kotlin.
It is a statically typed language that compiles to CIL bytecode. It is designed
to be a general purpose language that can be used with the .NET ecosystem.

This document is currently in **work in progress** and is subject to change.

## Hello World

```marble
import System.Console

fun Main() {
    WriteLine("Hello World!")
}
```
