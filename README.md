CS 230 – Software Design Project
The Gaming Room – Draw It or Lose It

This repository contains the completed software design document developed for The Gaming Room client as part of CS 230 at Southern New Hampshire University.

The project focused on designing a scalable, web-based version of the game Draw It or Lose It, expanding it from an Android-only application into a multi-platform solution.

⸻

 Project Overview

The Gaming Room required a web-based application capable of:
	•	Supporting multiple games, teams, and players
	•	Enforcing unique identifiers for all entities
	•	Maintaining a single instance of the game service in memory
	•	Supporting cross-platform access
	•	Preparing for scalable deployment

The solution applies object-oriented programming principles and design patterns, including the Singleton pattern, to ensure efficient memory management and controlled service access.

⸻

 Key Design Concepts
	•	Object-Oriented Design
	•	Inheritance and Composition
	•	Singleton Design Pattern
	•	Multi-tier Client-Server Architecture
	•	Cross-platform deployment considerations
	•	Operating system evaluation (Linux, Mac, Windows, Mobile)
	•	Relational database recommendations
	•	Security and distributed systems planning

⸻

Reflection: 
Client Summary and Software Requirements

The Gaming Room was a client seeking to expand their existing Android game, Draw It or Lose It, into a scalable web-based application. The goal was to design a system that could support multiple games, teams, and players while enforcing strict rules such as unique names and a single instance of the game service in memory.

The client required a platform-independent solution that would allow users to access the application across different operating systems while maintaining consistent behavior. This meant designing a structured, object-oriented system that could scale and operate efficiently in a distributed environment. The software needed to enforce uniqueness across entities, maintain game state integrity, and prepare for future expansion beyond a single mobile platform.

___

What I Did Particularly Well

I believe I did particularly well in translating technical requirements into clear design decisions. Instead of simply restating what the client wanted, I connected each requirement to an architectural solution. For example, implementing the Singleton design pattern for the GameService directly addressed the requirement that only one instance exist in memory.

I also demonstrated strong object-oriented design principles by structuring the domain model around inheritance and composition. The Entity base class reduced duplication, and the relationships between Game, Team, and Player were logically organized and scalable. My recommendations section also reflects careful evaluation of operating systems, storage management, and security considerations rather than surface-level comparisons.

___

How the Design Document Helped During Development

Working through the design document before coding was extremely helpful. It forced me to think through constraints, system architecture, and design patterns before writing implementation logic. This reduced ambiguity during development because the structure was already clearly defined.

Documenting relationships between objects and defining system responsibilities ahead of time made the coding process more efficient. Instead of guessing how components should interact, I had already mapped out the architecture. This reinforces the importance of planning in software engineering, especially for applications that may scale in the future.

___

What I Would Revise and Improve

If I were to revise one portion of the document, I would expand the system architecture view. While the assignment did not require a detailed architectural diagram, adding a visual multi-tier architecture diagram would strengthen the documentation. A clear representation of client layer, application logic layer, and database layer would improve clarity for both technical and non-technical stakeholders.

In future projects, I would also incorporate more performance considerations, such as concurrency handling and load management strategies, to better anticipate real-world scaling challenges.

___

Interpreting User Needs and Why They Matter

I interpreted the client’s needs by identifying both explicit and implicit requirements. Explicitly, they required uniqueness, scalability, and cross-platform support. Implicitly, they needed reliability and maintainability.

Considering user needs is essential because software is built to serve real users, not just satisfy technical correctness. If design decisions ignore usability, scalability, or clarity, the final system may technically function but fail in practice. Designing with user requirements in mind ensures that architectural decisions align with real-world expectations and long-term growth.

___

My Approach to Designing Software

My approach to software design in this project was structured and requirement-driven. I began by analyzing the client’s constraints, then selected appropriate object-oriented principles and design patterns to address them. I used abstraction, inheritance, and controlled object creation to maintain organization and efficiency.

In the future, I would continue using requirement analysis, UML modeling, and architectural evaluation before implementation. I would also incorporate early risk analysis and possibly prototype critical components before full development. This structured approach improves code quality, maintainability, and scalability.

 Repository Contents
	•	Project3Completedcs230.docx – Final Software Design Document
	•	README.md – Portfolio reflection and project summary

⸻

🎯 Reflection
