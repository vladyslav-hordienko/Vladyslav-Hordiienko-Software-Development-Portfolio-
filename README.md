# Vladyslav-Hordiienko-Software-Development-Portfolio

## [SQL Helper](https://github.com/vladyslav-hordienko/SQL_Helper)

This project focuses on creating a safe environment for practising, validating, and troubleshooting SQL queries through a Python-based web application. A synthetic SQLite sales database containing customers, orders, products, payments, refunds, and employees is used to simulate realistic database tasks without relying on real or sensitive data.

SQL queries are processed with **SQLGlot**, which is used for parsing, formatting, and validation before execution. The application allows only read-only `SELECT` and `WITH` queries, while destructive commands are detected and blocked to protect the database.

The interface provides query-result previews, validation feedback, structured exercises, and trainer hints covering concepts such as `JOIN`, `GROUP BY`, `COUNT`, `SUM`, `AVG`, and filtering. The application structure was also prepared for **planned OpenAI API integration**, allowing an AI-based SQL tutor to be added through the backend.

**Tools:** Python, SQLite, SQLGlot, HTML, CSS, JavaScript

**Key Areas:** SQL Validation, Query Processing, Database Safety, Backend Logic, Input Handling, API Integration

---

## [Recipe Finder API](https://github.com/vladyslav-hordienko/Recipe-Finder-API)

Using **TheMealDB API**, this Java application retrieves recipe information from an external service and converts API responses into structured information that can be used within the application. HTTP requests and JSON processing are separated from the rest of the program logic to keep the application organised and easier to maintain.

Recipe information can also be stored locally, while application settings remain available between sessions through file-based persistence. This provides a combination of remote API data and locally managed application information.

Error handling was included to deal with unsuccessful requests, unavailable data, and unexpected responses without stopping normal application execution. The project provided practical experience connecting a Java application to an external service and working with structured web data.

**Tools:** Java, TheMealDB API, HTTP, JSON, File I/O

**Key Areas:** REST API Integration, JSON Parsing, Error Handling, Persistence, Modular Design, OOP

---

## [Robocode Autonomous Tank](https://github.com/vladyslav-hordienko/Robocode-Autonomous-Tank)

Created as a collaborative university project, this autonomous tank operates inside the **Robocode** environment and reacts dynamically to walls, collisions, enemies, and other events occurring during a battle.

My contribution concentrated on movement behaviour, including random and evasive movement, wall detection and avoidance, and reactions to collisions. These behaviours were tested and adjusted repeatedly so that the robot could continue operating without direct user control.

Because different components were developed by different team members, the project also required integrating code into a shared application and coordinating changes through Git. This introduced practical experience with collaborative development, event-driven behaviour, debugging, and working within an existing codebase.

**Tools:** Java, Robocode, Git

**Key Areas:** Event-Driven Programming, OOP, Team Development, Debugging, Autonomous Behaviour, Version Control

---

## [Inventory & Order Management System](https://github.com/vladyslav-hordienko/Inventory-Order-Management-System)

The system represents products, inventory, and customer orders through a structured object-oriented model. Products can be stored, searched, sorted, removed, and associated with orders while Java Collections are used to manage groups of objects efficiently.

Several OOP techniques are applied to protect and organise application data. Orders use immutable design and defensive copying, while `Comparable`, `equals()`, and `hashCode()` define how objects are compared, sorted, and identified within the program.

Information can also be written to files, allowing data to persist outside the running application. The project demonstrates how object relationships, collections, data integrity, and persistence can be combined within a larger Java program rather than implemented as isolated exercises.

**Tools:** Java, Java Collections, File I/O

**Key Areas:** OOP, Immutable Objects, Defensive Copying, Comparable, equals/hashCode, Data Persistence

---

## [Sorting Algorithms Benchmark](https://github.com/vladyslav-hordienko/Sorting-Algorithms-Benchmark)

To examine how algorithm choice affects performance, this project implements **Selection Sort, Quick Sort, and Merge Sort** and compares their execution across increasingly large arrays.

Quick Sort and Merge Sort use recursive divide-and-conquer approaches, while Selection Sort provides a simpler algorithm with different performance characteristics. Testing was performed across datasets reaching **100,000 elements**, making the difference between the algorithms visible through actual execution time.

Rather than treating computational complexity only as theory, the benchmark connects concepts such as recursion and algorithm efficiency with measurable program behaviour. It provides a practical comparison of how different approaches scale as the amount of data increases.

**Tools:** Java

**Key Areas:** Sorting Algorithms, Recursion, Computational Complexity, Performance Benchmarking, Algorithm Analysis

---

## [Custom Data Structures](https://github.com/vladyslav-hordienko/Custom-Data-Structures)

Rather than relying entirely on Java's built-in collection classes, this project implements commonly used data structures manually to understand how their internal operations work.

A generic array-backed stack is implemented through a custom `Stack<E>` interface, covering operations such as adding, removing, and accessing elements while handling structure limits and empty states. The project also includes a circular linked list built from linked nodes with custom insertion, removal, and traversal logic.

Working directly with indexes, generic types, object references, and nodes provided a clearer understanding of the mechanisms behind higher-level collection classes and the importance of correctly handling boundary conditions.

**Tools:** Java

**Key Areas:** Data Structures, Generics, Interfaces, Stack, Circular Linked List, Node Traversal

---

## [Higher or Lower Card Game](https://github.com/vladyslav-hordienko/Higher-or-Lower-Card-Game)

An interactive console application based around predicting whether the next randomly generated card will be higher or lower than the current one. The program manages the complete game flow, including user choices, random card generation, scoring, and progression between rounds.

Input validation prevents incorrect values from interrupting execution, while session statistics track player performance throughout the game. Player levels are determined from results, adding another layer of state and conditional logic to the application.

The interface also includes messages in **English, Irish, and German**, together with console formatting to improve readability. The project combines user interaction, validation, randomisation, statistics, and application state within one complete program.

**Tools:** Java

**Key Areas:** Application Logic, Input Validation, Randomisation, State Management, Statistics, Console UI

---

## [Building Management OOP](https://github.com/vladyslav-hordienko/Building-Management-OOP)

This project models different residential and commercial buildings through a hierarchy of related Java classes. Shared properties and behaviour are represented through inheritance, while composition is used where objects contain or depend on additional domain objects.

Specialised classes override inherited behaviour where necessary, while overloaded constructors provide different ways of creating objects. Java Collections are used to store and manage groups of buildings within the application.

Search functionality also allows properties to be located through identifiers such as **Eircodes**. The project was primarily focused on applying inheritance, composition, encapsulation, and object relationships to a structured real-world model.

**Tools:** Java, Java Collections

**Key Areas:** OOP, Inheritance, Composition, Method Overriding, Constructor Overloading, Object Modelling

---

## [Student Card System](https://github.com/vladyslav-hordienko/Student-Card-System)

Students and their associated card records are represented as connected objects, with encapsulation controlling how information is stored and modified throughout the application.

Composition links student and card information together, while several values are derived automatically from existing data rather than being entered independently. `LocalDate` is used to work with date-based information related to student card records.

The application also keeps related information synchronised when underlying data changes, helping prevent inconsistent values between connected objects. This project provided practice with class relationships, constructors, derived fields, date handling, and maintaining consistent object state.

**Tools:** Java, Java Date API

**Key Areas:** Encapsulation, Composition, Object Relationships, LocalDate, Data Synchronisation, OOP

