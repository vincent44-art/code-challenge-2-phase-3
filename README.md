# code-challenge-2-phase-3
# 📝 Object Relations Code Challenge - Articles

## 📚 Overview

This project models a relational database system for managing **Authors**, **Articles**, and **Magazines** using Python and SQL (SQLite or PostgreSQL). The system mimics basic Object-Relational Mapping (ORM) behavior **without relying on external ORM libraries**.

### 🔗 Entity Relationships

- An **Author** can write many **Articles**
- A **Magazine** can publish many **Articles**
- Each **Article** belongs to one **Author** and one **Magazine**
- An **Author** can contribute to many **Magazines** (via Articles → many-to-many)

---

## ⚙️ Setup Instructions

### Option 1: Using `pipenv` (Recommended)
```bash
pipenv install pytest sqlite3
pipenv shell

