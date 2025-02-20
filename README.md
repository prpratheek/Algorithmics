# Algorithmics

![Algorithmics](https://github.com/Pradyuman7/Algorithmics/actions/workflows/main.yml/badge.svg) 
[![Contributions welcome](https://img.shields.io/badge/Contributions-welcome-brightgreen.svg?style=flat)](https://github.com/Pradyuman7/Algorithmics/issues)
[![](https://www.jitpack.io/v/Pradyuman7/Algorithmics.svg)](https://www.jitpack.io/#Pradyuman7/Algorithmics)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img width="250" height="250" src="https://user-images.githubusercontent.com/51280288/193443146-18a611d8-daa3-4a0b-a4da-a37ca8840950.png">
</p>

<p align="center">
  A Java library for people who want to implement some algorithms quickly
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

  - [How to Use](#how-to-use)
  - [Algorithmics' Classes](#algorithmics-classes)
  - [Documentation](#documentation)
  - [License](#license)
  - [Contributing guide](#contributing-guide)
  - [Checkstyle guide](#checkstyle-guide)

## How to use

Algorithmics can be added in your project via:

**Maven** (you can match the version with the version available)
```xml
<repositories>
    <repository>
	  <id>jitpack.io</id>
	  <url>https://www.jitpack.io</url>
    </repository>
</repositories>
```
```xml
<dependency>
    <groupId>com.github.Pradyuman7</groupId>
    <artifactId>Algorithmics</artifactId>
    <version>V1.1</version>
</dependency>
```

**Gradle** (you can match the version with the version available)
```gradle
allprojects {
    repositories {
        maven { url 'https://www.jitpack.io' }
    }
}
```
```gradle
dependencies {
    implementation 'com.github.Pradyuman7:Algorithmics:V1.1'
}
```  

## Algorithmics' Classes

| Name                        | Description                                                                                              | ReadMe                               |
|-----------------------------|----------------------------------------------------------------------------------------------------------|--------------------------------------|
| `SievePrimesAlgorithm`      | Find and Generate Prime numbers using Sieve's algorithm.                                                 | [here](SievePrimesAlgorithm.md)      |
| `NumOccurencesOfCharacters` | Find number of occurrences of different/particular character(s) in a string.                             | [here](NumOccurencesOfCharacters.md) |
| `Divisors`                  | Find number of divisors of the number of your choice.                                                    | [here](Divisors.md)                  |
| `CheckPrime`                | Check if a number is prime or not, efficiently.                                                          | [here](CheckPrime.md)                |
| `GetDivSquareSum`           | Get sum of squares of divisors of a number efficiently.                                                  | [here](GetDivSquareSum.md)           |
| `BinarySearch`              | Search result for a number in an array of integers.                                                      | [here](BinarySearch.md)              |
| `MaxSubArraySum`            | Find the maximum continuous sub array sum in a given array.                                              | [here](MaxSubArraySum.md)            |
| `FindMaxSubArrayProduct`    | Find the maximum continuous sub array product in a given array of fixed length and no length constraint. | [here](FindMaxSubArrayProduct.md)    |
| `Exponent`                  | Calculate exponents of natural numbers.                                                                  | [here](Exponent.md)                  |
| `FindPhrase`                | Find number of occurrences of a smaller string in a bigger string.                                       | [here](FindPhrase.md)                |
| `Find2DMatrixSum`           | Find sum of 2d matrix with long and int return types.                                                    | [here](Find2DMatrixSum.md)           |
| `CountDistinctElements`     | Returns the number of distinct elements in an integer array                                              | [here](CountDistinctElements.md)     |
| `CountSorting`              | Returns the sorted array after sorting via count sort algorithm                                          | [here](CountSorting.md)              |
| `MatrixMultiplication2D`    | Returns the multiplied matrix (if possible or returns null)                                              | [here](MatrixMultiplication2D.md)    |
| `PerfectPowerAlgorithm`     | Returns the root and the exponent in an array of size 2 for a given natural number n (or null)           | [here](PerfectPowerAlgorithm.md)     |

## Documentation
Kindly refer the [docs](docs/ReadMe.md).

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

**Algorithmics** is under *MIT License*. See **[License](License.md)** for more info.

## Contributing guide

Do you want to contribute to Algorithmics? Awesome, there are not many rules but just a few things to consider before making a PR, simply refer to [CONTRIBUTING.md](./CONTRIBUTING.md) and some guidelines in the available issues.

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you're new to GitHub and/or contributing to open source projects, please refer this [resource](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

## Checkstyle guide

This repository follows the [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html). Feel free to download formatting presets for your IDE from [Google's GitHub repository](https://github.com/google/styleguide).
We have set up [checkstyle](https://github.com/Pradyuman7/Algorithmics/blob/master/checkstyle.xml) to enforce them throughout this project. You can check locally if your changes comply with these guidelines by executing the maven goal `compile`. If the build of your Pull Request fails make sure to checkout the logs in the checks of your Pull Request to see what exactly does not comply with our guidelines. If you think that you are still complying with the guidelines, feel free to make corresponding changes to our [checkstyle file](https://github.com/Pradyuman7/Algorithmics/blob/master/checkstyle.xml).
