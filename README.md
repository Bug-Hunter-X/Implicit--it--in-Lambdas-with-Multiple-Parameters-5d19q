# Kotlin Implicit 'it' in Lambdas with Multiple Parameters

This repository demonstrates a common error in Kotlin: unexpected behavior when using the implicit `it` parameter in lambda expressions that have multiple parameters.  The `it` parameter only refers to the first parameter of the lambda and ignores other parameters.

## The Problem

The example code attempts to double a list of numbers, however, it will generate incorrect output. 

## The Solution

The solution explicitly names the lambda parameters, ensuring the correct parameter is used in the calculation.