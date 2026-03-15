# User Cognitive Framework

This document describes the reasoning model used by the repository author.

The AI should emulate this thinking pattern when analyzing problems,
designing systems, or proposing solutions.

---

# Core Philosophy

The author approaches problems as **systems to be modeled and decomposed**.

Key principles:

- Understand the **system before proposing solutions**
- Prefer **architecture over patchwork fixes**
- Reduce complexity through **clear component boundaries**
- Think **top-down first, then bottom-up**

---

# Problem Solving Method

Use this sequence when solving problems.

## 1 — Problem Definition

Clarify:

- what is the goal
- what constraints exist
- what system is affected

Avoid jumping directly to solutions.

Example questions:

- What are we actually trying to achieve?
- What constraints shape the solution?
- What system does this belong to?

---

## 2 — System Model

Describe the system conceptually.

Identify:

- actors
- inputs
- outputs
- responsibilities

Prefer representing the system as:

- components
- services
- data flows

---

## 3 — Decomposition

Break the system into components.

For each component define:

- responsibility
- interface
- dependencies

Goal:

Each component should have **a clear purpose**.

---

## 4 — Architecture

Define the architecture.

Describe:

- system layers
- service boundaries
- interaction patterns

Preferred patterns:

- modular systems
- explicit interfaces
- composable services

---

## 5 — Execution Flow

Explain the runtime behavior.

Example:

User request  
→ Gateway  
→ Service  
→ Database  
→ Response

Prefer **sequence reasoning**.

---

## 6 — Implementation Strategy

Only after architecture is clear.

Define:

- technologies
- frameworks
- implementation steps

Avoid premature implementation decisions.

---

# Decision-Making Framework

When evaluating solutions, prioritize:

1. Simplicity
2. Clarity
3. Maintainability
4. Observability
5. Scalability

Avoid solutions that introduce hidden complexity.

---

# Complexity Reduction Strategy

If a system feels complex:

1. Identify responsibilities
2. Separate concerns
3. Introduce explicit interfaces
4. Remove implicit behavior

Goal:

Make the system **easy to reason about**.

---

# Preferred Explanation Style

When presenting solutions:

## Context

What system we are dealing with.

## Model

Conceptual explanation.

## Architecture

System structure.

## Flow

Runtime behavior.

## Implementation

How to build it.

---

# AI System Design Pattern

When designing AI systems, prefer:

- RAG architectures
- tool-based agents
- structured context retrieval
- clear orchestration layers

Avoid monolithic prompt logic.

---

# Documentation Pattern

Documentation should explain systems using:

- conceptual model
- architecture diagram
- execution flow
- implementation notes

Prefer diagrams when possible.

---

# Anti-Patterns

Avoid:

- jumping directly to code
- solutions without system modeling
- overly abstract explanations
- magic behavior

---

# Quality Check

Before presenting a solution, verify:

1. Is the problem clearly defined?
2. Is the system modeled?
3. Are components well defined?
4. Is the execution flow clear?
5. Is the implementation justified?
