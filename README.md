# Namal Mess Management System - Project Documentation

This repository contains the comprehensive documentation and design artifacts for the **Namal Mess Management System**. This project aims to streamline and automate the operations of a university mess, providing efficient management of menus, orders, payments, and user interactions. This documentation serves as a foundational resource for understanding the system's requirements, design, and testing phases, adhering to professional software engineering standards.

## Project Metadata

* **Students:** Muhammad Raqib Hayat, Abu Bakar
* **Instructor:** Muhammad Ali Shahid
* **Course:** CS-260 - Software Engineering
* **Semester:** 6th, Spring 2025
* **Institution:** Namal University, Mianwali

## Project Overview

The Namal Mess Management System is designed to modernize and simplify the traditional mess management processes within a university setting. It provides a robust platform for students/faculty (customers) to browse menus, place orders, track their order status, manage their wallets, and view their order history. For mess managers, it offers tools for user registration, report generation, transaction management, and sending notifications. Menu managers can create and edit menus, manage food items, and set item prices, while kitchen staff can view and update order statuses. The system aims to enhance efficiency, transparency, and user satisfaction in mess operations.

## Key Documents and Diagrams

This repository is structured to provide a clear and detailed insight into the project's lifecycle, from requirements gathering to design and testing. Below is a list of the key documents and diagrams included, each serving a unique purpose in the software development process.

### 1. Software Requirement Specification (SRS)

**File:** `Namal Mess Mangement System Documents/Software Requirement Specification for Namal Mess Management System.pdf`

The SRS document is a comprehensive description of the functional and non-functional requirements of the Namal Mess Management System. It details the system's purpose, scope, intended audience, and the various features it will offer, such as user authentication, menu management, order processing, payment systems, reporting, notifications, and user profile management. This document serves as a foundational agreement between stakeholders and the development team, ensuring a clear understanding of what the system is intended to do.

### 2. Software Design Document (SDD)

**File:** `Namal Mess Mangement System Documents/Software Design Document Namal Mess Management System.pdf`

The SDD outlines the architectural and detailed design of the Namal Mess Management System. It covers the system context, user roles, interfaces, and the chosen architectural patterns (Client-Server, MVC). The document breaks down the system into various subsystems like Authentication, Menu Management, Order Processing, Payment, Notification, Reporting, and User Profile Management. It also details the data design, including database structure and relationships, and provides insights into component-level design and implementation details. This document is crucial for developers to understand how the system is structured and how its various components interact.

### 3. Software Testing Report (STR)

**File:** ` Namal Mess Mangement System Documents/Software Testing Report Namal Mess Management System.pdf`

The STR provides a detailed account of the testing activities performed on the Namal Mess Management System. It covers the test objectives, scope of testing, and the various types of testing conducted, including Unit Testing, Integration Testing, System Testing, Acceptance Testing, and UI/UX Testing. The report also lists the tools and frameworks used for testing, provides test case designs for different functionalities, summarizes test execution, and discusses test coverage. It concludes with a summary of testing outcomes, current system quality level, known issues, and recommendations for future improvements. This document is vital for quality assurance and for understanding the system's stability and reliability.

### 4. Diagrams

The repository includes a variety of diagrams to visually represent the system's structure, behavior, and data flow. These diagrams are essential for a quick and intuitive understanding of the system's complexities.

* **Use Case Diagram:** `Namal Mess Mangement System Diagrams/use_case_diagram.png`
  This diagram illustrates the functional scope of the system by showing the interactions between different types of users (actors) and the system's functionalities (use cases). It provides a high-level view of what the system does from an external perspective.
* **Class Diagram:** `Namal Mess Mangement System Diagrams/class_diagram.png`
  The Class Diagram presents the static structure of the system, showing the classes, their attributes, operations (methods), and the relationships among them. It is fundamental for understanding the object-oriented design and the underlying data model of the system.
* **Level 0 DFD (Context Level DFD):** `Namal Mess Mangement System Diagrams/Level_0_DFD.png`
  This Data Flow Diagram (DFD) provides a top-level view of the system, illustrating the main processes and external entities that interact with the Namal Mess Management System. It shows the overall data flow into and out of the system.
* **Level 1 DFD:** `Namal Mess Mangement System Diagrams/level_1_DFD.png`
  The Level 1 DFD decomposes the main process of the Level 0 DFD into more detailed sub-processes, showing the data stores and data flows within the system. It offers a more granular understanding of how data moves and is transformed within the system.
* **Login Sequence Diagram:** `Namal Mess Mangement System Diagrams/login_sequence.png`
  This sequence diagram illustrates the interactions between the user and the system during the login process, detailing the sequence of messages exchanged between objects to achieve the login functionality.
* **Order Delivery Sequence Diagram:** `Namal Mess Mangement System Diagrams/order_delivery.png`
  This diagram visualizes the sequence of operations involved in the order delivery process, showing how different system components interact to ensure successful order fulfillment and payment processing.
* **Place Order Sequence Diagram:** `Namal Mess Mangement System Diagrams/place_order_seq.png`
  This sequence diagram details the steps and interactions involved when a customer places an order, including menu browsing, item selection, cart management, and order confirmation, along with wallet balance checks.

## Tools and Methodologies Used

This project adheres to standard software engineering practices and methodologies to ensure a structured and efficient development process. Key aspects include:

* **UML (Unified Modeling Language):** Extensively used for creating various diagrams such as Use Case Diagrams, Class Diagrams, and Sequence Diagrams, providing a standardized visual representation of the system's design and behavior.
* **Data Flow Diagrams (DFD):** Utilized to illustrate the flow of data within the system, from external entities to internal processes and data stores, at both context (Level 0) and detailed (Level 1) levels.
* **Agile Principles:** While not explicitly detailed in the documentation, the iterative nature of software development and the focus on clear requirements and design suggest an underlying adherence to agile principles, allowing for flexibility and responsiveness to change.
* **Comprehensive Documentation:** Emphasis on detailed documentation (SRS, SDD, STR) ensures clarity, maintainability, and traceability throughout the project lifecycle.

## Intended Use and Audience

This documentation repository is primarily intended for:

* **Software Developers:** To understand the system requirements, architectural design, and detailed component designs for implementation and maintenance.
* **Quality Assurance (QA) Engineers:** To comprehend the testing scope, test cases, and overall quality of the system, facilitating effective testing and validation.
* **Project Managers:** To gain a holistic view of the project, track progress, and ensure alignment with initial requirements and objectives.
* **Academic Researchers/Students:** As a case study for understanding the practical application of software engineering principles, documentation standards, and system design methodologies.
* **Stakeholders/Clients:** To review the system's proposed functionalities, design choices, and testing outcomes, ensuring the developed solution meets their expectations and business needs.

## License

This project documentation is provided under the [MIT License](LICENSE). While the documentation is openly accessible, its use for academic purposes should appropriately cite the original authors and institution. For commercial use or redistribution, please contact the authors for explicit permission.

## Acknowledgements

We extend our sincere gratitude to **Dr. Muhammad Ali Shahid**, our instructor for the CS-260 Software Engineering course at Namal University, Mianwali, for his invaluable guidance, support, and mentorship throughout the development of this project. His expertise and insights were instrumental in shaping the system's design and ensuring adherence to rigorous software engineering principles.

## Conclusion

This repository serves as a central hub for all documentation related to the Namal Mess Management System. It reflects a diligent application of software engineering best practices, from detailed requirements elicitation to robust design and thorough testing. The artifacts contained herein are crucial for anyone involved in the project, providing a clear, concise, and comprehensive understanding of the system. We believe this documentation will facilitate seamless collaboration, efficient development, and successful deployment of the Namal Mess Management System.
