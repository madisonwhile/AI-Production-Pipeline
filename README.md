# AI Production Pipeline (Figma Weave)

## Overview

This project was my first serious exploration into designing structured AI prompt workflows for creative production.

Built in Figma Weave, the workflow combined product imagery, creative references and brand direction to generate production-ready prompts for AI image generation.

Although this project was ultimately replaced by a more flexible Python multi-agent architecture, it became the foundation for many of the ideas that evolved into my AI E-Commerce Engine.

---

## Project Goal

I wanted to answer one question:

> Can a structured workflow generate more consistent creative prompts than writing prompts manually?

Rather than treating every prompt as a blank page, I explored breaking the creative process into separate stages that could be reused across projects.

---

## Workflow

The system combines:

- Product images
- Brand moodboards
- Creative references
- Brand direction
- Prompt templates

These inputs pass through a node-based workflow that generates structured prompts ready for AI image generation.

---

## What I Learned

This project completely changed how I think about prompt engineering.

Some of the biggest lessons included:

- Prompt structure matters more than prompt length.
- Separating creative tasks into stages produces more reliable outputs.
- Product accuracy improves when AI uses reference images rather than relying entirely on text descriptions.
- Systems design has a greater impact on consistency than writing increasingly detailed prompts.

Those discoveries directly led me to redesign the project as a Python-based multi-agent system.

---

## Why This Repository Exists

I wanted to keep this project public because it represents an important step in my learning journey.

Rather than hiding earlier experiments, I think it's valuable to document how my thinking evolved—from a node-based prototype to a more scalable architecture.

---

## Next Step

This workflow eventually evolved into:

**AI E-Commerce Engine**

A Python multi-agent system capable of learning an entirely new brand from a creative brief, product photography, moodboards and brand assets before generating production-ready prompts for catalogue imagery, website imagery and banner videos.

This repository documents the experimentation that made that system possible.
