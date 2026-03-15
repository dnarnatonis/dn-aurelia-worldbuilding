# Architecture Example

## Problem

We need a system capable of answering questions using external data.

## Concept

An agent is a reasoning loop that can select tools.

## Architecture

The system consists of:

- LLM
- Tool registry
- RAG index
- SQL connector

## Flow

```
User question
→ Agent reasoning
→ Tool selection
→ Tool execution
→ Final answer
```

## Summary

Agent-based architecture with RAG and SQL tools for hybrid retrieval.
