# Git Workflow Demonstration

A minimal project showcasing professional Git practices used in DevOps pipelines.

## Overview
This repository demonstrates how branching, merging, and semantic version tagging are applied to maintain clean, traceable version control — the same structure used in CI/CD environments.

## Key Concepts Demonstrated
- **Branching:** Creating isolated `feature/*` branches for new changes.  
- **Merging:** Integrating feature branches into `main` using fast-forward merges.  
- **Commit Discipline:** Following the *Conventional Commits* standard (`feat:`, `fix:`, `docs:`, `refactor:`).  
- **Release Tagging:** Applying semantic versions (`v1.0.0`) for deployment triggers.

## Workflow Summary
1. Created branch `feature-readme-update`.
2. Added new file `intro.txt` with demo content.
3. Committed with a structured message.
4. Merged back into `main`.
5. Tagged release `v1.0.0`.

## Why This Matters
Version control discipline ensures predictable automation.  
Most CI/CD pipelines depend on clean commit history and tagging for reliable deployments.

## Author
**Saleh Sulieman** — Computer Engineering Student @ Ostim Teknik University  

