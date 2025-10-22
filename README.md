# SNHU-CS230-TheGamingRoom  
**Software Design Document – The Gaming Room (Draw It or Lose It)**  
**Author:** Rimon “Ray” Hamo  
**Course:** CS-230 Operating Platforms  
**Institution:** Southern New Hampshire University  

> “Technology is the bridge between today’s dreams and tomorrow’s reality.” – Rimon H.

---

## 1. Client and Software Requirements
The client, **The Gaming Room**, wanted to expand its Android-based game *Draw It or Lose It* into a **web-based, multi-platform version** accessible through browsers on Windows, macOS, Linux, and mobile devices.  

Key requirements included:
- Support for multiple teams and multiple players per team  
- Unique identifiers for games, teams, and players  
- Reliable, real-time performance and synchronization  
- Security and scalability across different platforms  

My task was to design the complete software architecture to meet these goals and ensure smooth scalability, performance, and cross-platform compatibility.

---

## 2. What I Did Well
I developed a **comprehensive and modular software design document** detailing the architecture, operating platform, and deployment approach.  
I particularly excelled in the **Recommendations** section, where I proposed:
- A **Linux (Ubuntu Server LTS)** operating platform with **Docker + Kubernetes** for scalability  
- A **PostgreSQL + Redis** hybrid storage model for persistence and caching  
- A **secure design** implementing TLS 1.3, OAuth 2.0, and AES-256 encryption  

This approach demonstrates strong architectural planning, technical accuracy, and professional communication.

---

## 3. What I Found Helpful
Creating the design document first allowed me to structure my thinking and clearly map system components before coding.  
It helped me identify dependencies early (such as storage, memory management, and distributed systems), which would otherwise create challenges during development.  
Documenting first made the software easier to visualize and simplified decisions around scalability and maintainability.

---

## 4. What I Would Revise
If I were to improve one section, I would revise the **Evaluation** section to include more measurable metrics—such as performance benchmarks, estimated throughput, and cost breakdowns between cloud platforms like AWS, Azure, and Google Cloud.  
This would make the document more data-driven and useful for real-world deployment planning.

---

## 5. Interpreting and Implementing User Needs
I interpreted the user’s needs—multi-platform access, fair competition, and reliability—and translated them into system-level solutions such as:
- RESTful API endpoints for interoperability  
- WebSocket communication for real-time events  
- Strong authentication and data validation to protect player identities  

Understanding and implementing user needs ensured that the design aligned with **both technical feasibility and user experience**, which is critical in software architecture.

---

## 6. Approach to Software Design and Future Strategies
I approached software design using **object-oriented and modular principles** with clear class hierarchies (Game, Team, Player) and **design patterns** like Singleton and Iterator.  
Future design strategies I’ll continue using include:
- **Agile iterative development** for flexibility  
- **Containerization (Docker/Kubernetes)** for scalability  
- **Infrastructure as Code (IaC)** for reproducible environments  
- **Continuous Integration and Delivery (CI/CD)** for efficient deployment  

These methods ensure scalable, reliable, and maintainable software systems.

---

## 📁 Portfolio Artifact
**Artifact:** `CS 230 Project 3 Software Design Template.docx`  
**Repository:** [https://github.com/rayhamo98/SNHU-CS230-TheGamingRoom](https://github.com/rayhamo98/SNHU-CS230-TheGamingRoom)  

This repository contains the final **Software Design Document** submitted for CS-230, demonstrating skills in **system analysis, architecture design, and technical communication**.

---

## 🧠 Summary
The Gaming Room project showcases my ability to:
- Translate client needs into scalable technical solutions  
- Design secure, distributed architectures  
- Communicate software design decisions professionally  

This project is a strong representation of my architectural thinking, problem-solving, and documentation skills as a software engineer.

---

> © 2025 Rimon Hamo | SNHU Computer Science Portfolio
