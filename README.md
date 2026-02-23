## AutoDev Crew is an autonomous software engineering system built with CrewAI.

It takes high-level product requirements and automatically generates:

A detailed system design

A fully implemented Python backend module

A simple Gradio frontend

Unit tests

Instead of prompting an LLM once, this project simulates a structured engineering team where each agent has a clear role and responsibility.

## What This Project Does

Given a set of requirements, the system:

Designs the architecture

Implements the backend in a single self-contained Python module

Builds a demo UI for the backend

Writes unit tests

Saves all artifacts into an output directory

All steps are executed sequentially using CrewAI.

## How It Works

The system defines four specialized agents:

Engineering Lead

Backend Engineer

Frontend Engineer

Test Engineer

Each agent receives a clearly defined task. Outputs from earlier stages are passed as context to later stages, creating a structured workflow.

The process flow looks like this:

Requirements
→ Design Document
→ Backend Implementation
→ Gradio UI
→ Unit Tests
