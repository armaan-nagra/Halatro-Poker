# Halatro - Haskell-Based Functional Poker with an AI-leveraging strategy 🃏

## Introduction

**Halatro** is a functional programming **project** based on the game Balatro which is a mixture of Poker and Solitaire, it implements a simplified version of **poker hand evaluation and AI decision-making** using **Haskell**. It focuses on **optimal card selection, scoring mechanics, and strategic discarding**, leveraging the power of **pure functions, combinatorial optimization, and declarative programming**.

The AI plays strategically by **evaluating hands, selecting the highest-scoring cards, and discarding intelligently** to maximize scores over multiple rounds.

## Features 🚀

- **Functional Programming Principles**: Uses **immutable data**, **higher-order functions**, and **lazy evaluation** for a structured, declarative approach.
- **Poker Hand Classification**: Implements classic **hand ranking logic**, supporting **Pairs, Straights, Flushes, Full Houses, and Royal Flushes**.
- **Score Calculation**:
  - Computes **base chip values** based on hand strength.
  - Applies **bonus chips** for individual card contributions.
  - Uses **multipliers** to compute the final score.
- **AI Decision-Making**:
  - `myAI`: Implements an **optimized strategy** to **maximize long-term score** through selective discarding. Averaging a score of 713.8
- **Hand Selection & Optimization**: Dynamically determines the **best possible hand** from a given set of cards.
- **Strategic Discarding**: AI **identifies weak cards and discards them** to improve future hands.
- **Performance Benchmarking**: Runs thousands of AI-driven games to evaluate strategy effectiveness.

---

## Functional Programming Highlights 💡

### **1️⃣ Pure Functions & Immutability**
- No **side effects**, ensuring **deterministic behavior**—AI strategy runs **identically across simulations**.
- Uses **persistent data structures** to model hands and optimize evaluation.

### **2️⃣ Combinatorial Optimization**
- Explores **all possible five-card subsets** using **list comprehensions and recursion**.
- Implements **higher-order functions** (`map`, `filter`, `foldr`) to express logic concisely.

### **3️⃣ Lazy Evaluation & Pattern Matching**
- **Lazy evaluation** ensures that only necessary computations are performed.
- Uses **pattern matching** for clear, readable hand classification logic.

### **4️⃣ AI Strategy using Functional Paradigms**
- **Functional composition** keeps AI logic modular and reusable.
- Implements **recursive decision trees** to select the best move dynamically.

## 🎓 Developed as Part of CS141 at Warwick

This project was completed as part of **CS141 Functional Programming** at **The University of Warwick**. The coursework aimed to develop **Haskell proficiency**, focusing on **functional programming techniques, recursive problem-solving, and AI-driven strategy development**.

---
