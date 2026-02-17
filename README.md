# CS50x – Computer Science Foundations for Cloud & Systems Engineering

## Overview

This repository contains structured coursework completed through Harvard’s CS50x program, organized to demonstrate foundational computer science principles that directly support cloud engineering, backend infrastructure, and scalable systems design.

The objective of this repository is not coursework archival — it is to demonstrate engineering discipline, performance awareness, and systems-level thinking.

---

## Core Engineering Competencies Demonstrated

### Algorithmic Efficiency & Performance Analysis
- Big-O time complexity evaluation (O(n), O(log n), O(n log n), O(n²))
- Tradeoff analysis between sorting algorithms
- Search optimization techniques
- Computational cost awareness

### Memory Management (C Programming)
- Manual memory allocation and deallocation (malloc/free)
- Pointer manipulation
- Stack vs Heap behavior
- Memory leak prevention
- Runtime performance considerations

### Data Structures
- Arrays
- Linked Lists
- Hash Tables
- Collision resolution strategies
- Efficient lookup design

### Database & Query Foundations
- SQL query structuring
- Relational data modeling
- Data normalization concepts
- Query efficiency awareness

### Backend Logic & Web Basics
- Python scripting
- Server-side logic fundamentals
- Basic web application structure

---

## Repository Structure

cs50x-computer-science-fundamentals/
│
├── week-01-c-basics/
├── week-02-arrays/
├── week-03-algorithms/
├── week-04-memory/
├── week-05-hash-tables/
│ └── speller/
├── week-06-python/
├── week-07-sql/
├── week-08-web/


Each directory contains:
- Source code implementations
- Problem-solving logic
- Algorithm breakdowns
- Performance considerations
- Memory handling approaches (where applicable)

---

## Highlight Engineering Project: Hash Table Spell Checker

### Objective
Design and implement a custom hash table to efficiently validate word lookups from a dictionary.

### Engineering Focus
- Designed hash function for distribution efficiency
- Implemented collision handling via chaining
- Managed dynamic memory allocation
- Minimized lookup latency toward O(1) average-case performance
- Analyzed tradeoffs between memory consumption and speed

### Why It Matters
Efficient lookup structures are foundational to:
- High-performance APIs
- Scalable backend services
- Distributed caching systems
- Low-latency cloud applications

This project mirrors the type of data structure optimization required in real-world cloud environments.

---

## Engineering Mindset Applied

Throughout this repository, emphasis was placed on:

- Writing clean, modular code
- Avoiding unnecessary computational overhead
- Thinking in terms of scalability
- Understanding low-level memory behavior
- Analyzing performance bottlenecks

These principles directly support cloud architecture where cost, performance, and reliability are interconnected.

---

## Relevance to Cloud Engineering

Cloud infrastructure depends heavily on:

- Efficient backend services
- Low-latency data retrieval
- Memory-conscious application design
- Performance optimization under load
- Scalable systems thinking

This repository demonstrates the foundational logic that supports infrastructure-level engineering decisions.

---

## Future Enhancements

Planned improvements to extend this repository beyond coursework:

- Containerize select projects using Docker
- Deploy simple services to AWS (EC2 / ECS)
- Benchmark algorithm performance under load
- Integrate CI/CD pipelines using GitHub Actions
- Add performance measurement scripts

---

## Author

Carter  
Cloud Engineering Track  
Focused on scalable infrastructure, automation, and performance-optimized systems

