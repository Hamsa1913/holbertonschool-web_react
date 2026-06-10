# holbertonschool-web_react

This repository contains TypeScript tasks completed as part of the Holberton School Web React curriculum.

## Project: TypeScript

The goal of this project is to practice TypeScript fundamentals and understand how TypeScript improves JavaScript development by adding strong typing, interfaces, classes, and safer code structure.

## Learning Objectives

By completing this project, I practiced:

* Basic TypeScript types
* Interfaces
* Classes
* Functions
* DOM manipulation with TypeScript
* Function interfaces
* Extending interfaces
* Advanced types
* Type predicates
* String literal types
* Ambient namespaces
* Declaration merging
* Namespaces
* Nominal typing using brand convention
* Webpack and TypeScript compilation

## Project Structure

```text
TypeScript/
├── task_0
├── task_1
├── task_2
├── task_3
├── task_4
└── task_5
```

## Tasks Overview

### Task 0: Creating an interface for a student

Created a `Student` interface and used TypeScript with DOM manipulation to render a table containing student names and locations.

### Task 1: Teacher Interface

Created a `Teacher` interface using:

* `readonly` properties
* optional properties
* dynamic properties using index signatures

### Task 2: Extending Interfaces

Created a `Directors` interface that extends the `Teacher` interface and adds `numberOfReports`.

### Task 3: Printing Teachers

Created a function interface named `printTeacherFunction` and implemented a function that returns a formatted teacher name.

### Task 4: Writing a Class

Created a `StudentClass` with:

* constructor
* methods
* class interface
* constructor interface

### Task 5: Advanced Types Part 1

Created `Director` and `Teacher` classes with interfaces and implemented a `createEmployee` function using union types.

### Task 6: Employee-Specific Functions

Created:

* `isDirector` type predicate
* `executeWork` function

This allowed TypeScript to safely determine whether an employee is a `Director` or a `Teacher`.

### Task 7: String Literal Types

Created a `Subjects` string literal type that only accepts:

```text
Math
History
```

### Task 8: Ambient Namespaces

Created type declarations for an external JavaScript file using a `.d.ts` file.

Files included:

* `interface.ts`
* `crud.js`
* `crud.d.ts`
* `main.ts`

### Task 9: Namespace and Declaration Merging

Created a `Subjects` namespace and used declaration merging to extend the `Teacher` interface across multiple subject files:

* `Cpp.ts`
* `Java.ts`
* `React.ts`
* `Subject.ts`
* `Teacher.ts`

### Task 10: Brand Convention and Nominal Typing

Created `MajorCredits` and `MinorCredits` interfaces using brand properties to distinguish between similar types.

## Technologies Used

* TypeScript
* JavaScript
* Webpack
* npm
* Node.js
* HTML
* Git
* GitHub

## How to Run a Task

Go to any task directory, for example:

```bash
cd TypeScript/task_0
```

Install dependencies:

```bash
npm install
```

Build the project:

```bash
npm run build
```

Run the development server:

```bash
npm run start-dev
```

Then open:

```text
http://localhost:8080
```

## Author

Hamsa Alammar
