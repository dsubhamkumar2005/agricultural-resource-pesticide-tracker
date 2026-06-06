# Agricultural Resource and Pesticide Tracker

## Overview

The Agricultural Resource and Pesticide Tracker is a C++ console-based application designed to assist farmers and agricultural professionals in monitoring plant health and managing pesticide usage efficiently.

The system records plant information, analyzes infection levels, classifies plant conditions, and recommends suitable actions based on plant health.

---

## Features

- Add plant records
- Update plant information
- Search plants using Plant ID
- Generate plant health reports
- Analyze infection levels
- Recommend pesticide actions
- Save records to files
- Load records from files

---

## Technologies Used

- C++
- Object-Oriented Programming
- File Handling
- Exception Handling

---

## OOP Concepts Implemented

### Inheritance

- `Plant` inherits from `plant_base`
- `FileStorage` inherits from `Plant`

### Polymorphism

- Virtual function `reviewPlant()`
- Runtime polymorphism through base class pointers

### Encapsulation

- Plant data and operations are grouped into classes

### Exception Handling

- Validation of Plant ID
- Validation of Infection Levels

### Constructors

- Default constructors used for initialization

### File Handling

- Save plant records
- Load plant records
- Append plant records

---

## System Modules

### Plant Data Management

- Add new plant records
- Update plant details
- Delete and maintain records

### Search and Display

- Search plants using Plant ID
- Display stored plant information

### Analysis and Report Generation

- Analyze infection levels
- Generate health reports
- Suggest pesticide recommendations

### File Storage

- Save records to file
- Load records from file
- Append records

---

## Plant Health Classification

| Infection Level | Condition |
|---------------|-----------|
| 0 - 10 | Healthy |
| 11 - 30 | Mild Infection |
| 31 - 65 | Moderate Infection |
| Above 65 | Critical Condition |

---

## Applications

- Agricultural Monitoring
- Crop Health Analysis
- Pesticide Management
- Farm Record Keeping

---

## Author

D Subham Kumar
