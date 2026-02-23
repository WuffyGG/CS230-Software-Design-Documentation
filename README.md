# CS 230 – Software Design Portfolio Artifact  
## The Gaming Room – Draw It or Lose It

## Overview

In this course, I worked with a fictional client, **The Gaming Room**, to design a scalable, multi-platform version of their game *Draw It or Lose It*. The client originally had an Android-based application and wanted to expand it to support web, desktop, and mobile platforms in a distributed environment.

The application needed to support multiple concurrent game sessions, manage a large image library, and ensure consistent performance across operating systems. The goal of this project was to design a complete software architecture and document system requirements, platform evaluation, storage and memory management, distributed systems considerations, and security strategies.

---

## What I Did Well

One of my strongest contributions in this project was evaluating different operating platforms and recommending an appropriate server environment based on scalability, performance, and cost considerations. I effectively analyzed memory and storage requirements, especially when calculating resource needs and applying operating system concepts such as indexed allocation, virtual memory, and disk scheduling.

I focused on connecting technical decisions directly to the client’s requirements rather than simply listing system features.

---

## How the Design Document Helped Development

Working through the design document before coding was extremely helpful. It required me to think about architecture, scalability, and system constraints early in the process. Instead of immediately implementing code, I considered:

- Operating system architecture  
- File system structure  
- Memory management strategies  
- Distributed communication models  

This structured planning process made the overall system design more intentional and organized.

---

## What I Would Improve

If I were to revise one part of this project, I would expand the distributed systems section to include deeper discussion of fault tolerance and failure recovery strategies. While scalability and networking were addressed, adding more detail about redundancy and high-availability design would strengthen the overall architecture.

---

## Interpreting User Needs

I interpreted the client’s needs by focusing on scalability, performance, and multi-platform compatibility. Since the application needed to support multiple simultaneous game sessions and rapid image rendering, I designed the system with efficient memory and storage management in mind.

Considering user needs is critical because software architecture decisions directly impact performance, reliability, and user experience.

---

## My Approach to Software Design

My approach to designing this system was structured and analytical. I began with requirement analysis, evaluated platform trade-offs, and then designed for scalability and modularity. I applied operating system principles such as process scheduling, virtual memory management, indexed file allocation, and interrupt-driven I/O to guide my decisions.

In future projects, I will continue to:

- Start with clear requirement analysis  
- Evaluate platform trade-offs before implementation  
- Design for scalability and modularity  
- Consider distributed systems and security early in development  

This course strengthened my ability to connect operating system theory to practical software design decisions.
