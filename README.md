# Gift Card Management System

> This project was developed during my **Software Development Engineer Internship
> at Youjia Gym**, focusing on building a production-style internal system to
> manage gift card and membership transactions.

---

## Overview

The Gift Card Management System is a Java-based desktop application designed to
manage multiple gift cards under a single account. The system supports balance
tracking, prioritized spending, transaction logging, and persistent storage,
simulating real-world retail and membership payment workflows.

The project emphasizes **object-oriented design**, **clean architecture**, and
**end-to-end ownership**, covering system design, implementation, testing, and
data persistence.

---

## Key Features

- Add, remove, and list multiple gift cards under one account
- Automatically prioritize gift cards with the **lowest balance** when completing payments
- Display total available balance across all gift cards
- Persist application state using **JSON-based storage** (save / load)
- Interactive desktop user interface built with **Java Swing**
- Event logging for gift card transactions (add, remove, payment)

---

## Tech Stack

- **Language:** Java
- **UI:** Java Swing
- **Persistence:** JSON serialization
- **Testing:** JUnit
- **Tools:** IntelliJ IDEA, Git

---

## System Design

- Designed core domain models including `Account`, `GiftCard`, `Transaction`,
  and `EventLog`
- Applied **Model–View separation** to decouple business logic from UI components
- Implemented a dedicated persistence layer for loading and saving application state
- Included UML diagrams to document class relationships and system architecture

---

## My Role & Contributions

- Designed and owned the system end-to-end, from initial design to implementation
  and testing
- Defined object-oriented domain models to ensure extensibility and maintainability
- Implemented **prioritized payment logic** to correctly handle multi-card transactions
- Built JSON-based persistence and recovery mechanisms to prevent data loss
- Developed an interactive Swing-based GUI to streamline front-desk workflows
- Wrote **50+ JUnit tests** to validate critical purchase, redemption, and refund scenarios

---

## How to Run

1. Clone the repository
2. Open the project in **IntelliJ IDEA**
3. Run `Main.java` from the `src/main/ui` directory
4. (Optional) Load an existing gift card list from file when prompted

---

## Future Improvements

- Refactor duplicated logic across gift card view components into reusable modules
- Allow users to initialize accounts with custom parameters instead of default values
- Extend transaction analytics and reporting capabilities
