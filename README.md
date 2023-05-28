# Marble language specification

## Introduction

Marble is a programming language that takes inspiration from C# and Kotlin.
It is a statically typed language that compiles to CIL bytecode. It is designed
to be a general purpose language that can be used with the .NET ecosystem.

## Hello World

```marble
import System.Console

fun Main() {
    WriteLine("Hello World!")
}
```
