# Movie Theater Ticket Sales

A Java console application for managing movie theater ticket sales, movie showings, theater information, and ticket pricing.

This project demonstrates object-oriented programming, arrays, console input, ticket price calculation, file/report planning, and JUnit-based testing in Java.

## Overview

Movie Theater Ticket Sales is a Java application designed for a cinema complex that manages multiple theaters, movies, showtimes, and ticket categories. The system supports different pricing rules based on patron type, matinee status, and luxury theater options.

The goal of this project was to translate a set of real-world requirements into an object-oriented Java program with separate classes for movies, theaters, client interaction, and testing.

## Features

* Console-based movie theater ticket sales system
* Stores movie information such as title, length, genre, rating, and showtimes
* Supports multiple theaters in a cinema complex
* Allows the same movie to appear in more than one theater
* Supports ticket pricing for different patron categories
* Includes matinee pricing logic
* Supports luxury theater pricing
* Tracks ticket sales information for analysis
* Includes JUnit test files for validating program behavior

## Tech Stack

* Java
* Object-Oriented Programming
* Arrays
* Scanner Input
* JUnit
* Console Application Design
* File/Report Output Planning

## Repository Structure

```text
Movie-Theater-Ticket-Sales/
├── README.md
├── CinemagicClient.java
├── CinemagicClientTest.java
├── Movie.java
├── TheaterTest.java
├── client-idea.md
└── junit-platform-console-standalone-1.6.2.jar
```

> Note: Compiled `.class` files should generally be removed from the public repository because they can be regenerated from the `.java` source files.

## Main Classes

### `Movie.java`

Represents a movie shown in the cinema complex.

Stores information such as:

* Movie title
* Movie length
* Genre
* Rating
* Showtimes

### `Theater.java`

Represents an individual theater in the cinema complex.

Stores information such as:

* Theater number
* Theater name
* Whether the theater is a luxury theater
* Movies assigned to that theater

### `CinemagicClient.java`

Provides the main console-based user interface.

Handles:

* Theater selection
* Movie selection
* Showtime selection
* Ticket category input
* Ticket price calculation
* User interaction flow

### Test Files

The project includes test files such as:

* `CinemagicClientTest.java`
* `TheaterTest.java`

These tests help validate expected behavior for core program logic.

## How It Works

1. The user runs the console application.
2. The program displays available theater and movie options.
3. The user selects a theater, movie, and showtime.
4. The user enters ticket information based on patron type.
5. The system calculates the ticket price using the selected options.
6. Ticket sales information can be used for reporting and analysis.

At a high level, the system follows this flow:

```text
User Input → Theater Selection → Movie Selection → Ticket Pricing → Sale Tracking → Report Planning
```

## Key Concepts Demonstrated

* Object-oriented class design
* Encapsulation through custom Java classes
* Arrays of objects
* Console input using `Scanner`
* Conditional logic for ticket pricing
* Test-driven validation with JUnit
* Requirement analysis and implementation planning
* Team-based software development

## Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Movie-Theater-Ticket-Sales.git
cd Movie-Theater-Ticket-Sales
```

### 2. Compile the Java files

```bash
javac *.java
```

### 3. Run the client program

```bash
java CinemagicClient
```

## Running Tests

If using the included JUnit standalone jar, tests can be run with a command similar to:

```bash
java -jar junit-platform-console-standalone-1.6.2.jar --class-path . --scan-class-path
```

The exact command may vary depending on your Java version and final file organization.

## What I Learned

Through this project, I strengthened my understanding of:

* Designing Java programs from written requirements
* Creating and using custom classes
* Storing related objects in arrays
* Building a console-based user interaction flow
* Writing conditional pricing logic
* Creating test files for Java classes
* Collaborating with a team on a programming project
* Documenting requirements, design, implementation, and testing decisions

## Future Improvements

* Remove compiled `.class` files from the repository
* Move the JUnit `.jar` file into a `lib/` folder
* Add a dedicated `src/` folder for source files
* Add a dedicated `test/` folder for test files
* Add file output for detailed ticket sales reports
* Add persistent storage for movie and theater data
* Replace arrays with Java collections for more flexible storage
* Add a graphical user interface
* Add more detailed sales analytics by movie, theater, and ticket category

## Portfolio Note

This is a cleaned portfolio version of a Java programming project. Course-specific instructions, assignment text, and restricted materials have been removed. The repository is intended to demonstrate Java object-oriented programming, console interaction, ticket pricing logic, and team-based software development.

## Contributors

* Shreeya Wadodkar
* Anthony Ma
* Jayani Sivakumar
* Essence Hill

## Author

Jayani Sivakumar
Computer Science, North Carolina State University
