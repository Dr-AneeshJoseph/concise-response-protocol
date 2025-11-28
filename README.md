# Concise Response Protocol

![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)

A strict prompt engineering framework designed to force Large Language Models (LLMs) into maximum information density.

## Purpose
Default LLM behavior prioritizes conversational politeness and comprehensive coverage, often resulting in "filler" text. This protocol inverts that priority, enforcing brevity and high signal-to-noise ratios.

## The Protocol
The system operates on three logic gates:
1.  **Pre-computation:** Assess necessity before generation.
2.  **Runtime Check:** Recursive self-correction for repetition.
3.  **Compression:** Algorithmic replacement of verbose phrases.

## Usage
Copy the contents of `protocol.md` into your system prompt or user custom instructions.

## License
This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).
