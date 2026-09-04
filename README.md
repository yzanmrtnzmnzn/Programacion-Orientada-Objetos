# Subscription & Plan Management System (POO)

A modular, object-oriented system written in Java designed to manage user accounts, activity tracking, subscription plans, and dynamic cost calculations. This project demonstrates core Object-Oriented Programming (POO) principles including abstraction, encapsulation, inheritance, and interface-driven design.

---

## 🛠️ Tech Stack & Architecture

- **Language:** Java (JDK 8+)
- **Paradigm:** Object-Oriented Programming (POO)
- **Modeling:** UML (Unified Modeling Language) Architecture

---

## 📂 Repository Structure

The code is structured under the `UML/Model/` namespace:

```text
UML/
└── Model/
    ├── User.java                # Represents system users and personal details
    ├── Planes.java              # Abstract/Base representation of subscription plans
    ├── PlanesSubscritos.java   # Tracks active and historical user subscriptions
    ├── CostePlanes.java         # Handles pricing rules, discounts, and cost logic
    ├── Actividades.java         # Tracks user activities/usage linked to plans
    ├── Interfaz de Usuario.java # User interface / CLI interactions
    └── Interface1.java          # Service/Contract interface definition
