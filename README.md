# MongoDB Checkpoint Project

## Overview

This project demonstrates basic MongoDB operations using MongoDB Atlas cloud service. The goal was to practice and showcase skills in CRUD operations (Create, Read, Update, Delete), query filtering, and data modeling with a simple contacts database.

---

## What We Did

### 1. Created a Database and Collection

- **Database:** `contact`
- **Collection:** `contactlist`

### 2. Inserted Documents

Inserted 5 documents representing contacts with the following fields:

- `last_name`
- `first_name`
- `email` (optional)
- `age`

Sample documents include:
- Ben Moris, ben@gmail.com, age 26
- Kefi Seif, kefi@gmail.com, age 15
- Emilie Brouge, emilie.b@gmail.com, age 40
- Alex Brown, age 4
- Denzel Washington, age 3

### 3. Read Operations (Queries)

- **Display all contacts:** Show all documents in the collection.
- **Find one contact by _id:** Query a single document using its unique ObjectId.
- **Find contacts with age > 18:** Use `$gt` operator to filter by age.
- **Find contacts with age > 18 and first name containing "ah":** Combined filter using `$gt` and a case-insensitive regex `$regex`.

### 4. Update Operation

- Changed the first name of the contact with last name "Kefi" and first name "Seif" to "Anis" using the `$set` operator.

### 5. Delete Operation

- Deleted all contacts with age less than 5 to demonstrate removal based on a condition.

### 6. Final Display

- Displayed all remaining contacts after deletions to confirm the current state of the collection.

---

## Tools & Technologies Used

- **MongoDB Atlas:** Cloud-hosted MongoDB service
- **MongoDB Query Language:** Used for CRUD and query operations via the Atlas UI

---

## How to Use This Repository

- Review the screenshots folder for step-by-step visuals of each operation.
- Use the queries documented here as a reference for learning MongoDB CRUD operations.
- This project serves as a checkpoint to test foundational MongoDB skills.

---

If you have any questions, feel free to contact me!

---

*Prepared by Thafsouthe HASSANI.*
