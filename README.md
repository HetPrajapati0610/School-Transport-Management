# School Transport Management

A console-based C++ application for managing school transport records. The program lets an operator register students, drivers, buses, and routes; assign students to valid routes; view records; and save information for later use.

## Features

- Register students, drivers, buses, and transport routes
- Assign students to routes after validating the route and available bus capacity
- Prevent duplicate student, driver, bus, and route IDs
- Validate related records such as routes, buses, and drivers
- View student, driver, bus, and route records from the menu
- Save and reload data using text files
- Demonstrate encapsulation, inheritance, runtime polymorphism, dynamic memory, constructors, destructors, and file handling

## Requirements

- A C++17-compatible compiler, such as `g++`

## Compile and Run

Open a terminal in the `source_code` folder and run:

```bash
g++ -std=c++17 -Wall -Wextra -pedantic SchoolTransportManagement.cpp -o school_transport
./school_transport
```

On Windows, run:

```bash
school_transport.exe
```

## Menu Options

1. Add Student
2. Add Driver
3. Add Bus
4. Add Route
5. Assign Student to Route
6. View Students
7. View Drivers
8. View Buses
9. View Routes
0. Save and Exit

## Project Structure

```text
School_Transport_Management_Submission/
├── source_code/
│   ├── SchoolTransportManagement.cpp
│   ├── students.txt
│   ├── drivers.txt
│   ├── buses.txt
│   └── routes.txt
├── diagrams/
│   ├── UseCaseDiagram.png
│   ├── ClassDiagram.png
│   ├── SequenceDiagram1.png
│   └── SequenceDiagram2.png
├── screenshots/
└── documents/
```

## Data Storage

The program stores records in four pipe-separated text files:

- `students.txt`
- `drivers.txt`
- `buses.txt`
- `routes.txt`

The files are loaded when the program starts and updated after successful changes or when the program exits.

## UML Diagrams

The project includes a use case diagram, class diagram, and two sequence diagrams in the `diagrams` folder.

## Author

**Name:** Add your name here  
**Enrollment Number:** IU2541230070  
**Course:** CPP46 C++ Guided Project
