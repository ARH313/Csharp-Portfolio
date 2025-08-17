# Csharp-Portfolio

These are small projects I built using **C#** and **.NET**. They cover OOP (classes, interfaces, polymorphism), operator overloading, and data access with Entity Framework (Code-First).

 Projects

1) Car Insurance (ASP.NET MVC)
- Repo: https://github.com/ARH313/CarInsuranceMVC
- What it is: An MVC app that collects policy info and calculates a quote using business rules. Includes an admin page to view issued quotes.
- Tech: C#, ASP.NET MVC, EF6, SQL Server (LocalDB)
- Highlights: Model binding, controllers/views, EF Code-First workflow.

2) Code-First Student DB (Console + EF6)
- Repo: https://github.com/ARH313/CodeFirstStudentDemo
- What it is: Console app that defines a `Student` class and **creates the DB/table from code** (Code-First), then inserts a student.
- Tech: C#, EF6, LocalDB
- Highlights: `DbContext`, `DbSet<>`, connection strings, `SaveChanges()`.

3) Operator Overloading – Employee Equality
- Repo: https://github.com/ARH313/OperatorsAssignment
- What it is: `Employee` class with overloaded `==` and `!=` that compare by `Id`.
- Tech: C#
- Highlights: Operator overloading, `Equals`/`GetHashCode` consistency, null-safety.

4) Polymorphism with Interfaces – IQuitable
- Repo: https://github.com/ARH313/PolymorphismAssignment
- What it is: `IQuitable` interface with `Quit()`. `Employee` implements it. Program calls `Quit()` **via the interface type** to demonstrate polymorphism.
- Tech: C#
- Highlights: Interfaces, interface-typed variables, polymorphism in practice.

---

## Skills Gained
- OOP in C#: classes, properties, methods, interfaces, polymorphism  
- Operator overloading and equality semantics  
- Entity Framework **Code-First** and data persistence  
- ASP.NET MVC patterns and LocalDB setup  
- Git/GitHub workflow (commit, push, README writing)

