🎬 Movie Review and Recommendation System (DBMS Project)

This repository contains the **Database Management Systems (DBMS)** project titled  
**“Movie Review and Recommendation System.”**  
The project focuses on designing a complete relational database that supports movie reviews, ratings, watchlists, and user–movie interactions.

This repository includes the **project documentation**, ERD, schema design explanation, and SQL concepts applied throughout the system.

📌 Project Overview

**Course:** Database Management Systems  
**Project:** Movie Review and Recommendation System  

This project focuses mainly on **database design**, including:

- Entity–Relationship modeling  
- Database schema design  
- Defining relationships and constraints  
- Writing SQL queries  
- Using MySQL DDL & DML features  

The system models real-world interactions between users and movies, allowing reviews, ratings, genres, and watchlist management.

🧱 Entities in the System

The database includes the following core entities:

**1️⃣ USERS**
- Stores user profile data  
- Attributes: Username, Email, Preferences  

**2️⃣ MOVIES**
- Stores general movie information  
- Attributes: Title, Year, Director, GenreID  

**3️⃣ GENRES**
- Category list such as Action, Comedy, Drama, etc.

**4️⃣ REVIEWS**
- Stores user-written text reviews  

**5️⃣ RATINGS**
- Numerical rating (0–10) given by a user  

**6️⃣ WATCHLISTS**
- Tracks movies users want to watch or have watched  

🔗 Relationships

- A **USER** writes multiple **REVIEWS**  
- A **USER** gives **RATINGS** to multiple MOVIES  
- A **USER** maintains a **WATCHLIST**  
- Each **MOVIE** belongs to one **GENRE**  
- A **USER** can watch multiple MOVIES  

The ER diagram in the document clearly represents these relationships.

🛠 SQL Concepts Covered

The project uses MySQL with the following features:

**DDL (Data Definition Language)**  
- `CREATE TABLE`  
- `ALTER TABLE`  
- PRIMARY KEY, FOREIGN KEY  
- CHECK constraints  
- ENUM  
- Data types and indexing  

**DML (Data Manipulation Language)**  
- `INSERT`, `UPDATE`, `DELETE`  
- `SELECT` queries with conditions  

**JOINs & Query Techniques**
- INNER JOIN  
- LEFT JOIN  
- RIGHT JOIN  
- FULL JOIN (via UNION)  
- Aggregation functions (COUNT, AVG, MAX, MIN, SUM)  
- GROUP BY & HAVING  
- Nested queries  
- Correlated subqueries  
- VIEWS  
- Stored Procedures  

🎯 Purpose of the Project

- Practice database modeling  
- Understand entity relationships  
- Write complex SQL queries  
- Learn real-world DB design techniques  
- Build a scalable, normalized database
- 
📝 Conclusion

This project demonstrates a complete understanding of DBMS concepts, including:

- ERD development  
- Schema design  
- Relational integrity  
- SQL operations and constraints  
- Real-world system analysis  

It serves as an academic DBMS project showcasing proper backend database structure and SQL knowledge.

👩‍💻 Author

Manahil Rizvi
BS Computer Science (UCP) 
5th Semester 
---

## 📄 Contents of This Reposi
