# Airline Reservation System

A console-based Airline Reservation System built using Core Java, demonstrating fundamental programming concepts and serving as a foundation for understanding larger reservation systems.

## 📋 Project Overview

This Java application simulates a basic airline reservation system where users can view seat availability and reserve seats on a flight. The system maintains seat status in memory and provides an intuitive console-based interface for user interactions.

## ✨ Features

- **Seat Reservation**: Reserve available seats by selecting seat numbers
- **Seat Status Viewing**: Display current status of all seats (Available/Reserved)
- **Interactive Console Menu**: User-friendly text-based interface
- **Input Validation**: Basic validation for menu choices
- **Persistent Session**: Maintains seat data during program execution

## 🛠️ Technical Specifications

- **Programming Language**: Java (Core Java)
- **Data Structure**: Boolean Array for seat management
- **Paradigm**: Procedural programming with static methods
- **Input Method**: Console-based using Scanner class
- **Memory Management**: In-memory data storage (volatile)

## 🚀 Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Any Java IDE (Eclipse, IntelliJ IDEA, NetBeans) or text editor
- Command Line/Terminal access

### Installation & Execution

1. **Clone or Download the project files**
2. **Compile the Java file:**
   ```bash
   javac AirlineReservationSystem.java
   
Run the application:
bash
java AirlineReservationSystem

💻 How to Use
Launch the application - The main menu will be displayed

Choose from the following options:

Press 1 to reserve a seat

Press 2 to view all seat statuses

Press 3 to exit the application

For seat reservation:

Select option 1 from the main menu

Enter the desired seat number (1-10)

Receive confirmation or error message based on availability

To check seat availability:

Select option 2 to see the current status of all seats

🏗️ System Architecture

AirlineReservationSystem
├── seats[] (boolean array)
├── main(String[] args)
│   ├── Menu Display Loop
│   ├── User Input Handling
│   └── Method Invocation
├── reserveSeat()
│   ├── Seat Availability Check
│   ├── Reservation Logic
│   └── User Feedback
└── viewSeats()
    ├── Array Iteration
    └── Status Display

🔧 Code Structure
Main Class: AirlineReservationSystem

Core Data: seats[] - boolean array tracking reservation status

Key Methods:

main(): Program entry point and main control loop

reserveSeat(): Handles seat booking logic

viewSeats(): Displays current seat map

⚠️ Limitations & Learning Scope
This is a educational implementation with the following limitations:

Volatile Storage: All data is lost when program terminates

Single Flight: Supports only one flight instance

Basic Error Handling: Limited input validation

No User Authentication: No login/security features

Console Interface: No graphical user interface

No Persistence: No database integration

🎯 Learning Objectives Achieved
Array manipulation and management

Console-based user input/output handling

Conditional logic implementation

Method decomposition and modular programming

Loop structures and control flow

Basic program state management

🔮 Future Enhancements
The following features can be added to extend this project:

Database integration for data persistence

Graphical User Interface (GUI) using Swing/JavaFX

Multiple flight management

Passenger information storage

Booking cancellation feature

Payment gateway integration

User authentication system

Advanced input validation and error handling

Flight scheduling capabilities

Email confirmation system

👨‍💻 Developer Information
Developed By: Khushi Malviya
Institution: VIT Bhopal University
Project Type: Academic Java Application



