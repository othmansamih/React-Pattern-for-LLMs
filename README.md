# A simple Python implementation of the ReAct pattern for LLMs

This notebook provides a simple implementation of the **React pattern** (Reasoning + Acting) using Python. The React pattern allows language models to interact with external APIs or functions, reason about their observations, and generate answers in an iterative loop.

---

## Features

- Implements a React loop: Thought → Action → Observation, finaly the Answer.
- Supports interaction with predefined functions:
  - `get_planet_mass`: Retrieves the mass of a planet in kilograms.
  - `calculate`: Performs mathematical calculations.
- Uses the Groq API for managing LLM interactions with a preloaded system prompt.
