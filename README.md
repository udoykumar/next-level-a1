# TypeScript Assignment - Level 2, Assignment 1

This repository contains the solutions for the TypeScript beginner exercises and technical blog posts as part of the Level 2 assignment.

## Table of Contents

- [Project Overview](#project-overview)
- [Solutions](#solutions)
- [Blog Posts](#blog-posts)
- [How to Run](#how-to-run)

## Project Overview

This project demonstrates proficiency in TypeScript's core concepts, including type guards, generics, interfaces, classes, and inheritance. It also includes two technical blog posts aimed at developers transitioning to TypeScript.

## Solutions

The `solutions.ts` file contains the following TypeScript functions and classes:

1.  **filterEvenNumbers**: A function that takes an array of numbers and returns only the even ones.
2.  **reverseString**: A function that reverses any given string.
3.  **checkType**: A type guard function that identifies whether a value is a `string` or a `number`.
4.  **getProperty**: A generic function that safely retrieves a property value from an object based on its key.
5.  **toggleReadStatus**: A function that updates the `isRead` status of a `Book` object.
6.  **Person & Student Classes**: Demonstrates class inheritance where `Student` extends `Person` and adds a `getDetails` method.
7.  **getIntersection**: A function that returns an array containing common elements from two input arrays.

## Blog Posts

There are two technical blog posts included in this repository:

1.  **[blog-1.md](./blog-1.md)**: _Learning TypeScript: Why "any" is the Forbidden Fruit (and what to use instead)_. This post explores the dangers of using the `any` type and introduces `unknown` as a safer alternative.
2.  **[blog-2.md](./blog-2.md)**: _TypeScript Generics: One Function to Rule Them All_. An introductory guide to understanding and implementing Generics in TypeScript for reusable and type-safe code.

## How to Run

To run the TypeScript code locally, follow these steps:

1.  **Install TypeScript** (if not already installed):

    ```bash
    npm install -g typescript
    ```

2.  **Compile the solutions**:

    ```bash
    tsc solutions.ts
    ```

3.  **Run with Node.js**:
    ```bash
    node solutions.js
    ```

Alternatively, you can use `ts-node` to run the file directly:

```bash
npx ts-node solutions.ts
```
