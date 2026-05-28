# Movie Theater Ticket Sales System

A Java-based movie theater management application for selling tickets, managing theater showings, calculating ticket prices, and generating sales reports.

This project demonstrates object-oriented programming, file processing, arrays, user input handling, and basic reporting logic in Java.

## Overview

Movie Theater Ticket Sales System is a Java application designed to help a cinema complex manage ticket sales across multiple theaters. The system supports different movies, showtimes, ticket categories, theater types, and pricing rules.

The application allows users to select a theater, choose a movie and showtime, calculate ticket prices, and record sales information for later analysis.

## Features

* Manage multiple theaters in a cinema complex
* Support movies showing in more than one theater
* Store movie details including title, length, genre, and rating
* Store showtimes for each movie
* Support different ticket categories:

  * Child
  * Adult
  * Senior
  * Matinee
* Apply higher fixed pricing for luxury theaters
* Calculate ticket prices based on age category, showtime, and theater type
* Track tickets sold by category, movie, and theater
* Output sales reports to files
* User-friendly console-based interface

## Tech Stack

* Java
* Object-Oriented Programming
* Arrays
* Scanner Input
* File Processing
* PrintWriter
* Command-Line Interface

## Repository Structure

```text
Movie-Theater-Ticket-Sales-System/
├── README.md
├── src/
│   └── Java source files
├── input/
│   └── sample input files, if included
├── output/
│   └── generated sales reports, if included
└── docs/
    └── project documentation, if included
```

## Main Classes

### Movie

Stores information about each movie, including:

* Title
* Length
* Genre
* Rating
* Showtimes

### Theater

Stores information about each theater, including:

* Theater number
* Theater name
* Whether the theater is luxury
* Movies playing in that theater

### CinemagicClient

Provides the console-based user interface. It guides users through theater selection, movie selection, ticket category selection, and ticket price calculation.

## How It Works

1. The user opens the program through the command-line interface.
2. The program displays available theaters and movies.
3. The user selects a theater, movie, and showtime.
4. The user selects ticket categories such as child, adult, senior, or matinee.
5. The system calculates the ticket price based on the selected options.
6. Ticket sale data is recorded.
7. Sales reports can be written to files for later analysis.

At a high level, the project follows this flow:

```text
User Selection → Theater + Movie Lookup → Ticket Price Calculation → Sale Recording → Report Output
```

## Key Concepts Demonstrated

* Object-oriented class design
* Encapsulation through custom classes
* Arrays of objects
* Console input using `Scanner`
* File output using `PrintWriter`
* Conditional pricing logic
* Report generation
* Team-based software development

## Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Movie-Theater-Ticket-Sales-System.git
cd Movie-Theater-Ticket-Sales-System
```

### 2. Compile the project

If the source files are inside `src/`, use:

```bash
javac src/*.java
```

### 3. Run the client program

```bash
java -cp src CinemagicClient
```

Adjust the command if the main class or package structure is different.

## Testing

Testing focused on verifying that the system correctly handles:

* Theater selection
* Movie selection
* Multiple showtimes
* Different ticket categories
* Matinee pricing
* Luxury theater pricing
* Ticket sales tracking
* File output for reports
* Invalid or unexpected user input

## What I Learned

Through this project, I strengthened my understanding of:

* Designing Java programs with multiple interacting classes
* Translating requirements into an object-oriented design
* Using arrays to store related objects
* Handling user input through a console interface
* Writing output reports to files
* Collaborating with teammates on a shared programming project
* Documenting requirements, design, implementation, and testing

## Future Improvements

* Add a graphical user interface
* Replace arrays with more flexible collection types
* Add persistent storage for movies, theaters, and sales
* Add admin functionality for updating showtimes and prices
* Improve input validation and error messages
* Add automated unit tests
* Add more detailed sales analytics and visual reports

## Portfolio Note

This is a cleaned portfolio version of a Java programming project. Course-specific instructions, assignment text, and restricted materials have been removed. The repository is intended to demonstrate Java object-oriented programming, file processing, ticket pricing logic, and team-based software development.

## Contributors

* Shreeya Wadodkar
* Anthony Ma
* Jayani Sivakumar
* Essence Hill

## Author

Jayani Sivakumar
Computer Science, North Carolina State University
