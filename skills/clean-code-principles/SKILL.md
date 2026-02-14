---
name: clean-code-principles
description: Enforce clean code principles when writing or reviewing code. Use when writing new functions, refactoring existing code, or reviewing code for readability and maintainability. Covers guard clauses, modularization, naming conventions, and more.
---

# Clean Code Principles

A collection of principles and patterns for writing clean, readable, and maintainable code.

## When to Use This Skill

- Writing new functions or methods
- Refactoring nested or complex code
- Reviewing code for readability
- Discussing code quality improvements

## Principles Overview

| Principle | Description | Reference |
| --- | --- | --- |
| Guard Clause Pattern | Fail fast with early returns, keep code flat | `guard-clause-pattern.md` |

## Core Philosophy

1. **Readability First** — Code is read far more often than it is written
2. **Fail Fast** — Handle errors and edge cases early, keep the happy path clear
3. **Single Responsibility** — Each function/class should do one thing well
4. **Minimal Nesting** — Flat code is easier to follow than deeply nested code
5. **Meaningful Names** — Names should reveal intent without needing comments
6. **DRY, but not at the cost of clarity** — Avoid premature abstraction
