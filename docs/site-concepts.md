# Drift Interactive Learning – Site Concepts

## Purpose
The goal of the Drift Interactive Learning site is to provide a guided, interactive, and adaptive learning experience for programmers of all skill levels. The platform introduces Drift language concepts through real-world, scenario-driven steps, backed by hands-on exercises and immediate feedback.

## Core Principles

### 1. Adaptive Learning Path
Users begin with a short yes/no questionnaire that gauges:
- General programming experience
- Systems-level familiarity
- Exposure to ownership/borrowing
- Comfort with error-handling models
- Experience with concurrency and generics

Based on the answers, users are classified into one of three tracks:
- **Track A – Beginner**
- **Track B – Intermediate**
- **Track C – Advanced**

Each track determines the starting point, depth, and pacing of the content.

### 2. Minimal Friction Onboarding
No sign-up required.  
Progress is stored locally in the browser.  
Users can start coding immediately.

### 3. Real-World Anchoring
Every Drift concept is introduced with:
- A concise explanation
- A real scenario (files, network, embedded, plugins, backend logic)
- Hands-on examples
- Exercises that simulate real problems

### 4. Interactive Editor Experience
Core page layout:
- **Left:** Drift code editor (Monaco)
- **Right:** Output, test results, SSA/MIR views, and visualizations
- **Bottom:** Step-by-step guidance for each exercise

### 5. Progressive Chapter Structure
Each chapter follows a consistent sequence:
1. Introduce the concept (one screen)
2. Explain real use-cases
3. Show interactive examples
4. Provide structured exercises
5. Unlock next chapter upon completion

### 6. Technical Transparency for Advanced Users
Advanced learners get:
- SSA visualizations
- MIR lowering steps
- ABI mapping
- Plugin boundary rules
- Error-edge control-flow visual diagrams

### 7. Safety & Sandboxing
All user code is compiled and executed in a sandbox environment (WASM or isolated backend).  
No filesystem or network access unless mocked.

### 8. Content Tracks Overview
#### Track A — Beginner
Start with fundamentals:
- Values, vars, refs
- Strings, arrays
- Functions
- Simple loops
- Intro to errors

#### Track B — Intermediate
Start with core Drift features:
- Drift philosophy
- Refs & mutability
- Arrays & iteration
- Error edges
- Structs & mutation
- Generics & traits

#### Track C — Advanced
Skip basics and dive into:
- Error-edge control-flow
- Borrow/ref semantics
- SSA lowering
- Memory model
- FFI & ABI rules
- Plugins and signed modules

### 9. Final Capstone
Each track ends with a real, small project:
- Beginner: CLI tool with arrays and errors
- Intermediate: Simple API-style logic or data transformer
- Advanced: Plugin-enabled application with C-FFI and error-edge control-flow

## Outcome
This site ensures users learn Drift how Drift is meant to be learned: through clarity, pragmatism, and hands-on problem-solving. The site balances accessibility for beginners with deep insight for systems-level experts.

