# Online Job Portal System
### A C++ Object-Oriented Programming Project

---

## Overview

The **Online Job Portal System** is a console-based application developed in **C++**, designed to simulate a real-world job recruitment platform. It enables seamless interaction between **Job Seekers**, **Employers**, and **Administrators** through a structured, menu-driven interface.

The project demonstrates the implementation of **Object-Oriented Programming (OOP)** concepts, **file handling**, **data validation**, and **exception management**. It is a practical example of applying C++ programming principles to build a scalable and interactive system.

---

## Features

### For Employers
- Register and log in securely.
- Post new job openings with detailed information.
- View, edit, or delete posted jobs.
- Review applications submitted by job seekers.
- Select or reject candidates after reviewing applications.
- Maintain a company profile with description and location details.

### For Job Seekers
- Register and log in to the system.
- Create and manage profiles including education, skills, and experience.
- Apply for available jobs and upload resume and cover letter.
- View application status (Pending, Selected, or Rejected).
- Update personal information and resume.
- Search and explore available jobs.

### For Administrators
- Register and log in securely.
- View all registered employers and job seekers.
- Remove inactive or inappropriate user accounts.
- Review and delete jobs if necessary.
- Generate a comprehensive system report containing job and user statistics.

---

## Object-Oriented Concepts Implemented

| Concept | Description |
|----------|--------------|
| **Encapsulation** | Data and related functions are contained within classes, ensuring modularity and data protection. |
| **Inheritance** | Derived classes such as `employer`, `jobseeker`, and `admin` inherit common functionality from base classes. |
| **Polymorphism** | Overridden methods allow for specialized behavior across different user roles. |
| **Abstraction** | Users interact with high-level menus, hiding underlying implementation details. |
| **Composition** | Logical relationships between entities (e.g., employers owning job postings) are modeled effectively. |

---

## Data Management

The system uses **CSV files** for persistent data storage, ensuring that user and job data remain available even after the program terminates.

Files used:
- `jobseekers.csv` – stores job seeker information
- `employers.csv` – stores employer data
- `jobs.csv` – stores job postings
- `admins.csv` – stores admin credentials

---

## Technical Implementation

- **Language:** C++
- **Paradigm:** Object-Oriented Programming
- **File Handling:** Implemented using `fstream` for reading and writing CSV files.
- **Error Handling:** Achieved through `try-catch` blocks and exception classes like `invalid_argument`.
- **Data Structures:** Utilizes `vector`, `string`, `stringstream`, and `fstream`.
- **Interface:** Menu-driven, console-based system with input validation and data verification.

---

## Project Structure

Online Job Portal/
│
├── main.cpp # Complete implementation
├── jobseekers.csv # Job seeker profiles
├── employers.csv # Employer data
├── jobs.csv # Job listings
├── admins.csv # Admin credentials
└── README.md # Documentation

yaml
Copy code

---

## How to Run

1. **Clone or Download the Project**
   ```bash
   git clone https://github.com/yourusername/Online-Job-Portal.git
   cd Online-Job-Portal
## Learning Outcomes

- Applied object-oriented design principles to develop a real-world application.  
- Gained proficiency in C++ file handling and data persistence techniques.  
- Strengthened understanding of exception handling and input validation.  
- Designed a multi-user system demonstrating inheritance, encapsulation, and polymorphism.  
- Practiced developing structured and maintainable code following modular programming practices.  

## Future Enhancements

- Integrate with a database system (MySQL or SQLite) for better scalability.  
- Develop a graphical user interface (GUI) using frameworks like Qt or FLTK.  
- Implement email notifications for job updates.  
- Add advanced search filters and AI-based job recommendations.  
- Create a web-based version using modern web technologies.  

---

## Author

**Shivang Tonde**  
Department of Computer Science and Engineering  
_Interested in software development, system design, and real-world C++ applications._
