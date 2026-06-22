# Task 2 - Data Model Implementation

Completed by: MPANGA BENARD

I implemented the ERD data model in the Spring application by creating JPA entity classes for the main business objects. I added `Client`, `Portfolio`, and `Security` entities and updated the existing `Advisor` entity so the Java classes match the database structure shown in the ERD.

Each entity is annotated with `@Entity`, uses an auto-generated id, and maps its fields with `@Column` or relationship annotations. I also added constructors, getters, and setters, and used relationships such as `@ManyToOne` and `@JoinColumn` to connect clients to advisors, portfolios to clients, and securities to portfolios.
