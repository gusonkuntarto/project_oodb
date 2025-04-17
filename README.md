# 🧩 Java OODB App with db4o

A simple Java command-line application using **db4o** (Database for Objects) to demonstrate Object-Oriented Database (OODB) concepts. The app manages `Person` objects and their associated `Address`, allowing data storage, querying (QBE, NQ, and SODA), and transaction control with `commit()` and `rollback()`.

---

## 🗂️ Features

- Add, update, and list `Person` and `Address` objects
- Relational data: each `Person` may have an `Address`
- Query support:
  - QBE (Query By Example)
  - NQ (Native Query)
  - SODA (Simple Object Database Access)
- Manual transaction management
- CLI-based interface

---

## 📁 Folder Structure
├── src/ │ ├── Address.java │ ├── Person.java │ ├── MyApps.java │ └── QueryAll.java ├── db/ │ └── person.db4o


---

## 🚀 Getting Started

### Requirements
- Java JDK 1.8
- [db4o jar](https://sourceforge.net/projects/db4o/) (included or downloaded manually)

### Run the App

```bash
javac -cp .;lib/db4o-8.0.249.16098-all-java5.jar src/*.java
java -cp .;lib/db4o-8.0.249.16098-all-java5.jar src.MyApps

