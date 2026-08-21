# Progressive Prompting for Calculator Design

This repository demonstrates the concept of **progressive prompting** - a technique where AI prompts are gradually enhanced with more context, constraints, and examples to produce progressively better outputs.

## Overview

The same task (designing a simple calculator program) is approached three times with increasing levels of detail:

1. **Level 1: Minimal Prompt** - Only the function name
2. **Level 2: Enhanced Prompt** - With comments explaining intent
3. **Level 3: Complete Prompt** - With detailed comments, docstrings, and usage examples

## Why Progressive Prompting?

- **Iterative Refinement**: Build context incrementally rather than overwhelming the AI with everything at once
- **Better Clarity**: Each enhancement reduces ambiguity and sets clearer expectations
- **Quality Improvement**: More detailed specifications lead to more robust implementations
- **Learning Tool**: Shows how prompt engineering directly impacts code quality

## File Structure

```
├── README.md
├── level-1-minimal.py          # Only function name
├── level-2-enhanced.py         # With explanatory comments
├── level-3-complete.py         # With docstrings and examples
└── comparison.md               # Analysis of differences
```

## Quick Start

Review each file in sequence to see how the same calculator design evolves:

```bash
# Start with the minimal prompt
cat level-1-minimal.py

# See how comments improve clarity
cat level-2-enhanced.py

# Experience the complete, well-documented version
cat level-3-complete.py
```

## Key Takeaways

1. **Minimal specifications** may produce basic, incomplete solutions
2. **Comments and intent** guide the AI toward better design decisions
3. **Docstrings and examples** create comprehensive, production-ready code
4. **Progressive enhancement** is more effective than trying to be perfect initially

## Usage

Each Python file can be run independently:

```python
python level-1-minimal.py
python level-2-enhanced.py
python level-3-complete.py
```

---

**Created**: August 21, 2026  
**Purpose**: Educational demonstration of AI prompt engineering best practices
