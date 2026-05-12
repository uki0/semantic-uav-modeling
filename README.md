# semantic-uav-modeling

This repository contains the prompt templates used in our study on semantics-driven SysML v2 modeling for task-oriented UAV system architecture design.

## Overview

The project supports a cross-level design workflow organized around the Requirement–Functional–Logical–Physical (RFLP) hierarchy.  
The prompt templates are designed for four reasoning stages:

- **Requirement LLM**: extracts mission, operation, performance, and optimization requirements from a user request
- **Functional LLM**: performs hierarchical functional decomposition based on the extracted requirements
- **Logical LLM**: constructs logical subsystems and their interaction relations from functional artifacts
- **Physical LLM**: selects the required physical components based on logical artifacts and ontology constraints

## Files

- `requirement_llm_prompt.txt`
- `functional_llm_prompt.txt`
- `logical_llm_prompt.txt`
- `physical_llm_prompt.txt`

## Purpose

These prompt templates are used to generate structured design artifacts for UAV system architecture modeling under ontology-guided semantic constraints.  
They are intended to support downstream transformation into formal SysML v2 models, as well as cross-level traceability construction and consistency verification.

## Notes

- The prompts are designed for research use.
- The JSON output schemas are preserved to support automated processing in later stages of the modeling pipeline.
- More implementation details will be released in future updates.
