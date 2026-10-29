# 🎸 Guitar Inventory Management System (Java)

A console application for managing a guitar shop's stock — add, remove, list and search guitars — built with object-oriented Java.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![OOP](https://img.shields.io/badge/OOP-Classes_%26_Encapsulation-555555?style=flat-square)

## Features

Menu-driven console interface:

1. **Add guitar** — brand, model, type (Acoustic / Electric / Bass), price, serial number
2. **Remove guitar** by serial number
3. **Display inventory**
4. **Search guitar** by serial number
5. Exit

## Design

| Class | Responsibility |
|---|---|
| `Guitar` | Model class holding a guitar's details, with getters and `toString()` |
| `Inventory` | Stores the collection and handles add / remove / search / display |
| `GuitarInventorySystem` | Entry point with the `Scanner`-based menu loop |

## Run it

```bash
cd "Project 7/src"
javac *.java
java GuitarInventorySystem
```
Or open the `Project 7` folder in IntelliJ IDEA and run `GuitarInventorySystem`.

---
Coursework · Java Programming, BCA, Alliance University

**Dakshraj Singh Chandawat** · [GitHub](https://github.com/DakshrajKurki) · [LinkedIn](https://www.linkedin.com/in/dakshraj-singh-chandawat-0a6349314)
