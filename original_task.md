# Test Task: Scalable Order Processing System for a Digital Marketplace

## Scenario

A rapidly growing digital marketplace needs a scalable, resilient, and efficient system to process customer transactions. You have been tasked with proposing and implementing a technical solution that ensures smooth order processing, payment handling, and fulfillment triggering while considering future growth, reliability, and operational efficiency.

The company has limited internal technical expertise and prefers solutions that minimize operational complexity. However, leadership is open to different approaches if they align with long-term scalability, cost-effectiveness, and maintainability.

## Task Overview

### Functional requirements (discussed additionaly)

Implement 1 basic use case: user adds/removes items to the cart -> tap order -> redirected to payment -> redirect back after successful payment.

### System Design & Architecture

Design a technical approach for handling customer transactions at scale.
Consider trade-offs in architecture, technology choices, and implementation models.
The company is unsure about:
The be the followingst architecture model (e.g., monolithic, microservices, event-driven, serverless).
How much custom development vs. third-party services should be used.
The most effective storage strategy (e.g., SQL, NoSQL, hybrid, event-driven storage).
Your job is to recommend a solution and explain why it is the right approach.

### Implementation (Optional, Based on Your Approach)

Depending on your design, demonstrate part of the solution in code (if applicable).
Show how orders, payments, and fulfillment can be processed with sample logic and APIs.
There are no specific requirements on implementation scope—decide what best illustrates your solution.

### Review & Presentation

Document your approach and justify your decisions.
Present your solution, highlighting trade-offs, alternatives considered, and possible improvements.
Discuss:
How your proposed system scales dynamically based on demand.
Deployment strategies for your chosen architecture.
How your solution ensures security, monitoring, and fault tolerance.
You may submit architecture diagrams, implementation samples, or other materials that best convey your approach.

## Evaluation Criteria

**Clarity of Thought**: How well do you analyze trade-offs and justify your decisions?

**Problem-Solving Approach**: How do you handle ambiguity in requirements?

**Technical Depth**: Are the proposed solutions technically sound and scalable?

**Communication**: How effectively can you explain your approach to different audiences?

## **Estimated load** (discussed additionaly)

10000 orders / day

100000 orders/ day - after 1 year

3-5 items per order
