# math-stat

> Easy to use typescript math library

![coverage](https://img.shields.io/badge/coverage-100%25-brightgreen.svg)
[![Github Issues](https://img.shields.io/github/issues-raw/turtledev1/math-stat.svg)](https://github.com/turtledev1/math-stat/issues)
[![Pending Pull-Requests](https://img.shields.io/github/issues-pr-raw/turtledev1/math-stat.svg)](https://github.com/turtledev1/math-stat/pulls)

## Table of Contents

- [Example](#example)
- [Installation](#installation)
- [Features](#features)
- [FAQ](#faq)
- [Support](#support)


---

## Example

```javascript
import { Matrix } from "math-stat";

let matrix = new Matrix([[1, 2, 3], [4, 5, 6], [7, 8, 9]]);
let matrix2 = new Matrix([[2, 4], [5, 7]]);

console.log(matrix.multiply(matrix2).toString());
```



## Installation

```javascript
npm install math-stat
```



## Features

- **Completed**
    - Matrices
    - Vectors
    - Fractions

- **Work in progess**


- **Incoming**
    - Statistic



## FAQ

- **How to make VSCode Intellisense suggest typed-math typings?**
    - Check if in your tsconfig you have "typeRoots": ["./node_modules"] and "moduleResolution": "node"



## Support

Create an issue in this repo mentionning the version of the package.


---
