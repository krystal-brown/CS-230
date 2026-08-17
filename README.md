# CS-230 Operating Platforms
## Module Eight Journal Reflection

Summary of the Client and Requirements

The client, The Gaming Room, wanted to expand their existing Android game, Draw it or Lose It, into a web-based application that supports multiple platforms. Their requirements included a multi-team gameplay, unique player and team names, multiple simultaneous game instances and a scalable architecture that could run on Windows, macOS, Linux, and mobile environments. They needed a design that ensured consistency, concurrency control, and efficient resource management. 

What I Did Well

I did particularly well in organizing the design document clearly and logically. Each section flowed naturally, and I explained technical decisions in a way that both developers and non-technical stakeholders could understand. My evaluation of platforms and architectural choices was especially strong because I backed up each recommendation with reasoning tied directly to the client's needs. 

What Helped Me When Developing the Code

Working through the design document first made the coding process much easier. Defining requirements, constraints, and architecture ahead of time gave me a clear mental model of how the system should behave. Understanding the relationship between classes and why certain patterns (like Singleton for game instance control) were necessary helped me write cleaner, more intentional code. 

What I Would Revise

If I were to revise one part of the document, I would expand the Domain Model section. Adding a more detailed UML diagram or clarifying the interactions between services and game objects would make the design even stronger. I would also refine some of the descriptions to better illustrate how the system handles concurrency and state management.

Interpreting and Implementing User needs

I interpreted the user's needs by focusing on scalability, cross-platform compatibility, and ease of future expansion. The Gaming Room wanted a system that could grow without major redesigns, so I made sure the architecture was modular and flexible. Considering user needs is essential because the design must solve real problems, not just look technically impressive. A good design anticipates future changes and prevents unnecessary complexity later. 

My Approach to Designing Software

I approached the design by breaking down the problem into structured sections: requirements, constraints, architecture, evaluation, and recommendations. I relied on object-oriented principles, design patterns, and early architectural planning to keep the system organized and maintainable. In future projects, I would continue using techniques like UML modeling, platform evaluation, and interactive refinement to analyze and design similar applications. Starting with a strong design foundation always leads to better coding. 
