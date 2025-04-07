# Review Lab (Individual Work)

**Name:** *Renata Toleugazina*  
**Student Number:** *125098228*  

---

## Part 1: Create a Question

**Topic:** *Domain Layer Patterns*  
**Question Type:** *In-Depth Question (Why)*

> **Why is the Domain Model pattern considered a better architectural choice than the Transaction Script pattern for handling complex business logic in enterprise applications?*

---

## Part 2: Answer Your Question

### Why is the Domain Model pattern considered a better architectural choice than the Transaction Script pattern for handling complex business logic in enterprise applications?

The **Domain Model pattern** is considered a better fit than the **Transaction Script pattern** in complex applications for several important reasons:

---

### 1. Separation of Concerns  
The Domain Model pattern organizes business logic within domain objects, keeping it separate from infrastructure and application coordination logic. This results in cleaner, more maintainable code.  
Transaction Scripts often combine coordination and logic, leading to tangled code.

---

### 2. Maintainability and Testability  
By encapsulating logic inside domain entities, the Domain Model enables focused unit testing and easy modifications.  
Transaction Scripts are harder to isolate and test as they grow in size and scope.

---

### 3. Reusability and Rich Behavior  
Domain Models allow objects to hold behavior along with data, making them reusable and expressive.  
In contrast, Transaction Scripts are procedural and typically repeat logic across different workflows.

---

### 4. Scalability with Complexity  
As business logic becomes more intricate, the Domain Model handles complexity more gracefully by organizing rules into relevant domain structures.  
Transaction Scripts become large, cluttered, and harder to manage.

---

### 5. Alignment with Domain-Driven Design  
The Domain Model pattern supports Domain-Driven Design, where the software closely models real-world business rules.  
This keeps the system aligned with business needs and easier to evolve over time.

---

### onclusion  
While Transaction Scripts work for simple applications, the Domain Model pattern is the better choice for scalable, testable, and maintainable systems that must handle complex business logic.
